# KHelper
kindle 助手，kindle 最好的伙伴

## 一款帮助你找书的软件🔧

![Version](https://img.shields.io/badge/version-1.0.0-green)  ![Python Version](https://img.shields.io/badge/python-3.6+-blue) ![Support Platforms](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-lightgrey)

一个兴趣使然的桌面应用开发者，一个 Kindle 爱好者，利用业余时间开发了 KHelper。

KHelper 是一款找书的软件，目前支持三个站点的搜索。界面使用 PyQt5 开发的所以相对比较简单，但是完全不影响使用。

## ✨特点

1. 📖过滤掉找书过程中烦人的广告
2. ❌过滤到网站的一些无效链接
3. ⏬支持下载
4. ✈️支持推送

## 💻应用界面

![KHelper](http://ww1.sinaimg.cn/large/006wYWbGly1gfrkh4h2rwj30xq0pm757.jpg)

## ⌨️本地开发

### 克隆代码

```bash
git clone https://github.com/Peach-Coding/KindleHelper.git
```

### 安装依赖

```bash
pip install -r requirements.txt
```

### 开发模式

```bash
python src\kindleHelper.py
```

### 打包

#### macOS

```bash
pip install py2app
python3 -m setup.py py2app
```

#### Windows、Linux

```bash
pip intall pyinstaller
pyinstaller src\kindelHelper.spec
```

## ☑️ TODO

更多其他的站点

## 🤝 参与共建 [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

如果你有兴趣参与共同开发，欢迎 FORK 和 PR。

## 📜 开源许可

基于 [MIT license](https://opensource.org/licenses/MIT) 许可进行开源。

## ➕ 作者

![微信公众号](http://ww1.sinaimg.cn/large/006wYWbGly1gfrkwvgus7j30lb0l7go9.jpg)