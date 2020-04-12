# AliUserId

#### 介绍
AliUserId （支付宝小程序授权，获取支付宝用户id）

![2](https://scimence.gitee.io/AliUserId/files/AliUserId.png)

--------------------------------------

#### 1、添加AliTool.cs至您的工程中即可(无需添加任何依赖文件)


#### 2、调用接口，即可获取支付宝用户id

string userId = Sci.AliTool.GetUserId(auth_code, app_id, private_key, alipay_public_key);

// auth_code 	为支付宝小程序中获取的授权码

// app_id	为支付宝小程序AppId

// private_key	为配置在支付宝小程序上的应用私钥

// alipay_public_key	为支付宝后台提供的支付宝公钥


--------------------------------------

#### 示例demo
https://scimence.gitee.io/AliUserId/AliUserId.exe


#### 示例核心源码
https://scimence.gitee.io/AliUserId/files/C#获取支付宝用户id.zip

