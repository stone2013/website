GitHub Pages 部署说明

1. 解压这个 ZIP。
2. 把 index.html 和 .nojekyll 两个文件上传到 GitHub 仓库根目录。
3. 不要只上传 ZIP 文件，GitHub Pages 不会把 ZIP 自动解压成网页。
4. 打开仓库 Settings -> Pages。
5. Source 选择 Deploy from a branch。
6. Branch 选择 main，Folder 选择 / root。
7. 保存后等待 GitHub Pages 生成链接。

如果还是 404：
- 确认仓库根目录真的有 index.html。
- 确认 Pages 发布目录选择的是 / root。
- 确认文件名是 index.html，不能是 67_vip_github_pages_payment.html。
