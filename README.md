# AI Agent Virtual Classroom
### An Interactive Multi-Agent World for Studying Human Cooperation

**AI Systems · Product Design · Behavioral Research · Data Analytics**

> 从研究问题到交互式AI产品：构建一个能够自主运行、产生合作行为并支持行为研究的虚拟智能体世界。

## 🌟 Project Overview | 项目概述

**AI Agent Virtual Classroom** 是一个融合生成式智能体、多智能体交互、虚拟世界模拟与行为科学研究的创新项目。

项目围绕一个核心问题展开：

**Can cooperation in a virtual agent world promote cooperation in the real world?**

虚拟世界中的合作，能否促进现实世界中的人际合作？

为探索这一问题，我设计并持续开发了一个以公共管理硕士（MPA）课堂为原型的多智能体虚拟世界。

在这个虚拟环境中，每位学生对应一个具有独立状态和行为规则的AI智能体。智能体可以按照预设课程日程，自主进行课堂活动、移动、交流及合作。系统记录虚拟世界中的行为事件，并通过差异化的信息展示机制，为研究虚拟互动与现实人际行为之间的关系提供支持。

项目不仅关注AI系统能否运行，更重视如何将研究需求转化为具体产品功能、可操作的交互流程以及可衡量的行为指标。

## 💡 The Challenge | 项目背景与核心问题

多智能体技术使AI角色能够在共享环境中自主互动，但如何将这些互动转化为具有实际研究价值的产品体验，仍然面临多个挑战：

- **Behavioral Simulation：** 如何让多个AI智能体按照统一规则持续开展活动与合作？
- **User Experience：** 如何通过直观的虚拟世界界面呈现复杂的智能体行为？
- **Information Design：** 如何设计不同的信息展示方式，并研究其对用户行为的影响？
- **Data Analytics：** 如何记录和分析虚拟互动事件及现实合作行为？
- **System Scalability：** 如何在有限的计算资源下支持多智能体持续运行？

项目以真实研究场景为需求来源，将上述挑战转化为系统功能、产品设计任务和数据分析方案。

## 🚀 Key Features | 核心功能

### 01. Autonomous Multi-Agent Simulation

**自主运行的多智能体虚拟世界**

系统为不同智能体设置独立的身份、行为状态及活动规则，使其能够在共享虚拟环境中执行任务。

主要设计包括：

- 基于时间推进的智能体活动机制
- 课堂、走廊、茶水间等虚拟场景
- 智能体位置、出勤和活动状态管理
- 自主互动及合作事件记录
- 可配置的行为优先级和运行规则

系统强调智能体行为的独立性，减少人工直接干预。

### 02. Interactive Pixel-Based Virtual World

**交互式像素风虚拟课堂**

项目使用 Phaser 3 和 Tiled 构建可视化虚拟场景，通过像素角色呈现智能体在不同空间中的活动。

主要界面功能包括：

- 像素地图与角色展示
- 智能体活动状态可视化
- 角色详情与信息查看
- 教师及学生角色管理
- 系统运行与状态监测界面

相比传统的数据表格或后台日志，交互式虚拟世界能够更加直观地展示多智能体系统的运行过程。

### 03. Behavioral Event Tracking

**行为事件记录与数据分析**

系统通过结构化数据记录智能体的活动及互动事件，为后续行为分析提供数据基础。

主要记录内容包括：

- 智能体身份与活动状态
- 虚拟活动时间及场景位置
- 合作事件及参与对象
- 系统运行批次及相关事件信息

项目重视数据可追溯性，使产品运行与研究分析能够建立联系。

### 04. Cooperation Signal Experiment

**虚拟合作信号与现实合作研究（研究设计阶段）**

在现有虚拟课堂系统基础上，项目进一步设计合作信息展示实验。

研究方案拟比较两种信息展示方式：

- **Identifiable Cooperation Signals：** 展示具体的虚拟合作对象信息。
- **Neutral Activity Summaries：** 展示不包含具体合作对象身份的中性活动摘要。

通过对现实合作关系开展基线与后续调查，研究计划检验不同信息展示方式是否影响用户主动建立新合作关系的行为。

该部分属于拟实施的研究设计，其研究结果尚未形成，不代表已经证实相关因果效果。

## 👩‍💻 My Role | 我的角色

**Project Initiator · Product & Research Designer · AI-Assisted Developer**

