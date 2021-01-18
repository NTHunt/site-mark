1、https://github.com/jsocol/django-ratelimit
(注意：针对uwsgi+nginx环境中，如果uwsgi运行了多个进程，这个限制效果会有影响。因为uwsgi多进程之间，内存是不共享的。
如果一个请求，刚好分配到一个新的uwsgi中，则是不受限制的。如果刚好分配到刚刚访问到的uswgi，才会有频率限制效果。)  
2、https://github.com/alibaba/Sentinel
only for java  
3、https://www.jb51.net/article/184741.htm  
https://cloud.tencent.com/developer/article/1050465  
https://zhuanlan.zhihu.com/p/20872901  
https://www.jianshu.com/p/ee2c8843f7a9  
https://yq.aliyun.com/articles/680964
