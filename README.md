# Xu Jin - Personal Resume Website

这是一个基于Hugo和Hugo Blox主题构建的个人简历网站，部署在GitHub Pages上。

## 项目结构

```
Resume/
├── hugo.yaml              # Hugo主配置文件
├── go.mod                 # Go模块依赖
├── content/
│   ├── _index.md          # 主页内容
│   └── authors/admin/     # 个人资料配置
├── assets/media/          # 媒体文件（图片、图标等）
├── static/uploads/        # 静态文件（如PDF简历）
├── .github/workflows/     # GitHub Actions自动部署配置
└── README.md             # 项目说明

```

## 本地开发

1. 安装Hugo（需要extended版本）:
   ```bash
   # macOS
   brew install hugo

   # 或下载二进制文件
   # https://github.com/gohugoio/hugo/releases
   ```

2. 安装Go依赖:
   ```bash
   hugo mod tidy
   ```

3. 本地预览:
   ```bash
   hugo server
   ```

   访问 http://localhost:1313 查看网站

## 部署到GitHub Pages

### 步骤1: 创建GitHub仓库
1. 在GitHub上创建一个新仓库
2. 将代码推送到GitHub

### 步骤2: 启用GitHub Pages
1. 进入仓库设置页面
2. 找到"Pages"设置
3. 将Source设置为"GitHub Actions"

### 步骤3: 自动部署
每次推送到main分支时，GitHub Actions会自动构建和部署网站。

## 自定义域名设置

如果你有自己的域名，需要进行以下配置：

### 1. 更新Hugo配置
在 `hugo.yaml` 中修改 `baseURL`:
```yaml
baseURL: 'https://yourdomain.com'
```

### 2. DNS配置
在你的域名服务商处添加以下DNS记录：
- CNAME记录: `www` -> `yourusername.github.io`
- A记录: `@` -> GitHub Pages IP地址

### 3. GitHub Pages域名设置
在仓库设置的Pages页面中，添加你的自定义域名。

## 内容修改

### 个人信息
编辑 `content/authors/admin/_index.md` 文件来修改个人信息、技能、工作经历等。

### 主页布局
编辑 `content/_index.md` 文件来调整主页的区块布局和内容。

### 添加PDF简历
将PDF文件放在 `static/uploads/` 目录下，文件名为 `resume.pdf`。

## 主题自定义

这个项目使用Hugo Blox的resume主题。你可以通过以下方式自定义：

1. 修改 `hugo.yaml` 中的主题配置
2. 在 `assets/` 目录下添加自定义CSS
3. 调整配色方案和字体

## 支持的功能

- ✅ 响应式设计
- ✅ 深色/浅色主题切换
- ✅ 联系表单
- ✅ 社交媒体链接
- ✅ PDF简历下载
- ✅ SEO优化
- ✅ 自动部署

## 故障排除

如果遇到问题，请检查：
1. Hugo版本是否为extended版本
2. Go模块依赖是否正确安装
3. GitHub Actions工作流是否成功运行
4. DNS配置是否正确（如使用自定义域名）

## 技术栈

- Hugo (静态网站生成器)
- Hugo Blox (主题框架)
- GitHub Actions (CI/CD)
- GitHub Pages (托管服务)