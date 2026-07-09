生日祝福 GitHub Pages 部署说明

文件结构需要保持为：

birthday_github_pages/
├─ index.html
└─ photos/
   ├─ 01.jpg
   ├─ 02.jpg
   ├─ 03.jpg
   ├─ 04.jpg
   ├─ 05.jpg
   └─ 06.jpg

使用步骤：
1. 把你要展示的照片放到 photos 文件夹。
2. 按 01.jpg、02.jpg、03.jpg ... 命名。文件名大小写必须一致。
3. 如果你想用 png 或 webp，改 index.html 顶部 JS 里的 PHOTOS 数组。
4. 在 GitHub 新建一个仓库，例如 birthday-card。
5. 上传 index.html 和 photos 文件夹。
6. 打开仓库 Settings -> Pages。
7. Source 选择 Deploy from a branch。
8. Branch 选择 main，目录选择 /root，然后保存。
9. 等 1 分钟左右，GitHub Pages 会给你一个链接。
10. 把这个链接直接发给她，在微信里点开即可。

需要改文字时，打开 index.html，搜索 DEFAULTS，修改 name、from、message。
需要改每张照片下面的文案时，搜索 PHOTO_CAPTIONS。
