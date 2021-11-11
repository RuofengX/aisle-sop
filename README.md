# aisle-sop
这是中国人民公安大学学生心理素质教育中心的SOP的基础服务容器仓库，心理中心SOP的数据库NFS系统已部署在weiruofeng@ruofengx.cn的腾讯云南京地区的内网上。  

## 如何部署心理中心SOP
1. 联系weiruofeng@ruofengx.cn，通过云联网构建跨账号同地域VPC的互通。
2. 运行容器 `sudo docker-compose up -d`

## 相关项目
- [aisle-reverse](https://gitee.com/ruofengx/aisle-reverse) 快速部署nginx反代内网服务的容器
