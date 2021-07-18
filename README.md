<div align="center">
  <a href="https://cjh0613.com/" target="_blank" rel="noopener noreferrer" alt="CJH0613">
    <img src="https://cdn.jsdelivr.net/gh/cjh0613/blog/images/icons/CJHicon.jpg" width="100" height="100">
  </a>
</div>
<h2 align="center">anti-selfish-browser</h2>
<p align="center">
Language: <a href="https://github.com/cjh0613/anti-selfish-browser/blob/master/README.md" target="_blank" rel="noopener noreferrer">English</a>
  | <a href="https://github.com/cjh0613/anti-selfish-browser/blob/master/README_zh.md" target="_blank" rel="noopener noreferrer">文言</a>
</p>
<p align="center">
Now the English document is not quite perfect, welcome to submit the optimization of pull request
</p>
<!--Key Features • How To Use • Download • Credits • Related • License-->
<p align="center">
  <a href="#roadmap">Roadmap</a> •
  <a href="#donate">Donate</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#summary">Summary</a> •
  <a href="#thanks">Thanks</a>
</p>

[![GitHub stars](https://img.shields.io/github/stars/cjh0613/anti-selfish-browser.svg?style=social)](https://github.com/cjh0613/anti-selfish-browser/stargazers)     [![GitHub forks](https://img.shields.io/github/forks/cjh0613/anti-selfish-browser.svg?style=social)](https://github.com/cjh0613/anti-selfish-browser/network/members)  `Please click on the top right of the page star and fork【请点击页面顶部靠右star与fork】`

[![GitHub release](https://img.shields.io/github/release/cjh0613/anti-selfish-browser.svg?label=%E7%89%88%E6%9C%AC)](https://github.com/cjh0613/anti-selfish-browser/releases/tag/)   ![GitHub top language](https://img.shields.io/github/languages/top/cjh0613/anti-selfish-browser.svg)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cjh0613/anti-selfish-browser.svg)  ![GitHub repo size](https://img.shields.io/github/repo-size/cjh0613/anti-selfish-browser.svg) ![GitHub](https://img.shields.io/github/license/cjh0613/anti-selfish-browser.svg) ![platforms](https://img.shields.io/badge/platform-win32%20%7C%20win64%20%7C%20linux%20%7C%20osx-brightgreen.svg)     [![GitHub issues](https://img.shields.io/github/issues/cjh0613/anti-selfish-browser.svg)](https://github.com/cjh0613/anti-selfish-browser/issues)  [![GitHub closed issues](https://img.shields.io/github/issues-closed/cjh0613/anti-selfish-browser.svg)](https://github.com/cjh0613/anti-selfish-browser/issues?q=is%3Aissue+is%3Aclosed) ![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/cjh0613/anti-selfish-browser.svg)   ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/cjh0613/anti-selfish-browser.svg)  ![GitHub contributors](https://img.shields.io/github/contributors/cjh0613/anti-selfish-browser.svg)

[![Stargazers repo roster for @cjh0613/anti-selfish-browser](https://reporoster.com/stars/cjh0613/anti-selfish-browser)](https://github.com/cjh0613/anti-selfish-browser/stargazers)


## Roadmap
[Roadmap](https://github.com/cjh0613/anti-selfish-browser/projects/1) 

## [Donate](https://sponsor.cjh0613.com/index.html) 

## Documentation

This is the first open source project in the world that supports 105 languages to prompt users to stop using IE.

When the IE browser (including the browser using the IE kernel) accesses the website, it will automatically jump to the browser upgrade page.

As of January 12, 2016, Microsoft no longer provides corresponding support and updates for IE 11 and below. Without critical browser security updates, users’ computers may be vulnerable to attacks by harmful viruses, spyware, and other malicious software, which can steal or damage your business data and information.

And everyone has experienced the page loading speed of it.

In order to be compatible with this former browser hegemony, web designers need to do a lot of code work, and the final result is always unsatisfactory. For ordinary users, the low version of IE is a precarious security risk. In the history of Windows, several major Trojan virus incidents have used IE vulnerabilities to spread. So please join us in boycotting IE.

So, we can:

When an IE browser (including a browser using the IE kernel) accesses a website, it will redirect to a page suggesting that you update your browser.

That's what this repo to do.

It is detected to use IE browser, and it will redirect to the tip page after judging the language.

It now support **105 languages**, so that developers around the world are happy to use it, so that people around the world can switch to more advanced browsers.

In July 2021, I added some features to boycott rogue browsers in mainland China.

If you think there are some browsers in your area that also have rogue behavior, please report it [here](https://github.com/cjh0613/anti-selfish-browser/issues/2)

You are welcome to submit（pull request）the version of your native language.

### Instructions:

1. Clone this project to your own server

2. Add this between the `<head></head>` of the webpage source code:

```html
# You may need to change the CDN server
<script src="https://cdn.staticfile.org/jquery/3.4.1/jquery.min.js"></script>
<script src="https://cdn.staticfile.org/layer/3.1.1/layer.min.js"></script>
<script src="/anti-selfish-browser/Browser.js"></script>
<script src="/anti-selfish-browser/anti-selfish-browser.js"></script>
```

Welcome to submit versions in other languages by PR.


## Summary


If you like this repo, please **click "Star" as support**, thank you!

## Thanks
### Contributors
<a href="https://github.com/cjh0613/anti-selfish-browser/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cjh0613/anti-selfish-browser" />
</a>

### Others


Other items：

- mumuy/browser
- TransparentLC's blog
- jquery
- layer

Machine Translate:
- Deepl
- Google
- Baidu