# aisle-sop
这是中国人民公安大学学生心理素质教育中心的SOP的基础服务容器仓库  

## 如何部署
1. 内网配置postgresql数据库和内网nfs服务，并填入docker-compose文件和.env文件中
2. 在同个vpc（或云联网）下的计算单元内运行本仓库容器  
`sudo docker-compose up -d`

## 如何使用
浏览器打开[SOP首页](http://sop.ruofengx.cn)