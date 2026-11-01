# data2 导航

网站：https://map.data2.cn/

轻量的静态网站导航，整理数据集、AI 教学、学习资源与效率工具。
每个入口包含一句话介绍、标签、访问地址，以及已确认的个人公开仓库和上游项目地址。

## 开发与维护

无需安装依赖，运行 `python -m http.server 8767 --directory dist` 即可预览。

- `dist/sites.json`：网站名称、地址、分类、一句话介绍和源码链接。
- `dist/index.html`、`dist/style.css`、`dist/app.js`：页面、样式、搜索与收藏。
- 收藏保存在浏览器 localStorage，禁用持久存储时退化为当前页面会话。
- 静态文件可部署至 Nginx 或 Vercel，Vercel 项目根目录设为 `dist`。

公开仓库只展示已确认公开的项目；“基础项目 Fork”并不表示包含线上站点的全部定制代码。
链接状态为整理时的检查结果，访问受网络环境影响。

## 许可

导航自身代码采用 MIT 许可。被链接项目保留各自许可证，科学实验室课件采用 CC BY-NC 4.0。
