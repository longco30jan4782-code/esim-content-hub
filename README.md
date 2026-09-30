# eSIM Content Hub

面向搜索引擎和用户的 eSIM 国际网络内容中枢。用于集中承载后续的指南、独立页面、产品说明、宣传物料和公开购买入口。

## 网站定位

网站围绕用户真实搜索问题组织内容：

- eSIM 国际上网与移动数据
- 旅行、出差和备用网络
- 设备兼容与热点共享
- 香港线路、短信和长期使用场景
- eSIM 与 VPN 的方案比较
- Telegram 公开下单流程

## SEO 基础设施

- 首页 title、description、keywords 和 canonical
- Open Graph 与 Twitter Card 元数据
- WebSite、Organization、CollectionPage 结构化数据
- `robots.txt`
- `sitemap.xml`
- 每个内容页独立 title、description、canonical 和长尾主题
- 语义化标题层级、内部链接和主题聚合

## 内容扩展规则

新增内容建议遵循：

1. 先确定用户搜索问题。
2. 放入 `guides/`、`business/` 或未来新增的主题目录。
3. 为页面写独立 title、description、canonical 和正文标题。
4. 从首页或主题页建立内部链接。
5. 把新 URL 加入 `sitemap.xml`。
6. 保持价格、覆盖、兼容性和服务能力的条件说明。
7. 不在公开仓库放置 Token、Webhook、API 地址、供应商后台或客户数据。

## 公开页面

- 网站首页：<https://longco30jan4782-code.github.io/esim-content-hub/>
- Telegram 公开入口：<https://t.me/esimka_orderbot>

## 本地预览

```powershell
python -m http.server 8080
```

打开 `http://localhost:8080` 即可预览。
