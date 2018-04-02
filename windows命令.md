1. windows查看指定端口并杀死进程

   ```shell
   netstat -ano|findstr 8100 //查找8100端口占用情况
   taskkill /PID 进程号 /F //杀死进程命令
   netstat -ano|findstr 8100 //再次查找进程是否已经被杀死
   ```

