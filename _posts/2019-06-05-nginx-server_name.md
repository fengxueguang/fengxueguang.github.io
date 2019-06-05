## 默认域名

```nginx
server_name  aaaa bbbb;
server_name_in_redirect off;
```

如果有return 那么off的时候就是用它本身的域名，但是如果是开启的那么就是用aaa

## 取值

在下文取这个变量是用$domain来取的

