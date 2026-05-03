<div align="center">

## 👋 你好，我是 He Hongbo

### 高级 PHP & Go 双栈开发工程师 | 10年+后端经验

> 专注高并发系统设计与微服务架构，用代码解决真实世界的复杂问题

PHP 资深开发者（9年） × Go 进阶实践者（2年+），既能维护高并发 PHP 存量系统，也能从 0 构建 Go 分布式微服务。主导过日均 600 万级数据增量的交易平台、万级并发 IM 系统、企业级 ERP 等高并发项目，具备全链路架构设计与性能优化能力。

[![GitHub](https://img.shields.io/badge/GitHub-HeRedBo-181717?logo=github)](https://github.com/HeRedBo)
[![Email](https://img.shields.io/badge/Email-hhbjkd@163.com-D14836?logo=gmail)](mailto:hhbjkd@163.com)

</div>

---

## 🛠 技术栈 Tech Stack

### 编程语言 Languages
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

### PHP 框架 PHP Frameworks
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![ThinkPHP](https://img.shields.io/badge/ThinkPHP-3B82F6?logo=php&logoColor=white)
![Hyperf](https://img.shields.io/badge/Hyperf-009999?logo=php&logoColor=white)

### Go 框架 Go Frameworks
![Go-Zero](https://img.shields.io/badge/Go--Zero-00ADD8?logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?logo=go&logoColor=white)
![Iris](https://img.shields.io/badge/Iris-5E00D6?logo=go&logoColor=white)

### 数据库 Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)

### 消息队列 Message Queue
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)

### 运维与部署 DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

### 监控与日志 Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?logo=jaeger&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-005571?logo=elasticstack&logoColor=white)

### 前端技术 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)
![Element UI](https://img.shields.io/badge/Element%20UI-409EFF?logo=element&logoColor=white)

### 开发工具 Tools
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile-427819?logo=gnu&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?logo=docker&logoColor=white)

---

## 🚀 核心开源项目 Featured Projects

### [EasyChat — 高性能分布式 IM 即时通讯系统](https://github.com/HeRedBo/easy-chat)

> 基于 Go-Zero 微服务框架构建的生产级分布式即时通讯系统

![Go-Zero](https://img.shields.io/badge/Go--Zero-微服务框架-00ADD8?style=flat-square&logo=go) ![gRPC](https://img.shields.io/badge/gRPC-协议通信-4285F4?style=flat-square) ![WebSocket](https://img.shields.io/badge/WebSocket-长连接-010101?style=flat-square) ![Kafka](https://img.shields.io/badge/Kafka-消息队列-231F20?style=flat-square&logo=apachekafka) ![MongoDB](https://img.shields.io/badge/MongoDB-聊天存储-47A248?style=flat-square&logo=mongodb) ![Redis](https://img.shields.io/badge/Redis-状态缓存-DC382D?style=flat-square&logo=redis) ![Docker](https://img.shields.io/badge/Docker-容器化部署-2496ED?style=flat-square&logo=docker)

- 单机支持 **10,000+** WebSocket 长连接，消息推送延迟 < 100ms
- 消息确认 + 重试队列 + 幂等性校验三重保障，消息到达率 99.99%
- 深度落地 go-zero 自动熔断降级、自适应限流，3倍流量压测服务仍可用
- 基于 Makefile 实现 dev/test/prv/prod 四环境一键构建部署

---

### [Go-ES8 高并发搜索微服务商城系统](https://github.com/HeRedBo/go-search)

> 以 Elasticsearch 8 为核心构建毫秒级响应的企业级搜索中台

![Go](https://img.shields.io/badge/Go-微服务架构-00ADD8?style=flat-square&logo=go) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch_8-搜索引擎-005571?style=flat-square&logo=elasticsearch) ![Kafka](https://img.shields.io/badge/Kafka-数据管道-231F20?style=flat-square&logo=apachekafka) ![Docker](https://img.shields.io/badge/Docker-容器编排-2496ED?style=flat-square&logo=docker) ![Microservices](https://img.shields.io/badge/Microservices-服务拆分-FF6F00?style=flat-square)

- 商品搜索响应从 2-3s 优化至 **50ms** 以内，提升 60 倍
- Kafka + 重试机制保障索引同步成功率 **99.9%**
- 严格遵循 Go project-layout 标准目录结构
- Docker Compose 一键启动完整环境，部署时间从 2h 降至 10min

---

### [Go-Spider 高性能并发爬虫框架](https://github.com/HeRedBo/go-spider)

> 基于 Go 原生并发能力的高性能数据采集引擎

![Go](https://img.shields.io/badge/Go-并发编程-00ADD8?style=flat-square&logo=go) ![Goroutine](https://img.shields.io/badge/Goroutine-协程池-00ADD8?style=flat-square) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-批量写入-005571?style=flat-square&logo=elasticsearch) ![goquery](https://img.shields.io/badge/goquery-HTML解析-E34F26?style=flat-square)

- 并发架构相比串行爬虫效率提升 **300%**，单节点 QPS 达 500+
- 信号量机制动态控制并发度，长时间运行稳定不崩溃
- 模块化分层架构，新增数据源仅需实现 Parser 接口，接入成本 < 30 分钟
- 指数退避重试机制保障数据抓取成功率 **98%+**

---

## 📊 GitHub 概览 GitHub Overview

![HeRedBo's GitHub](https://img.shields.io/badge/GitHub-HeRedBo-181717?style=for-the-badge&logo=github)
![Repos](https://img.shields.io/badge/Public_Repos-20+-blue?style=for-the-badge)
![Go Projects](https://img.shields.io/badge/Go_Projects-5+-00ADD8?style=for-the-badge&logo=go)
![PHP Projects](https://img.shields.io/badge/PHP_Experience-9_Years-777BB4?style=for-the-badge&logo=php)

---

## 💼 职业经历 Professional Experience

| 时间 | 公司 | 角色 |
|:---|:---|:---|
| 2023 - 至今 | 深圳飞之度科技 | PHP 高级工程师（日均 600 万级数据交易平台） |
| 2022 | 深圳爱追光科技 | PHP 高级工程师（50 万 DAU 社交 APP） |
| 2020 - 2022 | 深圳载信软件 | PHP 高级工程师 / 技术负责人（ERP 系统，6 人团队） |
| 2015 - 2020 | 广州多家科技公司 | PHP 开发工程师（壹心理、房者荣耀等） |

---

## 📫 联系方式 Contact

[![Email](https://img.shields.io/badge/Email-hhbjkd@163.com-D14836?logo=gmail&logoColor=white)](mailto:hhbjkd@163.com)
[![GitHub](https://img.shields.io/badge/GitHub-HeRedBo-181717?logo=github&logoColor=white)](https://github.com/HeRedBo)

---

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=HeRedBo&color=blue)](https://github.com/HeRedBo)

> **「代码是思想的延伸，架构是系统的灵魂。」** — 用工程化思维构建高可用、高性能的分布式系统

</div>
