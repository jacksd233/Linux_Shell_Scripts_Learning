
后台执行，且关闭terminal后不挂起:

```nohup rsync -avzlP username@1.1.1.1:/home/files/* ./ > output.log 2>&1 &```

```nohup /root/runoob.sh > runoob.log 2>&1 &```

查看该进程PID：
```ps -aux | grep "rsync" ```

终止该进程：
```kill -9 进程号PID```
