# 崔皓月
## 前端开发工程师 ｜ 三年经验
📞 17852033192 | 📧 moonc2021@outlook.com | 🌐 https://github.com/Phoebe0/

## 教育经历
山东理工大学 | 软件工程 | 本科
2017.09 - 2021.06

英语水平：CET4

奖项：蓝桥杯程序设计竞赛（C/C++）省二等奖（2020）

## 专业技能
**技术栈**

1. 精通JavaScript（ES6+），熟悉异步编程、闭包、原型链等核心概念。
2. 熟练使用React技术栈（Hooks/Redux/React-Router），具备组件化开发与状态管理经
验。
3. 熟悉AntDegisn等前端开发UI组件库。
4. 熟练使用Tailwind CSS，掌握Flex/Grid布局构建响应式页面。
5. 能够使用TypeScript，运用泛型、装饰器等特性开发类型安全项目。
6. 熟练使用Node.js+Express开发高性能API服务以及掌握中间件使用。
7. 熟练编写复杂的SQL查询语句，包括多表连接、子查询、聚合函数、窗口函数等。
8. 熟练使用Git进行版本控制，熟悉Git Flow工作流与分支管理策略。
9. 熟练使用npm/pnpm管理依赖，掌握Vite构建工具配置与优化。
10. 擅长使用AI工具辅助编程。

## 工作经历
**上海金仕达成信息科技有限公司** | **前端开发工程师**
2022.09 - 2025.02

1. 报表系统迭代与功能开发
负责核心功能模块开发与迭代优化，提升代码可维护性，开发效率提升20%。

2. 数据可视化大屏开发
基于ECharts开发自适应可视化大屏，支持十万级数据实时渲染，页面加载速度提升40%。

3. 前端性能优化
通过代码分割+懒加载策略优化首屏性能，FCP从2.1s降至1.3s。

4. 跨系统数据交互与协作
与数据团队协作解决跨系统数据交互问题，推动项目提前2周交付。

## 项目经验
### 文章平台（个人项目）
2024.10 - 至今

**项目技术点：**

React + TanStack Query + Tailwind CSS + Axios + Express + MongoDB

**项目描述：**

本项目是一个多功能的文章发布与互动平台，支持用户权限管理、文章创作、评论互动、
文章管理等功能，旨在为用户提供高效的内容创作与交流体验。
实现用户鉴权，确保接口安全性与数据隔离。
富文本编辑器，支持Markdown与图文混排。
评论与互动功能实现多级评论功能，支持点赞、收藏、推荐。
文章展示与收藏基于分页与懒加载技术优化文章列表展示，支持按分类、标签与关键词
搜索。

**技术描述：**

**前端（React/Vite）**

1. 使用React Router 6 实现 10+ 页面路由。
2. 封装Layout组件，进行公共组件提取，确保相同的页面共享组件结构。
3. 通过 react-toastify 实现全局通知系统。
4. 使用Tailwind CSS构建响应式页面，支持多端适配。
5. 基于react-quilljs封装自定义的富文本框组件。
6. 采用 TanStack Query 实现数据缓存，跨组件数据同步，以及乐观更新机制优化用户体验。

**后端（Express）**

1. 基于 Express 5 搭建 RESTful API，采用 TypeScript 实现 15+ 核心接口。
2. 使用MVC架构，构建清晰、可维护的服务端程序。
3. 通过 Mongoose 设计 4 个数据模型（文章/用户/评论/访问统计）。
4. 配置 Clerk Webhook，监听 user.created 事件，实时获取新增用户信息。
5. 集成 ImageKit 云存储，支持自动 WebP 格式转换，优化图片资源响应速度。


### 报表与分析平台
2022.09 - 2025.02

**项目技术点：**

React + RBAC权限控制 + XLSX + Canvas

**项目描述：**

本项目是内部的报表与分析平台项目，为不同角色的用户提供灵活、便捷的数据查询与分
析功能，同时确保数据的安全性和系统的稳定性，为日常运营和决策支持提供了强大的技
术保障。
对登录用户的功能权限和数据权限进行精细化管理。通过角色分配，确保每个用户只能
访问其权限范围内的功能和数据，有效防止数据泄露和越权操作。
实现报表展示、发布、修改、下线、导入导出等操作。
异常数据邮件告警，定时发送每日日报等。

**技术描述：**
1. 使用 React 和 React Router 实现基于角色的权限控制。通过路由守卫（Route Guard）和动态路由加载，确保用户只能访问其权限范围内的页面和功能。
2. 后端根据用户的角色（总部、分公司、营业部）返回不同的数据范围。前端通过 Redux 管理用户权限状态，动态渲染不同的数据视图。
3. 利用XLSX.js库处理Excel文件，实现上传、下载、文件数据处理。
4. 通过RSA非对称加密对用户信息进行加密，确保数据的安全性。
5. 使用 useState 和 useEffect 实现分页加载与懒加载。通过 pageSize 和 loadPage 方法分批加载大规模数据，减少初始加载时间。
6. 图片资源进行优化，采用Base64编码，减少图片加载时间，提升前端性能。
7. 扁平结构数据转换为树状结构，并通过 Ant Design Tree 组件展示。
8. 敏感字段使用正则进行动态脱敏（资金账号、证券账号等部分隐藏）。
9. 通过 Canvas 动态生成用户 ID 水印，防止数据泄露。
10. 使用 setInterval 的轮询功能定时请求实时接口，动态更新图表和数据

### 客户信息一本帐大屏
2023.09 - 2023.12

React + vw/vh + swiper + echarts

**项目描述：**

本项目主要针对的是客户信息的可视化展示。通过不同的维度对客户状态进行分析。

**技术描述：**

1. 使用 vw/vh 确保不同设备比例一致性，结合Grid布局，动态调整组件排列方式，做到响
应式布局。
2. 使用 swiper 实现不同页签的轮播。
3. 使用React封装自定义表格组件、指标翻牌组件等。
4. 通过 React.memo 和 useCallback 优化组件性能，减少不必要的渲染，提升页面响应速
度。
5. 使用 ECharts 对数据进行常见的图表、地图等可视化展示。
6. 使用骨架屏占位，svg、canvas等提高大屏的展示效果。
7. 使用过滤器以及前端方法对复杂数据进行处理。
8. 使用SQL处理上游原表数据，并实现接口进行前端开发。

### 个人总结
驱动力强，主动学习新技术并快速应用，持续追求技术成长与突破。
具有良好的沟通、协调能力，曾与多部门协同，高效沟通并推动项目交付，确保团队目标一致。
乐于分享，在CSDN、GitHub等分享自己的学习成果以及技术见解。
在高强度工作环境下保持高效，具备较强的抗压能力和执行力，确保项目按时高质量完成。
