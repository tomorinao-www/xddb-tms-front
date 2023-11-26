# xddb-tms-front

使用百度低代码框架 amis 搭建的数据库大作业-公交安全管理系统-前端

amis 文档
https://aisuda.bce.baidu.com/amis

模板项目
https://github.com/aisuda/amis-admin

### 安装依赖

```bash
npm i
```

下载依赖到本地 `localpkg/`

| 依赖                                                                               | 本地路径                        |
| ---------------------------------------------------------------------------------- | ------------------------------- |
| [amis sdk](https://aisuda.bce.baidu.com/amis/zh-CN/docs/start/getting-started#sdk) | localpkg/amis/sdk               |
| [vue.js](https://unpkg.com/vue@2)                                                  | localpkg/vue/vue.js             |
| [history.js](https://unpkg.com/history@4.10.1)                                     | localpkg/history/umd/history.js |

### 启动

```bash
npm start
```

前端端口默认 3000，在`server.js`修改端口，或者使用.env 配置文件

后端默认`localhost:28080`，在`index.html`修改`API_HOST`
