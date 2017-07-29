#文章列表

**list**  

访问路径：http://api.ivysboy.com/articles/list

method: GET

request parameters: 

* page(int) : 1
* orderBy(String) : -create_time
* groupId(String) : 123

response:  

```json
{
  "data": [
    {
      "id": "987fea82-2dcc-4b38-a56d-a9e20e1c071a",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第三篇 现代",
      "image": "http://static.ivysboy.com/images/781a91e2-0a6a-4999-97d3-675277a040e6.png"
    },
    {
      "id": "e15beb86-1f50-4546-a488-c05788ff3ab0",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第二篇 发展",
      "image": "http://static.ivysboy.com/images/fa568a1b-8e55-4ec6-a465-9d21c5f9ce48.jpg"
    },
    {
      "id": "e09b634b-bb22-4649-9711-a985685edb83",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第一篇 起源",
      "image": "http://static.ivysboy.com/images/30da569a-e41e-414c-95aa-b4a004d1cdd2.jpg"
    }
  ],
  "message": "操作成功",
  "code": 1000200
}
```

#文章内容

**list**  

访问路径：http://api.ivysboy.com/articles/list

method: GET

request parameters: 

* page(int) : 1
* orderBy(String) : -create_time
* groupId(String) : 123

response:  

```json
{
  "data": [
    {
      "id": "987fea82-2dcc-4b38-a56d-a9e20e1c071a",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第三篇 现代",
      "image": "http://static.ivysboy.com/images/781a91e2-0a6a-4999-97d3-675277a040e6.png"
    },
    {
      "id": "e15beb86-1f50-4546-a488-c05788ff3ab0",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第二篇 发展",
      "image": "http://static.ivysboy.com/images/fa568a1b-8e55-4ec6-a465-9d21c5f9ce48.jpg"
    },
    {
      "id": "e09b634b-bb22-4649-9711-a985685edb83",
      "title": "咖啡基础知识介绍",
      "auther": "wuyuan",
      "brief": "第一篇 起源",
      "image": "http://static.ivysboy.com/images/30da569a-e41e-414c-95aa-b4a004d1cdd2.jpg"
    }
  ],
  "message": "操作成功",
  "code": 1000200
}
```
