---
parent: EN201-CE
title: M05：软件工程和测试
---

# M05：软件工程和测试

|词汇|词性|中文释义|示例句|备注|
|---|---|---|---|---|
|**software engineering**|n.|软件工程|Software engineering focuses on designing reliable and maintainable systems.|计算机专业核心领域之一|
|**software lifecycle**|n.|软件生命周期|The software lifecycle includes development, testing, and maintenance.|SDLC 缩写|
|**requirement**|n.|需求|The system must meet the user’s requirements.|分为 functional / non-functional|
|**specification**|n.|规格说明|The software specification defines what the system should do.|通常为文档|
|**analysis**|n.|分析|Requirement analysis helps clarify what users actually need.|软件开发早期阶段|
|**design**|n./v.|设计|The software architecture design defines the system structure.|分为高层/详细设计|
|**implementation**|n.|实现；编码|The team is working on the implementation phase.|即编码阶段|
|**testing**|n.|测试|Testing ensures the software meets its specifications.|贯穿全周期|
|**deployment**|n.|部署|The final version was deployed to the production server.|代码上线过程|
|**maintenance**|n.|维护|Software maintenance includes bug fixes and updates.|生命周期最后阶段|
|**iteration**|n.|迭代|Each iteration delivers an improved version of the product.|常用于敏捷开发|
|**agile development**|n.|敏捷开发|Agile development emphasizes flexibility and collaboration.|对比瀑布模型|
|**waterfall model**|n.|瀑布模型|The waterfall model follows a linear development process.|传统开发模型|
|**scrum**|n.|敏捷框架|The team holds a daily scrum meeting.|一种敏捷方法|
|**sprint**|n.|冲刺周期|A sprint usually lasts two weeks.|敏捷开发单位|
|**backlog**|n.|待办事项|The product backlog lists all planned features.|Scrum 中常见术语|
|**stakeholder**|n.|利益相关者|Stakeholders include users, managers, and developers.|涉及系统的各方|
|**architecture**|n.|架构|The software architecture defines the system’s components and interactions.|例如三层架构|
|**module**|n.|模块|Each module should perform a single function.|模块化设计原则|
|**interface**|n.|接口|A well-defined interface simplifies integration.|模块间通信点|
|**API (Application Programming Interface)**|n.|应用程序接口|Developers use APIs to connect different services.|软件交互核心概念|
|**UML (Unified Modeling Language)**|n.|统一建模语言|UML diagrams help visualize software structure.|包括类图、用例图等|
|**use case**|n.|用例|Each use case represents a user interaction scenario.|需求分析常用工具|
|**class diagram**|n.|类图|The class diagram shows the relationships between classes.|UML图之一|
|**sequence diagram**|n.|时序图|A sequence diagram shows message flow between objects.|展示交互顺序|
|**data flow diagram (DFD)**|n.|数据流图|A DFD illustrates how data moves through a system.|强调数据过程|
|**entity-relationship diagram (ERD)**|n.|实体关系图|The ERD describes the database structure.|数据库设计图|
|**design pattern**|n.|设计模式|The singleton pattern ensures only one instance of a class exists.|常用如 MVC, Factory|
|**MVC (Model-View-Controller)**|n.|模型-视图-控制器模式|MVC separates business logic from user interface.|常用于前后端架构|
|**cohesion**|n.|内聚|High cohesion improves module readability.|模块内部关系紧密|
|**coupling**|n.|耦合|Loose coupling makes code easier to maintain.|模块之间依赖松散|
|**refactoring**|n.|重构|Refactoring improves code structure without changing behavior.|优化代码|
|**version control**|n.|版本控制|Git is the most popular version control system.|跟踪代码变更|
|**repository**|n.|仓库|The code repository is hosted on GitHub.|存储项目代码|
|**commit**|v./n.|提交|Remember to commit your changes with a clear message.|Git命令之一|
|**merge**|v.|合并|We need to merge the feature branch into the main branch.|Git操作|
|**conflict**|n.|冲突|A merge conflict occurs when two edits overlap.|Git冲突|
|**bug**|n.|程序错误|The team fixed a critical bug in the latest release.|软件缺陷|
|**debugging**|n.|调试|Debugging helps identify and fix software errors.|程序员日常任务|
|**breakpoint**|n.|断点|Set a breakpoint to inspect variable values.|调试工具术语|
|**log file**|n.|日志文件|The log file records system events for analysis.|追踪运行状态|
|**unit test**|n.|单元测试|Unit tests verify the correctness of individual functions.|测试最小单位|
|**integration test**|n.|集成测试|Integration testing ensures modules work together.|模块间测试|
|**system test**|n.|系统测试|System testing checks the entire system’s performance.|综合测试阶段|
|**acceptance test**|n.|验收测试|Acceptance testing verifies if the system meets business goals.|客户验收阶段|
|**regression test**|n.|回归测试|Regression tests ensure new updates don’t break old features.|更新后检查稳定性|
|**black-box testing**|n.|黑盒测试|Black-box testing focuses on inputs and outputs.|不关注内部结构|
|**white-box testing**|n.|白盒测试|White-box testing examines the internal logic.|查看源代码执行|
|**test case**|n.|测试用例|Each test case defines inputs, actions, and expected outputs.|基础测试单元|
|**test coverage**|n.|测试覆盖率|High test coverage indicates good code reliability.|衡量测试充分性|
|**automation testing**|n.|自动化测试|Automation testing saves time and reduces human error.|使用工具自动执行测试|
|**CI/CD (Continuous Integration / Continuous Deployment)**|n.|持续集成与持续部署|CI/CD pipelines automate build, test, and deployment.|DevOps核心实践|
|**documentation**|n.|文档编写|Good documentation helps maintain software over time.|项目交付重要组成|
|**review**|n./v.|评审|Code review improves software quality.|同行检查机制|
|**quality assurance (QA)**|n.|质量保证|QA ensures the software meets predefined standards.|包含多阶段测试|
