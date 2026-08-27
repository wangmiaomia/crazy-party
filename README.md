# 成年人放风派对 · V54 GitHub Pages 最终包

## 文件入口
- `index.html`：项目首页 / 测试入口
- `admin.html`：邀请链接生成器（主题、邀请信息、5首歌、可编辑文案）
- `preview.html`：01–08 全局测试预览
- `01.html` ... `08.html`：八个正式主题邀请页
- `assets/audio/`：5 首完整 MP3
- `.nojekyll`：让 GitHub Pages 原样发布静态资源

## V54 最终锁定
- 03：快乐街机增强交互（投币 → 可动摇杆 Combo → A/B/C 连击 → PLAYER 01 通行卡 → 手写签名）
- 05：E「疗养院档案」配色
- 08：电影式全屏开门转场

## 使用方式
部署 GitHub Pages 后先访问 `admin.html`，生成专属邀请链接。正式链接会携带 `share=1` 和 `music=` 参数，朋友只看到你指定的一首 BGM，不会看到五首歌曲选择器。

## 音乐
音乐放在 `assets/audio/` 中，HTML 使用相对路径加载。请保持目录结构不变。
