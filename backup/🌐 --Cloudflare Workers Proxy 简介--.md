🌐 **Cloudflare Workers Proxy 简介**

- **功能**：Cloudflare Workers Proxy 是一个开源工具，用于代理被屏蔽的地址，理论上支持代理任何被屏蔽的域名。
- **使用方式**：只需设置环境变量 PROXY_HOSTNAME 为被屏蔽的域名，然后通过你的 Worker 自定义域名访问即可。

🚀 **应用场景**

- 最常见的应用场景是搭建 Docker 镜像源国内加速。

📝 **操作步骤**

1. **注册 Cloudflare 账号**：
   - 注册过程简单，无门槛。
   - 官网地址：[Cloudflare 官网](https://www.cloudflare.com/zh-cn/)
2. **获取项目代码**：
   - 项目地址：[Cloudflare Workers Proxy](https://github.com/jonssonyan/cf-workers-proxy)