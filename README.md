# 实验室主页（Lab website）

基于 [Hugo](https://gohugo.io) + Hugo Blox Builder，部署在 Netlify。
改内容只需要编辑 `content/` 和 `data/` 里的文本文件，推送到 GitHub 后 Netlify 会自动重新发布。

## 我要改……去哪里改

| 想改的内容 | 文件位置 |
|---|---|
| 实验室名称、学校、邮箱、地址 | `data/lab.yaml`（全站通用，改一次即可） |
| 导航栏上的站名 | `config/_default/hugo.yaml` 的 `title` |
| 导航栏栏目 | `config/_default/menus.yaml` |
| 首页文字（大标题、简介） | `content/_index.md` |
| 研究方向 | `content/research/<方向>/index.md`，配图命名为 `featured.jpg/png` |
| 成员 | `content/authors/<姓名>/_index.md`，头像命名为 `avatar.jpg` |
| 毕业生去向 | `data/alumni.yaml` |
| 新闻 | `content/post/<日期-标题>/index.md`，配图命名为 `featured.jpg` |
| 相册 | 把照片放进 `content/gallery/<年份>/`，说明文字写在 `content/gallery/index.md` |
| 论文 | `content/publication/<年份-简称>/index.md` + `cite.bib` |
| 交互演示网页 | 把 `.html` 放进 `static/demos/`，再在 `content/resources/index.md` 里加一条 |
| 资源、文化、加入我们 | `content/resources/`、`content/culture/`、`content/contact/` 下的 `index.md` |
| 主题色 | `data/themes/lab.toml` 的 `primary`，以及 `assets/scss/custom.scss` 顶部的颜色变量 |
| 页面版式 | `layouts/`（一般不需要动） |

## 常见操作

**新增一条新闻**：复制 `content/post/` 下任意一个文件夹，改文件夹名（`2027-03-01-xxx`），再改 `index.md` 里的 `title`、`date`、`summary` 和正文。

**新增一位成员**：复制 `content/authors/luyue-wang/`，文件夹改成姓名拼音（如 `san-zhang`），填写 `title`、`first_name`、`last_name`、`name_zh`、`role`、`user_groups`，放入 `avatar.jpg`。
`user_groups` 可选：`Principal Investigator`、`Postdoctoral Researchers`、`PhD Students`、`Master's Students`、`Undergraduate Researchers`、`Visitors`。

**新增一篇论文**：复制 `content/publication/` 下任意一个文件夹，改 `index.md` 和 `cite.bib`。
`featured: true` 的论文会出现在首页 "Selected work"；`research_areas` 填研究方向的文件夹名，论文就会出现在对应方向页面。
作者里与 `content/authors/` 文件夹同名的人会自动加粗并链接到个人页。

**新增相册照片**：照片直接放进 `content/gallery/2027/` 这样的年份文件夹即可，不写说明也能显示。

## 本地预览（可选）

安装 Hugo **extended** 0.135.0（<https://github.com/gohugoio/hugo/releases/tag/v0.135.0>），在本文件夹运行：

```
hugo server
```

然后打开 <http://localhost:1313>。主题文件已经放在 `_vendor/` 里，不需要安装 Go，也不需要联网下载。

## 部署到 GitHub Pages（推荐的日常更新方式）

仓库里已经带好自动发布脚本 `.github/workflows/hugo.yml`：每次把修改推送到 GitHub 的 `main` 分支，GitHub 会自动用 Hugo 构建并发布网站，不需要手动构建。

第一次设置：
1. 用 GitHub Desktop 打开本文件夹（File → Add local repository），按提示在这里创建仓库，提交全部文件，然后 Publish repository。仓库必须是 **Public**（免费账号的私有仓库不能用 Pages）。
2. 在 GitHub 网页上打开这个仓库 → Settings → Pages → Build and deployment → Source 选 **GitHub Actions**。
3. 到仓库的 Actions 页面，等 "Deploy site to GitHub Pages" 变成绿色对勾，网址就是 `https://<用户名>.github.io/<仓库名>/`。

以后：改文件 → 在 GitHub Desktop 里 Commit → Push，一两分钟后网站自动更新。

## 部署到 Netlify

1. 在 GitHub 新建一个仓库，把本文件夹的全部内容上传（`public/` 和 `resources/` 不用传）。
2. 在 Netlify 选择 **Add new site → Import an existing project → GitHub**，选中这个仓库。
3. 构建设置已写在 `netlify.toml` 里（命令 `hugo --gc --minify`，发布目录 `public`，Hugo 0.135.0），保持默认，点 **Deploy**。
4. 以后每次往 GitHub 推送修改，网站会自动更新。

## 目前还是占位内容、需要确认的地方

在文件里搜索 `TODO` 可以找到全部待填项。
