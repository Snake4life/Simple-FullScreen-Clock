Simple Fullscreen Clock
===

![Update 2020-04-17](https://img.shields.io/badge/Update-2020--04--17-blue)

一个简单的全屏时钟。尽可能地支持老旧设备，使它们可以摆在桌面上继续陪伴我们。

需要将网站添加到桌面，然后从此快捷方式打开才是全屏显示。

建议在设备上安装如 Chrome、Firefox 或者 Yandex 等浏览器，可以获得最佳体验。iOS 设备如因为版本太低无法安装，用自带 Safari 也可以，经测试 iOS 9 下可以运行。

参数说明
---

可通过锚点（`#hash`）向网页传递参数，调整页面配色和显示内容。多个参数间用 `-` 进行连接。

* `light` 亮色。白色背景，黑色文字（默认为黑底白字；
* `auto` 自动。白天亮色，晚上暗色。均匀消耗所有像素，不再担心烧屏；
* `ink` 电子墨水屏模式，关闭所有过渡效果；
* `breathe` 打开呼吸效果（电子墨水屏模式下无效；
* `more` 显示更多内容。会在时间上方显示星期几和秒数（秒数切换不十分精确）；

细节说明
---

* 有周期为 15 秒的呼吸效果。
* 颜色自动切换时间为早晚七点。
* 凌晨 3 点页面自动刷新，以避免某些可能潜在的问题。
* 受刷新频率限制，秒数可能存在 ±1s 的误差，误作为精确时间依据。

网址列表
---

可直接通过如下网址访问对应功能，然后添加到桌面。

**Github pages**

以下仅为示例写法，可自由组合参数

* **默认样式：** https://snake4life.github.io/Simple-FullScreen-Clock/
* **老鼠自用：** https://snake4life.github.io/Simple-FullScreen-Clock/#more-breathe

更新日志
---

**2020-04-19**

加入竖屏模式，自动切换。基本目标为最大化文字显示

**2020-04-17**

用 React 重写，基本完成上一版本的所有功能
