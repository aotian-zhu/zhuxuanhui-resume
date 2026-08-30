# 个人简历静态站

这是一个纯静态简历站点，可直接部署到 GitHub 和 Vercel。

## 本地预览

```bash
npx serve .
```

或使用任意静态服务器打开当前目录。

## 部署思路

1. 将本目录初始化为 Git 仓库并推送到 GitHub
2. 在 Vercel 中导入该仓库
3. Framework 选择 `Other`
4. Output Directory 留空即可
