# AIFinLearn 启动指南

## 项目概述
这是一个静态HTML项目，展示AI+金融调研合集页面。无需构建步骤，可直接预览。

## . - AIFinLearn (静态HTML)

### 快速启动

**方式一：直接打开（推荐）**

直接在浏览器中打开 index.html 文件即可预览。

**方式二：使用HTTP服务器**

```bash
# 使用 Python
python3 -m http.server 8000

# 或使用 npx
npx serve .
```

**启动后访问**：http://localhost:8000 (HTTP服务器方式)

```yaml
subProjectPath: .
command: open index.html
cwd: .
port: null
previewUrl: file://index.html
description: AI+金融调研合集静态首页
```
