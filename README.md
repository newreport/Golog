# Golog
一个跨平台的Blog项目
# V1
##  开发环境
> 基于 MySQL 8.0——.NET6( EF Core+ C#10 + IOC(三层) + WebAPI + JWT + Log4Net + VS2022)——VUE3( Axios + TypeScript + VS Code)  
> 安卓基于kotlin
> IOS基于Swift

## 部署环境
### Linux单机部署
1. MySQL——CnetOS 8.2
2. API——CentOS 8.2 .NET 6 RunTime Kestrel自托管
3. VUE3——Nginx 反向代理

### Docker单机部署
1. MySQL——Docker 20.10.16 挂载目录进行持久化
2. API——Docker 20.10.16  无状态服务.NET 6 RunTime Kestrel自托管
3. VUE3——Docker 20.10.16

### K8S集群部署
1. MySQL
2. API——.NET 6 RunTime Kestrel自托管
3. VUE3——Naginx镜像
4. 监控——Prometheus

