# 电子时钟

一个简洁的电子时钟 PWA 应用,可以添加到 iPhone 主屏幕,像原生 App 一样使用。

## 功能

- 大字号实时显示当前时间(时:分:秒)
- 显示日期和星期
- 深色背景,适合长时间查看
- 全屏沉浸式运行(添加到主屏幕后)
- 防止屏幕自动休眠(需 iOS 17+)

## 在 iPhone 上使用

1. 在 iPhone 的 **Safari**(不能用 Chrome)打开:
   ```
   https://yide9718.github.io/IOS_app/
   ```
2. 点底部 **分享** 按钮 → 滚动找到 **添加到主屏幕** → 完成
3. 主屏幕出现"时钟"图标,点击即全屏运行

## 在线预览

启用 GitHub Pages 后(仓库 Settings → Pages → Source 选 main 分支),访问上面的网址即可。

## 文件说明

- `index.html` — 时钟主页面(CSS 和 JS 全部内嵌)
- `manifest.json` — PWA 配置(决定图标、名称、启动行为)
- `icon.svg` — 应用图标
- `.nojekyll` — 让 GitHub Pages 直接服务文件,不做额外处理
