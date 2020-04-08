## reuse a port in linux
If you use a port for listening in you server and edit some codes in file and rerun your server It may not work saying, this is because the port is still in use. So, you have to kill the process on the port 


```
sudo fuser -k {port number}/tcp
```