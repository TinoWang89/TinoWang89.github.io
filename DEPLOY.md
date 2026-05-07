# 发布这个个人网站

这个网站是纯静态网页，不需要购买服务器，也不需要域名。你可以把它发布到免费的静态网站平台，获得一个可分享的链接。

## 最简单：Netlify Drop

适合：想最快拿到一个别人能点击的链接。

1. 打开 https://app.netlify.com/drop
2. 登录或注册一个免费 Netlify 账号。
3. 把整个 `personal-website` 文件夹拖进去。
4. 等待上传完成，Netlify 会给你一个 `https://xxx.netlify.app` 链接。
5. 把这个链接发给别人即可。

以后要更新网站时，改完本地文件后，再把整个文件夹拖到 Netlify 的部署区域即可。

## 当前发布目标：GitHub Pages

GitHub 用户名：`TinoWang89`

个人主页仓库名应为：`TinoWang89.github.io`

发布后的免费网址应为：`https://tinowang89.github.io/`

注意：`tinowang.github.io` 需要 GitHub 用户名或组织名是 `tinowang`。当前账号是 `TinoWang89`，所以不能直接使用 `tinowang.github.io`。

1. 在 GitHub 新建一个公开仓库：`TinoWang89.github.io`。
2. 上传本文件夹里的 `index.html`、`styles.css`、`script.js` 和 `.nojekyll`。
3. 进入仓库的 Settings -> Pages。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main` 和 `/root`，然后保存。
6. 等待一两分钟，访问 `https://tinowang89.github.io/`。

## 只临时展示

如果只是给朋友看几分钟，也可以用临时内网穿透工具。但这种方式要求你的电脑一直开着，链接也不稳定，不适合作为正式个人网站。
