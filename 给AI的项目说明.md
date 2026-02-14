# 巴厘岛行程规划 — 项目说明

## 背景

这是 Jiaxi（LUO/JIAXI）和 Xulin（WEI/XULIN）两个人的巴厘岛旅行计划。机票和酒店已全部订好，AI 根据 Mac Calendar 里的航班和酒店信息，做了一份事无巨细的行程规划，最终呈现为一个 Apple 设计风格的单页 HTML 网页。

## 项目结构

这个项目只有一个核心文件：`index.html`。纯 HTML + 内联 CSS，无外部依赖，无 JavaScript。文件名不可更改。

## 部署方式

- GitHub 仓库：https://github.com/qqluojxyxoo/bali-trip-2026
- 线上地址：https://bali-trip-2026-q1re.vercel.app
- 部署流程：修改 `index.html` → `git add . && git commit -m "描述" && git push` → Vercel 自动部署，约十几秒后生效
- 本地文件路径：`/Users/jiaxiluo/Haha/临时/bali plan 03/正式 GitHub 版/index.html`

## 用户原始需求

用户当时给的要求：

1. 出行方式：租摩托车通勤，行程要结合骑行距离安排
2. 详细程度：事无巨细的 itinerary，包括几点去哪里、干什么、那个地方有什么好玩的
3. 地理位置：结合酒店位置（仓古 Canggu）安排路线
4. 转机安排：雅加达两次转机期间都要安排活动
5. 作息习惯：早上 10:00 起床，凌晨 2:00 睡觉，行程排满一点
6. 信息筛选：多参考小红书等平台的真实经验，避开推广和虚假信息
7. 最终输出：Apple 设计风格的 HTML 网页

## 航班信息

| 段 | 航班 | 日期 | 路线 | 时间 | 备注 |
|---|------|------|------|------|------|
| 1 | 8B861 | 2月19日(四) | 广州CAN T2 → 雅加达CGK T3 | 02:30→06:35 | PNR: YJD13E |
| 2 | QZ818 | 2月19日(四) | 雅加达CGK T2 → 巴厘岛DPS | 18:00→20:50 | 注意：T3到达，T2出发 |
| 3 | QZ809 | 2月23日(一) | 巴厘岛DPS → 雅加达CGK T2 | 18:50→19:50 | |
| 4 | 8B860 | 2月24日(二) | 雅加达CGK T3 → 广州CAN T2 | 18:50→01:30+1 | 注意：T2到达，T3出发 |

关键提醒：两次雅加达转机航站楼不同（T2↔T3），需要坐 Skytrain 换航站楼，约10分钟。

## 酒店信息

- 酒店：Amandaya Canggu
- 地址：9 Gang Jalak Indah, Canggu, Bali 80361
- 房型：Deluxe Room（大床/无烟）
- 入住：2月19日 22:00
- 退房：2月23日 12:00（共4晚）
- 含免费早餐、WiFi、迎宾饮料
- 预订号：Agoda 955713410

## 雅加达酒店信息（已确认预订）

- 酒店：Hotel GranDhika Iskandarsyah
- 地址：Jalan Iskandarsyah Raya No.65, Blok M, Jakarta 12160
- 房型：豪华间（大床/无烟/高楼层/安静/远离电梯）
- 入住：2月23日 22:00-23:00
- 退房：2月24日
- 含早餐、免费WiFi、健身中心、停车
- 客人参考号码：1692141348
- 酒店电话：+628111090802
- 支付方式：Alipay
- 位置说明：酒店在雅加达南区 Blok M 商圈，附近有 MRT Blok M BNI 站，步行5分钟。Blok M 有「小东京」之称，日本餐厅和居酒屋密集，夜市小吃丰富。

## 行程结构（D0 — D5）

### D0 · 2月19日（周四）— 出发 · 雅加达半日游
- 凌晨广州出发，06:35到雅加达，有约11小时转机时间
- 搭机场快线 ARS 进城游览：科塔图阿老城区 → Cafe Batavia → 伊斯蒂克拉尔清真寺 + 大教堂 → 巴东菜午餐
- 14:30回机场，Skytrain 转 T2，18:00飞巴厘岛
- 20:50到巴厘岛，Grab 到酒店，入住后 Batu Bolong 路宵夜 + Old Man's 酒吧

### D1 · 2月20日（周五）— 仓古深度游 · 海神庙日落
- 上午：租摩托车 → Batu Bolong 海滩冲浪
- 中午：Hungry Bird Coffee 早午餐
- 下午：骑行穿越仓古稻田（Jl. Subak Canggu）→ The Shady Shack 休息
- 傍晚：骑车20分钟到海神庙 Tanah Lot 看日落（约18:40）
- 晚上：The Lawn Canggu 海滨晚餐
- 夜生活路线：Deus Ex Machina → Pretty Poison → Old Man's

