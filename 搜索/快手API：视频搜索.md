# 快手API：视频搜索
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


## 快手API：视频搜索

### 请求API
```http
http://主机地址/kwshow/search/videos?token=xxx&keyword=美女

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
        "feeds": [
            {
                "following": 0,
                "video": true,
                "type": 1,
                "forwardCount": 0,
                "headUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "webpCoverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_B6f835ac13450cead7c54da69aa0cbc92.jpg?clientCacheKey=3x76e7k52hd8r66.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_B6f835ac13450cead7c54da69aa0cbc92.jpg?clientCacheKey=3x76e7k52hd8r66.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "userId": 1805816224,
                "viewCount": 18538638,
                "headUrl": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                "verifiedDetail": {
                    "description": "贵州台《综艺最前沿》官方帐号",
                    "iconType": 2,
                    "musicCompany": false,
                    "newVerified": true,
                    "type": 7
                },
                "verified": true,
                "width": 720,
                "height": 1280,
                "commentCount": 17548,
                "likeCount": 705187,
                "userSex": "M",
                "shareCount": 6418,
                "coverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_B6f835ac13450cead7c54da69aa0cbc92.jpg?clientCacheKey=3x76e7k52hd8r66.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_B6f835ac13450cead7c54da69aa0cbc92.jpg?clientCacheKey=3x76e7k52hd8r66.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "mainMvUrls": [
                    {
                        "cdn": "txmov2.a.yximgs.com",
                        "url": "https://txmov2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_b_B3e50ac8eab647a570a4cc1eb5d0a8079.mp4?clientCacheKey=3x76e7k52hd8r66_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "jsmov2.a.yximgs.com",
                        "url": "https://jsmov2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_b_B3e50ac8eab647a570a4cc1eb5d0a8079.mp4?clientCacheKey=3x76e7k52hd8r66_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    }
                ],
                "singlePicture": false,
                "timestamp": 1599967226758,
                "userName": "贵州台综艺最前沿",
                "isSubscribe": false,
                "liked": 0,
                "webShareInfo": {
                    "smartCorpUrl": "https://tx2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_crop_intelli_B669ea1660145e2efd0d13c3077d0fe86.jpg?clientCacheKey=3x76e7k52hd8r66_crop_intelli.jpg&di=3a65aec6&bp=14150",
                    "preCorpUrl": "https://tx2.a.yximgs.com/upic/2020/09/13/10/BMjAyMDA5MTMxMDIzNTJfMTgwNTgxNjIyNF8zNTk1OTgyNDMwNF8wXzM=_crop_intelli_B669ea1660145e2efd0d13c3077d0fe86.jpg?tag=1-1605317582-unknown-0-mtmax5juyg-b557c206623934a8&clientCacheKey=3x76e7k52hd8r66_crop_intelli.jpg&di=3a65aec6&bp=13463",
                    "webShareTitle": "##非常完美 # ##美女 # ##男神 #",
                    "webShareVerifyData": {
                        "shareUserId": "1753183896",
                        "objectId": "35959824304",
                        "timestamp": 1605317582898,
                        "verifyData": "8730ebc3610a32081b2b0db633ac2989"
                    }
                },
                "share_info": "userId=3xfrkacxd7a8qba&photoId=3x76e7k52hd8r66",
                "photoId": "5249508350589478128",
                "userEid": "3xfrkacxd7a8qba",
                "sameFrame": {
                    "allow": false
                },
                "adminTags": [],
                "exp_tag": "1_u/0_unknown0",
                "ext_params": {
                    "mtype": 3,
                    "color": "5E5557",
                    "w": 720,
                    "sound": 148866,
                    "h": 1280,
                    "interval": 29,
                    "video": 148866
                },
                "caption": "##非常完美 # ##美女 # ##男神 #",
                "serverExpTag": "feed_photo|5249508350589478128|1805816224|1_u/0_unknown0"
            },
            {
                "following": 0,
                "video": true,
                "type": 1,
                "forwardCount": 0,
                "headUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "webpCoverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_B202ed0fde0936e27e8865766fc27d83c.jpg?clientCacheKey=3x6jdw47b7hs8ck.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_B202ed0fde0936e27e8865766fc27d83c.jpg?clientCacheKey=3x6jdw47b7hs8ck.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "userId": 1805816224,
                "viewCount": 1513038,
                "headUrl": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                "verifiedDetail": {
                    "description": "贵州台《综艺最前沿》官方帐号",
                    "iconType": 2,
                    "musicCompany": false,
                    "newVerified": true,
                    "type": 7
                },
                "verified": true,
                "width": 720,
                "height": 1280,
                "commentCount": 239,
                "likeCount": 17351,
                "userSex": "M",
                "coverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_B202ed0fde0936e27e8865766fc27d83c.jpg?clientCacheKey=3x6jdw47b7hs8ck.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_B202ed0fde0936e27e8865766fc27d83c.jpg?clientCacheKey=3x6jdw47b7hs8ck.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "mainMvUrls": [
                    {
                        "cdn": "txmov2.a.yximgs.com",
                        "url": "https://txmov2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_b_Bf9406657b75838348eaeafe2da6539d7.mp4?clientCacheKey=3x6jdw47b7hs8ck_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "jsmov2.a.yximgs.com",
                        "url": "https://jsmov2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_b_Bf9406657b75838348eaeafe2da6539d7.mp4?clientCacheKey=3x6jdw47b7hs8ck_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    }
                ],
                "singlePicture": false,
                "timestamp": 1603208190240,
                "userName": "贵州台综艺最前沿",
                "isSubscribe": false,
                "liked": 0,
                "webShareInfo": {
                    "smartCorpUrl": "https://tx2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_crop_5x4_Be9c21d3b4d2033375e4ea843866c71f0.jpg?clientCacheKey=3x6jdw47b7hs8ck_crop_5x4.jpg&di=3a65aec6&bp=14150",
                    "preCorpUrl": "https://tx2.a.yximgs.com/upic/2020/10/20/23/BMjAyMDEwMjAyMzIyMTZfMTgwNTgxNjIyNF8zODAwMDE4NTU5M18wXzM=_crop_5x4_Be9c21d3b4d2033375e4ea843866c71f0.jpg?tag=1-1605317582-unknown-0-djohiklnpr-7df4d6e424b1977d&clientCacheKey=3x6jdw47b7hs8ck_crop_5x4.jpg&di=3a65aec6&bp=13463",
                    "webShareTitle": "#非常完美 # #美女 # #男神 #",
                    "webShareVerifyData": {
                        "shareUserId": "1753183896",
                        "objectId": "38000185593",
                        "timestamp": 1605317582898,
                        "verifyData": "5274dd5fd5f275f7fd479f112bf6a5ee"
                    }
                },
                "share_info": "userId=3xfrkacxd7a8qba&photoId=3x6jdw47b7hs8ck",
                "photoId": "5255419325724830468",
                "userEid": "3xfrkacxd7a8qba",
                "sameFrame": {
                    "allow": false
                },
                "adminTags": [],
                "exp_tag": "1_u/0_unknown0",
                "ext_params": {
                    "mtype": 3,
                    "color": "0C154B",
                    "w": 720,
                    "sound": 101717,
                    "h": 1280,
                    "interval": 30,
                    "video": 101686
                },
                "caption": "#非常完美 # #美女 # #男神 #",
                "serverExpTag": "feed_photo|5255419325724830468|1805816224|1_u/0_unknown0"
            },
            {
                "following": 0,
                "video": true,
                "type": 1,
                "forwardCount": 0,
                "headUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                        "urlPattern": "https://js2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg@base@tag%3DimgScale%26r%3D0%26q%3D85%26w%3D{w}%26h%3D{h}%26rotate"
                    }
                ],
                "webpCoverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_B3a1862f2abf47b2af4a78dab626c45ba.jpg?clientCacheKey=3xj2fnqrjs3vtww.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_B3a1862f2abf47b2af4a78dab626c45ba.jpg?clientCacheKey=3xj2fnqrjs3vtww.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "userId": 1805816224,
                "viewCount": 162810,
                "headUrl": "https://tx2.a.yximgs.com/uhead/AB/2020/07/10/14/BMjAyMDA3MTAxNDEzMjZfMTgwNTgxNjIyNF8yX2hkNzM0XzE0NA==_s.jpg",
                "verifiedDetail": {
                    "description": "贵州台《综艺最前沿》官方帐号",
                    "iconType": 2,
                    "musicCompany": false,
                    "newVerified": true,
                    "type": 7
                },
                "verified": true,
                "width": 720,
                "height": 1280,
                "commentCount": 7,
                "likeCount": 1392,
                "userSex": "M",
                "coverUrls": [
                    {
                        "cdn": "tx2.a.yximgs.com",
                        "url": "https://tx2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_B3a1862f2abf47b2af4a78dab626c45ba.jpg?clientCacheKey=3xj2fnqrjs3vtww.jpg&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "js2.a.yximgs.com",
                        "url": "https://js2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_B3a1862f2abf47b2af4a78dab626c45ba.jpg?clientCacheKey=3xj2fnqrjs3vtww.jpg&di=3a65aec6&bp=14150"
                    }
                ],
                "mainMvUrls": [
                    {
                        "cdn": "txmov2.a.yximgs.com",
                        "url": "https://txmov2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_b_Bf10e2e1a5febbfd26afe5a2df37bff0c.mp4?clientCacheKey=3xj2fnqrjs3vtww_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    },
                    {
                        "cdn": "jsmov2.a.yximgs.com",
                        "url": "https://jsmov2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_b_Bf10e2e1a5febbfd26afe5a2df37bff0c.mp4?clientCacheKey=3xj2fnqrjs3vtww_b.mp4&tt=b&di=3a65aec6&bp=14150"
                    }
                ],
                "singlePicture": false,
                "timestamp": 1604243873731,
                "userName": "贵州台综艺最前沿",
                "isSubscribe": false,
                "liked": 0,
                "webShareInfo": {
                    "smartCorpUrl": "https://tx2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_crop_5x4_Bde7fb99b0f4c47d5210c5d3848e2b51e.jpg?clientCacheKey=3xj2fnqrjs3vtww_crop_5x4.jpg&di=3a65aec6&bp=14150",
                    "preCorpUrl": "https://tx2.a.yximgs.com/upic/2020/11/01/23/BMjAyMDExMDEyMzEwNTJfMTgwNTgxNjIyNF8zODYxNDQ4MTM4MF8wXzM=_crop_5x4_Bde7fb99b0f4c47d5210c5d3848e2b51e.jpg?tag=1-1605317582-unknown-0-xznwi7slul-e07fc9c11b60b3e3&clientCacheKey=3xj2fnqrjs3vtww_crop_5x4.jpg&di=3a65aec6&bp=13463",
                    "webShareTitle": "#非常完美 #美女 #男神 #",
                    "webShareVerifyData": {
                        "shareUserId": "1753183896",
                        "objectId": "38614481380",
                        "timestamp": 1605317582898,
                        "verifyData": "8df572d4bf4e041c564c698ccbad4b27"
                    }
                },
                "share_info": "userId=3xfrkacxd7a8qba&photoId=3xj2fnqrjs3vtww",
                "photoId": "5212072179702248920",
                "userEid": "3xfrkacxd7a8qba",
                "sameFrame": {
                    "allow": false
                },
                "adminTags": [],
                "exp_tag": "1_u/0_unknown0",
                "ext_params": {
                    "mtype": 3,
                    "color": "21202D",
                    "w": 720,
                    "sound": 101675,
                    "h": 1280,
                    "interval": 30,
                    "video": 101633
                },
                "caption": "#非常完美 #美女 #男神 #",
                "serverExpTag": "feed_photo|5212072179702248920|1805816224|1_u/0_unknown0"
            }
        ],
        "pcursor": "3",
        "host-name": "bjfk-rs7180.yz02",
        "ussid": "MTRfMTc1MzE4Mzg5Nl8xNjA1MzE3NTgyNTAwX18xOTcw"
    },
    "msg": "success",
    "app": "kwshow"
}
```


