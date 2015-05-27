---
category: gallery
path: '/api/photo/qiniu_image/'
title: '获取qiniu uptoken'
type: 'POST'

layout: nil
---

获取七牛上传token

### Request

```
{
    qiniu_key: 'image_name.jpg',
}
```

### Response

```Status: 201 OK```
```
{
   qiniu_key: 'upload/123-1231-123-123/image_name.jpg',
   uptoken: '1234567asdfasdf2039togjasodf01-349'
}
```
