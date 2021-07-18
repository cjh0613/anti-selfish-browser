<div align="center">
  <a href="https://cjh0613.com/" target="_blank" rel="noopener noreferrer" alt="CJH0613">
    <img src="https://cdn.jsdelivr.net/gh/cjh0613/blog/images/icons/CJHicon.jpg" width="100" height="100">
  </a>
</div>
<h2 align="center">cjh-github-template</h2>
<p align="center">
語言: <a href="https://github.com/cjh0613/anti-selfish-browser/blob/master/README.md" target="_blank" rel="noopener noreferrer">English</a>
  | <a href="https://github.com/cjh0613/anti-selfish-browser/blob/master/README_zh.md" target="_blank" rel="noopener noreferrer">文言</a>
</p>
<p align="center">
  <a href="#序">序</a> •
  <a href="#策劃">策劃</a> •
  <a href="#資">資</a> •
  <a href="#指南">指南</a> •
  <a href="#致謝">致謝</a>
</p>

[![GitHub stars](https://img.shields.io/github/stars/cjh0613/anti-selfish-browser.svg?style=social)](https://github.com/cjh0613/anti-selfish-browser/stargazers)     [![GitHub forks](https://img.shields.io/github/forks/cjh0613/anti-selfish-browser.svg?style=social)](https://github.com/cjh0613/anti-selfish-browser/network/members)  `【請點擊頁面頂右之 star 與 fork】`

[![GitHub release](https://img.shields.io/github/release/cjh0613/anti-selfish-browser.svg?label=%E7%89%88%E6%9C%AC)](https://github.com/cjh0613/anti-selfish-browser/releases/tag/)   ![GitHub top language](https://img.shields.io/github/languages/top/cjh0613/anti-selfish-browser.svg)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cjh0613/anti-selfish-browser.svg)  ![GitHub repo size](https://img.shields.io/github/repo-size/cjh0613/anti-selfish-browser.svg) ![GitHub](https://img.shields.io/github/license/cjh0613/anti-selfish-browser.svg) ![platforms](https://img.shields.io/badge/platform-win32%20%7C%20win64%20%7C%20linux%20%7C%20osx-brightgreen.svg)     [![GitHub issues](https://img.shields.io/github/issues/cjh0613/anti-selfish-browser.svg)](https://github.com/cjh0613/anti-selfish-browser/issues)  [![GitHub closed issues](https://img.shields.io/github/issues-closed/cjh0613/anti-selfish-browser.svg)](https://github.com/cjh0613/anti-selfish-browser/issues?q=is%3Aissue+is%3Aclosed) ![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/cjh0613/anti-selfish-browser.svg)   ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/cjh0613/anti-selfish-browser.svg)  ![GitHub contributors](https://img.shields.io/github/contributors/cjh0613/anti-selfish-browser.svg)

[![Stargazers repo roster for @cjh0613/anti-selfish-browser](https://reporoster.com/stars/cjh0613/anti-selfish-browser)](https://github.com/cjh0613/anti-selfish-browser/stargazers)

## 序

夫瀏覽器者，觀景之窗也。然今有瀏覽器者，不思為民，賣李鑽核為禍天下蒼生。駐後臺，彈廣告，篡網頁，封良站，庇惡牒，捆綁軟體，侵濫隱私，無所不用其極。士有士節，臥榻之側，豈容他人鼾睡邪？元樞二十二年夏，寡人特重修拒 IE 之庫，增其舊制，以 anti-selfish-browser 名之。

至於今日，此庫功能有二：
- 其一，檢測到 IE 瀏覽器，直接跳轉至提示頁面提示更換，**支持 105 種語言**；
- 其二，檢測到其他自私的瀏覽器，則彈框提示更換瀏覽器，**支持 2 種語言**（如果需要其他語言的版本，請到[這個地址](https://github.com/cjh0613/anti-selfish-browser/issues/2)發表您的觀點）。

望諸君不助其倀。雖小站之星星之火，必成燎原之勢。

```
吾欲作文，置之於此，今尚未成
```

## 策劃
[策劃，Roadmap, 開發計劃、路線圖](https://github.com/cjh0613/anti-selfish-browser/projects/1)

## [資](https://sponsor.cjh0613.com/)

前往 https://sponsor.cjh0613.com/ 以資作者。

## 指南

1. 將項目資料夾放在你網站根目錄。

2. 在您的網頁中**依次**引入這些庫: jquery , layer , Browser , anti-selfish-browser 。置之於網頁原始程式碼 `<head></head>` 間（儘量靠前）：

```html
<script src="https://cdn.staticfile.org/jquery/3.4.1/jquery.min.js"></script>
<script src="https://cdn.staticfile.org/layer/3.1.1/layer.min.js"></script>
<script src="/anti-selfish-browser/Browser.js"></script>
<script src="/anti-selfish-browser/anti-selfish-browser.js"></script>
```

若喜歡此倉庫，請**點贊薦友為支**，不勝感激！

> 這個項目中添加了一些協力廠商統計程式碼（但僅在本項目提供的 html 檔案中添加了），用於分析不同地域的瀏覽器特徵，為本項目接下來的優化提供參攷。如果不希望這些統計程式碼運作，網站科技人員可以直接删掉這部分程式碼，訪客可以使用廣告遮罩器攔截。

## 致謝

### 貢獻者
<a href="https://github.com/cjh0613/anti-selfish-browser/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cjh0613/anti-selfish-browser" />
</a>

### 其他

此項目參攷、使用的其他項目：

- mumuy/browser
- TransparentLC 的網誌
- jquery
- layer
- [前端（只有簡體中文）](https://support.dmeng.net/upgrade-your-browser.html)

機器翻譯:
- Deepl
- Google
- Baidu
