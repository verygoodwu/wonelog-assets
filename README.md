# wonelog-assets

博客图片存储仓库，用于 Hexo 博客文章配图。

## 使用方式

图片上传后，通过以下格式引用：

```
https://cdn.jsdelivr.net/gh/verygoodwu/wonelog-assets@main/图片路径
```

## 目录结构

```
wonelog-assets/
├── README.md
├── images/          # 通用图片
├── posts/           # 文章配图（按年份/月份整理）
│   ├── 2026/
│   │   ├── 03/
│   │   └── 04/
│   └── 2027/
└── avatars/         # 头像类图片
```

## 快速上传

推荐使用 [PicGo](https://github.com/Molunerfinn/PicGo) 配合 GitHub 图床插件使用。

或手动通过 Git 上传：

```bash
git add .
git commit -m "add: 图片描述"
git push
```
