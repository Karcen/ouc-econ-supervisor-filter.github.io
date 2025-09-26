# ouc-econ-supervisor-filter 🎓

A supervisor screening system tailored for the School of Economics, Ocean University of China (OUC), designed to help students quickly find suitable supervisors based on multiple filters.

一款为中国海洋大学经济学院量身打造的导师筛选系统，助力学生通过多维度筛选快速找到合适的导师。

## 📋 Project Overview 项目概述

This system aims to solve the problem of inefficient supervisor searching for students in the School of Economics, OUC. It aggregates supervisor information (such as supervisor type, professional title, research direction, etc.) and provides intuitive filtering functions, enabling students to accurately locate potential supervisors that match their needs.

该系统旨在解决中国海洋大学经济学院学生寻找导师效率低的问题，整合了导师信息（如导师类别、职称、研究方向等）并提供直观的筛选功能，让学生能精准定位符合自身需求的潜在导师。

## ✨ Key Features 核心功能



1.  **Multi-dimensional Filtering** 🎯

    Support filtering by supervisor type (master supervisor/doctoral supervisor), professional title (professor/associate professor/lecturer), and research direction (e.g., international trade, financial economics).

    支持按导师类别（硕导 / 博导）、职称（教授 / 副教授 / 讲师）、研究方向（如国际贸易、金融经济学）等多维度筛选。

2.  **Clear Information Display** 📄

    Show detailed supervisor information including name, educational background, research achievements, and contact information (with privacy protection).

    清晰展示导师姓名、学历背景、研究成果、联系方式（含隐私保护）等详细信息。

3.  **Real-time Filtering Feedback** ⚡

    The results are updated in real-time as filtering conditions change, without the need for page reloading.

    筛选条件变化时结果实时更新，无需页面刷新。

4.  **Responsive Design** 📱

    Adapt to different devices (computers, tablets, mobile phones) to ensure a good user experience on various screens.

    适配不同设备（电脑、平板、手机），确保在各类屏幕上均有良好使用体验。

## 🚀 How to Use 使用方法



1.  Visit the system homepage (local deployment or online link).

    访问系统首页（本地部署或在线链接）。

2.  Set filtering conditions in the left/top filter panel:

*   Select "Supervisor Type" (e.g., "Master Supervisor" to exclude doctoral supervisors).

*   Choose "Professional Title" (e.g., "Professor" to focus on senior supervisors).

*   Pick "Research Direction" (e.g., "Financial Economics" to match academic interests).

    在左侧 / 顶部筛选面板设置筛选条件：

*   选择 “导师类别”（如 “硕导” 可排除博导）。

*   勾选 “职称”（如 “教授” 聚焦资深导师）。

*   挑选 “研究方向”（如 “金融经济学” 匹配学术兴趣）。

1.  View the filtered supervisor list in the main content area, and click on a supervisor card to view detailed information.

    在主内容区查看筛选后的导师列表，点击导师卡片可查看详细信息。

## 🛠️ Installation & Deployment 安装部署

### Prerequisites 前置条件



*   Node.js (v14+)

*   npm/yarn

*   Git

### Local Deployment Steps 本地部署步骤



1.  Clone the repository 克隆仓库



```
git clone https://github.com/your-username/ouc-econ-supervisor-filter.git

cd ouc-econ-supervisor-filter
```



1.  Install dependencies 安装依赖



```
npm install

\# or

yarn install
```



1.  Run the development server 启动开发服务器



```
npm run dev

\# or

yarn dev
```



1.  Access the system 访问系统

    Open your browser and go to `http://localhost:3000` (port may vary, refer to the terminal prompt).

    打开浏览器，访问 `http://localhost:3000`（端口可能不同，以终端提示为准）。

## 📦 Technology Stack 技术栈



*   Frontend: HTML, CSS (Tailwind CSS), JavaScript (Vue.js/React)

    前端：HTML、CSS（Tailwind CSS）、JavaScript（Vue.js/React）

*   Data Storage: JSON (for static data) / Firebase (for dynamic data)

    数据存储：JSON（静态数据）/ Firebase（动态数据）

*   Build Tool: Vite/Webpack

    构建工具：Vite/Webpack

## 🤝 Contribution 贡献方式



1.  Fork the repository 分叉仓库

2.  Create a feature branch 创建功能分支



```
git checkout -b feature/your-feature-name
```



1.  Commit your changes 提交修改



```
git commit -m "Add: your feature description"
```



1.  Push to the branch 推送到分支



```
git push origin feature/your-feature-name
```



1.  Open a Pull Request 打开拉取请求

## 📄 License 许可证

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

本项目基于 MIT 许可证开源 - 详见 [LICENSE](LICENSE) 文件。

## 📞 Contact 联系方式

If you have any questions or suggestions, please contact:

如遇问题或有建议，可联系：



*   Email: your-email@example.com

*   GitHub Issues: [https://github.com/your-username/ouc-econ-supervisor-filter/issues](https://github.com/your-username/ouc-econ-supervisor-filter/issues)

> （注：文档部分内容可能由 AI 生成）