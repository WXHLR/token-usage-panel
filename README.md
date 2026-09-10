# Token 用量面板

一个跑在 Windows 桌面的 **AI / Token 用量监控小面板**（支持 DeepSeek），纯本地运行、绿色免安装。

## 功能

- 账户余额、已充值、赠送额度
- 本月 / 今日 Token 与费用
- 近 10 天趋势图（红涨绿跌）
- 按模型拆分用量、缓存命中率
- 一键复制报告 / 导出 CSV
- 右上角「充值」按钮直达官方充值页
- 深色 / 浅色主题、系统托盘常驻

## 下载

到本仓库的 **Releases** 页面，下载最新的 `Token用量面板-vX.X-win64.zip`。

解压后两种用法：

| 方式 | 操作 |
|---|---|
| 正式安装（推荐） | 双击 `Token用量面板-安装程序.exe`，自动创建桌面/开始菜单快捷方式，带卸载 |
| 免安装绿色版 | 双击 `Token用量.exe` |

> Windows 弹出「未知发布者 / SmartScreen」时，点「更多信息」→「仍要运行」即可（软件未购买数字签名证书）。

## 首次使用

1. 双击运行
2. 在「设置」里填入你的 DeepSeek **API Key** 和 **userToken**，保存
3. 之后每次打开即可直接查看用量

**去哪儿拿这两个值？**

- 打开并登录 <https://platform.deepseek.com>
- **API Key**：「API Keys」页面创建一个，形如 `sk-xxxxxx`
- **userToken**：按 F12 打开开发者工具 → Application → Cookies → 找到 `platform.deepseek.com` 下的 `userToken`，复制其值

## 隐私

你的 API Key / userToken 只保存在本机（`%APPDATA%\TokenUsagePanel\config.json`），**不会上传到任何地方**。

## 免责声明

本工具为第三方非官方工具，与 DeepSeek 无隶属关系。使用本工具请遵守 DeepSeek 平台的服务条款。