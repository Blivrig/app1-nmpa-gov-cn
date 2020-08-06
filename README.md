# app1-nmpa-gov-cn
## 药监局Cookie和6SQk6G2z及c1SoYK0a生成接口(2020.08.05测试可用)
## 概述
> 反爬厂商：瑞数
## 项目说明
- 为了测试通杀思路
- 随机生成浏览器指纹，避免被大数据标记
- 本接口并不访问药监局，仅用于为客户端生成加密后请求参数，需要客户端自行解决IP封禁问题。
- 阿里云1核1G服务器，大的并发，切勿用于大规模的数据采集，并发过大会自动关闭
- 本接口仅用于研究javascript加解密技术，严禁商用！
- 作者与药监局和瑞数信息无利益关系，开发此接口仅出于兴趣使然，如侵犯了您的合法权益，请在issue区提出！
- 服务器我也是掏了钱的，假如你感觉对你有用，请支付宝或者微信支持一下
## 接口描述
## 获取url接口

### 1) 请求地址

>http://rs.qyplc.com:1788/nmpa/getHz?param=c2VhcmNoLmpzcA==

### 2) 调用方式：HTTP get

### 3) 接口描述：

* 此接口获取后缀名6SQk6G2z和c1SoYK0a

### 4) 请求参数:

#### GET参数:

```
请求列表时：param为c2VhcmNoLmpzcA==
请求详情时：param为Y29udGVudC5qc3A/dGFibGVJZD0yNSZ0YWJsZU5hbWU9VEFCTEUyNSZ0YWJsZVZpZXc95Zu95Lqn6I2v5ZOBJklkPTY0NzEx

ps：都是base64编码以后的，请求详情的参数base64以后作为参数传输

```
### 5) 请求返回结果:

```
{
    "data":"http://app1.nmpa.gov.cn:80/data_nmpa/face3/content.jsp?6SQk6G2z=GBK-57iNi_Jtzj_IZscW4uClza2dwWHQKMJpC9T_x3qUUhQWlpa0SDv_xYVNIeoXSyp79vLECzd.2roIr0FC0xw.ZAd_dayekMD4K_Un3JfvCGv_zqMDPnGqUe5FSpxNJsX_0AFDCr6ppow4nLaL4xFBRukkSuvzp0Mi7wSsp4.eZbW8T4n19UxbshiqDBuUghxb_oHrazlbN.UJ1.oZ0lHEqpaT7xTfZtQ_Q0KSBbRa31BbIdaonSXV.2OwgIYLhEpwd1_i6m3y5E9SrPK3SCyMqa_z50vI.BQzKMQUeIvsZMcidbQ2D2fJxsGnpnT.9Cq51WFBdpE7lHHId_2rCbASVtJGtct9ntIcrGTlNebjTw.Z&c1SoYK0a=GBK-4OuNWf9Rpvkjtg7jDAsukD9XWDhusQeGTXAvaaK5uYvGHMWtf7SGfoRoKmMH0lgCm1QiISxQezQnAFcrF2LnbYTS_CCgDIGlg.HT9AFFrRSY1D.cgdNTQfdX5euIr_Fl_.np3.U3OWmPHj6n8Lrgdi9sdkhqKhlyscCFWyW5oZ4iY38F1VkOiHTNxvBdTenQ0am9SHsXYYyQTmYihcXUTza",
    "ok":true,
    "status":0,
    "message":"公众号：编码天空，付费1999带你通杀！"
}
```


### 6) 请求返回结果参数说明:
|字段名称       |字段说明         |类型            |必填            |备注     |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|data|url，构造请求时直接使用此链接|string|Y|详情链接比列表链接多一个c1SoYK0a|
