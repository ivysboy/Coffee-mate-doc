#首页banner

**banner**  

访问路径：http://api.ivysboy.com/home/banner

method: GET

request parameters: 

* null

response:  

```json
{
  "data": {
    "id": "123",
    "title": "咖啡历史起源",
    "brief": "咖啡的历史起源和传播",
    "image": "http://static.ivysboy.com/images/9ebe7b30-7476-4ed6-9ae1-5fa1bafd1a55.jpg",
    "auther": "小宝咖啡厅",
    "articleId": "0d982266-9299-40d7-bbe0-a2e8f502523d"
  },
  "code": 1000200,
  "message": "操作成功"
}
```

#首页内容列表

**contentList**  

访问路径：http://api.ivysboy.com/home/contentList

method: GET

request parameters: 

* null

response:  

```json
{
    "resultCode": 200,
    "mag": "success",
    "data": [
      {
        "title" : "咖啡的历史及起源",
        "groupId" : "123",
        "articleList" : [
          {
            "id":"123",
            "title" : "haha",
            "brief" : "介绍",
            "image" : "http://www.baidu.com/1.png"
          },
          {
              "id":"123",
              "title" : "haha",
              "brief" : "介绍",
              "image" : "http://www.baidu.com/1.png"
          }
        ]
      },
      {
          "title" : "手冲咖啡",
          "groupId" : "123",
          "articleList" : [
            {
              "id":"123",
              "title" : "haha",
              "brief" : "介绍",
              "image" : "http://www.baidu.com/1.png"
            },
            {
                "id":"123",
                "title" : "haha",
                "brief" : "介绍",
                "image" : "http://www.baidu.com/1.png"
            }
          ]
      }
    ]
}
```