# Codex — 公开课程资料归档

本仓库是我个人学习用的公开课程资料归档,所有资料按课程分文件夹存放,每个课程目录独立自包含,方便直接浏览或按需取用。

## 目录一览

| 文件夹 | 课程 |
|---|---|
| [`cs61a-2023/`](cs61a-2023/) | UC Berkeley CS 61A(2023 秋) |
| [`cs61b-2024/`](cs61b-2024/) | UC Berkeley CS 61B(2024 春) |
| [`cs329a-stanford/`](cs329a-stanford/) | Stanford CS329A(2025 秋) |
| [`cmu-agents-11768/`](cmu-agents-11768/) | CMU 11-768(2026 秋) |
| [`jhu-695744-reverse-engineering/`](jhu-695744-reverse-engineering/) | JHU EN.695.744 |
| [`hss-purdue/`](hss-purdue/) | Purdue HSS(2021–2024) |
| [`cs598lmz-uiuc/`](cs598lmz-uiuc/) | UIUC CS598LMZ(2024 春) |
| [`software-agents-uiuc/`](software-agents-uiuc/) | UIUC Software Engineering with LLM Agents |

## 各课程说明

### cs61a-2023 — UC Berkeley CS 61A:Structure and Interpretation of Computer Programs(Fall 2023)

- `UCBerkeley-CS61A-Fall2023/`:全量课程资料及答案,含 Projects(hog / cats / ants / scheme)、Labs、HW、Discussion、Exams 与 Slides_fall22。
- `cs61a-2023-fall-selfstudy/`:本人自学时的整理笔记。
- `site-fa23/`:官方 cs61a.org Fall 2023 站点存档快照(取自 web.archive.org,2023-12-15)。

### cs61b-2024 — UC Berkeley CS 61B:Data Structures(Spring 2024)

- `skeleton-sp24/`:官方 skeleton 代码(hw / lab / proj 框架)。
- `library-sp24/`:作业库。
- `lectureCode-sp24/`:课堂示例代码。
- `site-sp24/`:官方 sp24.datastructur.es 站点完整镜像(77 页 HTML + 48 份 discussion 工作表 PDF)。

### cs329a-stanford — Stanford CS329A:Self-Improving AI Agents(Autumn 2025)

- `cs329a-schedule.md`:完整 20 讲课程日程,附全部论文链接与评分政策。

### cmu-agents-11768 — CMU 11-768:AI Agents(Fall 2026)

课程官网为客户端渲染 SPA,以下为抓取与渲染提取产物:

- `schedule-rendered.txt` / `syllabus-rendered.txt` / `assignments-rendered.txt` / `staff-rendered.txt` / `page-full-rendered.html`:用 headless Chromium 渲染后提取的课程日程、教学大纲、作业与教师信息。
- `slides-lecture-01-agents.pdf`:第一讲课件。
- `index.raw.html` + `app.js`:原始 SPA 页面与前端 bundle(备用)。

### jhu-695744-reverse-engineering — JHU EN.695.744:Reverse Engineering & Vulnerability Analysis

- `course-page.md`:课程目录页内容,含教材与教学大纲链接。

### hss-purdue — Purdue Holistic Software Security(Fall 2021–2024,Machiry)

- `hss-site/`:purs3lab/hss 完整 Jekyll 站点源码,含 lectures、assignments、schedule 与 materials。

### cs598lmz-uiuc — UIUC CS598LMZ:Software Quality Assurance with Generative AI(Spring 2024)

- `slides/`:5 份教师讲义 PDF(课程介绍、程序分析、软件测试、自动调试、LLM 基础);其余课时为论文研讨,无教师课件。
- `course-page.html`:完整课程页存档。
- `README.md`:课程模块划分与论文清单说明。

### software-agents-uiuc — UIUC Software Engineering with LLM Agents(Lingming Zhang)

- `repo/`:GitHub lingming/software-agents 仓库副本,仅含 README 课程大纲;正式资料发布在 Campuswire/Canvas,无公开文件。

## 获取方式说明

仓库类资料在归档时已去除 `.git`;网页类资料为原站直接抓取或 web.archive.org 存档;CMU 课程站点为 SPA,使用 headless Chromium 渲染后提取文本。

## 声明

本仓库所有课程资料仅供个人学习参考,版权归原作者及原课程主办方所有;如有侵权请联系删除。