<p align="center">
  <img src="./app-icon.png" width="88" height="88" alt="payfor工大 图标">
</p>
<h1 align="center">payfor工大</h1>
<p align="center">面向合肥工业大学校园日常消费与费用查询的第三方 Android 校园卡工具</p>

**payfor工大** 是一款个人维护的第三方 Android 校园卡工具（支持 Android 8.0 及以上），适用于食堂消费、校内缴费及费用核对等日常场景，提供校园付款二维码与条形码展示、校园卡余额与校园费用查询，以及部分费用的手动充值功能。合肥校区与宣城校区的可用项目存在差异。

> 本项目为个人维护的非官方工具，与合肥工业大学及校园服务提供方无任何关联。涉及扣款或到账记录，请以校方账单为准。

### 下载 Android 主应用

仅需日常付款码展示与费用查询，安装 Android 主应用即可：

- **安装包下载**：[Gitee 发行版](https://gitee.com/dustbin1415/hfut-payment-release/releases)（国内下载） · [GitHub 发行版](https://github.com/hfut-payment/hfut-payment/releases/latest)
- **功能说明**：[主仓库文档](https://github.com/hfut-payment/hfut-payment#readme)

### 设备扩展

- **小米手环**：支持在手环端出示校园付款码；手机端手环连接功能已内置（Beta），手环本体需另行安装快应用 RPK（已实测小米手环 11，其他机型以固件与互联能力为准），详见 [手环安装教程](https://github.com/hfut-payment/hfut-payment-band#readme)。
- **小米背屏**：面向小米手机背屏的独立付款码扩展，需同时安装插件和背屏主题，详见 [背屏安装教程](https://github.com/hfut-payment/hfut-payment-rear#readme)。

### 自动充值插件（Beta）

自动充值以独立 HFP 插件形式提供，目前处于 Beta 测试阶段，当前仅支持宣城校区的常规电费、空调电费、校园网费及洗浴费用。插件会在满足预设条件时尝试从校园卡实际扣款；独立分发旨在使测试功能与日常使用隔离，有需要的同学可自行安装。

仅建议具备相应技术能力、能够自行完成配置与问题排查、核对账单并愿意承担试用风险的用户安装。若充值结果尚未确认，请先核对校方账单后再决定是否继续操作。

- **插件文档与下载**：安装前请阅读 [说明与风险](https://github.com/hfut-payment/hfut-payment-auto-recharge#readme)，安装包见 [插件发行版](https://github.com/hfut-payment/hfut-payment-auto-recharge/releases)。
