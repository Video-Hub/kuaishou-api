# 快手API：视频评论的子评论
## 快手视频API、快手爬虫、快手去水印、快手视频下载、快手视频解析


---

#### TiToData：专业的短视频、直播数据接口服务平台。
#### 更多信息请联系： [TiToData](https://www.titodata.com?from=kuaishouAPI)
覆盖主流平台：抖音，快手，小红书，TikTok，YouTube



## 快手API：视频评论的子评论

### 请求API
```http
http://主机地址/kwshow/video/sub/comments?token=xxx&photoId=5254293427996693557&rootCommentId=266591870402

```

### 

### 请求方式
```http
GET
```

### 

### 参数

| 字段 | 类型 | 说明 |
| --- | --- | --- |
| token | string | 接口授权码 |
| photoId | string | 视频的photoId，可以是5190398608707912800这个格式或者3xr4s9mcx8x8axm这个格式 |
| rootCommentId | int | 一级评论的id |
| cursor | int | 翻页游标，根据结果返回的cursor传入作为下一页翻页参数，初始为0 |


### 

### 返回示例
```json

{
    "code": 200,
    "data": {
        "result": 1,
        "pcursor": "269358157849",
        "host-name": "sd-bjpg-rs768.yz02",
        "subComments": [
            {
                "content": "机智[赞]",
                "replyToUserName": "凉凉的18",
                "commentBottomTags": [],
                "likedCount": 105,
                "time": "2020-10-10 12:46:02",
                "timestamp": 1602305161670,
                "type": 0,
                "photo_id": "5254293427996693557",
                "author_liked": false,
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2019/04/20/13/BMjAxOTA0MjAxMzI5MzVfNDMzMTg3NTY1XzFfaGQ2NjVfMTQw_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2019/04/20/13/BMjAxOTA0MjAxMzI5MzVfNDMzMTg3NTY1XzFfaGQ2NjVfMTQw_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2019/04/20/13/BMjAxOTA0MjAxMzI5MzVfNDMzMTg3NTY1XzFfaGQ2NjVfMTQw_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "user_id": 433187565,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2019/04/20/13/BMjAxOTA0MjAxMzI5MzVfNDMzMTg3NTY1XzFfaGQ2NjVfMTQw_s.jpg",
                "author_id": 433187565,
                "comment_id": 266672673226,
                "reply_to": 977032978,
                "user_sex": "F",
                "author_name": "车行鹿姐"
            },
            {
                "content": "我遇到过，很多年前的事",
                "replyToUserName": "凉凉的18",
                "commentBottomTags": [],
                "likedCount": 7,
                "time": "2020-10-10 21:56:36",
                "timestamp": 1602338196457,
                "type": 0,
                "photo_id": "5254293427996693557",
                "author_liked": false,
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/08/23/17/BMjAyMDA4MjMxNzAzMjlfMjA2NDU5OTYxMl8yX2hkOTQ4XzEwOA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/08/23/17/BMjAyMDA4MjMxNzAzMjlfMjA2NDU5OTYxMl8yX2hkOTQ4XzEwOA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/08/23/17/BMjAyMDA4MjMxNzAzMjlfMjA2NDU5OTYxMl8yX2hkOTQ4XzEwOA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "user_id": 433187565,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/08/23/17/BMjAyMDA4MjMxNzAzMjlfMjA2NDU5OTYxMl8yX2hkOTQ4XzEwOA==_s.jpg",
                "author_id": 2064599612,
                "comment_id": 266831095277,
                "reply_to": 977032978,
                "user_sex": "U",
                "author_name": "蓝色梦境"
            },
            {
                "content": "-[赞]",
                "replyToUserName": "车行鹿姐",
                "commentBottomTags": [],
                "likedCount": 2,
                "time": "2020-10-10 22:16:14",
                "timestamp": 1602339373848,
                "type": 0,
                "photo_id": "5254293427996693557",
                "author_liked": false,
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2019/10/25/22/BMjAxOTEwMjUyMjMwMjJfMTU0ODQ4OTE0M18yX2hkNjk3Xzc5OQ==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2019/10/25/22/BMjAxOTEwMjUyMjMwMjJfMTU0ODQ4OTE0M18yX2hkNjk3Xzc5OQ==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2019/10/25/22/BMjAxOTEwMjUyMjMwMjJfMTU0ODQ4OTE0M18yX2hkNjk3Xzc5OQ==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "user_id": 433187565,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2019/10/25/22/BMjAxOTEwMjUyMjMwMjJfMTU0ODQ4OTE0M18yX2hkNjk3Xzc5OQ==_s.jpg",
                "author_id": 1548489143,
                "comment_id": 266839371945,
                "reply_to": 433187565,
                "user_sex": "F",
                "author_name": "婷婷92745"
            }
        ]
    },
    "msg": "success",
    "app": "kwshow"
}
```


