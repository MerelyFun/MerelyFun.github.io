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

首页采用用户提供的双游戏封面 assets/game-covers.png，以 CSS 分别显示上下横幅，保留原图。整幅横幅均可点击，不重复添加图片已有的游戏名称和进入提示。页面背景使用用户指定的纸纹图片 assets/paper-background.png。