### D2 · 2月21日（周六）— 乌布文化之旅
- 骑摩托车去乌布（约1-1.5小时）
- Warung Biah Biah 午餐（巴厘烤乳猪）
- 德格拉朗梯田 Tegalalang（门票25,000 IDR）
- 圣泉寺 Tirta Empul 净化体验（门票50,000 IDR）
- 乌布猴林 Sacred Monkey Forest（门票80,000 IDR）
- 乌布王宫 + 艺术市场
- Locavore To 晚餐
- 骑车返回仓古（注意夜间骑行安全）
- La Brisa 或 Finn's Beach Club 放松

### D3 · 2月22日（周日）— 乌鲁瓦图 · 南巴厘悬崖海岸
- 骑摩托车去乌鲁瓦图（约1.5-2小时）
- Single Fin 悬崖餐厅午餐
- Suluban Beach 蓝点海滩（岩洞入口）
- 乌鲁瓦图寺（门票50,000 IDR，注意防猴）
- 17:00占位 → 18:00 Kecak 火舞（门票150,000 IDR）— 悬崖日落背景，必看
- **19:10 TreVietNam-Ungasan / Ithon Mart 采购伴手礼**（用户指定的首选超市，Jl. Pura Batu Pageh No.48, Ungasan）
- 19:45 金巴兰海滩海鲜晚餐
- 骑车返回仓古
- Atlas Beach Fest 或 La Brisa 最后一夜

### D4 · 2月23日（周一）— 仓古最后的早晨 · 告别巴厘岛
- 上午：Crate Cafe 咖啡 + Love Anchor Market 购物 → 退还摩托车 → 退房
- 午餐：The LOE 或 Warung Local
- **13:15 Bintang Supermarket 水明漾店**（Jl. Raya Seminyak No.17，巴厘岛最大连锁超市）
- **14:00 Mal Bali Galeria 库塔购物中心**（Jl. Bypass Ngurah Rai, Kuta，内有 Hypermart 大超市）
- 15:00 前往机场（从 Mal Bali Galeria 仅10分钟）
- 18:50 飞雅加达，19:50到达 T2

### D5 · 2月23日晚—2月24日（周二）— 雅加达深度一日游
- 23日晚：入住 Hotel GranDhika Iskandarsyah（Blok M）+ Blok M 夜市觅食（Sate Taichan、Martabak、日式居酒屋）
- 24日上午：酒店含早餐 → Grab 去 Monas 国家纪念碑 + 独立广场（酒店到 Monas 约20分钟）
- 午餐：Nasi Padang（巴东菜）
- 下午：Grand Indonesia Mall 或国家博物馆
- 15:00 回 Blok M 酒店取行李，前往机场 T3（可搭 MRT 到 Dukuh Atas 换 ARS 快线，或 Grab 约45-60分钟）
- 18:50 飞广州，25日凌晨01:30到达

## 三家超市（用户后续指定添加）

用户从小红书看到推荐，要求把以下三家超市加入行程：

1. **Bintang Supermarket 水明漾店** — Jl. Raya Seminyak No.17，巴厘岛最大连锁超市，两层楼，明码标价。安排在 D4 离岛日，仓古去机场的路上顺路。
2. **Mal Bali Galeria** — Jl. Bypass Ngurah Rai, Simpang Dewa Ruci, Kuta，库塔最大购物中心，内有 Hypermart。安排在 D4，Bintang 之后、去机场之前，距机场仅10分钟。
3. **TreVietNam-Ungasan / Ithon Mart** — Jl. Pura Batu Pageh No.48, Ungasan。**用户指定的首选超市**，价格便宜种类全。安排在 D3 看完 Kecak 火舞后，去金巴兰吃海鲜之前（Ungasan 正好在乌鲁瓦图和金巴兰之间）。

## 设计风格说明

- Apple / SF Pro 风格：`-apple-system, 'SF Pro Display', 'PingFang SC'` 字体栈
- 浅灰底色 `#f5f5f7`，白色卡片，圆角 20px，柔和阴影
- Hero 区域渐变：深蓝 → 青绿
- 时间线布局：左侧竖线 + 彩色圆点标记
- 每个时间段有颜色编码的标签（美食/景点/交通/夜生活/文化/海滩/实用提示）
- 航班信息用横向卡片展示，带飞行线动画
- 响应式设计，支持移动端

## 修改注意事项

- 所有内容在一个 `index.html` 文件内，含内联 CSS
- 无外部 JS 依赖，纯静态页面
- 修改后务必 `git commit + git push`，Vercel 会自动部署
- 巴厘岛2月日落时间约 18:40（已校正）
- 价格单位为 IDR（印尼盾），汇率参考：1 CNY ≈ 2,200 IDR
