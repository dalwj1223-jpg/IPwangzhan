# 食卡卡互动展示网站 · GitHub Pages 发布说明

`site/` 是可以直接部署的静态网站：包含 HTML、构建后的 JavaScript、CSS、图片、视频与模型资源。资源路径已处理为相对路径，适用于普通项目仓库的 GitHub Pages 地址。

## 发布步骤

1. 新建 GitHub 仓库，并将 `site/` 内的**全部内容**上传到仓库根目录。
2. 打开仓库的 **Settings → Pages**，选择从分支部署，并选择对应分支及根目录 `/`。
3. 保存后等待 GitHub Pages 生成访问地址。

## 文件说明

- `site/`：完整可部署站点，含 `index.html`、`assets/*.js`、`assets/*.css` 及所有运行资源。
- `images/`：从站点中独立整理的 PNG、JPG、WebP 图片，保持原目录结构。
- `svg/`：SVG 清单。当前项目不包含需单独上传的 SVG 文件。
- `media/`：页面使用的 MP4 视频副本。

请不要改变 `site/` 内的目录层级；页面素材依赖这些相对位置加载。
