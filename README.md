# 程铁峰个人主页

这个 `github` 文件夹就是可直接上传到 GitHub 仓库根目录的完整静态站点版本。

## 页面结构

- `index.html`：首页
- `education.html`：教育背景页
- `research.html`：研究项目页
- `publications.html`：成果产出页
- `contact.html`：联系页
- `404.html`：404 页面

## 资源结构

- `assets/images/avatar.jpg`：头像
- `assets/images/research-1.jpg`：研究图片 1
- `assets/images/research-2.jpg`：研究图片 2
- `assets/images/conference-2025-bme.jpg`：会议报告图片
- `assets/docs/cheng-tiefeng-resume.pdf`：简历 PDF
- `styles/style.css`：公共样式

## 上传方式

把这个 `github` 文件夹里的全部内容上传到你的 GitHub 仓库根目录即可。

如果你使用 GitHub Pages：

1. 新建仓库并上传本目录全部文件。
2. 进入 `Settings -> Pages`。
3. 选择：
   - `Source: GitHub Actions`，或
   - `Deploy from a branch -> main /(root)`。

## 本地预览

在该目录下执行：

```powershell
python -m http.server 8000
```

然后访问：`http://localhost:8000`
