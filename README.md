# 你好，我是黄翩然 👋

哈尔滨工业大学硕士研究生，关注 **机器人系统、边缘计算与系统软件**。

我喜欢把设备、数据、能力与调度流程连成可运行的完整系统，并在实际工程中处理性能、可观测性、异构设备接入和稳定性问题。

- 🎓 研究方向：机器人中间件、边缘计算、分布式系统
- 🛠️ 工作方式：架构设计、性能分析、代码审查、部署调试与问题排查
- 🤖 当前关注：多模态感知、机器人能力编排、视觉与机械臂控制闭环
- 📍 坐标：中国·哈尔滨

## 代表项目

### [Edge Sidecar Logger](https://github.com/hollow2003/edge_sidecarlogger)

可配置的边缘日志采集系统。使用 C 实现多线程 sidecar，支持 HTTP、Redis 和 Unix FIFO 数据采集，包含进程监控、动态采集配置、NTP 时间同步与动态库插件。

`C` `Redis` `HTTP` `Unix FIFO` `Dynamic Library`

### [Remote Logger](https://github.com/hollow2003/remote_logger)

Edge Sidecar Logger 的中心侧数据处理组件。根据 JSON Schema 动态生成数据库表和 SQLAlchemy ORM 类，将边缘端日志转换为结构化数据。

`Python` `JSON Schema` `SQLAlchemy` `Redis` `PostgreSQL`

### [Robot & Server Simulator](https://github.com/hollow2003/server_and_robot_simulator)

面向机器人数据采集的早期原型：通过 UDP 发现设备，读取设备提供的 JSON Schema，按订阅频率轮询 API 并写入结构化数据库。

`Python` `Flask` `UDP Discovery` `JSON Schema` `SQLite`

### [Karpathy LLM Wiki Best Practice](https://github.com/hollow2003/Karpathy-LLM-Wiki-Best-Practice)

面向 LLM Agent 和 Obsidian 的长期知识库模板。使用 `raw / wiki / schema` 三层结构管理原始资料、可复用知识和 Agent 行为规则，支持持续累积、索引和维护。

`LLM Agent` `Obsidian` `Markdown` `Knowledge Management`

<details>
<summary><strong>更多早期探索</strong></summary>

- [sidecar_launcher](https://github.com/hollow2003/sidecar_launcher)：边缘 sidecar 进程启动与管理组件
- [Nginx_Lua_Proxy](https://github.com/hollow2003/Nginx_Lua_Proxy)：基于 Nginx + Lua 的边缘数据预处理实验
- [Admin_panel](https://github.com/hollow2003/Admin_panel)：数据采集系统控制面板
- [Intelligent_Box](https://github.com/hollow2003/Intelligent_Box)：基于 STM32 的温湿度自动控制终端

</details>

## 技术栈

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

## GitHub 数据

<p>
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=hollow2003&show_icons=true&hide_border=true&locale=cn" alt="GitHub 统计" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hollow2003&layout=compact&hide_border=true&locale=cn" alt="常用语言" />
</p>

## 联系我

- 📧 25S003016@stu.hit.edu.cn
- 🔗 [GitHub](https://github.com/hollow2003)

> 让真实设备、可复用能力与稳定的软件架构一起工作。
