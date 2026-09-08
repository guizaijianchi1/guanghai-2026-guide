# 🌊 2026级广东海洋大学新生生存指南

这是一个给 2026 级广海新生看的静态网站，包含新生干货群介绍、校园地图、学长学姐微信二维码等内容。

---

## 📁 项目文件说明

| 文件 | 作用 |
|---|---|
| `index.html` | 网站首页，打开网站时默认显示这个页面 |
| `pdf-converter.html` | 校园地图 PDF 下载页面 |
| `campus-map.jpg` | 湖光校区地图图片 |
| `qr-zhubai.jpg` | 渚白学长微信二维码 |
| `qr-mo.jpg` | 墨学长微信二维码 |
| `qr-canger.jpg` | 苍耳学姐微信二维码 |

---

## 🚀 如何部署到 GitHub Pages（完全免费）

GitHub Pages 是 GitHub 提供的免费网站托管服务，适合放这种静态网页。

### 第一步：注册 GitHub 账号

1. 打开 [github.com](https://github.com)
2. 点击右上角 **Sign up** 注册账号
3. 按照提示完成注册并登录

### 第二步：创建新仓库

1. 登录后点击右上角 **+** 号，选择 **New repository**
2. 在 **Repository name** 处填写仓库名，例如：`guanghai-2026-guide`
3. 选择 **Public**（公开，免费）
4. 勾选 **Add a README file**
5. 点击最下方 **Create repository**

### 第三步：上传网站文件

1. 进入刚创建的仓库页面
2. 点击页面上方的 **Add file** 按钮，选择 **Upload files**
3. 把下面这 6 个文件一起拖到网页中间：
   - `index.html`
   - `pdf-converter.html`
   - `campus-map.jpg`
   - `qr-zhubai.jpg`
   - `qr-mo.jpg`
   - `qr-canger.jpg`
4. 页面拉到最下面，点击 **Commit changes**

### 第四步：开启 GitHub Pages

1. 在仓库页面点击上方的 **Settings**（设置）
2. 左侧菜单找到并点击 **Pages**
3. 在 **Branch** 下面选择 **main**，然后点击 **Save**
4. 等待 1-3 分钟，刷新页面
5. 页面上方会出现绿色提示，里面就是你的网站地址，例如：
   ```
   https://你的用户名.github.io/guanghai-2026-guide/
   ```

### 第五步：访问网站

复制绿色提示里的网址，在浏览器中打开即可。

---

## 🔄 以后如何更新内容

如果要修改文字、替换二维码或地图：

1. 在 GitHub 仓库中找到要修改的文件
2. 点击文件进入，再点击右上角铅笔图标 **Edit this file**
3. 修改内容后，点击页面最下方的 **Commit changes**
4. 等待 1-3 分钟，网站就会自动更新

如果要替换二维码图片：

1. 在仓库中找到对应的 `qr-xxx.jpg` 文件
2. 点击文件进入，再点击右上角三个点 **...**，选择 **Delete this file**
3. 然后点击 **Add file → Upload files**，上传新的二维码图片
4. 注意：新图片的文件名必须和原来完全一样，比如替换渚白学长就还要叫 `qr-zhubai.jpg`

---

## ⚠️ 注意事项

- 不要删除 `index.html`，这是网站首页
- 所有图片和 HTML 文件要在同一个仓库里，不能放文件夹
- 如果网站打开后图片不显示，检查图片文件名是否和 HTML 里写的一致

---

## 💡 技术支持

如果部署过程中遇到问题，可以：

1. 检查文件名是否完全一致（包括大小写）
2. 确认 GitHub Pages 设置里 Branch 选择了 main
3. 等待几分钟再刷新，GitHub Pages 更新有延迟
