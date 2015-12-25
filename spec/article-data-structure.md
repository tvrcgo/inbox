# 文章数据模型

```js
{
    title: '标题',
    summary: '摘要',
    meta: {
        keywords: '页面头关键字',
        description: '页面头描述'
    },
    content: '正文',
    author: [
        {
            name: '作者A姓名',
            duty: '职位'
        },
        {
            name: '作者B姓名',
            duty: '职位'
        }
    ],
    create_time: 1234567890123,
    publish_time: 1234567890123,
    update_time: 1234567890123,
    tags: [
        {
            name: '科比',
            sourceUrl: 'http://sport.com',
            type: 'custom'
        },
        {
            name: 'NBA',
            sourceUrl: 'http://sport.com',
            type: 'recommend'
        }
    ],
    category: [
        {
            name: '体育',
            id: 'sport'
        },
        {
            name: 'NBA',
            id: 'nba'
        }
    ]
    media: [
        {
            id: '资源ID',
            type: 'cover',
            url: '封面图片URL',
            title: '图片标题',
            summary: '描述',
            author: [{
                name: '拍摄者姓名'
            }]
        },
        {
            id: '资源ID',
            type: 'image',
            url: '普通图片URL',
            title: '图片标题',
            summary: '描述',
            author: [{
                name: '拍摄者姓名'
            }]
        },
        {
            id: '资源ID',
            type: 'video',
            url: '视频播放地址',
            title: '标题',
            summary: '描述',
            author: [{
                name: '拍摄者姓名'
            }]
        }
    ]
}
```
