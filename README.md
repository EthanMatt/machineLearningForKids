# 🌤️ 青少年机器学习 10 天入门

> 适合 10-16 岁同学的 Machine Learning 入门课程
> 从零开始，用天气数据学编程和机器学习！

## 📋 学前准备

### 需要提前了解的知识

这门课从零开始教 Python 和机器学习，**不需要任何编程基础**。但如果你提前了解以下内容，学习会更顺利：

| 知识点 | 重要程度 | 说明 |
|--------|---------|------|
| 基本的电脑操作 | ⭐⭐⭐ | 会打开终端/Terminal、安装软件、管理文件夹 |
| 英语阅读 | ⭐⭐ | 代码和报错信息都是英文，能借助翻译工具读懂即可 |
| 数学基础 | ⭐⭐ | 小学高年级水平的算术就够了（加减乘除、小数、百分比） |
| 编程经验 | ⭐ | 有加分，没有完全没关系，Day 01 会从零教起 |

### 需要安装的软件

在开始之前，请确保你的电脑上安装了以下软件：

| 软件 | 用途 | 下载地址 | 安装提示 |
|------|------|---------|---------|
| **Python 3.10+** | 运行代码的核心语言 | [python.org](https://www.python.org/downloads/) | 安装时记得勾选 **"Add Python to PATH"** |
| **Jupyter Notebook** | 写代码和看结果的交互式页面 | 安装后自动可用 | 通过 `pip install notebook` 安装 |
| **VS Code**（推荐） | 代码编辑器，方便管理文件 | [code.visualstudio.com](https://code.visualstudio.com/) | 可选，但比系统自带的记事本好用很多 |

### 需要安装的 Python 库

打开终端（Terminal / 命令行），进入项目文件夹后运行：

```bash
pip install -r requirements.txt
```

如果 `pip` 命令报错，试试：

```bash
pip3 install -r requirements.txt
```

### 如何打开终端

| 系统 | 方法 |
|------|------|
| **Windows** | 按 `Win + R`，输入 `cmd` 或 `powershell`，回车 |
| **macOS** | 按 `Cmd + 空格`，搜索 "终端" 或 "Terminal" |
| **Linux** | 按 `Ctrl + Alt + T` |

### 如何启动 Jupyter Notebook

在终端中进入项目文件夹，然后运行：

```bash
cd MLforKids
jupyter notebook
```

浏览器会自动打开 Jupyter 页面。如果没有自动打开，把终端里显示的链接复制到浏览器即可。

> **提示**：如果 `jupyter` 命令找不到，先运行 `pip install jupyter` 再试。

## ✨ 你会学到什么？

- 🐍 Python 编程基础
- 📊 数据处理和可视化
- 🤖 机器学习的核心概念
- 🌤️ 用天气数据做真实的预测项目

## 🚀 快速开始

### 1. 安装 Python

确保你的电脑上有 Python 3.10 或更高版本。在终端输入：

```bash
python --version
```

如果没有，去 [python.org](https://python.org) 下载安装。

### 2. 下载本项目

```bash
git clone <仓库地址>
cd MLforKids
```

### 3. 安装依赖

```bash
pip install -r requirements.txt
```

### 4. 启动 Jupyter

```bash
jupyter notebook
```

浏览器会自动打开 Jupyter 页面，从 `day01` 开始依次学习！

## 📚 课程安排

| 天数 | 主题 | 知识点 |
|------|------|--------|
| Day 01 | Python 小热身 | 变量、列表、循环、函数 |
| Day 02 | 认识机器学习 | 监督学习、数据可视化 |
| Day 03 | 线性回归 | 用历史数据预测温度 |
| Day 04 | 分类问题 | 预测明天是否下雨 |
| Day 05 | 决策树 | 像规则一样思考 |
| Day 06 | 模型评估 | 谁更准？ |
| Day 07 | 聚类分析 | 给城市分分组 |
| Day 08 | 特征工程 | 让数据说话 |
| Day 09 | 天气助手 | 完整项目实战：数据清洗→特征工程→训练3个模型→评估→保存模型 |
| Day 10 | 大项目 | 建自己的预测模型：自选任务+设计特征+训练模型+写实验报告 |

## 📝 学习建议

- 每天 30-60 分钟，**动手敲代码**比看更重要
- 遇到不懂的地方，先自己试试再看提示
- 每个 notebook 最后的「挑战任务」是选做的，学有余力可以尝试
- 推荐按顺序学习，因为后面的内容会用到前面的知识

## 🔧 技术栈

- Python 3.10+
- Jupyter Notebook
- pandas（数据处理）
- scikit-learn（机器学习）
- matplotlib + seaborn（数据可视化）
- Open-Meteo API（免费天气数据）

## 📄 License

MIT License — 自由使用和分享！
