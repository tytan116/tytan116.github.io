# tytan116.github.io

个人主页，发布后地址为 https://tytan116.github.io

## 发布步骤

1. 登录 GitHub，新建一个**公开**仓库，名字必须是 `tytan116.github.io`（前提是你的 GitHub 用户名是 `tytan116`）。
2. 把本文件夹里的文件上传到仓库根目录（网页上点 “Add file → Upload files”，或用下面的命令）：

   ```bash
   cd homepage
   git init && git add . && git commit -m "init homepage"
   git branch -M main
   git remote add origin https://github.com/tytan116/tytan116.github.io.git
   git push -u origin main
   ```

3. 打开仓库的 Settings → Pages，Source 选 “Deploy from a branch”，分支选 `main`、目录 `/ (root)`，保存。
4. 等 1～2 分钟，访问 https://tytan116.github.io 。

## 修改内容

所有内容都在 `index.html` 里，搜索方括号 `[...]` 替换成你的信息即可：

- 教育 / 研究 / 工作经历：每段经历是一个 `<div class="item">…</div>`，复制粘贴就能加一条，删掉就是去掉一条。
- 头像：把照片命名为 `avatar.jpg` 放进仓库，按 `index.html` 里的注释替换。
- CV：把简历命名为 `cv.pdf` 放进仓库，主页上的 “CV” 按钮会直接链接到它；不需要就删掉那一行。
