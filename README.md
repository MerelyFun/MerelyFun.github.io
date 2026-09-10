# 桌游封面

独立的手机游戏选择网站，只负责跳转，不包含任何游戏业务、账号或数据库。

- 封面：https://merelyfun.github.io/tabletop-hub/
- 狼人真言：https://merelyfun.github.io/werewords/
- 血染钟楼：https://merelyfun.github.io/blood-on-the-clocktower/

修改 `index.html` 后推送 main，GitHub Actions 自动发布。两个游戏各自在原来的独立仓库维护。

## 域名转发

桌游.club 目前由 Spaceship 隐藏框架转发到狼人真言。域名所有者登录 Spaceship → Domain list → 桌游.club → URL redirect，将目标替换为本封面地址，选择普通 302 转发并保存。普通转发会显示实际 GitHub Pages 地址。

如需地址栏始终显示中文域名，应另行绑定自定义域名并修改 DNS。

## 素材

钟楼徽章来自原项目提供的原创素材包，仅用作钟楼入口标识；狼人图案为内联 SVG。
