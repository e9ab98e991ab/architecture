# IDEA 服务器激活

## 方案一

1. 打开你正在使用的 Jetbrains 软件，点击菜单栏 – Help – Register，选择 `License Server`
2. 然后在`Server address`输入下方的正版许可服务器地址，再点击“Active”，如果不生效的话会报红色错误提示，一个不行再换另一个试验

```
http://134.53.225.196
```

## 方案二

如果上方的服务器激活地址都失效了，还有个办法可以搜索网络上可用的激活服务器，一般人我不告诉他，请务必低调使用。

1. 首先打开这个网站：https://search.censys.io/
2. 然后在搜索框中输入：`services.http.response.headers.location: account.jetbrains.com/fls-auth`，点击`搜索`，网站会检索出很多 IP 地址
   ![search.censys.io](https://anspoon.com/wp-content/uploads/2022/08/BOtcf5.png)
3. 任意点一个 IP 地址查看详情页，确保`80/HTTP`地址下的`Status Code`状态码为`302`，这时候复制出`Detail`这里的 IP 地址，作为我们的 License Server 地址
   ![IP地址详情页](https://anspoon.com/wp-content/uploads/2022/08/eKrOrk.png)
4. 和上面一样，输入地址后点击激活
   ![输入激活服务器IP地址](https://anspoon.com/wp-content/uploads/2022/08/HSziOB.png)
5. 如果无法激活再回到搜索结果页换一个 IP 地址再次试验，小编试验了 3 次就成功了，IDEA 成功永久 激活，亲测有效
   ![IEAD正版激活成功](https://anspoon.com/wp-content/uploads/2022/08/blzHwP.png)

