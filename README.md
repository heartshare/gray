# gray灰度方案
1. nginx+lua 开发的灰度方案、轻量级
2. 按流量灰度、支持多个级别 比如:0.01% -> 1% -> 20% -> 50% -> 100% 流量依次递增
3. 默认路由到老系统、支持配置100%流量路由到新系统

本项目已在我们生产环境中使用
