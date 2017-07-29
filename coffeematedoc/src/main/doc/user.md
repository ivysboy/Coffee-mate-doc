#注册用户

**signUp**  

访问路径：http://api.ivysboy.com/coffee-mate/user/signUp

method: POST

request body: 
```json
{
  "email" : "ivysboy@icloud.com",
  "passWord" : "973910126wuyuan"
}
```
response:  

```json
{
  "data": {
    "id": "a810a17e-b6b3-4993-aee5-06f0fe04fd0f",
    "userName": "359696929@qq.com",
    "imageUrl": null
  },
  "code": 1000200,
  "message": "操作成功"
}
```

#登录

**signIn**  

访问路径：http://api.ivysboy.com/coffee-mate/user/signIn

method: POST

request body: 
```json
{
	"email" : "xuwuyuanyuan@gmail.com",
	"passWord" : "973910126"
}
```
response:  

```json
{
  "data": {
    "id": "359696929",
    "userName": "WuyuanXu",
    "imageUrl": "http://static.ivysboy.com/images/9d85e410-870e-4e81-8575-395fe871aed4.jpg"
  },
  "code": 1000200,
  "message": "操作成功"
}
```

#注册检测邮箱重复

**checkRepeatAccount**  

访问路径：http://api.ivysboy.com/coffee-mate/user/checkRepeatAccount?email=xuwuyuan007@gmail.com

method: GET

request parameters:

* email(String) : xuwuyuan007@gmail.com

response:  
检测不重复 操作成功
检测重复 操作失败
```json
{
  "data": "",
  "code": 1000200,
  "message": "操作成功"
}
```
