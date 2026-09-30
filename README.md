# eSIM Content Hub

面向搜索引擎和用户的 eSIM 国际网络内容中枢。首页先承接 `Kite eSIM`、`CMLink` 等购买比较搜索，再把用户引导到自有官网、指南、视频和公开购买入口。

## 网站定位

网站围绕用户真实搜索问题组织内容：

- eSIM 国际上网与移动数据
- 旅行、出差和备用网络
- 设备兼容与热点共享
- 香港线路、短信和长期使用场景
- eSIM 与 VPN 的方案比较
- Telegram 公开下单流程

## 首页转化逻辑

1. 先讲用户购买 eSIM 时真正要比较的内容：价格、每 GB 成本、激活地点、实名流程、覆盖、短信、热点和续费。
2. 用 Kite eSIM、CMLink 等名称承接比较型搜索，但只做客观维度对照，不对竞品规则作绝对化判断。
3. 把自有网站作为实时方案承接页：<https://esimka.top>。
4. 把 Telegram 作为更短的公开下单路径：<https://t.me/esimka_orderbot>。

当前首页核心卖点包括：部分短期方案低至 0.6 CNY/G、长期方案低至 3.5 CNY/G、指定方案支持中国内地激活、部分套餐提供香港 IP/号码短信/热点能力，以及在线交付和续费场景。所有价格、覆盖和功能均以实际套餐页面为准。

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
- 横向比较测评：<https://longco30jan4782-code.github.io/esim-compare-review/>
- 视频宣传资料库：<https://longco30jan4782-code.github.io/esim-video-showcase/>
- Telegram 公开入口：<https://t.me/esimka_orderbot>

首页已将横向比较测评和视频资料库作为最新公开资源统一挂载，并通过 ItemList 结构化数据、站内导航与专题卡片建立关联。

## 本地预览

```powershell
python -m http.server 8080
```

打开 `http://localhost:8080` 即可预览。
