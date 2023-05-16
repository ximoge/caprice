## wget下载GLDAS数据

##### windows环境

```
wget -r -nc -P [download directory] --load-cookies [cookies file] --save-cookies [cookies file] --auth-no-challenge=no --content-disposition -i [url file]
```

其中

-r	递归下载

-nc	不会下载已存在文件

-P	下载位置

--load-cookies	加载cookies文件

--save-cookies	保存cookies文件

--auth-no-challenge=no	从无证书的网页下载

--content-disposition	GLDAS的subset要求

-i	下载的url文件