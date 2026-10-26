基于智能体的结构力学机动分析

张乐业1，唐仕蛟1，张洪俊2

（1. 南京审计大学金审学院，南京210023；

2. 万世先行数智交通科技有限公司，南京210016）

摘要：机动分析是结构力学中判断平面杆系体系几何组成与稳定性的基础性工作。本文基于 LangChain 框架构建了一个面向结构力学机动分析的智能体系统。系统以大语言模型为推理核心，集成两项技能：其一为具有图像理解与渲染能力的 doubao-visualization技能包，用于识别输入的结构实例图片并绘制带分析结果的示意图；其二为依据结构力学教材编写的 structural-kinematic-analysis 专业技能包，可解析节点、杆件与支座，计算体系自由度，并调用二元体、两刚片、三刚片等法则进行机动分析。用户只需输入结构图片，智能体即可自主规划、调用技能，输出几何不变或几何可变体系的判定结论及可视化结果，并凭借记忆能力支持 "去掉某一支座是否仍稳定" 等交互式追问。对几何不变体系与几何可变体系两个典型实例的测试表明，智能体分析结果正确，验证了该方法的可行性，为结构力学教学辅助与工程结构初判的智能化提供了一条新途径。

Kinematic analysis of structural mechanics based on AI Agent

Leye Zhang1，Shijiao Tang1，Hongjun Zhang2

（1. Nanjing Audit University Jinshen College, Nanjing, 210023, China;

2. Wanshi Antecedence Digital Intelligence Traffic Technology Co., Ltd, Nanjing, 210016, China）

Abstract：Kinematic analysis is a foundational task in structural mechanics for determining the geometric composition and stability of planar bar systems. This paper develops an agent system based on the LangChain framework for structural mechanics kinematic analysis. The system takes a large language model as its reasoning core and integrates two skills: one is the doubao-visualization skill package, which provides image understanding and rendering capabilities to recognize input structural example images and draw schematic diagrams annotated with analysis results; the other is the structural-kinematic-analysis professional skill package, built according to structural mechanics textbooks, which can parse nodes, bars, and supports, compute the degrees of freedom of the system, and invoke rules such as the binary-body, two-rigid-plate, and three-rigid-plate rules to perform kinematic analysis. By merely inputting a structural image, the agent can autonomously plan and invoke the required skills, output a verdict on whether the system is geometrically stable or unstable together with visualized results, and, thanks to its memory capability, support interactive follow-up questions such as "Is it still stable if a certain support is removed?" Tests on two typical examples of a geometrically stable system and a geometrically unstable system show that the agent produces correct results, verifying the feasibility of the proposed approach and offering a new pathway toward intelligent assistance for structural mechanics teaching and the preliminary assessment of engineering structures.
