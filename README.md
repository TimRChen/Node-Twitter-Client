# Node-Douban-Client
    该项目包含了三个文件，其中server.js与client.js为学习用http发送数据本地测试文件
    douban.js利用了豆瓣v2API电影接口
# 用于搜索豆瓣影人信息
    node douban.js + 影视作品/影人
    例如: node douban.js 张艺谋
# superDouban
    使用superagent模块，该模块会自动将数据进行缓存并解析，然后将数据放在res.body中

    node superDouban.js + 影视作品/影人