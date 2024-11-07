## 用途


获取Hexo博客giscus评论组件的最新评论

## 一键部署

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/Achuan-2/recent-comment)

## 配置

需要在vercel中设置环境变量，配置完成后请redeploy！

|name|description|
|:---|:---|
| `LIMIT` |获取数量|
| `GITHUB_REPO_OWNER` |Github用户名|
| `GITHUB_REPO_NAME` |仓库名|
| `GITHUB_CATEGORY_ID` |Discussions分类名称|
| `GITHUB_TOKEN` |Github Access Token|

> `GITHUB_CATEGORY_ID` :你可以在 https://giscus.app/ 中找到 `data-category-id` 注意是 ID 不是名称！
