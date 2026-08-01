# 猜数字升级版

经典猜数字（Bulls and Cows）游戏的玩法扩展版本。

## 在线试玩

**[https://guessnumberupgrade.netlify.app/](https://guessnumberupgrade.netlify.app/)**

无需注册，免费，无广告，打开即玩。

&gt; 目前仅支持中文界面。

## 与经典版的不同

- **位数自由**：答案位数可自行设定，不限于传统 4 位
- **非对称猜测**：允许设置"答案位数"与"猜测位数"不同，策略空间更大
- **难度自选**：提供多种难度组合，可更简单也可更难

## 本地运行

本项目为纯前端，双击 `猜数字.html` 即可运行，无需安装依赖。

或者：

```bash
python -m http.server 8000
# 然后浏览器访问 http://localhost:8000/猜数字.html
