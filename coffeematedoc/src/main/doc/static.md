#上传文章主图

**uploadImage**  

访问路径：http://static-api.ivysboy.com/CMStaticResource/upload/uploadImage

method: upload

request parameters: 

* file(data)
* articleId(String) : "123456"

response:  

```json
{
  "readable": true,
  "original": "4ed471e7-f480-4441-8256-9466708016e6.jpg",
  "name": "4ed471e7-f480-4441-8256-9466708016e6.jpg",
  "title": "4ed471e7-f480-4441-8256-9466708016e6.jpg",
  "url": "images/4ed471e7-f480-4441-8256-9466708016e6.jpg",
  "status": "SUCCESS"
}
```