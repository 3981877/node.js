# node.js
一个功能丰富的Node.js应用管理Shell脚本

```
bash <(curl -sL https://github.com/3981877/node.js/releases/download/1.2/node-manager.sh)
```
<img width="697" alt="截屏2025-03-23 20 38 51" src="https://github.com/user-attachments/assets/90364120-aa64-4e5b-bbbb-6a53d586f198" />

功能说明：

启动/停止/重启应用：支持PM2和普通模式两种进程管理方式

状态监控：实时显示应用运行状态

日志查看：自动记录日志并支持查看

依赖管理：一键安装生产依赖

测试运行：快速执行测试套件

环境清理：安全清理node_modules

版本管理：集成nvm版本控制（需预先安装）

生产环境支持：自动设置NODE_ENV环境变量

友好交互：彩色输出+菜单导航

使用说明：

将脚本保存为 

```node-manager.sh```

添加执行权限：

```chmod +x node-manager.sh```

修改开头的配置参数（应用名称、入口文件等）

运行脚本：

```
./node-manager.sh

```
高级功能扩展建议：

添加Docker支持

集成CI/CD流程

增加健康检查端点

支持集群模式启动

添加性能监控功能

集成Let's Encrypt自动证书

这个脚本通过菜单驱动的方式简化了Node.js应用的日常运维操作，特别适合需要频繁进行部署调试的开发环境。
