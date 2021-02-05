# Nginx_-_-
Nginx_线程池_删减版

**编译**
```shell
gcc demo_main.c thread_cond.c thread_mutex.c thread_pool.c -o demo_main -lpthread
```
**运行**
```shell
➜  Nginx_-_- git:(main) ✗ ./demo_main
Hello, this is 1th test.index=0
Hello, this is 2th test.index=0
Hello, this is 3th test.index=0
arg1: 666, arg2: 888
➜  Nginx_-_- git:(main) ✗
```
