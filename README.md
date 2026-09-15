# 桌游封面

独立的手机游戏选择网站，只负责跳转，不包含游戏业务、账号或数据库。

- 封面：https://桌游.club/
- 狼人真言：https://桌游.club/werewords/
- 血染钟楼：https://桌游.club/blood-on-the-clocktower/

本仓库是 GitHub 账号主页 MerelyFun.github.io。两个游戏在各自原仓库维护，通过 GitHub Pages 继承账号主页域名。index.html 使用同域根路径链接。推送 main 自动发布。

## 当前域名切换状态

2026-09-11：GitHub Pages 已配置 xn--hyvt5k.club（桌游.club 的 ASCII 编码）。域名所有者尚需在 Spaceship 删除 URL redirect，并将 @ 的 A 记录设置为：

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

替换原转发 A 记录 15.197.162.184。TTL 默认。DNS 生效、GitHub HTTPS 证书签发后，再启用 Enforce HTTPS。完成前不能宣称域名已可用。

绑定账号域名后，原 github.io 项目网址可能跳转至自定义域名；DNS 切换完成前可能暂时无法使用。

## 素材

首页加载手机版 WebP 封面 assets/werewords-mobile.webp 和 assets/clocktower-mobile.webp（均为 800×600，质量 75），保持 4:3 比例。原始 PNG 保留作为源素材，不由页面加载。整幅横幅均可点击，不重复添加图片已有的游戏名称和进入提示。页面背景加载 assets/paper-background-mobile.webp（512×512，质量 60），保持原来的 CSS 纹理显示尺度。三张图片总计 232,024 字节，比原来 8,419,382 字节减少约 97.2%。

## 本机预览

这是无数据库的静态封面站，运行 python -m http.server 4178 --bind 0.0.0.0。电脑访问 http://localhost:4178/；手机连接同一 Wi-Fi 后访问本机当前 WLAN IPv4 地址的 4178 端口。默认仅本地预览，推送 main 会触发发布，须由用户明确要求。