我作为项目发起人与主要设计者，负责从研究需求到系统方案及产品迭代的整体规划。

**1. Product Strategy & Requirements Analysis**

- 将抽象研究问题转化为产品需求和功能模块
- 设计系统角色、使用场景与交互流程
- 制定分阶段开发任务和功能优先级
- 明确系统设计约束与验收标准

**2. AI System Design & Development Coordination**

- 设计多智能体行为逻辑和自主合作规则
- 规划虚拟世界、后台服务和数据管理模块
- 利用AI辅助编程工具推进系统实现与迭代
- 根据功能验证结果持续优化产品方案

**3. Experimental Design & Data Analytics**

- 设计虚拟合作信号的实验机制
- 规划数据收集与行为指标
- 设计纵向问卷与社会网络测量方案
- 规划随机实验、统计建模和行为数据分析

**4. Project Execution & Quality Control**

- 整理项目需求文档、开发计划和验收清单
- 组织阶段性功能检查与问题修复
- 管理系统开发过程中的功能变更
- 关注个人信息保护和研究数据治理

## 🛠 Technology Stack | 技术架构

| Category | Technologies |
|---|---|
| Backend | Python, FastAPI |
| Database | SQLite |
| Frontend | JavaScript, HTML, CSS, Jinja2 |
| Virtual World | Phaser 3, Tiled |
| AI-Assisted Development | OpenAI Codex |
| AI Integration | DeepSeek (optional integration) |
| Data Analytics | Python, Statistical Analysis, Social Network Analysis |
| Version Control | Git, GitHub |

系统采用以 Python 和轻量级 Web 技术为核心的架构，兼顾功能实现、部署成本及后续研究需求。

部分AI能力作为可选模块设计，系统不依赖持续调用外部大模型来维持基本运行。

## 📈 Product Development Process | 项目开发流程

**Research Problem → Requirements → System Design → Prototype Development → Testing → Behavioral Evaluation**

项目采用分阶段迭代方法，将复杂系统拆分为可设计、可实施、可验证的功能模块。

目前已开展的工作主要包括：

- 系统需求与总体架构设计
- 多智能体活动及事件记录机制
- 虚拟课堂场景与像素地图开发
- 智能体状态展示及管理界面
- 数据管理与功能验证
- 后续合作信号实验方案设计

项目仍在持续开发与完善中。研究实验、规模化运行及最终效果评估以实际完成情况为准。

## 🎯 Business & Product Value | 产品与商业能力

虽然项目源于学术研究，但其开发过程同样体现了可迁移至商业产品和业务拓展工作的能力。

**Problem Identification**

从复杂的现实问题中识别核心需求，并提出可执行的解决方案。

**Product Thinking**

将用户需求、业务流程和技术实现整合为完整的产品设计。

**Cross-Functional Integration**

融合人工智能、交互设计、数据库管理及行为研究等不同领域的知识。

**Data-Driven Decision Making**

建立可衡量的行为指标，利用数据支持产品评估和持续改进。

**Project Execution**

通过需求文档、阶段计划、任务拆解及验收标准推动复杂项目逐步落地。

本项目展示了我将跨学科知识转化为具体系统方案的能力，以及使用AI工具支持产品开发和问题解决的实践经验。

## 🔐 Privacy & Responsible AI

本项目涉及虚拟角色与潜在的社会网络研究数据，因此特别关注个人信息保护和负责任的AI使用。

公开展示材料不包含真实参与者的个人身份资料、原始社会网络问卷、敏感系统日志或API密钥。

对外展示优先采用模拟数据、脱敏截图和不涉及个人隐私的产品功能说明。

## 🌍 English Summary

AI Agent Virtual Classroom is an interdisciplinary project combining autonomous agent simulation, interactive product design, and behavioral research.

The project explores whether cooperation signals generated in a virtual multi-agent environment can influence real-world interpersonal collaboration.

As the project initiator and lead designer, I translate research questions into product requirements, design interaction mechanisms and system workflows, coordinate AI-assisted implementation, and develop data-driven evaluation strategies.

The project demonstrates my interests and practical experience in **AI product development, problem solving, project execution, and data-informed decision-making**.

---

**Project Status:** Research prototype under active development.

**Research Focus:** AI-mediated cooperation, multi-agent systems, human–AI interaction, and behavioral analytics.
