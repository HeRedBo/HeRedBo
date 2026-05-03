<div align="center">

## 👋 Hey there, I'm He Hongbo

### 高级 PHP & Go 双栈开发工程师 | 10年+后端经验

> 专注高并发系统设计与微服务架构，用代码解决真实世界的复杂问题

PHP 资深开发者（9年） × Go 进阶实践者（2年+），既能维护高并发 PHP 存量系统，也能从 0 构建 Go 分布式微服务。主导过日均 600 万级数据增量的交易平台、万级并发 IM 系统、企业级 ERP 等高并发项目，具备全链路架构设计与性能优化能力。

[![GitHub](https://img.shields.io/badge/GitHub-HeRedBo-181717?logo=github)](https://github.com/HeRedBo)
[![Email](https://img.shields.io/badge/Email-hhbjkd@163.com-D14836?logo=gmail)](mailto:hhbjkd@163.com)

</div>

---

## 🛠 Tech Stack

### Languages
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

### PHP Frameworks
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![ThinkPHP](https://img.shields.io/badge/ThinkPHP-3B82F6?logo=php&logoColor=white)
![Hyperf](https://img.shields.io/badge/Hyperf-009999?logo=php&logoColor=white)

### Go Frameworks
![Go-Zero](https://img.shields.io/badge/Go--Zero-00ADD8?logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?logo=go&logoColor=white)
![Iris](https://img.shields.io/badge/Iris-5E00D6?logo=go&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)

### Message Queue
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)

### DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

### Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?logo=jaeger&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-005571?logo=elasticstack&logoColor=white)

### Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)
![Element UI](https://img.shields.io/badge/Element%20UI-409EFF?logo=element&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile-427819?logo=gnu&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?logo=docker&logoColor=white)

---

## 🚀 Featured Projects

### EasyChat — 高性能分布式 IM 即时通讯系统

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HeRedBo&repo=easy-chat&theme=default)](https://github.com/HeRedBo/easy-chat)

**技术标签：** `Go-Zero` `gRPC` `WebSocket` `Kafka` `MongoDB` `Redis` `Docker`

**一句话描述：** 生产级分布式即时通讯解决方案，解决万级并发长连接管理、消息可靠投递与离线同步等核心 IM 难题。

**核心亮点：**
- 单机支持 **10,000+** WebSocket 长连接，消息推送延迟 **< 100ms**
- 设计「消息确认 + 重试队列 + 幂等性校验」三重保障，消息到达率 **99.99%**
- 深入落地 go-zero 自动熔断降级与自适应限流，压测 3 倍流量时核心服务仍可用
- MySQL + MongoDB + Redis 混合存储架构，协同提升系统吞吐量

---

### Go-ES8 高并发搜索微服务商城系统

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HeRedBo&repo=go-search&theme=default)](https://github.com/HeRedBo/go-search)

**技术标签：** `Go` `Elasticsearch 8` `Kafka` `Docker` `Microservices`

**一句话描述：** 以 Elasticsearch 8 为核心的毫秒级响应企业级搜索中台，实现商品/订单数据近实时同步与复杂聚合分析。

**核心亮点：**
- 商品搜索响应从传统方案 2-3s 优化至 **50ms** 以内，提升 **60 倍**
- Kafka + 重试机制保障，索引同步成功率 **99.9%**
- 服务边界清晰，高内聚低耦合，各服务可独立开发、测试、部署
- Docker 化实现开发/生产环境一致性，部署时间从 2 小时降至 **10 分钟**

---

### Go-Spider 高性能并发爬虫框架

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HeRedBo&repo=go-spider&theme=default)](https://github.com/HeRedBo/go-spider)

**技术标签：** `Go` `Goroutine` `Channel` `Elasticsearch` `goquery`

**一句话描述：** 基于 Go 并发编程实践的高性能爬虫框架，实现可配置、可观测、易维护的数据采集引擎。

**核心亮点：**
- 并发架构提升效率 **300%**，单节点 QPS 达 **500+**
- 信号量动态控制并发度，防止 goroutine 爆炸，长时间运行稳定
- 模块化分层架构，新增数据源仅需实现 Parser 接口，接入成本 **< 30 分钟**
- 指数退避重试 + 反爬策略，数据抓取成功率 **98%+**

---

## 📊 GitHub Stats

<div align="center">

[![HeRedBo's GitHub stats](https://github-readme-stats.vercel.app/api?username=HeRedBo&show_icons=true&theme=default&hide=prs&count_private=true)](https://github.com/HeRedBo)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=HeRedBo&layout=compact&theme=default)](https://github.com/HeRedBo)

</div>

---

## 💼 Professional Experience

| 时间 | 公司 | 角色 |
|:---|:---|:---|
| 2023 - 至今 | 深圳飞之度科技 | PHP 高级工程师（日均 600 万级数据交易平台） |
| 2022 | 深圳爱追光科技 | PHP 高级工程师（50 万 DAU 社交 APP） |
| 2020 - 2022 | 深圳载信软件 | PHP 高级工程师 / 技术负责人（ERP 系统，6 人团队） |
| 2015 - 2020 | 广州多家科技公司 | PHP 开发工程师（壹心理、房者荣耀等） |

---

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-hhbjkd@163.com-D14836?logo=gmail&logoColor=white)](mailto:hhbjkd@163.com)
[![GitHub](https://img.shields.io/badge/GitHub-HeRedBo-181717?logo=github&logoColor=white)](https://github.com/HeRedBo)

---

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=HeRedBo&color=blue)](https://github.com/HeRedBo)

> **「代码是思想的延伸，架构是系统的灵魂。」** — 用工程化思维构建高可用、高性能的分布式系统

</div>
