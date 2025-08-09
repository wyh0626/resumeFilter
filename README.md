# 简历筛选助手 Resume Screener Pro

<div align="center">
🎯 **AI 驱动的智能简历筛选助手**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/wyh0626/resumeFilter)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Dify](https://img.shields.io/badge/Powered%20by-Dify-purple.svg)](https://dify.ai/)

[中文](#chinese) | [English](#english)

</div>

---

`<a name="chinese"></a>`

## 🌟 简历筛选助手

**一个具备"外科手术式精准分析"能力的智能招聘助手**

### 📋 项目简介

简历筛选助手参考[简历警察](https://github.com/itMrBoy/resumePolice)项目，基于 Dify 工作流构建的 AI 招聘工具。

### ✨ 核心功能

* **🚀 智能快筛** - 30秒快速判断，适合初步筛选
* **🔍 深度分析** - 六维度全面评估，适合重点候选人
* **💡 面试题设计** - 生成精准面试问题，适合面试准备
* **📊 全面分析** - 包含以上所有内容，适合关键岗位

### 🎯 核心能力

#### P.O.S.E.R. 风险识别模型

* **P** (Problem): 业务问题理解深度
* **O** (Ownership): 个人贡献真实性
* **S** (Scale): 规模复杂度验证
* **E** (Engineering): 技术决策质量
* **R** (Results): 成果影响力评估

#### 六维度深度分析

1. **技术能力验证 (30%)** - 核心技术栈匹配、技术深度、架构能力
2. **项目真实性审计 (25%)** - 规模合理性、技术选型逻辑、贡献清晰度
3. **问题解决能力 (20%)** - 技术难题攻克、方案权衡、创新思维
4. **成长潜力评估 (10%)** - 技术栈更新、学习能力、职业清晰度
5. **团队协作能力 (10%)** - 跨部门协作、技术分享、冲突解决
6. **稳定性风险 (5%)** - 跳槽频率、职业连贯性、薪资期望

### 🚀 快速开始

#### 安装步骤

1. **访问 Dify 平台**

   * 访问 https://cloud.dify.ai/apps
   * 登录您的账号
2. **导入工作流**

   ```bash
   # 下载工作流文件
   git clone https://github.com/wyh0626/resumeFilter.git
   cd resumeFilter
   ```

   * 导航到 工作流 → 导入 DSL 文件
   * 选择 `workflow` 目录下的 `简历筛选助手.yml` 文件
   * 配置您的 AI API 密钥（支持任何 AI 提供商，不限于 Anthropic）
3. **开始使用**

   * 输入岗位描述（JD）
   * 上传候选人简历（支持批量上传）
   * 选择分析模式
   * 获取智能分析结果

### 📖 使用指南

#### 分析模式说明

| 模式                 | 使用场景       | 输出内容                 |
| -------------------- | -------------- | ------------------------ |
| **智能快筛**   | 初步大批量筛选 | 通过/淘汰决策 + 关键发现 |
| **深度分析**   | 入围候选人评估 | 六维度详细报告           |
| **面试题设计** | 面试准备       | 10个精准问题及评估标准   |
| **全面分析**   | 关键岗位       | 完整分析套餐             |

#### 输入参数

* **岗位职位描述（必填）** ：详细的职位要求和职责
* **简历文件（必填）** ：支持批量上传，最多10个文件
* **特殊筛选要求（选填）** ：额外的筛选标准
* **分析模式** ：根据需求选择

### 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

### 🙏 致谢

* 灵感来源：[简历警察](https://github.com/itMrBoy/resumePolice)
* 技术支持：[Dify](https://dify.ai/) 工作流引擎

### 📮 联系方式

* 问题反馈：[GitHub Issues](https://github.com/wyh0626/resumeFilter/issues)
* 邮箱：wyh19970626@gmail.com

---

---

`<a name="english"></a>`

## 🌟 Resume Screener Pro

**An intelligent recruitment assistant that performs surgical-precision analysis on resumes**

### 📋 Project Description

Resume Screener Pro is inspired by [Resume Police](https://github.com/itMrBoy/resumePolice) and built on Dify workflow as an AI-powered recruitment tool.

### ✨ Key Features

* **🚀 Smart Quick Screen** - 30-second rapid assessment for initial filtering
* **🔍 Deep Analysis** - Six-dimensional comprehensive evaluation for key candidates
* **💡 Interview Question Design** - Generate targeted interview questions based on resume analysis
* **📊 Comprehensive Analysis** - All-in-one analysis combining all features above

### 🎯 Core Capabilities

#### P.O.S.E.R. Risk Assessment Model

* **P** (Problem): Business problem understanding depth
* **O** (Ownership): Authenticity of personal contributions
* **S** (Scale): Scale and complexity verification
* **E** (Engineering): Technical decision quality
* **R** (Results): Impact assessment of achievements

#### Six-Dimensional Deep Analysis

1. **Technical Competency (30%)** - Core skills matching, technical depth, architecture abilities
2. **Project Authenticity (25%)** - Scale reasonableness, technical selection logic, contribution clarity
3. **Problem-Solving (20%)** - Technical challenges overcome, solution trade-offs, innovation
4. **Growth Potential (10%)** - Tech stack updates, learning ability, career clarity
5. **Team Collaboration (10%)** - Cross-functional experience, mentoring, conflict resolution
6. **Stability Risk (5%)** - Job-hopping frequency, career path coherence, salary expectations

### 🚀 Quick Start

#### Installation

1. **Access Dify Platform**

   * Visit https://cloud.dify.ai/apps
   * Log into your account
2. **Import Workflow**

   ```bash
   # Download the workflow file
   git clone https://github.com/wyh0626/resumeFilter.git
   cd resumeFilter
   ```

   * Navigate to Workflows → Import DSL file
   * Select the workflow file `简历筛选助手.yml` from the `workflow` directory
   * Configure your AI API key (supports any AI provider, not limited to Anthropic)
3. **Start Using**

   * Input job description (JD)
   * Upload candidate resumes (batch upload supported)
   * Select analysis mode
   * Get instant intelligent analysis results

### 📖 Usage Guide

#### Analysis Modes

| Mode                             | Use Case               | Output                                         |
| -------------------------------- | ---------------------- | ---------------------------------------------- |
| **Smart Quick Screen**     | Initial bulk screening | Pass/Fail decision + key findings              |
| **Deep Analysis**          | Shortlisted candidates | Six-dimensional detailed report                |
| **Interview Questions**    | Interview preparation  | 10 targeted questions with evaluation criteria |
| **Comprehensive Analysis** | Key positions          | Complete analysis package                      |

#### Input Parameters

* **Job Description (Required)** : Detailed position requirements and responsibilities
* **Resume Files (Required)** : Support batch upload up to 10 files
* **Special Requirements (Optional)** : Additional screening criteria
* **Analysis Mode** : Choose based on your needs

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 🙏 Acknowledgments

* Inspired by [Resume Police](https://github.com/itMrBoy/resumePolice)
* Powered by [Dify](https://dify.ai/) workflow engine
