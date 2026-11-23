# 个人主页 · 吕小鱼

米哈游「基础大模型技术分享 & 顶尖校招生（含实习）招募」报名用。

- 线上地址：https://waltymo.github.io
- 仓库：https://github.com/waltymo/waltymo.github.io
- 本地目录：`D:\dsh-wsp\homepage`

## 三个文件

| 文件 | 作用 |
|---|---|
| `index.html` | 全部内容 |
| `style.css` | 样式 |
| `README.md` | 这份说明，不会被网页显示 |

纯静态，无 JS、无构建步骤。改完直接刷新浏览器就能看到。

## 改内容后发布

```bash
cd D:\dsh-wsp\homepage
git add -A && git commit -m "改了什么" && git push
```

等 1 分钟刷新线上页面。

- 已装 GitHub CLI，登录账号 `waltymo`（`gh auth status` 可查）
- git 已配代理 `127.0.0.1:7890`（本机直连 GitHub 会超时）
- 仓库 main 分支，Pages 自动部署，不用手动点任何设置

## 发布记录

- 2026-11-23：建仓库 `waltymo.github.io`、推 main、Pages 自动启用、构建通过（HTTP 200）

## 待办

- [ ] 邮箱换学邮：`index.html` 第 19 行 `mailto:3036631683@qq.com`（QQ 邮箱公开挂着容易被爬）
- [ ] CV 链接：简历定稿后把 `cv.pdf` 放进来，取消 `index.html` 第 23–26 行的注释
- [ ] 笔记段：`index.html` 第 106–113 行注释着，等笔记写完再放开

## 内容底线

页面上每一句都要能被追问三层。AI 辅助写的部分不写成"我独立完成"。
