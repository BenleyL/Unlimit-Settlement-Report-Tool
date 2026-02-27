# 集成报表提取工具 / Integrated Report Extraction Tool

[English](#english) | [中文](#chinese)

---

<a name="chinese"></a>
## 中文

### 简介

这是一个纯前端单文件工具，用于批量提取和汇总结算单数据。支持两种类型的结算单：
- **Blended Settlement Report（通用结算单）**
- **IC++ Settlement Report（IC++ 结算单）**

### 功能特点

- 支持多文件批量上传
- 纯前端处理，数据不上传服务器，保障隐私安全
- 支持中英文界面切换
- 每种结算单提供两种汇总报表：
  - **结算单交易汇总** - 提取详细的交易记录
  - **结算单金额汇总** - 提取结算金额汇总信息
- 导出 Excel 文件，数字格式化处理

### 支持的结算单类型

| 报表类型 | 交易汇总 | 金额汇总 |
|---------|---------|---------|
| Blended Settlement Report | ✅ | ✅ |
| IC++ Settlement Report | ✅ | ✅ |

### 使用方法

#### 1. 打开工具

直接在浏览器中打开 `full function settlement report v260130.html` 文件，或访问 GitHub Pages 部署地址。

#### 2. 选择报表类型

点击顶部按钮切换结算单类型：
- **通用结算单 (General Report)** - 用于 Blended Settlement Report
- **IC++ 结算单** - 用于 IC++ Settlement Report

#### 3. 上传文件

- 点击文件选择区域选择文件
- 支持拖拽文件到上传区域
- 支持多文件同时上传（.xlsx 格式）

#### 4. 预览数据

- 点击「预览数据」或「预览交易信息」按钮
- 查看提取的数据预览表格
- 切换标签页查看不同类型的汇总报表

#### 5. 导出 Excel

- 选择需要的报表类型（交易汇总/金额汇总）
- 点击「导出Excel」按钮下载汇总文件

### 技术栈

- 纯 HTML/CSS/JavaScript
- SheetJS (xlsx) - Excel 文件解析和导出
- Font Awesome - 图标库

### 部署到 GitHub Pages

1. 将此项目推送到 GitHub 仓库
2. 进入仓库 Settings → Pages
3. Source 选择 Deploy from a branch
4. Branch 选择 main 或 master
5. 点击 Save

部署完成后，访问 `https://<username>.github.io/<repo>/` 即可使用。

### 注意事项

- 所有数据处理均在浏览器本地完成，不会上传到任何服务器
- 建议使用最新版本的 Chrome、Edge 或 Firefox 浏览器
- 支持的文件格式：.xlsx

### 许可证

MIT License

---

<a name="english"></a>
## English

### Introduction

This is a single-file pure frontend tool for batch extraction and consolidation of settlement report data. It supports two types of settlement reports:
- **Blended Settlement Report**
- **IC++ Settlement Report**

### Features

- Batch file upload support
- Pure frontend processing, no server upload, ensuring privacy and security
- Bilingual interface (Chinese/English)
- Two types of summary reports for each settlement type:
  - **Settlement Transactions Report** - Extracts detailed transaction records
  - **Settlement Amount Report** - Extracts settlement amount summary
- Export to Excel with formatted numbers

### Supported Report Types

| Report Type | Transactions | Amount |
|-------------|--------------|---------|
| Blended Settlement Report | ✅ | ✅ |
| IC++ Settlement Report | ✅ | ✅ |

### How to Use

#### 1. Open the Tool

Open the `full function settlement report v260130.html` file directly in your browser, or visit the GitHub Pages deployment URL.

#### 2. Select Report Type

Click the button at the top to switch between settlement types:
- **Blended Settlement Report** - For Blended Settlement Reports
- **IC++ Settlement Report** - For IC++ Settlement Reports

#### 3. Upload Files

- Click the file selection area to choose files
- Drag and drop files to the upload area
- Support for multiple files simultaneously (.xlsx format)

#### 4. Preview Data

- Click the "Preview Data" or "Preview Transactions" button
- View extracted data in the preview table
- Switch tabs to view different types of summary reports

#### 5. Export Excel

- Select the desired report type (Transactions/Amount)
- Click the "Export Excel" button to download the summary file

### Tech Stack

- Pure HTML/CSS/JavaScript
- SheetJS (xlsx) - Excel file parsing and export
- Font Awesome - Icon library

### Deploy to GitHub Pages

1. Push this project to your GitHub repository
2. Go to repository Settings → Pages
3. Select Deploy from a branch as Source
4. Choose branch (main or master)
5. Click Save

After deployment, visit `https://<username>.github.io/<repo>/` to use the tool.

### Notes

- All data processing is done locally in the browser; no data is uploaded to any server
- Recommended browsers: Chrome, Edge, or Firefox (latest versions)
- Supported file format: .xlsx

### License

MIT License
