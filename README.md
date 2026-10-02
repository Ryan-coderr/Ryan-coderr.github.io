# 我的 Hexo 博客

这是一个使用 Hexo 搭建的个人博客，文章存放在 `source/_posts` 文件夹中。

## 第一次使用

1. 打开 `_config.yml`，把博客名称、作者和网址中的“你的GitHub用户名”改成自己的信息。
2. 在当前文件夹运行 `pnpm run server`。
3. 浏览器访问 `http://localhost:4000` 查看博客。

## 写一篇新文章

运行：

```powershell
npx hexo new "文章标题"
```

然后打开 `source/_posts` 中新生成的 Markdown 文件开始写作。保存后，本地预览会自动更新。

## 发布博客

把这个项目上传到名为 `你的GitHub用户名.github.io` 的 GitHub 仓库，并在仓库的 `Settings → Pages` 中把发布来源设为 `GitHub Actions`。以后每次把修改推送到 `main` 分支，博客都会自动更新。

## 常用操作

```powershell
pnpm run server  # 本地预览
pnpm run build   # 生成网站文件
pnpm run clean   # 清理旧的生成结果
```
