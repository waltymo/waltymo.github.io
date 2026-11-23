# 个人主页（waltmyo.github.io）

吕小鱼的学术主页。纯静态，无框架、无构建步骤，双击 `index.html` 就能看。

## 文件

| 文件 | 作用 |
|---|---|
| `index.html` | 全部内容。改文字只改这个 |
| `style.css` | 样式。改颜色/字号改这个 |

## 本地预览

双击 `D:\dsh-wsp\homepage\index.html`，用浏览器打开。

## 推到 GitHub Pages

**仓库名必须是 `waltmyo.github.io`**，这是唯一能让网址变成
`https://waltmyo.github.io` 的方式（短、干净、报名表好填）。
如果叫别的名字，网址会变成 `waltmyo.github.io/xxx`。

1. GitHub 网页 → New repository → 名字填 `waltmyo.github.io` → Public → Create
2. 把 `index.html`、`style.css` 传上去（用 GitHub Desktop 加文件夹更省事）
   - GitHub Desktop：File → Add local repository → 选 `D:\dsh-wsp\homepage` → Publish repository
   - **发布时把 "Keep this code private" 的勾去掉**
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch` → Branch `main` / `(root)` → Save
4. 等 1–2 分钟，打开 https://waltmyo.github.io

## 上线前必须做的三件事

- [ ] CV 链接：`index.html` 里的 `<a href="#" class="muted">CV (PDF)</a>` 还是个空链接，
      等简历改完，把 PDF 放进仓库根目录，改成 `href="cv.pdf"`
- [ ] 邮箱：现在写的是 QQ 邮箱，如果学校有学邮可以考虑换，但 QQ 邮箱也不算错
- [ ] 项目卡片的数字：每一处都要能被追问三层，问不倒才留

## 待补

- `Notes` 段已写好但注释掉了（搜 `id="notes"`），等论文笔记写完再放开
- 持续学习那张卡片的「结果」一栏等实验跑完再补数字
