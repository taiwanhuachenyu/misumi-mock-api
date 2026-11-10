# misumi-mock-api

米思米在线客服 POC（C21 商品/订单卡片）演示数据，全部为模拟数据。

- `entry.html`：模拟官网商品详情页 / 订单详情页，「在线咨询」带 linkCard + visitorExtraInfo 进线
- `agent-tab.html`：在线客服工作台右侧自定义 TAB「米思米订单」，一键发送订单/商品卡片
- `orders.json`：访客端快捷入口「发送订单」的订单列表接口（静态 GET）
- `data.json`、`img/`：页面共用数据与商品图片

由 `make_site.py` 生成。
