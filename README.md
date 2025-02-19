<!-- markdownlint-configure-file {
  "MD013": {
    "code_blocks": false,
    "tables": false,
    "line_length":200
  },
  "MD033": false,
  "MD041": false
} -->

[license]: /LICENSE
[license-badge]: https://img.shields.io/github/license/jerrykuku/luci-theme-argon?style=flat-square&a=1
[prs]: https://github.com/jerrykuku/luci-theme-argon/pulls
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[issues]: https://github.com/jerrykuku/luci-theme-argon/issues/new
[issues-badge]: https://img.shields.io/badge/Issues-welcome-brightgreen.svg?style=flat-square
[release]: https://github.com/jerrykuku/luci-theme-argon/releases
[release-badge]: https://img.shields.io/github/v/release/jerrykuku/luci-theme-argon?style=flat-square
[download]: https://github.com/jerrykuku/luci-theme-argon/releases
[download-badge]: https://img.shields.io/github/downloads/jerrykuku/luci-theme-argon/total?style=flat-square
[contact]: https://t.me/jerryk6
[contact-badge]: https://img.shields.io/badge/Contact-telegram-blue?style=flat-square
[en-us-link]: /README.md
[zh-cn-link]: /README_ZH.md
[en-us-release-log]: /RELEASE.md
[zh-cn-release-log]: /RELEASE_ZH.md
[config-link]: https://github.com/jerrykuku/luci-app-argon-config/releases
[lede]: https://github.com/coolsnowwolf/lede
[official]: https://github.com/openwrt/openwrt
[immortalwrt]: https://github.com/immortalwrt/immortalwrt


# 一个全新的 OpenWrt 主题

Edge2 是修改至argon的**一款干净整洁的 OpenWrt LuCI 主题**，  
允许用户使用图片或视频自定义其登录界面。  
它还支持在浅色模式和深色模式之间自动或手动切换。

[![license][license-badge]][license]
[![prs][prs-badge]][prs]
[![issues][issues-badge]][issues]
[![release][release-badge]][release]
[![download][download-badge]][download]
[![contact][contact-badge]][contact]

**简体中文**

[特色](#特色) •
[分支介绍](#分支介绍) •
[版本历史](#版本历史) •
[快速开始](#快速开始) •
[屏幕截图](#屏幕截图) •
[贡献者](#贡献者) •
[鸣谢](#鸣谢)
<img src="https://github.com/yuos-bit/other/releases/download/Openwrt/2025-02-19_16-58-54.jpg">
<img src="https://raw.githubusercontent.com/jerrykuku/staff/master/argon2.gif">

## 特色

- 干净整洁的布局。
- 适配移动端显示。
- 可自定义主题颜色。
- 支持使用 Bing 图片作为登录背景。
- 支持自定义上传图片或视频作为登录背景。
- 通过系统自动在明暗模式之间切换，也可设置为固定模式。
- 带有扩展功能的设置插件 [luci-app-argon-config][config-link]

### 在官方和 ImmortalWrt 上安装

```bash
opkg install luci-compat
opkg install luci-lib-ipkg
wget --no-check-certificate https://github.com/jerrykuku/luci-theme-argon/releases/download/v2.3.2/luci-theme-argon_2.3.2-r20250207_all.ipk
opkg install luci-theme-argon*.ipk
```

## 注意

- 强烈建议使用 Chrome 浏览器。这个主题中使用了一些新的 css3 功能，目前只有 Chrome 浏览器有最好的兼容性。
- 微软已正式退役 Internet Explorer，安息吧 IE🙏<del>目前，IE 系列的主线版本有需要解决的错误。</del>
- FireFox 默认不启用 backdrop-filter，[见这里](https://developer.mozilla.org/zh-CN/docs/Web/CSS/backdrop-filter)的打开方法。

## 屏幕截图

![desktop](/Screenshots/screenshot_pc.jpg)
![mobile](/Screenshots/screenshot_phone.jpg)

## 贡献者

<a href="https://github.com/jerrykuku/luci-theme-argon/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jerrykuku/luci-theme-argon" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## 鸣谢

[luci-theme-material](https://github.com/LuttyYang/luci-theme-material/)
[luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon/)
