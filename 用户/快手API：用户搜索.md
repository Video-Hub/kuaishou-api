# 快手API：用户搜索
## 快手视频API、快手爬虫、快手去水印、快手视频下载、快手视频解析


---

#### TiToData：专业的短视频数据采集、处理平台。
#### 更多信息请联系： [TiToData](https://www.titodata.com?from=kuaishouAPI)

```
海量数据采集
每天为客户采集5亿条数据
覆盖主流平台：TikTok，Zynn，YouTube，抖音，快手，1688，小红书，拼多多，淘宝，美团，饿了么，淘宝，微博
联系vx：ifuxing123
```


## 快手API：用户搜索

### 请求API
```http
http://主机地址/kwshow/search/users?token=xxx&keyword=美女

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
| keyword | string | 搜索关键词 |
| cursor | int | 翻页游标，根据结果返回的cursor传入作为下一页翻页参数，初始为0 |


### 

### 返回示例
```json

{
    "code": 200,
    "data": {
        "result": 1,
        "pcursor": "3",
        "host-name": "bjzyx-c3910.zqy",
        "ussid": "MzAwXzE3NTMxODM4OTZfMTYwNTMxNzQ5NDA3Nl9fNjQ5Mg",
        "users": [
            {
                "kwaiId": "pppjjjy6",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1216146931,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/08/18/16/BMjAyMDA4MTgxNjI2NTNfMTIxNjE0NjkzMV8xX2hkMjMxXzQ4Mg==_s.jpg",
                "user_text": "用伊对找对象，真的靠谱",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/08/18/16/BMjAyMDA4MTgxNjI2NTNfMTIxNjE0NjkzMV8xX2hkMjMxXzQ4Mg==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/08/18/16/BMjAyMDA4MTgxNjI2NTNfMTIxNjE0NjkzMV8xX2hkMjMxXzQ4Mg==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/08/18/16/BMjAyMDA4MTgxNjI2NTNfMTIxNjE0NjkzMV8xX2hkMjMxXzQ4Mg==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女等你在本地"
            },
            {
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 607954334,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/06/13/17/BMjAyMDA2MTMxNzUzMzNfNjA3OTU0MzM0XzFfaGQ2ODhfNDky_s.jpg",
                "user_text": "感谢相遇，这场生命中最美的遇见，希望能长久能开心，不负遇见！",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/06/13/17/BMjAyMDA2MTMxNzUzMzNfNjA3OTU0MzM0XzFfaGQ2ODhfNDky_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/06/13/17/BMjAyMDA2MTMxNzUzMzNfNjA3OTU0MzM0XzFfaGQ2ODhfNDky_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/06/13/17/BMjAyMDA2MTMxNzUzMzNfNjA3OTU0MzM0XzFfaGQ2ODhfNDky_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "琴琴美女来了"
            },
            {
                "kwaiId": "s520888888",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 298053996,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2019/07/03/16/BMjAxOTA3MDMxNjIyNDZfMjk4MDUzOTk2XzFfaGQ4MzhfMjk2_s.jpg",
                "user_text": "感谢快手提供的绿色直播平台！\n街拍分享不同类型作品和美女🌹",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2019/07/03/16/BMjAxOTA3MDMxNjIyNDZfMjk4MDUzOTk2XzFfaGQ4MzhfMjk2_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2019/07/03/16/BMjAxOTA3MDMxNjIyNDZfMjk4MDUzOTk2XzFfaGQ4MzhfMjk2_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2019/07/03/16/BMjAxOTA3MDMxNjIyNDZfMjk4MDUzOTk2XzFfaGQ4MzhfMjk2_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "厦门美女街拍榜"
            },
            {
                "kwaiId": "dazi9309",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 388473775,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/01/29/09/BMjAyMDAxMjkwOTE5NDNfMzg4NDczNzc1XzJfaGQ3OThfNDMx_s.jpg",
                "user_text": "带你们看什么叫真正的美女\n如果口味相同，请留个关注",
                "user_sex": "M",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/01/29/09/BMjAyMDAxMjkwOTE5NDNfMzg4NDczNzc1XzJfaGQ3OThfNDMx_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/01/29/09/BMjAyMDAxMjkwOTE5NDNfMzg4NDczNzc1XzJfaGQ3OThfNDMx_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/01/29/09/BMjAyMDAxMjkwOTE5NDNfMzg4NDczNzc1XzJfaGQ3OThfNDMx_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "达哥（收藏美女）"
            },
            {
                "kwaiId": "mote5566",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 2058895067,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/10/24/12/BMjAyMDEwMjQxMjI5MTJfMjA1ODg5NTA2N18xX2hkODhfNTMw_s.jpg",
                "user_text": "感谢快手提供平台：",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/10/24/12/BMjAyMDEwMjQxMjI5MTJfMjA1ODg5NTA2N18xX2hkODhfNTMw_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/10/24/12/BMjAyMDEwMjQxMjI5MTJfMjA1ODg5NTA2N18xX2hkODhfNTMw_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/10/24/12/BMjAyMDEwMjQxMjI5MTJfMjA1ODg5NTA2N18xX2hkODhfNTMw_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女模特"
            },
            {
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1657623,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/11/12/11/BMjAyMDExMTIxMTU2MjFfMTY1NzYyM18xX2hkODI5XzY0NA==_s.jpg",
                "user_text": "关注我，你就是姐姐的人了，要开心哟^_^\n如有侵权请告知删除",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/11/12/11/BMjAyMDExMTIxMTU2MjFfMTY1NzYyM18xX2hkODI5XzY0NA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/11/12/11/BMjAyMDExMTIxMTU2MjFfMTY1NzYyM18xX2hkODI5XzY0NA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/11/12/11/BMjAyMDExMTIxMTU2MjFfMTY1NzYyM18xX2hkODI5XzY0NA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "姐姐带你看美女"
            },
            {
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1970546107,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/09/10/08/BMjAyMDA5MTAwODQwNDFfMTk3MDU0NjEwN18xX2hkNTQ4XzM3NA==_s.jpg",
                "user_text": "本人单身\n\n喜欢就关注我一下吧",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/09/10/08/BMjAyMDA5MTAwODQwNDFfMTk3MDU0NjEwN18xX2hkNTQ4XzM3NA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/09/10/08/BMjAyMDA5MTAwODQwNDFfMTk3MDU0NjEwN18xX2hkNTQ4XzM3NA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/09/10/08/BMjAyMDA5MTAwODQwNDFfMTk3MDU0NjEwN18xX2hkNTQ4XzM3NA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女裁判太阳姐"
            },
            {
                "kwaiId": "dedaoxitong",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 31896005,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/07/20/22/BMjAyMDA3MjAyMjA0MTVfMzE4OTYwMDVfMV9oZDI4N18xOTU=_s.jpg",
                "user_text": "谢谢你的关注 每天中午12点 晚上八点更新视频\n晚上八点直播\n👨助理V：15685723805\n👕创业V:weo1818\n👖记住我的名字和我带给你的故事！",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/07/20/22/BMjAyMDA3MjAyMjA0MTVfMzE4OTYwMDVfMV9oZDI4N18xOTU=_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/07/20/22/BMjAyMDA3MjAyMjA0MTVfMzE4OTYwMDVfMV9oZDI4N18xOTU=_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/07/20/22/BMjAyMDA3MjAyMjA0MTVfMzE4OTYwMDVfMV9oZDI4N18xOTU=_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "我的美女BOSS呀"
            },
            {
                "kwaiId": "liuwei0828",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 767396765,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/08/06/06/BMjAyMDA4MDYwNjQ4NDBfNzY3Mzk2NzY1XzFfaGQ4MDdfNDA3_s.jpg",
                "user_text": "喜欢的依旧喜欢着。❤️",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/08/06/06/BMjAyMDA4MDYwNjQ4NDBfNzY3Mzk2NzY1XzFfaGQ4MDdfNDA3_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/08/06/06/BMjAyMDA4MDYwNjQ4NDBfNzY3Mzk2NzY1XzFfaGQ4MDdfNDA3_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/08/06/06/BMjAyMDA4MDYwNjQ4NDBfNzY3Mzk2NzY1XzFfaGQ4MDdfNDA3_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "刘大美女.❣"
            },
            {
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1046313745,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/07/28/18/BMjAyMDA3MjgxODI1NDJfMTA0NjMxMzc0NV8yX2hkNjRfOTQw_s.jpg",
                "user_text": "想看美女就点关注。",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/07/28/18/BMjAyMDA3MjgxODI1NDJfMTA0NjMxMzc0NV8yX2hkNjRfOTQw_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/07/28/18/BMjAyMDA3MjgxODI1NDJfMTA0NjMxMzc0NV8yX2hkNjRfOTQw_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/07/28/18/BMjAyMDA3MjgxODI1NDJfMTA0NjMxMzc0NV8yX2hkNjRfOTQw_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "图片美女姐"
            },
            {
                "kwaiId": "UFMT99ha",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1740024015,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/02/20/23/BMjAyMDAyMjAyMzI5MzlfMTc0MDAyNDAxNV8xX2hkNTAwXzY3MQ==_s.jpg",
                "user_text": "感谢快手官方呀 爱宁💟\n⭐️UFMT88（接推）备注来意\n喜欢美女 分享美女 可投稿！",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/02/20/23/BMjAyMDAyMjAyMzI5MzlfMTc0MDAyNDAxNV8xX2hkNTAwXzY3MQ==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/02/20/23/BMjAyMDAyMjAyMzI5MzlfMTc0MDAyNDAxNV8xX2hkNTAwXzY3MQ==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/02/20/23/BMjAyMDAyMjAyMzI5MzlfMTc0MDAyNDAxNV8xX2hkNTAwXzY3MQ==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女鉴定所8"
            },
            {
                "kwaiId": "wml23876asd",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1812432980,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/11/13/23/BMjAyMDExMTMyMzA0NTNfMTgxMjQzMjk4MF8yX2hkNjg3XzY3NQ==_s.jpg",
                "user_text": "拿原图➕QQ：10339159（相册）\n接推广（骗人不要来）或者投稿 加Q3095616832 风格不定",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/11/13/23/BMjAyMDExMTMyMzA0NTNfMTgxMjQzMjk4MF8yX2hkNjg3XzY3NQ==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/11/13/23/BMjAyMDExMTMyMzA0NTNfMTgxMjQzMjk4MF8yX2hkNjg3XzY3NQ==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/11/13/23/BMjAyMDExMTMyMzA0NTNfMTgxMjQzMjk4MF8yX2hkNjg3XzY3NQ==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女生吃一个人"
            },
            {
                "kwaiId": "sm090717",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 75586604,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/03/07/22/BMjAyMDAzMDcyMjE5MzVfNzU1ODY2MDRfMV9oZDY3Nl81MjI=_s.jpg",
                "user_text": "👤她正在关注你哦\n\n私信有空就回，一般不看私信🔋",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/03/07/22/BMjAyMDAzMDcyMjE5MzVfNzU1ODY2MDRfMV9oZDY3Nl81MjI=_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/03/07/22/BMjAyMDAzMDcyMjE5MzVfNzU1ODY2MDRfMV9oZDY3Nl81MjI=_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/03/07/22/BMjAyMDAzMDcyMjE5MzVfNzU1ODY2MDRfMV9oZDY3Nl81MjI=_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "i-美女女🌾"
            },
            {
                "kwaiId": "jltd7777",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 1854383536,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/10/02/11/BMjAyMDEwMDIxMTAwMDRfMTg1NDM4MzUzNl8yX2hkMjk0XzQ3Ng==_s.jpg",
                "user_text": "世界美女尽收眼底",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/10/02/11/BMjAyMDEwMDIxMTAwMDRfMTg1NDM4MzUzNl8yX2hkMjk0XzQ3Ng==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/10/02/11/BMjAyMDEwMDIxMTAwMDRfMTg1NDM4MzUzNl8yX2hkMjk0XzQ3Ng==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/10/02/11/BMjAyMDEwMDIxMTAwMDRfMTg1NDM4MzUzNl8yX2hkMjk0XzQ3Ng==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女模特"
            },
            {
                "kwaiId": "xiaotiantian666",
                "following": false,
                "verified": false,
                "visitorBeFollowed": false,
                "user_id": 531508502,
                "headurl": "https://tx2.a.yximgs.com/uhead/AB/2020/06/24/18/BMjAyMDA2MjQxODU1MDhfNTMxNTA4NTAyXzFfaGQ2NjRfODE2_s.jpg",
                "user_text": "🌈感谢陪伴 你来我热情相拥\n\n只有一个v✉️：1021053253",
                "user_sex": "F",
                "headurls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/06/24/18/BMjAyMDA2MjQxODU1MDhfNTMxNTA4NTAyXzFfaGQ2NjRfODE2_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/06/24/18/BMjAyMDA2MjQxODU1MDhfNTMxNTA4NTAyXzFfaGQ2NjRfODE2_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/06/24/18/BMjAyMDA2MjQxODU1MDhfNTMxNTA4NTAyXzFfaGQ2NjRfODE2_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "isFavorited": false,
                "user_name": "美女姐姐_Tian🍓"
            }
        ]
    },
    "msg": "success",
    "app": "kwshow"
}
```


