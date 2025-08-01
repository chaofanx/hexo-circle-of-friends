`v6.0.2` 更新说明：
```
- 📋 新增JSON配置文件解析功能，支持从JSON文件读取友链配置
```

`v6.0.1` 更新说明：
```
- 🚀 API服务支持自定义端口启动，支持命令行参数 `-p/--port` 指定端口
- 📝 完善 start.sh 脚本，支持交互式输入API服务端口，默认8000
- 🔧 优化日期时间解析函数，支持70+种日期格式，包括两位年份智能识别
- 📊 更新`css_rules.yaml`规则文件
- 🛡️ 添加反向屏蔽选项，增强过滤功能
- ⚙️ 调整最大文章数限制，默认为5篇
- 🗑️ 优化删除过期文章的逻辑
- ⏰ 改进文章时间获取和验证机制
- 🔍 增强错误处理和用户友好的提示信息
```

`v6.0.0` 更新说明：

```
- 🎯 简化部署方式，简化环境变量，甚至无需配置任何环境变量即可运行
- 🔧 支持用户自定义抓取规则，兼容页面更多，更灵活
- 🗄️ 移除了leancloud，默认的sqlite即可满足大部分需求
- 🦀 Rust重构，提供跨平台支持
- 📦 优化部署脚本，一键部署和停止
```
