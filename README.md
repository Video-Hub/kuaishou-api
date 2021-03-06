# 快手Api：搜索、视频、用户
## 快手视频Api、快手爬虫、快手去水印、快手视频下载、快手视频解析


---

### 免责声明
```
有任何问题可交流学习, 微信: 1764328791
请勿使用本服务于商用
请勿使用本服务大量抓取
若因使用本服务与快手造成不必要的纠纷，本人盖不负责
本人纯粹技术爱好，若侵犯快手贵公司的权益，请告知
```


# 接口列表：

## 搜索

- 关键词搜索用户
- 关键词搜索视频

## 用户

- 用户信息
- 用户视频列表

## 视频

- 视频评论列表
- 视频评论的回复列表


# 视频列表接口示例如下：

### 请求地址


```http
GET http://api2.主机地址.com/api/video/lists
```


### 请求参数
| 名称 | 必填 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| token | 是 | string | 登录令牌 |
| create_time_start | 否 | int | 视频发布时间戳，开始时间 |
| create_time_end | 否 | int | 视频发布时间戳，结束时间 |
| author_id | 否 | int | 作者id |
| sort_field | 否 | string | 排序字段，默认digg_count，可选项：digg_count、comment_count、share_count |
| sort | 否 | string | 排序，默认desc，可选项：desc、asc |
| page | 否 | int | 默认第1页，最大100页 |
| page_size | 否 | int | 默认20条，最大100条每页 |
| min_digg_count | 否 | int | 最小点赞数 |
| min_comment_count | 否 | int | 最小评论数 |
| min_share_count | 否 | int | 最小分享数 |
| min_duration | 否 | int | 最小时长，毫秒为单位 |




### 返回参数

```json
{
    "code": 200,
    "msg": "成功",
    "data": {
        "total": 5000,
        "per_page": 1,
        "current_page": 1,
        "last_page": 100,
        "data": [
            {
                "user_id": 104255897823,	//作者id
                "vid": 6865534331515964679,	//视频id
                "user_nickname": "人民日报",	//作者昵称
                "user_avatar": "https:\/\/p3-dy-ipv6.byteimg.com\/aweme\/100x100\/30ed2000aad26be101cad.jpeg?from=4010531038",	//作者头像
                "desc": "珍贵视频！9年前袁隆平院士和钟南山院士的同台。今天袁老90岁生日，生日快乐，也愿两位都健康快乐！",	//视频描述
                "uri": "v0200fd60000bt3ke2te6v18nvs8q5q0",	//视频资源定位id
                "cover": "http:\/\/p3-dy-ipv6.byteimg.com\/large\/tos-cn-p-0015\/e6240ccea8a84ff5a77b514ccdf00bc7_1598506787.webp?from=2563711402_large",	//视频封面
                "play_addr_mark": "https:\/\/aweme.snssdk.com\/aweme\/v1\/playwm?video_id=v0200fd60000bt3ke2te6v18nvs8q5q0",	//视频播放地址，带水印
                "duration": 23840,	//视频时长，毫秒
                "digg_count": 12119790,	//点赞数
                "comment_count": 315139,	//评论数
                "share_count": 76000,	//分享数
                "create_time": "2020-08-27 13:39:41",	//时间发布时间
                "category": "政企",	//分类，26个分类
                "tag": "社会"	//标签，可选项：搞笑、生活、社会
            }
        ]
    }
}
```

![](https://visitor-badge.laobi.icu/badge?page_id=Video-Hub.kuaishou-api)


