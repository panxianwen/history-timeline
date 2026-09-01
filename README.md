# 中外历史对照图谱

以多文明时间轴呈现中外历史对照的教学工具：检索历史事件与人物，查看同一时期中国与世界的重大事件，覆盖公元前3500年至公元2000年。

## 功能

- 多文明泳道时间轴（中国 / 西亚·北非 / 欧洲 / 南亚 / 草原·内亚 / 美洲 / 东亚其他 / 撒哈拉以南非洲）
- 历史事件与人物检索
- 同一时期中外事件对照
- 对比视图、时间练习、课堂演示模式、讲义导出、教师批注、视图分享链接

## 本地运行

无需构建，直接双击 `index.html` 或启动任意静态服务器：

```bash
python3 -m http.server 8080
```

## 部署

纯静态站点，目录直接部署到 EdgeOne Pages / Cloudflare Pages / 任意静态托管即可，入口 `index.html`。

## 目录结构

```
index.html      主页面（含全部交互逻辑）
data.js         历史数据（CIVILIZATIONS / ITEMS / ERAS）
robots.txt / sitemap.xml / manifest.json   SEO 与 PWA 辅助文件
```
