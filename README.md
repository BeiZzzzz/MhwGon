# 小镇梦想家

基于 Hexo + Butterfly 的个人博客。

## 本地预览

```bash
cd D:\小镇梦想家
npm install
npm run server
```

打开 `http://localhost:4000/小镇梦想家/` 预览。

## 新建文章

```bash
npx hexo new "文章标题"
```

## 发布到 GitHub Pages

1. 用 GitHub Desktop 把 `D:\小镇梦想家` 添加为本地仓库。
2. 在 GitHub Desktop 里发布一个仓库，仓库名建议也叫 `小镇梦想家`。
3. 现在已经配置为 `BeiZzzzz`，如果后续更换账号，再修改 [`_config.yml`](D:\小镇梦想家\_config.yml)。
4. 首次推送后，到 GitHub 仓库的 `Settings > Pages`。
5. 在 `Build and deployment` 里选择 `Source: GitHub Actions`。
6. 之后每次推送到 `main` 分支，GitHub 会自动发布博客。

## 如果你改成用户名主页仓库

如果仓库名是 `<你的用户名>.github.io`，请把 [`_config.yml`](D:\小镇梦想家\_config.yml) 改成：

```yml
url: https://<你的用户名>.github.io
root: /
```

## 主要配置文件

- 站点主配置: [`_config.yml`](D:\小镇梦想家\_config.yml)
- Butterfly 主题配置: [`_config.butterfly.yml`](D:\小镇梦想家\_config.butterfly.yml)
- GitHub Pages 工作流: [pages.yml](D:\小镇梦想家\.github\workflows\pages.yml)
