# stock_app_demo 发布版

这是一个可直接托管到 `GitHub Pages` 的静态站点发布包，包含：

- `index.html`：首页
- `ai.html`：AI异动筛股
- `kline.html`：K线捕手
- `banner.jpg`
- `logo.png`

## 推荐发布方式

### 方式一：GitHub Pages

1. 在 GitHub 新建一个公开仓库，例如 `stock-app-demo`
2. 将本目录全部文件上传到仓库根目录
3. 进入仓库 `Settings`
4. 打开 `Pages`
5. 在 `Build and deployment` 里选择 `GitHub Actions`
6. 等待 Actions 跑完

发布成功后，链接通常是：

`https://你的GitHub用户名.github.io/stock-app-demo/`

### 方式二：Cloudflare Pages

1. 在 Cloudflare Pages 创建新项目
2. 选择 `Upload assets`
3. 直接上传本目录
4. 保持静态站点默认设置即可

发布成功后，链接通常是：

`https://项目名.pages.dev`

## 注意

- 页面之间使用相对路径跳转，适合直接做静态托管
- 当前版本已经按手机远程展示场景调整过编码和跳转
- 如果需要自定义域名，可以在 GitHub Pages 或 Cloudflare Pages 后台继续绑定
