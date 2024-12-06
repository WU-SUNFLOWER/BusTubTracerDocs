<img src="https://raw.githubusercontent.com/cmu-db/bustub/master/logo/bustub-whiteborder.svg" alt="BusTub Logo" height="200">

-----------------

# 什么是BusTubTracer

BusTubTracer是一款基于BusTub开发的关系型数据库管理系统（RDBMS）底层工作原理和内部数据结构的可视化工具，旨在帮助初学RDBMS底层原理（尤其是[CMU-15445/645课程](https://15445.courses.cs.cmu.edu/)）的计算机类专业学生更好地掌握RDBMS系统设计与实现中的关键概念。

[BusTub](https://github.com/cmu-db/bustub)是由[Carnegie Mellon University](https://www.cs.cmu.edu/)推出的一款开源教学型RDBMS系统。该系统仿照实际的商用RDBMS系统，实现了简单SQL查询、索引等基本功能，是计算机专业学生学习RDBMS底层设计实现和工作原理的宝贵资源。

BusTubTracer基于原版BusTub进行二次开发，在原版的基础上增加了可视化图形界面，用于直观展示BusTub内部的一些重要数据结构，以及BusTub针对SQL命令的处理和执行过程。

BusTubTracer在架构上由两部分组成，分别为前端用户界面`BusTubTracerFront`（基于Electron+Vue3独立开发）和后端核心`BusTubTracerCore`（基于原版BusTub修改）。两者按如下图所示的形式组织在一起，形成完整的BusTubTracer应用。

<img width="917" alt="微信图片_20241205195534" src="https://github.com/user-attachments/assets/bb742330-80ab-4100-a3ec-b9805f145acb">


# 关于本仓库

本仓库存储和管理BusTubTracer项目设计和开发过程中形成的文档资源。

前端用户界面`BusTubTracerCore`的源码仓库请移步：https://github.com/WU-SUNFLOWER/BusTubTracerFront

后端核心`BusTubTracerCore`的源码仓库请移步：https://github.com/WU-SUNFLOWER/BusTubTracerCore
