## EntryMD5.c  
C语言MD5加密字符串  
经验证，支持的操作系统Linux, Android, iOS(如编译不过，记得将EntryMD5.c改名为EntryMD5.mm)  
## usage 使用  
```  
char keyValue[64];  
memset(keyValue,0,sizeof(keyValue));  
EntryMD5("123456",keyValue);  
printf("%s", keyValue); // so, md5 123456 = "e10adc3949ba59abbe56e057f20f883e"  
```  
## MIT
