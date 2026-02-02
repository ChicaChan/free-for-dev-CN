# free-for.dev

开发者和开源作者现在有许多提供免费层级的服务，但要找到并全面比较这些服务需要时间，才能做出明智决定。

这是一份列出提供开发者免费层级的软件（SaaS、PaaS、IaaS 等）及其他服务的清单。

本清单聚焦基础设施方向的开发者（系统管理员、DevOps 从业者等）可能用得上的内容。我们也喜欢所有免费服务，但希望保持主题聚焦。有时界限并不明确，所以此列表带有主观取舍；如果未接受你的贡献，还请见谅。

本清单汇集了 1600+ 人通过 Pull Request、评审、想法和贡献完成的成果。你也可以通过提交 [Pull Request](https://github.com/ripienaar/free-for-dev) 来新增服务，或移除已变更或下线的项目。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**：本清单仅收录 as-a-Service 形式的服务，不包含自建/自托管软件。要符合条件，服务必须提供长期免费层级，而非短期试用；若免费层级按时间计量，至少应覆盖一年。我们也从安全角度评估免费层级，因此支持 SSO 没问题，但不会接受把 TLS 限制为付费专属的服务。

<a id="table-of-contents"></a>

# 目录

  * [主要云服务商的永久免费额度](#major-cloud-providers)
  * [云管理解决方案](#cloud-management-solutions)
  * [数据分析、事件与统计](#analytics-events-and-statistics)
  * [API、数据与机器学习](#apis-data-and-ml)
  * [制品仓库](#artifact-repos)
  * [BaaS（后端即服务）](#baas)
  * [低代码平台](#low-code-platform)
  * [CDN 与安全防护](#cdn-and-protection)
  * [CI 与 CD](#ci-and-cd)
  * [CMS（内容管理系统）](#cms)
  * [代码生成](#code-generation)
  * [代码质量](#code-quality)
  * [代码搜索与浏览](#code-search-and-browsing)
  * [崩溃与异常处理](#crash-and-exception-handling)
  * [地图数据可视化](#data-visualization-on-maps)
  * [托管数据服务](#managed-data-services)
  * [设计与 UI](#design-and-ui)
  * [设计灵感](#design-inspiration)
  * [开发者博客平台](#dev-blogging-sites)
  * [DNS](#dns)
  * [Docker 相关](#docker-related)
  * [域名](#domain)
  * [教育与职业发展](#education-and-career-development)
  * [电子邮件](#email)
  * [功能开关管理平台](#feature-toggles-management-platforms)
  * [字体](#font)
  * [表单](#forms)
  * [生成式 AI](#generative-ai)
  * [IaaS](#iaas)
  * [IDE 与代码编辑](#ide-and-code-editing)
  * [国际手机号验证 API 与 SDK](#international-mobile-number-verification-api-and-sdk)
  * [问题跟踪与项目管理](#issue-tracking-and-project-management)
  * [日志管理](#log-management)
  * [移动应用分发与反馈](#mobile-app-distribution-and-feedback)
  * [管理系统](#management-system)
  * [消息与流式处理](#messaging-and-streaming)
  * [杂项](#miscellaneous)
  * [监控](#monitoring)
  * [PaaS](#paas)
  * [包构建系统](#package-build-system)
  * [支付与计费集成](#payment-and-billing-integration)
  * [隐私管理](#privacy-management)
  * [截图 API](#screenshot-apis)
  * [Flutter 相关与无 Mac 构建 iOS 应用](#flutter-related-and-building-ios-apps-without-mac)
  * [搜索](#search)
  * [安全与 PKI](#security-and-pki)
  * [认证、授权与用户管理](#authentication-authorization-and-user-management)
  * [源代码仓库](#source-code-repos)
  * [存储与媒体处理](#storage-and-media-processing)
  * [隧道、WebRTC、WebSocket 服务器与其他路由方案](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [测试](#testing)
  * [团队协作工具](#tools-for-teams-and-collaboration)
  * [翻译管理](#translation-management)
  * [访客会话录制](#visitor-session-recording)
  * [网站托管](#web-hosting)
  * [评论平台](#commenting-platforms)
  * [基于浏览器的硬件仿真](#browser-based-hardware-emulation-written-in-javascript)
  * [远程桌面工具](#remote-desktop-tools)
  * [游戏开发](#game-development)
  * [其他免费资源](#other-free-resources)

<a id="major-cloud-providers"></a>

## 主要云服务商的永久免费额度

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 个前端实例小时，9 个后端实例小时
    * Cloud Firestore - 1GB 存储，每天 50,000 次读取、20,000 次写入、20,000 次删除
    * Compute Engine - 1 台非抢占式 e2-micro，30GB HDD，5GB 快照存储（限制在部分地区），每月 1 GB 从北美到各地区（不含中国和澳大利亚）的网络出站流量
    * Cloud Storage - 5GB 存储，1GB 出站流量
    * Cloud Shell - 基于 Web 的 Linux Shell/主 IDE，含 5GB 持久存储；每周限 60 小时
    * Cloud Pub/Sub - 每月 10GB 消息
    * Cloud Functions - 每月 200 万次调用（包含后台与 HTTP 调用）
    * Cloud Run - 每月 200 万次请求、360,000 GB-秒内存、180,000 vCPU-秒计算时间、每月 1 GB 从北美出站流量
    * Google Kubernetes Engine - 一个区域集群免管理费；每个用户节点按 Compute Engine 标准定价计费
    * BigQuery - 每月 1 TB 查询量，每月 10 GB 存储
    * Cloud Build - 每天 120 构建分钟
    * Cloud Source Repositories - 最多 5 个用户、50 GB 存储、50 GB 出站流量
    * [Google Colab](https://colab.research.google.com/) - 免费的 Jupyter Notebooks 开发环境。
    * [Firebase Studio](https://firebase.studio) - Google Firebase Studio（原 Project IDX），在 Google Cloud 上运行的在线 VSCode。
    * 完整、详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出站流量与 200 万次 Function 调用
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标与 10 个告警
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分钟构建时长
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 名活跃用户、50GB 存储、每月 10000 次请求
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 条活动流水线
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
    * [EC2](https://aws.amazon.com/ec2/) - 每月 750 小时 t2.micro 或 t3.micro（12 个月）；每月 100GB 出站流量
    * [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用型（SSD）或磁盘（12 个月）
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 每月 750 小时（12 个月）
    * [RDS](https://aws.amazon.com/rds/) - 每月 750 小时 db.t2.micro、db.t3.micro 或 db.t4g.micro，20GB 通用型（SSD）存储，20GB 备份存储（12 个月）
    * [S3](https://aws.amazon.com/s3/) - 5GB 标准对象存储、20K 次 Get 请求、2K 次 Put 请求（12 个月）
    * [Glacier](https://aws.amazon.com/glacier/) - 10GB 长期对象存储
    * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 万次请求
    * [SNS](https://aws.amazon.com/sns/) - 每月 100 万次发布
    * [SES](https://aws.amazon.com/ses/) - 每月 3,000 封邮件（12 个月）
    * [SQS](https://aws.amazon.com/sqs/) - 每月 100 万次队列请求
    * 完整、详细列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 台 B1S Linux VM，1 台 B1S Windows VM（12 个月）
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个 Web、移动或 API 应用（每天 60 CPU 分钟）
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万次请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 快速、易用且轻量的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月 50,000 个存储用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 名活跃用户，无限私有 Git 仓库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 针对开源项目的 Linux、macOS、Windows 提供 10 个免费并行作业且不限分钟数
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费的公共负载均衡 IP（VIP）
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万次推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 15GB 入站（12 个月）与每月 5GB 出站
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB 存储与 1000 RU 预置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) — 构建、部署、托管静态应用与无服务器函数，包含免费 SSL、认证/授权与自定义域名
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储（12 个月）
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译、人脸检测、机器人等），含有限额度的免费层
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AI 搜索与索引服务，免费 10,000 文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管 Kubernetes 服务，集群管理免费
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 每月 100K 次操作
    * 完整、详细列表 - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算
       - 2 台 AMD 计算型 VM，每台 1/8 OCPU 与 1 GB 内存
       - 4 个基于 Arm 的 Ampere A1 核心与 24 GB 内存，可作为 1 台 VM 或最多 4 台 VM 使用
       - 实例在被 [判定为空闲](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances) 时会被回收
    * Block Volume - 2 个卷，总计 200 GB（用于计算实例）
    * Object Storage - 10 GB
    * Load balancer - 1 个实例，10 Mbps
    * Databases - 2 个数据库，每个 20 GB
    * Monitoring - 5 亿条摄取数据点，10 亿条检索数据点
    * Bandwidth - 每月 10 TB 出站，x64 VM 速度限制 50 Mbps，ARM VM 速度限制为 500 Mbps * 核心数
    * Public IP - VM 2 个 IPv4，负载均衡 1 个 IPv4
    * Notifications - 每月 100 万次投递选项，1000 封邮件
    * 完整、详细列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudant 数据库 - 1 GB 数据存储
    * Db2 数据库 - 100MB 数据存储
    * API Connect - 每月 50,000 次 API 调用
    * Availability Monitoring - 每月 300 万个数据点
    * Log Analysis - 每日 500MB 日志
    * 完整、详细列表 - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - 提供无限域名的免费 DNS、DDoS 防护、CDN 以及免费 SSL、防火墙规则与页面规则、WAF、Bot 防护、免费不限量速率限制（每域名 1 条规则）、分析与邮件转发
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 位用户、24 小时活动日志、三个网络位置
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 可通过隧道将本地 HTTP 端口暴露到 trycloudflare.com 的随机子域名，使用 [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)，无需账号。更多功能（TCP 隧道、负载均衡、VPN）见 [Zero Trust](https://www.cloudflare.com/products/zero-trust/) 免费计划。
    * [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 全球网络免费部署无服务器代码——每天 100k 次请求。
    * [Workers KV](https://developers.cloudflare.com/kv) - 每天 100k 次读取、1000 次写入、1000 次删除、1000 次列表请求，1 GB 存储数据
    * [R2](https://developers.cloudflare.com/r2/) - 每月 10 GB，100 万次 Class A 操作/月，1000 万次 Class B 操作/月
    * [D1](https://developers.cloudflare.com/d1/) - 每天读取 500 万行、写入 100k 行，1 GB 存储
    * [Pages](https://developers.cloudflare.com/pages/) - 在 Cloudflare 快速安全的全球网络上开发并部署 Web 应用。每月 500 次构建、100 个自定义域名、集成 SSL、无限可访问席位、无限预览部署，并通过 Cloudflare Workers 集成实现全栈能力。
    * [Queues](https://developers.cloudflare.com/queues/) - 每月 100 万次操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) – 每月 1TB 免费出站流量。

  * [Zoho](https://www.zoho.com) — 起初是电子邮件提供商，如今提供一系列服务，其中部分提供免费计划。提供免费计划的服务列表：
    * [Email](https://zoho.com/mail) - 5 名用户免费。5GB/用户，25 MB 附件上限，1 个域名。
    * [Zoho Assist](https://www.zoho.com/assist) — Zoho Assist 的永久免费计划包含 1 个并发远程支持许可，并提供 5 台无人值守计算机许可，适用于专业与个人使用。
    * [Sprints](https://zoho.com/sprints) - 5 名用户免费，5 个项目，500MB 存储。
    * [Docs](https://zoho.com/docs) — 5 名用户免费，1 GB 上传限制与 5GB 存储。包含 Zoho Office Suite（Writer、Sheets 与 Show）。
    * [Projects](https://zoho.com/projects) — 3 名用户免费，2 个项目，10 MB 附件上限。同一计划适用于 [Bugtracker](https://zoho.com/bugtracker)。
    * [Connect](https://zoho.com/connect) — 团队协作版免费 25 名用户，包含 3 个群组、3 个自定义应用、3 个看板、3 个手册、10 个集成，以及频道、事件和论坛。
    * [Meeting](https://zoho.com/meeting) — 会议最多 3 名参会者，网络研讨会最多 10 名参会者。
    * [Vault](https://zoho.com/vault) — 个人可用的密码管理。
    * [Showtime](https://zoho.com/showtime) — 另一个培训会议工具，远程培训最多 5 名参与者。
    * [Notebook](https://zoho.com/notebook) — Evernote 的免费替代品。
    * [Wiki](https://zoho.com/wiki) — 3 名用户免费，50 MB 存储，无限页面，ZIP 备份，RSS 与 Atom 订阅，访问控制与可定制 CSS。
    * [Subscriptions](https://zoho.com/subscriptions) — 订阅/周期计费管理，20 位客户/订阅、1 名用户免费，支付托管由 Zoho 完成，保留最近 40 条订阅指标。
    * [Checkout](https://zoho.com/checkout) — 产品计费管理，3 个页面，最多 50 笔付款。
    * [Desk](https://zoho.com/desk) — 客户支持管理，包含 3 名坐席、私有知识库与邮件工单。与 [Assist](https://zoho.com/assist) 集成，含 1 名远程技术人员与 5 台无人值守电脑。
    * [Cliq](https://zoho.com/cliq) — 团队聊天软件，100 GB 存储、无限用户、每频道 100 用户与 SSO。
    * [Campaigns](https://zoho.com/campaigns) - 邮件营销
    * [Forms](https://zoho.com/forms) - 表单创建
    * [Sign](https://zoho.com/sign) - 无纸化签名
    * [Surveys](https://zoho.com/surveys) - 在线调查
     * [Bookings](https://zoho.com/bookings) - 预约排程

**[⬆️ 返回目录](#table-of-contents)**

<a id="cloud-management-solutions"></a>

## 云管理解决方案

  * [Brainboard](https://www.brainboard.co) - 协作式解决方案，可视化构建并端到端管理云基础设施。
  * [Cloud 66](https://www.cloud66.com/) - 个人项目免费（含 1 台部署服务器、1 个静态站点）。Cloud 66 让你在任意云上构建、部署并扩展应用，无需操心“服务器杂事”。
  * [deployment.io](https://deployment.io) - Deployment.io 帮助开发者自动化 AWS 部署。免费层中，开发者（单用户）可部署不限数量的静态站点、Web 服务与环境。免费层每月提供 10 次作业执行，并包含预览与自动部署。
  * [Pulumi](https://www.pulumi.com/) — 现代基础设施即代码平台，允许使用熟悉的编程语言和工具来构建、部署和管理云基础设施。
  * [scalr.com](https://scalr.com/) - Scalr 是 Terraform 自动化与协作（TACO）产品，用于提升 Terraform 管理的基础设施与配置的协作和自动化。支持完整 Terraform CLI、OPA 集成与分层配置模型。无 SSO 额外费用，所有功能均包含在内。每月可免费运行至多 50 次。

**[⬆️ 返回目录](#table-of-contents)**

<a id="source-code-repos"></a>

## 源代码仓库

  * [Bitbucket](https://bitbucket.org/) — 最多 5 名用户的无限公共/私有 Git 仓库，含 Pipelines 用于 CI/CD
  * [Codeberg](https://codeberg.org/) — 面向自由与开源项目的无限公共与私有 Git 仓库（协作者不限）。基于 [Forgejo](https://forgejo.org/)。提供 [Codeberg Pages](https://codeberg.page/) 静态网站托管、[Codeberg's CI](https://docs.codeberg.org/ci/) 的 CI/CD 托管、[Codeberg Translate](https://translate.codeberg.org/) 的翻译托管。包含包与容器托管、项目管理与问题跟踪
  * [framagit.org](https://framagit.org/) — Framasoft 的软件协作平台，基于 GitLab，包含 CI、静态页面、项目页面与问题跟踪。
  * [GitGud](https://gitgud.io) — 无限私有与公开仓库，永久免费。基于 GitLab 与 Sapphire。未提供 CI/CD。
  * [GitHub](https://github.com/) — 无限公共仓库与无限私有仓库（协作者不限）。包含 CI/CD、开发环境、静态托管、包与容器托管、项目管理与 AI Copilot
  * [gitlab.com](https://about.gitlab.com/) — 无限公共与私有 Git 仓库（最多 5 名协作者）。包含 CI/CD、静态托管、容器注册表、项目管理与问题跟踪
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab Community Edition 的友好分支，支持 Mercurial
  * [Pagure.io](https://pagure.io) — 面向 FOSS 许可项目的免费开源协作平台，基于 Git
  * [pijul.com](https://pijul.com/) - 无限免费的开源分布式版本控制系统。其独特之处是基于补丁理论，易于学习、使用和分发，可解决 git/hg/svn/darcs 的许多问题。
  * [projectlocker.com](https://projectlocker.com) — 提供 1 个免费的私有项目（Git 与 Subversion），50 MB 空间
  * [RocketGit](https://rocketgit.com) — 基于 Git 的仓库托管。公共与私有仓库不限量。
  * [savannah.gnu.org](https://savannah.gnu.org/) - GNU 项目的免费协作式软件开发管理系统
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 非 GNU 项目的免费协作式软件开发管理系统

**[⬆️ 返回目录](#table-of-contents)**

<a id="apis-data-and-ml"></a>

## API、数据与机器学习

  * [Abstract API](https://www.abstractapi.com) — 适用于多种场景的 API 套件，包括 IP 地理定位、性别检测或邮箱验证等。
  * [Apify](https://www.apify.com/) — Web 抓取与自动化平台，可为任意网站创建 API 并提取数据。提供现成爬虫、集成代理和定制方案。免费计划每月含 5 美元平台额度。
  * [APITemplate.io](https://apitemplate.io) - 通过简单 API 或 Zapier、Airtable 等自动化工具自动生成图片与 PDF。无需 CSS/HTML。免费计划每月 50 张图片与 3 个模板。
  * [APIVerve](https://apiverve.com) - 免费即时访问 120+ API，强调质量、一致性与可靠性。免费计划每月最多 50 个 API Token。（可能已下线，2025-06-25）
  * [Arize AI](https://arize.com/) - 机器学习可观测性，用于模型监控并定位数据质量、性能漂移等问题。最多免费支持 2 个模型。
  * [Beeceptor](https://beeceptor.com) - 无代码云平台，用于模拟与调试多协议 API（REST、SOAP、gRPC 与 GraphQL），提供基于规则的逻辑、CRUD 与有状态模拟、代理与 CORS 管理，加速集成与测试。免费计划每天 50 次请求，并提供公开仪表盘/端点，拥有仪表盘 URL 的任何人都可查看提交的请求与响应。
  * [BigDataCloud](https://www.bigdatacloud.com/) - 提供快速、准确、免费的 API（不限量或每月 10K-50K），涵盖 IP 定位、逆地理编码、网络洞察、邮箱与电话验证、客户端信息等。
  * [Browse AI](https://www.browse.ai) — 用于网页数据提取与监控。免费每月 1k 积分，相当于 1k 并发请求。
  * [BrowserCat](https://www.browsercat.com) - 无头浏览器 API，用于自动化、抓取、AI 代理访问、图片/PDF 生成等。免费计划每月 1k 次请求。
  * [Calendarific](https://calendarific.com) - 企业级公共假期 API，覆盖 200+ 国家。免费计划每月 500 次调用。
  * [Canopy](https://www.canopyapi.co/) - 面向 Amazon.com 商品、搜索与分类数据的 GraphQL API。免费计划每月 100 次调用。
  * [CarAPI.dev](https://carapi.dev) — 综合汽车数据 API，包含 VIN 解码、被盗车辆检查、估值、检验数据等。免费层覆盖 9 个端点合计每月 100 次请求。
  * [Cloudmersive](https://cloudmersive.com/) — 通用工具 API 平台，提供文档转换、病毒扫描等庞大 API 库。每月 600 次调用，仅北美可用，文件最大 2.5MB。
  * [Colaboratory](https://colab.research.google.com) — 免费的 Web 版 Python Notebook 环境，提供 Nvidia Tesla K80 GPU。
  * [CometML](https://www.comet.com/site/) - MLOps 平台用于实验追踪、模型生产管理、模型注册与完整数据谱系，覆盖从训练到生产的流程。个人与学术用户免费。
  * [Commerce Layer](https://commercelayer.io) - 可组合电商 API，可从任意前端构建、下单与管理订单。开发者计划每月免费 100 笔订单，最多 1,000 个 SKU。
  * [Composio](https://composio.dev/) - AI 代理与 LLM 的集成平台，可接入 200+ 工具。
  * [Conversion Tools](https://conversiontools.io/) - 在线文件转换器（文档、图片、视频、音频、电子书）。提供 REST API 与 Node.js、PHP、Python 库。付费计划支持最大 50 GB 文件。免费层限制文件大小 20MB，转换次数 30/天、300/月。
  * [Country-State-City Microservice API](https://country-state-city.rebuscando.info/) - 提供国家、地区、省份、城市、邮编等信息的 API/微服务。免费层每天最多 100 次请求。
  * [Coupler](https://www.coupler.io/) - 应用间数据同步工具，可创建仪表盘与报表、转换处理数据并备份洞察。免费计划限制为 1 名用户、1 个数据连接、1 个数据源和 1 个数据目的地，并需手动刷新。
  * [CraftMyPDF](https://craftmypdf.com) - 基于可复用模板自动生成 PDF，提供拖拽编辑器与简单 API。免费计划每月 100 份 PDF，3 个模板。
  * [Cube](https://cube.dev/) - 帮助数据工程师与应用开发者访问现代数据存储、统一定义并分发到应用。使用 Cube Cloud 的免费层每天最多 1,000 次查询。
  * [CurlHub](https://curlhub.io) — 用于检查与调试 API 调用的代理服务。免费计划每月 10,000 次请求。
  * [CurrencyScoop](https://currencyscoop.com) - 面向金融科技应用的实时汇率数据 API。免费计划每月 5,000 次调用。
  * [CustomJS](https://www.customjs.io) - 提供 HTML 转 PDF、PDF 转 PNG/文本、PDF 合并/提取等 API。免费层每月 600 次调用。
  * [Data Fetcher](https://datafetcher.com) - 无代码将 Airtable 连接到任意应用或 API。提供类似 Postman 的 Airtable 请求界面，内置几十种集成。免费计划每月 100 次运行。
  * [Data Miner](https://dataminer.io/) - 浏览器扩展（Chrome、Edge）用于从网页提取数据到 CSV 或 Excel。免费计划每月 500 页。
  * [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清洗并导入数据到 Salesforce 的工具。免费计划每月最多 20,000 条记录。
  * [Datalore](https://datalore.jetbrains.com) - JetBrains 的 Python Notebook。每月含 10 GB 存储与 120 小时运行时长。
  * [DB Designer](https://www.dbdesigner.net/) — 云端数据库架构设计与建模工具，免费入门计划含 2 个数据库模型，每个模型 10 张表。
  * [DB-IP](https://db-ip.com/api/free) - 免费 IP 地理定位 API，每个 IP 每天 1k 次请求。CC-BY 4.0 许可的 Lite 数据库也可免费使用。
  * [DeepAR](https://developer.deepar.ai) — 适用于任何平台的增强现实人脸滤镜，仅需一个 SDK。免费计划最多 10 月活用户（MAU），最多追踪 4 张人脸。
  * [Deepnote](https://deepnote.com) - 新的数据科学笔记本。兼容 Jupyter，支持实时协作并在云端运行。免费层包含无限个人项目、无限基础机型（5GB RAM、2 vCPU）以及最多 3 名编辑者的团队。
  * [DiffJSON](https://diffjson.com) - 在线工具，用于比较两份 JSON 数据结构的差异，帮助快速定位 JSON 差别。
  * [Disease.sh](https://disease.sh/) — 免费 API，提供构建 COVID-19 相关应用所需的准确数据。
  * [Doczilla](https://www.doczilla.app/) — SaaS API，可直接从 HTML/CSS/JS 生成截图或 PDF。免费计划每月 250 份文档。
  * [Doppio](https://doppio.sh/) — 托管 API，使用先进渲染技术生成并私密存储 PDF 与截图。免费计划每月 400 份 PDF 与截图。
  * [drawDB](https://drawdb.app/) — 免费开源的在线数据库图表编辑器，无需注册。
  * [DynamicDocs](https://advicement.io) - 基于 LaTeX 模板的 JSON 转 PDF API，用于生成 PDF 文档。免费计划每月 50 次 API 调用，并可访问模板库。
  * [Earnings Feed](https://earningsfeed.com/api) - 实时 SEC 申报、内幕交易与机构持仓 API。免费层每分钟 15 次请求。
  * [Export SDK](https://exportsdk.com) - 带拖拽模板编辑器的 PDF 生成 API，提供 SDK 与无代码集成。免费计划每月 250 页、无限用户、3 个模板。
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的 Web 端 HTTP 客户端，用于发送 HTTP 请求。
  * [Financial Data](https://financialdata.net/) - 股票市场与金融数据 API。免费计划每天 300 次请求。
  * [FormatJSONOnline.com](https://formatjsononline.com) - 免费的浏览器工具，可即时格式化、校验、比较与压缩 JSON 数据。
  * [FraudLabs Pro](https://www.fraudlabspro.com) — 订单信用卡支付欺诈检测服务。该 REST API 根据订单输入参数识别可能的欺诈特征。Free Micro 计划每月 500 笔交易。
  * [FreeIPAPI](https://freeipapi.com) - 免费、快速且可靠的 IP 地理定位 API，面向商用与非商用用户，提供 JSON 输出。
  * [Geolocated.io](https://geolocated.io) — 多地区服务器的 IP 定位 API，免费计划每天 2,000 次请求。
  * [Hex](https://hex.tech/) - 面向 Notebook、数据应用与知识库的协作式数据平台。免费社区层最多 5 个项目。
  * [Hook0](https://www.hook0.com/) - Hook0 是开源的 Webhooks-as-a-service（WaaS），让线上产品更容易提供 Webhook。免费每天最多派发 100 个事件，并保留 7 天历史记录。
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速且易用的 API 请求构建器。
  * [huggingface.co](https://huggingface.co) - 为 PyTorch、TensorFlow 与 JAX 构建、训练和部署 NLP 模型。免费额度为每月最多 30k 输入字符。
  * [Insomnia](https://insomnia.rest) - 开源 API 客户端，用于设计与测试 API，支持 REST 与 GraphQL。
  * [Invantive Cloud](https://cloud.invantive.com/) — 通过 Invantive SQL 或 OData4 访问 70+（云）平台（如 Exact Online、Twinfield、ActiveCampaign、Visma），包含数据复制与交换。面向开发者和实施顾问提供免费计划，部分平台免费但数据量有限制。
  * [IP Geolocation API by ipwho.org](https://ipwho.org/) - 每天 2,000 次免费请求。快速、企业级但价格非企业级的 API，受开发者、企业、政府与教育客户信赖。覆盖 12+ 区域服务器。
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) — Abstract 的 IP 地理定位 API，可免费请求 1,000 次。
  * [IP Geolocation](https://ipgeolocation.io/) — IP 地理定位 API，开发者永久免费计划每日上限 1,000 次请求。
  * [ip-api](https://ip-api.com) — IP 地理定位 API，非商业用途免费，无需 API Key，免费计划同一 IP 限制 45 次/分钟。
  * [IP.City](https://ip.city) — 每天 100 次免费的 IP 地理定位请求。
  * [IP2Location.io](https://www.ip2location.io/) — Freemium、快速且可靠的 IP 地理定位 API，可获取城市、坐标、ISP、ASN、AS 数据等。免费计划每月 50k 积分。IP2Location.io 还提供每月 500 次免费的 WHOIS 与托管域名查询，可查看域名注册详情并查找托管在特定 IP 上的域名。升级付费计划可获得更多功能。
  * [ipaddress.sh](https://ipaddress.sh) — 用不同 [格式](https://about.ipaddress.sh/) 获取公网 IP 的简单服务。
  * [ipapi.is](https://ipapi.is/) - 开发者打造的可靠 IP 地址 API，具备出色的托管检测能力。免费计划无需注册提供 1,000 次查询。
  * [ipapi](https://ipapi.co/) - Kloudend, Inc 的 IP 地址定位 API，基于 AWS，受 Fortune 500 信赖。免费层无需注册，每月 30k 查询（1k/天）。
  * [ipbase.com](https://ipbase.com) - IP 地理定位 API，永久免费计划每月 150 次请求。
  * [IPinfo](https://ipinfo.io/) — 快速、准确且免费（最多 50k/月）的 IP 地址数据 API。提供地理位置、公司、运营商、IP 段、域名、滥用联系等详细信息的 API。所有付费 API 均可免费试用。
  * [IPLocate](https://www.iplocate.io) — IP 地理定位 API，免费每天最多 1,000 次请求，包含代理/VPN/托管检测、ASN 数据、IP 到公司等功能。IPLocate 还提供可免费下载的 IP 到国家与 IP 到 ASN 数据库，支持 CSV 或 GeoIP 兼容的 MMDB 格式。
  * [IPTrace](https://iptrace.io) — 极简 API，为业务提供可靠且实用的 IP 地理定位数据，每月 50,000 次免费查询。
  * [JSON IP](https://getjsonip.com) — 返回请求客户端的公网 IP 地址。免费层无需注册。支持 CORS，可在浏览器端用 JS 直接请求数据。适用于监测客户端与服务器 IP 变化。请求不限量。
  * [JSON to Table](https://jsontotable.org) - 将 JSON 转为交互式表格，便于快速查看、编辑与在线分享。
  * [JSON2Video](https://json2video.com) - 视频编辑 API，用于自动化营销与社交媒体视频，可编程或无代码使用。
  * [JSONGrid](https://jsongrid.com) - 免费工具，将复杂 JSON 可视化、编辑、过滤为精美表格。通过链接保存并分享 JSON 数据。
  * [JSONing](https://jsoning.com/api/) — 从 JSON 对象创建虚拟 REST API，并自定义 HTTP 状态码、请求头与响应体。
  * [JSONSwiss](https://www.jsonswiss.com/) - 强大的在线 JSON 查看器、编辑器与校验工具。支持格式化、可视化、搜索、AI 修复、树形/表格视图、12+ 编程语言代码生成，以及转换为 CSV、XML、YAML、Properties 等。
  * [KillBait API](https://killbait.com/api/doc) - 允许提交 URL 进行内容评估，检测潜在标题党并分类文章。适合中等发布频率，限制每小时 1 次、每天 10 次提交；媒体合作伙伴可申请更高限制。
  * [Kreya](https://kreya.app) — 免费 gRPC GUI 客户端，用于调用与测试 gRPC API。可通过服务端反射导入 gRPC API。
  * [LoginLlama](https://loginllama.app) - 登录安全 API，用于检测欺诈或可疑登录并通知客户。每月免费 1,000 次登录。
  * [Market Data API](https://www.marketdata.app) - 提供股票、期权、共同基金等实时与历史金融数据。永久免费层每天可免费请求 100 次。
  * [Maxim AI](https://getmaxim.ai/) - 模拟、评估并观测你的 AI 代理。Maxim 是端到端评估与可观测平台，帮助团队更可靠地交付 AI 代理，速度提升 5 倍以上。独立开发者与小团队（3 个席位）永久免费。
  * [microlink.io](https://microlink.io/) – 将任意网站转换为数据，例如元标签标准化、精美链接预览、抓取能力或截图服务。每天 50 次请求，永久免费。
  * [Mintlify](https://mintlify.com) — 现代 API 文档标准，提供美观易维护的 UI 组件、应用内搜索与交互式 Playground。免费支持 1 名编辑者。
  * [MockAPI](https://www.mockapi.io/) — MockAPI 是简单工具，可快速模拟 API、生成自定义数据，并通过 RESTful 接口执行操作。用于原型/测试/学习。免费提供 1 个项目，每项目 2 个资源。
  * [Mockerito](https://mockerito.com/) — 免费 mock REST API 服务，提供覆盖 9 个领域（电商、金融、医疗、教育、招聘、社交媒体、股市、天气、航空）的逼真数据。无需注册、无需 API Key、请求不限。适合前端原型、API 测试、学习与教学。
  * [Mockfly](https://www.mockfly.dev/) — 值得信赖的 API 模拟与功能开关管理工具，可用直观界面快速生成与控制 mock API。免费层每天 500 次请求。
  * [Mocko.dev](https://mocko.dev/) — 代理你的 API，在云端选择要模拟的端点并检查流量，免费使用。加速开发与集成测试。
  * [Multi-Exit IP Address Checker](https://ip.alstra.ca/) — 免费且简单的工具，可跨多个节点检查出口 IP 地址，并了解你的 IP 在不同地区与服务中的呈现方式。适合测试诸如 Control D 的规则型 DNS 分流工具。
  * [News API](https://newsapi.org) — 通过代码在网上搜索新闻并获取 JSON 结果。开发者每天免费 100 次查询，文章有 24 小时延迟。
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API，每月 100 次免费请求。
  * [OCR.Space](https://ocr.space/) — OCR API 解析图片与 PDF，并以 JSON 返回文本结果。每月 25,000 次请求免费，文件大小上限 1MB。
  * [OpenAPI3 Designer](https://openapidesigner.com/) — 可视化创建 OpenAPI 3 定义，免费使用。
  * [Parseur](https://parseur.com) — 每月 20 页免费：从 PDF、邮件中提取数据，AI 驱动，提供完整 API 访问。
  * [PDF-API.io](https://pdf-api.io) - PDF 自动化 API，提供可视化模板编辑器或 HTML 转 PDF、动态数据集成与 PDF 渲染。免费计划包含 1 个模板、每月 100 份 PDF。
  * [PDFBolt](https://pdfbolt.com) - 面向开发者的 PDF 生成 API，强调隐私保护，提供 Stripe 风格文档，每月包含 500 次免费 PDF 转换。
  * [pdfEndpoint.com](https://pdfendpoint.com) - 使用简单 API 轻松将 HTML 或 URL 转为 PDF。每月免费 100 次转换。
  * [Pixela](https://pixe.la/) - 免费的日记流数据库服务，所有操作通过 API 完成，并支持热力图与折线图可视化。
  * [Postman](https://postman.com) — Postman 是 API 开发的协作平台，可简化流程并更快构建更好的 API。Postman 应用永久免费；Postman 云功能在一定限制内永久免费。
  * [PrefectCloud](https://www.prefect.io/cloud/) — 数据流自动化平台。免费计划包含 5 个已部署工作流与每月 500 分钟无服务器计算额度。
  * [Preset Cloud](https://preset.io/) - 托管的 Apache Superset 服务，最多 5 名用户团队永久免费，包含无限仪表盘与图表、无代码图表构建器与协作 SQL 编辑器。
  * [ProxySentry](https://proxysentry.io/) - 用于检测住宅代理与 VPN 的 IP API。ProxySentry.io 在 rapidapi.com 提供每月 10k 请求的免费层。
  * [Reducto](https://reducto.ai) - 将非结构化文档（PDF、XLSX、JPG、PPTX 等）转换为结构化 JSON 数据。支持解析、提取数据与编辑 PDF 表单。免费层含 15k 免费额度并支持按量付费。
  * [Rendi](https://rendi.dev) - FFmpeg API：FFmpeg 的 REST API，可在线运行 FFmpeg 而无需维护基础设施。免费层包含每月处理额度并提供 4 vCPU。
  * [RequestBin.com](https://requestbin.com) — 创建一个免费端点来接收 HTTP 请求。发送到该端点的请求会记录其负载与请求头，便于观察来自 Webhook 和其他服务的请求。
  * [ROBOHASH](https://robohash.org/) - 通过任意文本生成独特酷炫图片的 Web 服务。
  * [Scraper's Proxy](https://scrapersproxy.com) — 用于抓取的简单 HTTP 代理 API。匿名抓取，避免限制、封禁或验证码。每月前 100 次成功抓取免费（含 JavaScript 渲染），更多可联系支持。
  * [ScrapingAnt](https://scrapingant.com/) — 无头 Chrome 抓取 API 与免费可用代理服务，支持 JavaScript 渲染、高级轮换代理与 CAPTCHA 规避。免费 10,000 API 积分。
  * [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取 API，返回 Google、YouTube、Bing、Baidu、Walmart 等多个引擎的结构化 JSON 结果。免费计划每月 100 次成功 API 调用。
  * [Sheetson](https://sheetson.com) - 即时将任意 Google Sheets 转为 RESTful API。提供免费计划，每张表含 1,000 行免费额度。
  * [Simplescraper](https://simplescraper.io) — 每次操作后触发 Webhook。免费计划包含 100 个云抓取额度。
  * [Siterelic](https://siterelic.com/) - Siterelic API 支持截图、网站审计、TLS 扫描、DNS 查询、TTFB 测试等。免费计划每月 100 次 API 请求。
  * [SmartParse](https://smartparse.io) - SmartParse 是数据迁移与 CSV 转 API 平台，提供节省时间和成本的开发工具。免费层包含每月 300 Processing Units、浏览器上传、数据隔离、熔断器与任务提醒。
  * [Sofodata](https://www.sofodata.com/) - 从 CSV 文件创建安全的 RESTful API。上传 CSV 即可通过 API 访问数据，加速应用开发。免费计划包含 2 个 API、每月 2,500 次 API 调用，无需信用卡。
  * [Sqlable](https://sqlable.com/) - 免费在线 SQL 工具集合，包含 SQL 格式化与校验、SQL 正则测试、伪数据生成器与交互式数据库演练场。
  * [Supportivekoala](https://supportivekoala.com/) — 通过模板根据输入自动生成图片。免费计划每月最多 50 张。
  * [Svix](https://www.svix.com/) - Webhook 即服务。每月可免费发送最多 50,000 条消息。
  * [Tavily AI](https://tavily.com/) - 面向在线搜索与快速洞察/综合研究的 API，可组织研究结果。免费层每月 1,000 次请求，无需信用卡。
  * [The IP API](https://theipapi.com/) - IP 地理定位 API，每天 1,000 次免费请求，提供国家、城市、地区等位置信息。
  * [TinyMCE](https://www.tiny.cloud) - 富文本编辑 API，核心功能永久免费不限用量。
  * [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) - 提供免费的天气 API 计划，覆盖全球，包含历史数据与天气监测方案，预测准确且及时。
  * [Treblle](https://www.treblle.com) - Treblle 帮助团队构建、发布与治理 API，提供高级 API 日志聚合、可观测性、文档与调试。免费层功能全开，但每月请求上限为 250k。
  * [UniRateAPI](https://unirateapi.com) – 覆盖 590+ 货币与加密货币的实时汇率。免费计划 API 调用不限量，适合开发者与金融应用。
  * [vatcheckapi.com](https://vatcheckapi.com) - 简单免费的 VAT 号码验证 API，每月 150 次免费验证。
  * [WeatherXu](https://weatherxu.com/) — 提供全球天气数据，包括当前情况、小时/每日预报与天气预警。通过 AI/ML 模型整合与分析多种天气模型以提升预测准确性。免费层每月 10,000 次 API 调用。
  * [WebScraping.AI](https://webscraping.ai) - 简单的网页抓取 API，内置解析、Chrome 渲染与代理。每月 2,000 次免费 API 调用。
  * [Weights & Biases](https://wandb.ai) — 开发者优先的 MLOps 平台，支持实验跟踪、数据集版本与模型管理，帮助更快训练更好模型。免费层仅限个人项目，含 100 GB 存储。
  * [What The Diff](https://whatthediff.ai) - AI 驱动的代码评审助手。免费计划每月 25,000 tokens（约 10 个 PR）。
  * [wolfram.com](https://wolfram.com/language/) — 云端内置知识算法。
  * [wrapapi.com](https://wrapapi.com/) — 将任意网站转换为参数化 API。每月 30k 次 API 调用。
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — 使用无头浏览器与住宅 IP 的网页抓取 API，定价清晰。每月 1,000 次免费 API 调用，学生与非营利组织可获得额外额度。
  * [Zipcodebase](https://zipcodebase.com) - 免费邮编 API，可访问全球邮编数据。每月 5,000 次免费请求。
  * [Zipcodestack](https://zipcodestack.com) - 免费邮编 API 与邮编校验。每月 10,000 次免费请求。
  * [Zuplo](https://zuplo.com/) - 免费 API 管理平台，可在边缘设计、构建与部署 API。支持 API Key 认证、限流、开发者文档与变现。OpenAPI 原生、可用 Web 标准 API 与 TypeScript 完全编程。免费计划最多 10 个项目、无限生产边缘环境、每月 1M 请求与 10GB 出站流量。

**[⬆️ 返回目录](#table-of-contents)**

<a id="artifact-repos"></a>

## 制品仓库

  * [Gemfury](https://gemfury.com) — 面向 Maven、PyPI、NPM、Go Module、NuGet、APT 与 RPM 的私有/公开制品仓库。公开项目免费。
  * [jitpack.io](https://jitpack.io/) — 面向 GitHub 上 JVM 与 Android 项目的 Maven 仓库，公开项目免费。
  * [paperspace](https://www.paperspace.com/) — 构建与扩展 AI 模型、开发/训练/部署 AI 应用。免费计划：公开项目、5GB 存储、基础实例。
  * [RepoFlow](https://repoflow.io) - RepoFlow 简化包管理，支持 npm、PyPI、Docker、Go、Helm 等。可免费试用 10GB 存储、10GB 带宽、100 个包与无限用户（云端），或仅限个人使用的自托管。
  * [RepoForge](https://repoforge.io) - 私有云托管仓库，支持 Python、Debian、NPM 包与 Docker Registry。开源/公开项目免费。
  * [repsy.io](https://repsy.io) — 免费 1 GB 私有/公开 Maven 仓库。

**[⬆️ 返回目录](#table-of-contents)**

<a id="tools-for-teams-and-collaboration"></a>

## 团队协作工具

  * [3Cols](https://3cols.com/) - 免费的云端代码片段管理器，用于个人与协作代码。
  * [BookmarkOS.com](https://bookmarkos.com) - 免费的全能书签管理器、标签管理器与任务管理器，提供可自定义的在线桌面与文件夹协作。
  * [Braid](https://www.braidchat.com/) — 面向团队的聊天应用。公开访问群免费、用户不限、含历史记录与集成，并提供可自托管的开源版本。
  * [Calendly](https://calendly.com) — 用于连接并安排会议的工具。免费计划每用户 1 个日历连接，会议次数不限，并提供桌面与移动应用。
  * [cally.com](https://cally.com/) — 查找会议最佳时间与日期的工具，简单易用，适合小型与大型群体。
  * [Chanty.com](https://chanty.com/) — Slack 的替代方案之一。小团队永久免费（最多 10 人），含无限公开/私密会话、可搜索历史、无限 1:1 语音通话、无限语音消息、10 个集成与每团队 20 GB 存储。
  * [DevToolLab](https://devtoollab.com) — 在线开发者工具，免费访问所有基础工具，并支持为每个工具自动保存 1 条记录，提供标准处理速度与社区支持。
  * [Discord](https://discord.com/) — 公共/私密房间聊天，支持 Markdown 文本、语音、视频与屏幕共享。用户不限，免费使用。
  * [Dubble](https://dubble.so/) — 免费的分步指南生成器，支持截图、记录流程并与团队协作，也支持异步屏幕录制。
  * [Duckly](https://duckly.com/) — 实时沟通协作，支持 IDE 配对编程、终端共享、语音/视频/屏幕共享。小团队免费。
  * [element.io](https://element.io/) — 基于 Matrix 的去中心化开源通信工具，支持群聊、私聊、加密文件传输、语音/视频聊天与服务集成。
  * [evernote.com](https://evernote.com/) — 信息整理工具，可分享笔记并与他人协作。
  * [Fibery](https://fibery.io/) — 互联工作区平台，单人免费，最多 2 GB 磁盘空间。
  * [Fibo](https://fibo.dev) - 面向敏捷团队的在线实时估点（Scrum Poker）工具，成员不限，便于快速规划。
  * [Fizzy](https://www.fizzy.do/) - 基于看板的项目管理与问题跟踪平台。可创建公开看板、设置 Webhook、使用卡片标记并跟踪不限用户，免费最多 1000 项。
  * [flat.social](https://flat.social) - 互动可定制空间，用于团队会议与社交。会议不限，最多 8 个并发用户免费。
  * [flock.com](https://flock.com) — 更快的团队沟通方式：免费无限消息、频道、用户、应用与集成。
  * [GitBook](https://www.gitbook.com/) — 技术知识记录与文档平台，从产品文档到内部知识库与 API 文档。个人开发者免费。
  * [GitDailies](https://gitdailies.com) - 团队 GitHub 提交与 PR 活动日报，包含 Push 可视化、同行认可系统与自定义告警生成器。免费层用户不限、3 个仓库、3 个告警配置。
  * [gitter.im](https://gitter.im/) — 面向 GitHub 的聊天工具。公共/私密房间不限，团队最多 25 人免费。
  * [gokanban.io](https://gokanban.io) - 语法驱动、无需注册的看板，快速上手，免费且不限量。
  * [Hackmd.io](https://hackmd.io/) - Markdown 文档的实时协作写作工具，类似 Google Docs。免费“笔记”数量不限，但私有笔记与模板的协作者人数将受限（见 [pricing](https://hackmd.io/pricing)）。
  * [HeySpace](https://hey.space) - 含聊天、日历、时间线与视频通话的任务管理工具，最多 5 名用户免费。
  * [Huly](https://huly.io/) - 一体化项目管理平台（Linear、Jira、Slack、Notion、Motion 的替代），用户不限，每工作区 10GB 存储与 10GB 视频/音频流量。
  * [Keybase](https://keybase.io/) — Slack 的 FOSS 替代品，保障聊天与文件安全，适用于家庭、社区与公司。
  * [Linkinize](https://linkinize.com) — 团队书签管理器，支持标签、多工作区与协作。免费计划含 4 个工作区与 10 名团队成员。
  * [Lockitbot](https://www.lockitbot.com/) — 在 Slack 中预订并锁定共享资源（会议室、开发环境、服务器等）。最多 2 个资源免费。
  * [meet.jit.si](https://meet.jit.si/) — 一键视频通话与屏幕共享，免费使用。
  * [Miro](https://miro.com/) - 面向分布式团队的可扩展、安全、跨设备协作白板，提供免费计划。
  * [Notion](https://www.notion.so/) - Notion 是支持 Markdown 的笔记与协作应用，整合任务、Wiki 与数据库。官方将其描述为集笔记、项目管理与任务管理于一体的工作区。除跨平台应用外，也可通过多数浏览器访问。
  * [Nuclino](https://www.nuclino.com) - 轻量协作式 Wiki，用于团队知识、文档与笔记。免费计划包含全部核心功能，最多 50 项，5GB 存储。
  * [OnlineInterview.io](https://onlineinterview.io/) - 免费代码面试平台，内置视频聊天、画板与在线代码编辑器，可在浏览器内编译运行代码。一键创建远程面试房间。
  * [paste.sh](https://paste.sh/) — 基于 JavaScript 与加密的简易粘贴站点。
  * [Pastefy](https://pastefy.app/) - 美观简洁的 Pastebin，支持可选客户端加密、多标签粘贴、API 与高亮编辑器等。
  * [Pendulums](https://pendulums.io/) - 免费时间跟踪工具，界面易用，提供有价值的统计数据。
  * [Proton Pass](https://proton.me/pass) — 密码管理器，内置邮箱别名、2FA 验证器、共享与 passkeys。支持 Web、浏览器扩展、移动与桌面应用。
  * [Pullflow](https://pullflow.com) — AI 增强的代码评审协作平台，覆盖 GitHub、Slack 与 VS Code。
  * [Pumble](https://pumble.com) - 免费团队聊天应用，用户与消息历史不限，永久免费。
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - 简单的团队工时表与时间跟踪应用。免费计划提供时间跟踪与报表功能，最多 10 名用户。
  * [Raindrop.io](https://raindrop.io) - 私密安全的书签应用，支持 macOS、Windows、Android、iOS 与 Web。免费无限书签与协作。
  * [Revolt.chat](https://revolt.chat/) — 开源的 [Discord](https://discord.com/) 替代品，尊重隐私，并免费提供大多数 Discord 专有功能。Revolt 是安全且高速的一体化应用，所有功能均免费，同时支持官方与非官方插件（区别于多数主流聊天应用）。
  * [Rocket.Chat](https://rocket.chat/) - 开源通信平台，具备全渠道功能、Matrix 联邦、与其他应用的桥接、无限消息与完整历史记录。
  * [ruttl.com](https://ruttl.com/) — 一体化反馈工具，用于收集数字反馈并评审网站、PDF 与图片。
  * [Screen Sharing via Browser](https://screensharing.net) - 浏览器端屏幕共享工具，无需下载或注册，免费使用。
  * [seafile.com](https://www.seafile.com/) — 私有或云存储、文件共享、同步与讨论。云端版本仅 1 GB。
  * [SiteDots](https://sitedots.com/) - 在网站上直接收集反馈，无需仿真、画布或绕路。免费层功能完整。
  * [Slab](https://slab.com/) — 现代团队知识管理服务，最多 10 名用户免费。
  * [slack.com](https://slack.com/) — 免费计划用户不限，但部分功能受限。
  * [StatusPile](https://www.statuspile.com/) - 状态页的状态页，可跟踪上游服务的状态页。
  * [Stickies](https://stickies.app/) - 用于头脑风暴、内容整理与笔记的可视化协作应用。免费最多 3 面板、用户不限，1 GB 存储。
  * [StreamBackdrops](https://streambackdrops.com) — 视频通话与团队会议的免费高清虚拟背景。提供适用于 Zoom、Teams 与 Google Meet 的专业背景。无需注册，个人免费使用。
  * [talky.io](https://talky.io/) — 免费群组视频聊天，匿名、点对点，无需插件、注册或付费。
  * [Teamcamp](https://www.teamcamp.app) - 面向软件开发公司的全能项目管理应用。
  * [Teamhood](https://teamhood.com/) - 免费项目、任务与问题跟踪软件，支持带泳道看板与完整 Scrum，内置时间跟踪。免费支持 5 名用户与 3 个项目组合。
  * [Teamplify](https://teamplify.com) - 通过 Team Analytics 与 Smart Daily Standup 改进团队开发流程，包含面向远程团队的请假管理。小团队免费，最多 5 名用户。
  * [Telegram](https://telegram.org/) — Telegram 面向需要快速可靠消息与通话的用户。商业用户与小团队可受益于大群、用户名、桌面应用与强大的文件分享选项。
  * [Tencent RTC](https://trtc.io/) — Tencent Real-Time Communication（TRTC）提供群组音视频通话方案。第一年每月 10,000 分钟免费。
  * [TimeCamp](https://www.timecamp.com/) - 免费时间跟踪软件，用户不限。可轻松集成 Jira、Trello、Asana 等项目管理工具。
  * [tldraw.com](https://tldraw.com) — 免费开源白板与图示工具，具备智能箭头、吸附、便签与 SVG 导出功能，支持多人协作编辑，并提供官方 VS Code 扩展。
  * [transfernow](https://www.transfernow.net/) — 最简单、最快且安全的文件传输与分享界面。无需强制订阅即可发送照片、视频等大文件。
  * [Tugboat](https://tugboat.qa) - 为每个 Pull Request 生成预览，自动且按需。对所有人免费，非营利组织可获赠 Nano 档位。
  * [twist.com](https://twist.com) — 异步友好的团队沟通应用，让对话保持组织与主题。提供免费与不限计划，符合条件的团队可享折扣。
  * [userforge.com](https://userforge.com/) - 在线 Persona、用户故事与上下文映射工具，帮助设计与开发保持同步。免费最多 3 个 Persona 与 2 名协作者。
  * [Visual Debug](https://visualdebug.com) - 用于提升客户与开发沟通的可视化反馈工具。
  * [Webex](https://www.webex.com/) — 视频会议，免费计划每场 40 分钟、最多 100 与会者。
  * [Webvizio](https://webvizio.com) — 网站反馈、评审与缺陷报告工具，可在实时网站/应用、图片、PDF 与设计文件上协作，简化 Web 开发协作。
  * [whereby.com](https://whereby.com/) — 一键视频通话，免费使用（原 appear.in）。
  * [windmill.dev](https://windmill.dev/) - 开源开发者平台，用最少的 Python 与 TypeScript 脚本构建生产级多步自动化与内部应用。免费用户最多可创建并加入 3 个非高级工作区。
  * [wistia.com](https://wistia.com/) — 视频托管服务，含观看分析、高清视频交付与营销工具，提供 25 个视频与 Wistia 品牌播放器。
  * [wormhol.org](https://www.wormhol.org/) — 简洁的文件共享服务。单文件最多 5GB，可与任意多的对等方共享。
  * [Wormhole](https://wormhole.app/) - 端到端加密分享文件，最多 5GB，最长 24 小时。大于 5GB 时使用点对点传输。
  * [zoom.us](https://zoom.us/) — 提供安全的视频与 Web 会议附加功能，免费计划限 40 分钟。
  * [Zulip](https://zulip.com/) — 具有独特邮件式线程模型的实时聊天。免费计划包含 10,000 条可搜索消息历史与最多 5 GB 文件存储，也提供可自托管的开源版本。

**[⬆️ Back to Top](#table-of-contents)**

## CMS

  * [Contentful](https://www.contentful.com/) — Headless CMS。云端内容管理和交付 API。免费社区空间包含 5 名用户、25K 条记录、48 种内容类型、2 种语言环境。
  * [Cosmic](https://www.cosmicjs.com/) — Headless CMS 和 API 工具包。为开发者提供免费个人计划。
  * [Crystallize](https://crystallize.com) — 支持电商的 Headless PIM。内置 GraphQL API。免费版本包含无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用。
  * [DatoCMS](https://www.datocms.com/) - 为小型项目提供免费层级。DatoCMS 是基于 GraphQL 的 CMS。在低层级，您有 100k/月调用次数。
  * [Hygraph](https://hygraph.com/) - 为小型项目提供免费层级。GraphQL 优先 API。从传统解决方案迁移到 GraphQL 原生 Headless CMS - 并优先提供全渠道内容 API。
  * [Prismic](https://www.prismic.io/) — Headless CMS。具有完全托管和可扩展 API 的内容管理界面。社区计划为单个用户提供无限的 API 调用、文档、自定义类型、资产和语言环境。您下一个项目所需的一切。开源内容/开源项目有更大的免费计划。
  * [Sanity.io](https://www.sanity.io/) - 结构化内容平台，具有开源编辑环境和实时托管数据存储。无限项目。每个项目免费包含无限管理员用户、3 个非管理员用户、2 个数据集、500K API CDN 请求、10GB 带宽和 5GB 资产。
  * [Solo](https://soloist.ai) - 来自 Mozilla 的免费 AI 网站创建器，通过几个简单的输入为您的业务创建美丽的网站。免费自定义域名，无需信用卡。
  * [Squidex](https://squidex.io/) - 为小型项目提供免费层级。API / GraphQL 优先。开源并基于事件溯源（自动记录每个更改）。
  * [Storyblok](https://www.storyblok.com) - 适用于开发者和营销人员的 Headless CMS，适用于所有现代框架。社区（免费）层级提供管理 API、可视化编辑器、10 个来源、自定义字段类型、国际化（无限语言/语言环境）、资产管理器（最多 2500 个资产）、图像优化服务、搜索查询、Webhook + 包含 250GB 流量/月。
  * [TinaCMS](https://tina.io/) — 替代 Forestry.io。开源 Git 支持的 Headless CMS，支持 Markdown、MDX 和 JSON。基本免费，可使用 2 个用户。
  * [WPJack](https://wpjack.com) - 在不到 5 分钟内在任何云上设置 WordPress！免费层级包括 1 台服务器、2 个站点、免费 SSL 证书和无限的 cron 作业。没有时间限制或过期——您的网站，您的方式。

**[⬆️ Back to Top](#table-of-contents)**

## Code Generation

* [Appinvento](https://appinvento.io/) — 免费的无代码应用构建器。它提供对自动生成的后端源代码的完全访问权限，并允许使用无限的 API 和路由。免费计划包括 3 个项目和 5 个表。
* [DhiWise](https://www.dhiwise.com/) — 将 Figma 设计转换为动态 Flutter 和 React 应用程序。其代码生成技术专为优化构建生产就绪的移动和 Web 体验的工作流程而设计。
* [Karbon Sites](https://www.karbonsites.space) — AI 驱动的网站构建器和编辑器，可从文本提示、草图或简历生成生产就绪的前端代码。功能包括原生 Android (APK) 导出和每月 5 次生成的免费层级（通过自定义 Gemini API 密钥无限使用）。
* [Metalama](https://www.postsharp.net/metalama) — C# 专用工具，可在编译期间动态生成样板代码以保持源代码整洁。开源项目免费；商业友好的免费层级包括最多 3 个切面。
* [Supermaven](https://www.supermaven.com/) — 适用于 VS Code、JetBrains 和 Neovim 的高速 AI 代码完成插件。免费层级提供无限的内联完成，专注于超低延迟。
* [v0.dev](https://v0.dev/) — 由 Vercel 创建，v0 使用 shadcn/ui 和 Tailwind CSS 生成可复制粘贴的 React 代码。它使用积分系统，提供 1,200 个起始积分和每月 200 个免费积分。

**[⬆️ Back to Top](#table-of-contents)**

## Code Quality

  * [beanstalkapp.com](https://beanstalkapp.com/) — 编写、审查和部署代码的完整工作流程），一个免费账户，一个包含 100 MB 存储空间的仓库
  * [codacy.com](https://www.codacy.com/) — 针对 PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动化代码审查，无限公共和私有仓库免费
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 用于 DevOps 的自动化基础设施即代码审查工具，与 GitHub、Bitbucket 和 GitLab（包括自托管）集成。除了标准语言外，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等。（开源免费）
  * [codecov.io](https://codecov.io/) — 代码覆盖率工具 (SaaS)，开源免费，一个免费私有仓库
  * [CodeFactor](https://www.codefactor.io) — Git 的自动化代码审查。免费版本包括无限用户、公共仓库和一个私有仓库。
  * [coderabbit.ai](https://coderabbit.ai) — 与 GitHub/GitLab 集成的 AI 驱动代码审查工具。免费层级包括每小时 200 个文件、每小时 3 次审查和每小时 50 次对话。开源项目永久免费。
  * [CodSpeed](https://codspeed.io) - 在 CI 流水线中自动化性能跟踪。通过精确和一致的指标在部署前捕获性能回归。开源项目永久免费。
  * [coveralls.io](https://coveralls.io/) — 显示测试覆盖率报告，开源免费
  * [deepscan.io](https://deepscan.io) — 高级静态分析，自动查找 JavaScript 代码中的运行时错误，开源免费
  * [DeepSource](https://deepsource.io/) - DeepSource 持续分析源代码更改，发现和修复分类为安全、性能、反模式、bug 风险、文档和样式的问题。与 GitHub、GitLab 和 Bitbucket 原生集成。
  * [DiffText](https://difftext.com) - 即时找到两个代码块之间的差异。完全免费使用。
  * [eversql.com](https://www.eversql.com/) — EverSQL - 数据库优化排名第一的平台。自动获得对数据库和 SQL 查询的关键洞察。
  * [gerrithub.io](https://review.gerrithub.io/) — GitHub 仓库的 Gerrit 代码审查，免费
  * [goreportcard.com](https://goreportcard.com/) — Go 项目的代码质量，开源免费
  * [gtmetrix.com](https://gtmetrix.com/) — 优化网站的报告和全面建议
  * [holistic.dev](https://holistic.dev/) - PostgreSQL 优化排名第一的静态代码分析器。性能、安全和架构数据库问题自动检测服务
  * [houndci.com](https://houndci.com/) — 在 GitHub 提交上评论代码质量，开源免费
  * [reviewable.io](https://reviewable.io/) — GitHub 仓库的代码审查，公共或个人仓库免费。
  * [scan.coverity.com](https://scan.coverity.com/) — Java、C/C++、C# 和 JavaScript 的静态代码分析，开源免费
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检查平台，开源免费
  * [semanticdiff.com](https://app.semanticdiff.com/) — GitHub 拉取请求和提交的编程语言感知差异，公共仓库免费
  * [shields.io](https://shields.io) — 开源项目的质量元数据徽章
  * [sonarcloud.io](https://sonarcloud.io) — 针对 Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 等更多语言的自动化源代码分析，开源免费

**[⬆️ Back to Top](#table-of-contents)**

## Code Search and Browsing

  * [CodeKeep](https://codekeep.io) - 代码片段的 Google Keep。组织、发现和分享代码片段，具有强大的代码截图工具，具有预设模板和链接功能。
  * [libraries.io](https://libraries.io/) — 针对 32 个不同包管理器的搜索和依赖更新通知，开源免费
  * [Namae](https://namae.dev/) - 搜索各种网站（如 GitHub、Gitlab、Heroku、Netlify 等）以查找您的项目名称是否可用。
  * [tickgit.com](https://www.tickgit.com/) — 显示 `TODO` 注释（和其他标记）以识别值得返回改进的代码区域。

**[⬆️ Back to Top](#table-of-contents)**

## CI and CD

  * [appcircle.io](https://appcircle.io) — 企业级移动 DevOps 平台，自动化移动应用的构建、测试和发布商店，以实现更快速、高效的发布周期。免费：每次构建最多 30 分钟构建时间，每月 20 次构建和 1 个并发构建。
  * [appveyor.com](https://www.appveyor.com/) — Windows 的 CD 服务，开源免费
  * [bitrise.io](https://www.bitrise.io/) — 移动应用的 CI/CD，原生或混合。每月 200 次免费构建，10 分钟构建时间和两名团队成员。OSS 项目获得 45 分钟构建时间，+1 并发和无限团队规模。
  * [buddy.works](https://buddy.works/) — CI/CD，五个免费项目和一次并发运行（每月 120 次执行）
  * [Buildkite](https://buildkite.com) CI 流水线，3 名用户和每月 5k 任务分钟免费。测试分析免费开发者层级包括每月 100k 次测试执行，开源项目有更多免费包含。
  * [bytebase.com](https://www.bytebase.com/) — 数据库 CI/CD 和 DevOps。20 名用户和十个数据库实例以下免费
  * [CircleCI](https://circleci.com/) — 综合免费计划，包含托管的 CI/CD 服务针对 GitHub、GitLab 和 BitBucket 仓库的所有功能。多种资源类、Docker、Windows、Mac OS、ARM 执行器、本地运行器、测试拆分、Docker 层缓存和其他高级 CI/CD 功能。每月最多 6000 分钟执行时间、无限协作者、私有项目中 30 个并行作业以及开源项目最多 80,000 分钟免费构建时间免费。
  * [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 仓库免费
  * [cirun.io](https://cirun.io) - 公共 GitHub 仓库免费
  * [codemagic.io](https://codemagic.io/) - 每月免费 500 构建分钟
  * [deployhq.com](https://www.deployhq.com/) — 1 个项目，每天 10 次部署（每月 30 构建分钟）
  * [LocalOps](https://localops.co/) - 在 30 分钟内在 AWS/GCP/Azure 上部署您的应用程序。在任何云上设置标准化的应用程序环境，这些环境具有内置的持续部署自动化和高级可观察性。免费计划允许 1 个用户和 1 个应用程序环境。
  * [Make](https://www.make.com/en) — 工作流自动化工具让您使用 UI 连接应用程序并自动化工作流程。它支持许多应用程序和最流行的 API。公共 GitHub 仓库免费，免费层级包括 100 Mb、1000 次操作和 15 分钟的最小间隔。
  * [Mergify](https://mergify.com) — GitHub 的工作流自动化和合并队列——公共 GitHub 仓库免费
  * [Nx Cloud](https://nx.dev/ci) - Nx Cloud 通过远程缓存、跨机器分发任务甚至自动拆分 e2e 测试运行等功能，加速 CI 上的 monorepos。它包含一个最多 30 名贡献者的免费计划，包含慷慨的 150k 积分。
  * [RunMyJob](https://runmyjob.io) - 使用实时扩展 Spike Instances 更智能地运行 GitHub Actions 和 GitLab CI 流水线。免费层级包括 400 vCPU-分钟、800 GB-分钟和 10 个并发作业，具有高性能运行器（每个作业 12 vCPU 和 32 GB RAM）。
  * [Shipfox](https://www.shipfox.io/) - 将您的 GitHub actions 运行速度提高 2 倍，每月免费 3.000 构建分钟。
  * [Spacelift](https://spacelift.io/) - 基础设施即代码管理平台。免费计划功能：IaC 协作、Terraform 模块注册表、ChatOps 集成、使用 Open Policy Agent 的持续资源合规性、SAML 2.0 的 SSO，以及访问公共工作池：最多 200 分钟/月
  * [Squash Labs](https://www.squash.io/) — 为每个分支创建一个 VM 并使您的应用程序从唯一的 URL 可用，无限公共和私有仓库，最多 2 GB VM 大小。
  * [Terramate](https://terramate.io/) - Terramate 是基础设施即代码 (IaC) 工具（如 Terraform、OpenTofu 和 Terragrunt）的编排和管理平台。最多 2 名用户免费，包括所有功能。
  * [Terrateam](https://terrateam.io) - GitOps 优先的 Terraform 自动化，具有拉取请求驱动的工作流程、通过自托管运行器的项目隔离以及用于有序操作的分层运行。最多 3 名用户免费。

**[⬆️ Back to Top](#table-of-contents)**

## Testing

  * [Appetize](https://appetize.io) — 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序。免费层级包括两个并发会话，每月 30 分钟使用时间。应用程序大小无限制。
  * [Argos](https://argos-ci.com) - 面向开发者的开源视觉测试。无限项目，每月 5,000 个截图。开源项目免费。
  * [Bencher](https://bencher.dev/) - 连续基准测试工具套件，用于捕获 CI 性能回归。所有公共项目免费。
  * [BugBug](https://bugbug.io/) - Web 应用程序的轻量级测试自动化工具。易于学习，无需编码。您可以在自己的计算机上免费运行无限测试。您还可以通过每月额外费用获得云监控和 CI/CD 集成。
  * [checkbot.io](https://www.checkbot.io/) — 浏览器扩展，测试您的网站是否遵循 50 多项 SEO、速度和安全最佳实践。较小网站的免费层级。
  * [Checkly](https://checklyhq.com) - 面向现代 DevOps 的代码优先综合监控。以传统提供商价格的一小部分监控您的 API 和应用程序。由监控即代码工作流程和 Playwright 驱动。为开发者提供慷慨的免费层级。
  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 供开发者和 API 测试人员免费使用的工具，用于检查 API 是否为给定域启用了 CORS 并识别差距。获得可操作的见解。
  * [cypress.io](https://www.cypress.io/) - 针对任何在浏览器中运行的内容进行快速、简单和可靠的测试。Cypress 测试运行器始终免费和开源，没有限制和约束。Cypress 仪表板最多 5 名用户的开源项目免费。
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录和回放 Web 浏览器中完成的所有步骤并创建脚本，选项较少时免费
  * [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid 测试，免费计划最多 4 个并发 selenium 节点/10 次网格启动/4,000 测试分钟/月
  * [katalon.com](https://katalon.com) - 提供一个测试平台，可以帮助不同测试成熟度级别的各种规模的团队，包括 Katalon Studio、TestOps（+ 视觉测试免费）、TestCloud 和 Katalon Recorder。
  * [Keploy](https://keploy.io/) - Keploy 是面向开发者的功能测试工具包。记录 API 调用可为 API 生成 E2E 测试（KTests）和模拟或存根（KMocks）。开源项目免费。
  * [loadmill.com](https://www.loadmill.com/) — 通过分析网络流量自动创建 API 和负载测试。每月免费模拟最多 50 个并发用户，最多 60 分钟。
  * [lost-pixel.com](https://lost-pixel.com) - 针对 Storybook、Ladle、Histoire 故事和 Web 应用程序的整体视觉回归测试。无限团队成员，开源项目完全免费，7,000 个快照/月。
  * [pagegym.com](https://pagegym.com) - 负载行为和页面速度分析与优化工具。免费计划每天提供 10 次测试，每周 5 次实验，每月最多 15 GB 摄入数据。
  * [percy.io](https://percy.io) - 将视觉测试添加到任何 Web 应用程序、静态站点、样式指南或组件库。无限团队成员、演示应用程序和无限项目，5,000 个快照/月。
  * [qase.io](https://qase.io) - 面向 Dev 和 QA 团队的测试管理系统。管理测试用例、组合测试运行、执行测试、跟踪缺陷并衡量影响。免费层级包括所有核心功能，500MB 附件空间和最多 3 名用户。
  * [Repeato](https://repeato.app/) 基于计算机视觉和 AI 构建的无代码移动应用程序测试自动化工具。适用于原生应用程序、flutter、react-native、web、ionic 和许多其他应用程序框架。免费计划限制 iOS 10 次测试和 Android 10 次测试，但包括付费计划的大部分功能，包括无限测试运行。
  * [Requestly](https://requestly.com/) 拦截、重定向和模拟 HTTP 请求的开源 Chrome 扩展。功能包括[调试器](https://requestly.com/products/web-debugger/)、[模拟服务器](https://requestly.com/products/mock-server/)、[API 客户端](https://requestly.com/products/api-client/)和[会话录制](https://requestly.com/products/session-book/)。重定向 URL、修改 HTTP 标头、模拟 API、注入自定义 JS、修改 GraphQL 请求、生成模拟 API 端点、使用网络和控制台日志记录会话。免费层级最多创建 10 条规则。开源免费。
  * [seotest.me](https://seotest.me/) — 免费的页面 SEO 网站测试器。每天 10 次免费网站爬取。有用的 SEO 学习资源以及有关如何改进任何网站（无论技术如何）的页面 SEO 结果的建议。
  * [snippets.uilicious.com](https://snippets.uilicious.com) - 就像 CodePen，但用于跨浏览器测试。UI-licious 让您像编写用户故事一样编写测试，并提供一个免费平台——UI-licious Snippets——允许您在 Chrome 上运行无限测试，无需注册，每次测试运行最多 3 分钟。发现错误？您可以复制测试的唯一 URL，向您的开发人员展示确切如何重现错误。
  * [SSR (Server-side Rendering) Checker](https://www.crawlably.com/ssr-checker/) - 通过视觉比较页面的服务器渲染版本和常规版本，检查任何 URL 的 SSR（服务器端渲染）。
  * [testingbot.com](https://testingbot.com/) — Selenium 浏览器和设备测试，[开源免费](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - 用于发布自动化测试结果的仪表板和使用 GitHub 实现手动测试作为代码的框架。该服务[对开源项目免费](https://github.com/marketplace/testspace-com)，占每月 450 个结果。
  * [tesults.com](https://www.tesults.com) — 测试结果报告和测试用例管理。与流行的测试框架集成。开源软件开发人员、个人、教育者和开始使用的小团队可以请求超出基本免费项目的折扣和免费优惠。
  * [UseWebhook.com](https://usewebhook.com) - 从浏览器捕获和检查 webhook。转发到 localhost，或从历史记录重放。免费使用。
  * [Vaadin](https://vaadin.com) — 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成工具、组件和设计系统更快地迭代、更好地设计并简化开发过程。无限项目，五年免费维护。
  * [webhook-test.com](https://webhook-test.com) - 在集成期间使用唯一的 URL 调试和检查 webhook 和 HTTP 请求。完全免费，您可以创建无限的 URL 并接收建议。
  * [webhook.site](https://webhook.site) - 使用自定义 URL 验证 webhook、出站 HTTP 请求或电子邮件。临时 URL 和电子邮件地址始终免费。
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费网络和服务器工具。
  * [kogiQA](https://kogiqa.com) — 无需选择器即可运行的 Web UI 自动化工具。每位开发者每月免费获得 500 次操作。

**[⬆️ Back to Top](#table-of-contents)**

## Security and PKI

  * [aikido.dev](https://www.aikido.dev) — 一体化应用安全平台，涵盖 SCA、SAST、CSPM、DAST、Secrets、IaC、Malware、容器扫描、EOL 等。免费计划包括 2 名用户，扫描 10 个仓库、1 个云、2 个容器和 1 个域名。
  * [CertKit](https://www.certkit.io/certificate-management) - 管理 SSL 证书的颁发、续订和监控。搜索证书透明度日志。测试版后 3 个证书和 1 名用户免费。
  * [crypteron.com](https://www.crypteron.com/) — 云优先、对开发者友好的安全平台，防止 .NET 和 Java 应用程序中的数据泄露
  * [CyberChef](https://gchq.github.io/CyberChef/) — 一个简单、直观的 Web 应用程序，用于分析和解码/编码数据，而无需处理复杂的工具或编程语言。就像密码学和加密的瑞士军刀。所有功能都可以免费使用，没有限制。如果您希望自托管，则开源。
  * [Datree](https://www.datree.io/) — 开源 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及您的组织策略来防止 Kubernetes 配置错误
  * [Dependabot](https://dependabot.com/) 针对 Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git Submodules 和 GitHub Actions 的自动化依赖更新。
  * [DJ Checkup](https://djcheckup.com) — 使用此免费的自动化检查工具扫描您的 Django 站点的安全漏洞。从 Pony Checkup 站点分叉。
  * [Doppler](https://doppler.com/) — 应用程序秘密和配置的通用秘密管理器，支持同步到各种云提供商。5 名用户免费，具有基本访问控制。
  * [Dotenv](https://dotenv.org/) — 快速安全地同步您的 .env 文件。停止通过 Slack 和电子邮件等不安全渠道共享您的 .env 文件，永远不再丢失重要的 .env 文件。最多 3 名队友免费。
  * [GitGuardian](https://www.gitguardian.com) — 通过自动秘密检测和修复，将秘密排除在源代码之外。扫描您的 git 仓库中 350+ 种类型的秘密和敏感文件——个人和 25 名或更少开发者的团队免费。
  * [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - 免费搜索公共 GitHub 仓库、gist、问题和评论中暴露的 2000 万个秘密
  * [Have I been pwned?](https://haveibeenpwned.com) — 用于获取漏洞信息的 REST API。
  * [hostedscan.com](https://hostedscan.com) — Web 应用程序、服务器和网络的在线漏洞扫描器。每月 10 次免费扫描。
  * [Infisical](https://infisical.com/) — 开源平台，让您跨团队和基础设施管理开发者秘密：从本地开发到测试/生产第三方服务的任何地方。最多 5 名开发者免费。
  * [Internet.nl](https://internet.nl) — 测试现代 Internet 标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [letsencrypt.org](https://letsencrypt.org/) — 免费 SSL 证书颁发机构，证书受所有主要浏览器信任
  * [meterian.io](https://www.meterian.io/) - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目依赖项中的安全漏洞。一个私有项目免费，开源项目无限。
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您站点中的安全漏洞。
  * [Project Gatekeeper](https://gatekeeper.binarybiology.top/) - 一体化 SSL 工具包，提供私钥和 CSR 生成器、SSL 证书解码器、证书匹配器和订购 SSL 证书等各种功能。我们为用户提供使用 CNAME 记录而不是 TXT 记录从 Let's Encrypt、Google Trust 和 BuyPass 生成免费 SSL 证书的服务。
  * [Protectumus](https://protectumus.com) - 免费网站安全检查、站点杀毒和服务器防火墙 (WAF) 用于 PHP。免费层级中注册用户的电子邮件通知。
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) — 针对公共云基础设施的高置信度入侵指标 (IOC)，一部分在 github 上可用 (https://github.com/unknownhad/AWSAttacks)。完整列表通过 API 提供
  * [pyup.io](https://pyup.io) — 监控 Python 依赖项的安全漏洞并自动更新它们。一个私有项目免费，开源项目无限。
  * [qualys.com](https://www.qualys.com/community-edition) — 查找 Web 应用漏洞，审核 OWASP 风险
  * [Socket](https://socket.dev) — 为个人开发者、小团队和开源项目提供免费的供应链安全。包括一个免费应用程序和防火墙 CLI 工具，用于保护您的代码免受漏洞和恶意依赖项的侵害。检测 70 多种供应链风险指标。
  * [SOOS](https://soos.io) - 开源项目的免费、无限 SCA 扫描。在发布之前检测和修复安全威胁。使用简单有效的解决方案保护您的项目。
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器配置进行深入分析
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费网站安全检查和恶意软件扫描器
  * [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的安全服务器配置、证书、链等。不限于 HTTPS。
  * [Virgil Security](https://virgilsecurity.com/) — 用于在您的数字解决方案中实现端到端加密、数据库保护、IoT 安全等工具和服务。最多 250 名用户的应用程序免费。

**[⬆️ Back to Top](#table-of-contents)**

## Authentication, Authorization, and User Management

  * [360username](https://360username.com/) - 免费工具，可在 90+ 个社交平台上搜索用户名以查找匹配的个人资料。
  * [Aserto](https://www.aserto.com) - 面向应用程序和 API 的细粒度授权即服务。最多 1000 MAU 和 100 个授权器实例免费。
  * [asgardeo.io](https://wso2.com/asgardeo) - SSO、MFA、无密码身份验证等的无缝集成。包括前端和后端应用程序的 SDK。最多 1000 MAU 和五个身份提供商免费。
  * [Auth0](https://auth0.com/) — 托管 SSO。免费计划包括 25,000 MAU、无限社交连接、自定义域名等。
  * [Authgear](https://www.authgear.com) - 在几分钟内将无密码、OTP、2FA、SSO 带到您的应用程序。包括所有前端。最多 5000 MAU 免费。
  * [Authress](https://authress.io/) — 身份验证登录和访问控制，针对任何项目的无限身份提供商。Facebook、Google、Twitter 等。前 1000 次 API 调用免费。
  * [Authy](https://authy.com) - 多设备上的双因素身份验证 (2FA)，具有备份功能。Google Authenticator 的直接替代品。最多 100 次成功身份验证免费。
  * [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - 完整的授权管理系统，用于编写、测试和部署访问策略。细粒度授权和访问控制，最多 100 个每月活跃主体免费。
  * [Clerk](https://clerk.com) — 用户管理、身份验证、2FA/MFA、用于登录、注册、用户资料等的预构建 UI 组件。最多 10,000 名每月活跃用户免费。
  * [Cloud-IAM](https://www.cloud-iam.com/) — Keycloak 身份和访问管理即服务。最多 100 名用户和一个领域免费。
  * [Descope](https://www.descope.com/) — 高度可定制的 AuthN 流程，具有无代码和 API/SDK 方法，免费 7,500 名活跃用户/月，50 个租户（最多 5 个 SAML/SSO 租户）。
  * [duo.com](https://duo.com/) — 网站或应用程序的双因素身份验证 (2FA)。10 名用户免费，所有身份验证方法、无限集成、硬件令牌。
  * [Kinde](https://kinde.com/) - 简单、强大的身份验证，您可以在几分钟内与您的产品集成。开始使用所需的一切，7,500 免费 MAU。
  * [logintc.com](https://www.logintc.com/) — 通过推送通知进行双因素身份验证 (2FA)，10 名用户免费，支持 VPN、网站和 SSH
  * [Logto](https://logto.io/) - 开发、保护和管理您产品的用户身份——用于身份验证和授权。最多 5,000 MAU 免费，提供开源自托管选项。
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 让您在几分钟内在您的 Web、移动或任何应用程序上轻松实现无密码身份验证。
  * [Okta](https://developer.okta.com/signup/) — 用户管理、身份验证和授权。最多 100 名每月活跃用户免费。
  * [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/零信任托管安全平台。永久免费开发者账户，包含所有安全功能、无限团队成员、200 名每日活跃用户和 25k/月权限检查。
  * [Permit.io](https://permit.io) - 授权即服务提供商平台，为可扩展的微服务启用 RBAC、ABAC 和 ReBAC，具有实时更新和无代码策略 UI。1000 名每月活跃用户免费层级。
  * [Phase Two](https://phasetwo.io) - Keycloak 开源身份和访问管理。最多 1000 名用户的免费领域，最多 10 个 SSO 连接，利用 Phase Two 的 Keycloak 增强容器，其中包括 [组织](https://phasetwo.io/product/organizations/)扩展。
  * [PropelAuth](https://propelauth.com) — 只需几行代码即可立即向任何规模的公司销售，最多 200 名用户和 10k 事务性电子邮件免费（带有水印品牌："Powered by PropelAuth"）。
  * [Stack Auth](https://stack-auth.com) — 不难用的开源身份验证。最开发友好的解决方案，只需五分钟即可开始。免费自托管，或提供托管 SaaS 版本，具有 10k 免费每月活跃用户。
  * [Stytch](https://www.stytch.com/) - 为身份验证和欺诈防范提供 API 和 SDK 的一体化平台。免费计划包括 10,000 名每月活跃用户、无限组织、5 个 SSO 或 SCIM 连接以及 1,000 个 M2M 令牌。
  * [SuperTokens](https://supertokens.com/) - 开源用户身份验证，本机集成到您的应用程序中——让您能够快速开始，同时控制用户和开发者体验。最多 5000 MAU 免费。
  * [WorkOS](https://workos.com/) - 免费用户管理和身份验证，最多 100 万 MAU。支持电子邮件 + 密码、社交身份验证、Magic Auth、MFA 等。
  * [ZITADEL Cloud](https://zitadel.com) — 适合您的开箱即用用户和访问管理，支持多租户 (B2B) 用例。最多 25,000 次经过身份验证的请求免费，包含所有安全功能（OTP、无密码、策略等无需付费墙）。


**[⬆️ Back to Top](#table-of-contents)**

## Mobile App Distribution and Feedback

  * [Appho.st](https://appho.st) - 移动应用托管平台。免费计划包括五个应用程序、每月 50 次下载和最大 100 MB 文件大小。
  * [Diawi](https://www.diawi.com) - 直接将 iOS 和 Android 应用程序部署到设备。免费计划：应用程序上传、密码保护链接、1 天过期、十次安装。
  * [GetUpdraft](https://www.getupdraft.com) - 分发移动应用程序进行测试。免费计划包括一个应用程序项目、三个应用程序版本、500 MB 存储空间和每月 100 次应用程序安装。
  * [InstallOnAir](https://www.installonair.com) - 通过空中分发 iOS 和 Android 应用程序。免费计划：无限上传、私有链接、访客 2 天过期、注册用户 60 天。
  * [Loadly](https://loadly.io) - iOS 和 Android beta 应用程序分发服务提供完全免费的服务，具有无限下载、高速下载和无限上传。

**[⬆️ Back to Top](#table-of-contents)**

## Management System

  * [bitnami.com](https://bitnami.com/) — 在 IaaS 上部署准备好的应用程序。1 个 AWS 微实例管理免费
  * [Esper](https://esper.io) — 带有 DevOps 的 Android 设备 MDM 和 MAM。一个用户许可证和 25 MB 应用程序存储免费 100 台设备。
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone 和 Mac 的设备管理，三台设备免费
  * [Miradore](https://miradore.com) — 设备管理服务。随时了解您的设备群并免费保护无限设备。免费计划提供基本功能。
  * [moss.sh](https://moss.sh) - 帮助开发者部署和管理他们的 Web 应用程序和服务器。每月最多 25 次 git 部署免费
  * [ploi.io](https://ploi.io/) - 服务器管理工具，轻松管理和部署您的服务器和站点。一台服务器免费。
  * [runcloud.io](https://runcloud.io/) - 主要专注于 PHP 项目的服务器管理。最多 1 台服务器免费。
  * [serveravatar.com](https://serveravatar.com) — 通过自动化配置管理和监控基于 PHP 的 Web 服务器。一台服务器免费。
  * [xcloud.host](https://xcloud.host) — 具有用户友好界面的服务器管理和部署平台。一台服务器提供免费层级。

**[⬆️ Back to Top](#table-of-contents)**

## Messaging and Streaming

  * [Ably](https://www.ably.com/) - 具有在线状态、持久化和保证传递的实时消息服务。免费计划包括每月 300 万条消息、100 个峰值连接和 100 个峰值频道。
  * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服务。Little Lemur 计划：最多每月 100 万条消息、最多 20 个并发连接、最多 100 个队列、最多 10,000 条排队消息、不同 AZ 中的多个节点
  * [courier.com](https://www.courier.com/) — 用于推送、应用内、电子邮件、聊天、短信和其他消息通道的单个 API，具有模板管理和其他功能。免费计划包括 10,000 条消息/月。
  * [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) - 可扩展且安全的无服务器 MQTT 代理，您可以在几秒钟内获得。每月 100 万会话分钟永久免费（无需信用卡）。
  * [Engage](https://engage.so/) - 面向 SaaS 的一体化客户参与和自动化工具（电子邮件、推送、短信、产品导览、横幅等）。每月最多 1,000 名活跃用户免费。
  * [engagespot.co](https://engagespot.co/) — 面向开发者的多渠道通知基础设施，具有预构建的应用内收件箱和无代码模板编辑器。免费计划包括 10,000 条消息/月。
  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 将您的 MQTT 设备连接到云原生 IoT 消息代理。永久免费连接最多 100 台设备（无需信用卡）。
  * [httpSMS](https://httpsms.com) - 使用您的 Android 手机作为 SMS 网关发送和接收短信。每月免费发送和接收最多 200 条消息。
  * [knock.app](https://knock.app) – 面向开发者的通知基础设施。通过单个 API 调用发送到多个通道，如应用内、电子邮件、短信、Slack 和推送。免费计划包括 10,000 条消息/月。
  * [NotificationAPI.com](https://www.notificationapi.com/) — 在 5 分钟内将用户通知添加到任何软件。免费计划包括 10,000 条通知/月 + 100 条短信和自动通话。
  * [Novu.co](https://novu.co) — 面向开发者的开源通知基础设施。在一个地方管理所有通信通道的简单组件和 API：电子邮件、短信、直接、应用内和推送。免费计划包括 30,000 条通知/月，保留 90 天。
  * [Pocket Alert](https://pocketalert.app) - 向您的 iOS 和 Android 设备发送推送通知。通过 API 或 Webhook 轻松集成，并保持对警报的完全控制。免费计划：每天 50 条消息发送到 1 台设备和 1 个应用程序。
  * [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin 和 React 消息，每月 100 万次交易。交易可能包含多条消息。
  * [pusher.com](https://pusher.com/) — 实时消息服务。最多 100 个并发连接和每天 200,000 条消息免费
  * [scaledrone.com](https://www.scaledrone.com/) — 实时消息服务。最多 20 个并发连接和每天 100,000 个事件免费
  * [SMSGate](https://sms-gate.app) - Android™ 的 SMS 网关，支持使用云路由通过您的设备发送和接收短信。完全免费的云服务（建议在使用超过 10,000 条消息/天时进行通知，以维持所有用户的质量）。
  * [SuprSend](https://www.suprsend.com/) - SuprSend 是一个通知基础设施，采用 API 优先的方法简化您的产品通知。使用单个通知 API 在多个通道上创建和交付事务性、定时任务和参与通知。在免费计划中，您每月获得 10,000 条通知，包括不同的工作流节点，如摘要、批处理、多通道、偏好设置、租户、广播等。
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 即服务。全球、AWS、GCP 和 Azure。永久免费，具有 4k 消息大小、50 个活跃连接和每月 5GB 数据。
  * [webpushr](https://www.webpushr.com/) - Web 推送通知 - 最多 10k 订阅者免费，无限推送通知，浏览器内消息

**[⬆️ Back to Top](#table-of-contents)**

## Log Management

  * [bugfender.com](https://bugfender.com/) — 每天最多 100k 日志行免费，保留 24 小时
  * [log.dog](https://log.dog/) — LogDog 是一个远程调试/日志记录 SDK（iOS 和 Android），具有 Web UI。实时捕获所有日志、请求和事件并允许拦截它们。每月最多 100MB 日志免费
  * [logflare.app](https://logflare.app/) — 每个应用每月最多 12,960,000 条目免费，保留 3 天
  * [logtail.com](https://logtail.com/) — 基于 ClickHouse 的兼容 SQL 的日志管理。每月最多 1 GB 免费，保留 3 天。
  * [logzab.com](https://logzab.com/) — 审计跟踪管理系统。每月 1,000 条用户活动日志免费，保留 1 个月，最多 5 个项目。
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) — 由 Manage Engine 提供支持的日志管理服务。免费计划提供 50 GB 存储，保留 15 天和搜索 7 天。
  * [openobserve.ai](https://openobserve.ai/) - 每月 200 GB 摄取免费，保留 15 天

**[⬆️ Back to Top](#table-of-contents)**

## Translation Management

  * [AutoLocalise.com](https://www.autolocalise.com/) — 无需管理翻译文件即可即时本地化。每月最多 10,000 个字符免费，无限语言。
  * [crowdin.com](https://crowdin.com/) — 开源项目无限项目、无限字符串和协作者
  * [Free PO editor](https://pofile.net/free-po-editor) — 对所有人免费
  * [Lingo.dev](https://lingo.dev) – 用于 Web 和移动本地化的开源 AI 驱动 CLI。自带 LLM，或通过 Lingo.dev 管理的本地化引擎每月使用 10,000 个免费单词。
  * [lingohub.com](https://lingohub.com/) — 最多 3 名用户免费，开源项目永久免费
  * [localazy.com](https://localazy.com) - 1000 个源语言字符串免费，无限语言、无限协作者、初创公司和开源交易
  * [Localit](https://localit.io) – 快速、对开发者友好的本地化平台，具有无缝免费的 GitHub/GitLab 集成、AI 辅助和手动翻译，以及慷慨的免费计划（包括 2 名用户、500 个密钥和无限项目）。
  * [localizely.com](https://localizely.com/) — 开源项目免费
  * [Loco](https://localise.biz/) — 最多 2000 个翻译免费，无限翻译人员，每个项目十种语言，每个项目 1000 个可翻译资产
  * [POEditor](https://poeditor.com/) — 最多 1000 个字符串免费
  * [SimpleLocalize](https://simplelocalize.io/) - 最多 100 个翻译键免费，无限字符串、无限语言、初创企业交易
  * [Texterify](https://texterify.com/) - 单个用户免费
  * [Tolgee](https://tolgee.io) - 具有有限翻译的免费 SaaS 产品，永久免费的自托管版本
  * [transifex.com](https://www.transifex.com/) — 开源项目免费

**[⬆️ Back to Top](#table-of-contents)**

## Monitoring

  * [assertible.com](https://assertible.com) — Automated API testing and monitoring. Free plans for teams and individuals.
  * [Better Stack](https://betterstack.com/better-uptime) - Uptime monitoring, incident management, on-call scheduling/alerting, and status pages in a single product. The free plan includes ten monitors with 3-minute check frequency and status pages.
  * [bleemeo.com](https://bleemeo.com) - Free for 3 servers, 5 uptime monitors, unlimited users, unlimited dashboards, unlimited alerting rules.
  * [checklyhq.com](https://checklyhq.com) - Open source E2E / Synthetic monitoring and deep API monitoring for developers. Free plan with one user and 10k API & network / 1.5k browser check runs.
  * [Core Web Vitals History](https://punits.dev/core-web-vitals-historical/) - Find Core Web Vitals history for a url or a website.
  * [cronitor.io](https://cronitor.io/) - Performance insights and uptime monitoring for cron jobs, websites, APIs and more. A free tier with five monitors.
  * [datadoghq.com](https://www.datadoghq.com/) — Free for up to 5 nodes
  * [deadmanssnitch.com](https://deadmanssnitch.com/) — Monitoring for cron jobs. One free snitch (monitor), more if you refer others to sign up
  * [downtimemonkey.com](https://downtimemonkey.com/) — 60 uptime monitors, 5-minute interval. Email, Slack alerts.
  * [economize.cloud](https://economize.cloud) — Economize helps demystify cloud infrastructure costs by organizing cloud resources to optimize and report the same. Free for up to $5,000 spent on Google Cloud Platform every month.
  * [fivenines.io](https://fivenines.io/) — Linux server monitoring with real‑time dashboards and alerting — free forever for up to 5 monitored servers at 60-seconds interval. No credit card required.
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud is a composable observability platform that integrates metrics and logs with Grafana. Free: 3 users, ten dashboards, 100 alerts, metrics storage in Prometheus and Graphite (10,000 series, 14 days retention), logs storage in Loki (50 GB of logs, 14 days retention)
  * [healthchecks.io](https://healthchecks.io) — Monitor your cron jobs and background tasks. Free for up to 20 checks.
  * [incidenthub.cloud](https://incidenthub.cloud/) — Cloud and SaaS status page aggregator - 20 monitors and 2 notification channels (Slack and Discord) are free forever.
  * [inspector.dev](https://www.inspector.dev) - A complete Real-Time monitoring dashboard in less than one minute with a free forever tier.
  * [instatus.com](https://instatus.com) - Get a beautiful status page in 10 seconds. Free forever with unlimited subs and unlimited teams.
  * [linkok.com](https://linkok.com) - Online broken link checker, free for small websites up to 100 pages, completely free for open-source projects.
  * [loader.io](https://loader.io/) — Free load testing tools with limitations
  * [Middleware.io](https://middleware.io/) -  Middleware observability platform provides complete visibility into your apps & stack, so you can monitor & diagnose issues at scale. They have a free forever plan for Dev community use that allows Log monitoring for up to 1M log events, Infrastructure monitoring & APM for up to 2 hosts.
  * [MonitorMonk](https://monitormonk.com) - Minimalist uptime monitoring with beautiful status pages. The Forever Free plan offers HTTPS, Keyword, SSL and Response-time monitorming for 10 websites or api-endpoints, and provides 2 dashboards/status pages.
  * [netdata.cloud](https://www.netdata.cloud/) — Netdata is an open-source tool to collect real-time metrics. It's a growing product and can also be found on GitHub!
  * [newrelic.com](https://www.newrelic.com) — New Relic observability platform built to help engineers create more perfect software. From monoliths to serverless, you can instrument everything and then analyze, troubleshoot, and optimize your entire software stack. The free tier offers 100GB/month of free data ingest, one free full-access user, and unlimited free primary users.
  * [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot provides uptime monitoring for websites and APIs, monitoring for cron jobs and scheduled tasks. Also provides status pages. The first five checks with a 3-minute interval are free. The free tier sends alerts via Slack, Discord, and Email.
  * [OntarioNet.ca CN Test](https://cntest.ontarionet.ca) — Check if a website is blocked in China by the Great Firewall. It identifies DNS pollution by comparing DNS results and ASN information detected by servers in China versus servers in the United States.
  * [pagecrawl.io](https://pagecrawl.io/) -  Monitor website changes, free for up to 6 monitors with daily checks.
  * [pagertree.com](https://pagertree.com/) - Simple interface for alerting and on-call management. Free up to 5 users.
  * [phare.io](https://phare.io/) - Uptime Monitoring free for up to 100,000 events for unlimited projets and unlimited status pages.
  * [pingbreak.com](https://pingbreak.com/) — Modern uptime monitoring service. Check unlimited URLs and get downtime notifications via Discord, Slack, or email.
  * [Pingmeter.com](https://pingmeter.com/) - 5 uptime monitors with 10-minute interval. Monitor SSH, HTTP, HTTPS, and any custom TCP ports.
  * [pingpong.one](https://pingpong.one/) — Advanced status page platform with monitoring. The free tier includes one public customizable status page with an SSL subdomain. Pro plan is offered to open-source projects and non-profits free of charge.
  * [Pulsetic](https://pulsetic.com) - 10 monitors, 6 Months of historical Uptime/Logs, unlimited status pages, and custom domains included! For infinite time and unlimited email alerts for free. You don't need a credit card.
  * [robusta.dev](https://home.robusta.dev/) — Powerful Kubernetes monitoring based on Prometheus. Bring your own Prometheus or install the all-in-one bundle. The free tier includes up to 20 Kubernetes nodes. Alerts via Slack, Microsoft Teams, Discord, and more. Integrations with PagerDuty, OpsGenie, VictorOps, DataDog, and many other tools.
  * [Servervana](https://servervana.com) - Advanced uptime monitoring with support for large projects and teams. Provides HTTP monitoring, Browser based monitoring, DNS monitoring, domain monitoring, status pages and more. The free tier includes 10 HTTP monitors, 1 DNS monitor and one status page.
  * [Simple Observability](https://simpleobservability.com) — Powerful server monitoring in a unified platform for metrics and logs, with no setup complexity. Free for one server.
  * [sitesure.net](https://sitesure.net) - Website and cron monitoring - 2 monitors free
  * [skylight.io](https://www.skylight.io/) — Free for first 100,000 requests (Rails only)
  * [stathat.com](https://www.stathat.com/) — Get started with ten stats for free, no expiration
  * [statuscake.com](https://www.statuscake.com/) — Website monitoring, unlimited tests free with limitations
  * [statusgator.com](https://statusgator.com/) — Status page monitoring, 3 monitors free
  * [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) — Server monitoring, uptime monitoring, DNS & domain monitoring. Monitor 10 server, 10 uptime, and 10 domain for free.
  * [syagent.com](https://syagent.com/) — Noncommercial free server monitoring service, alerts and metrics.
  * [UptimeObserver.com](https://uptimeobserver.com) - Get 20 uptime monitors with 5-minute intervals and a customizable status page—even for commercial use. Enjoy unlimited, real-time notifications via email and Telegram. No credit card needed to get started.
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — Free monitoring for five websites, 60-second intervals, public statuspage.
  * [Wachete](https://www.wachete.com) - monitor five pages, checks every 24 hours.
  * [Xitoring.com](https://xitoring.com/) — Uptime monitoring: 20 free, Linux and Windows Server monitoring: 5 free, Status page: 1 free - Mobile app, multiple notification channel, and much more!

**[⬆️ Back to Top](#table-of-contents)**

## Crash and Exception Handling

  * [Axiom](https://axiom.co/) — Store up to 0.5 TB of logs with 30-day retention. Includes integrations with platforms like Vercel and advanced data querying with email/Discord notifiers.
  * [Bugsink](https://www.bugsink.com/) — Error-tracking with Sentry-SDK compatability. Free for up to 5,000 errors/month, or unlimited use when self-hosted.
  * [bugsnag.com](https://www.bugsnag.com/) — Free for up to 2,000 errors/month after the initial trial
  * [CatchJS.com](https://catchjs.com/) - JavaScript error tracking with screenshots and click trails. Free for open-source projects.
  * [elmah.io](https://elmah.io/) — Error logging and uptime monitoring for web developers. Free Small Business subscription for open-source projects.
  * [Embrace](https://embrace.io/) — Mobile app monitoring. Free for small teams with up to 1 million user sessions per year.
  * [exceptionless](https://exceptionless.com) — Real-time error, feature, log reporting, and more. Free for 3k events per month/1 user. Open source and easy to self-host for unlimited use.
  * [GlitchTip](https://glitchtip.com/) — Simple, open-source error tracking. Compatible with open-source Sentry SDKs. 1000 events per month for free, or can self-host with no limits
  * [honeybadger.io](https://www.honeybadger.io) - Exception, uptime, and cron monitoring. Free for small teams and open-source projects (12,000 errors/month).
  * [Jam](https://jam.dev) - Developer friendly bug reports in one click. Free plan with unlimited jams.
  * [memfault.com](https://memfault.com) — Cloud device observability and debugging platform. 100 devices free for [Nordic](https://app.memfault.com/register-nordic), [NXP](https://app.memfault.com/register-nxp), and [Laird](https://app.memfault.com/register-laird) devices.
  * [rollbar.com](https://rollbar.com/) — Exception and error monitoring, free plan with 5,000 errors/month, unlimited users, 30 days retention
  * [Semaphr](https://semaphr.com) — Free all-in-one kill switch for your mobile apps.
  * [sentry.io](https://sentry.io/) — Sentry tracks app exceptions in real-time and has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted
  * [Whitespace](https://whitespace.dev) – One-click bug reports straight in your browser. Free plan with unlimited recordings for personal use.

**[⬆️ Back to Top](#table-of-contents)**

## Search

  * [algolia.com](https://www.algolia.com/) — Hosted search solution with typo-tolerance, relevance, and UI libraries to easily create search experiences. The free "Build" plan includes 1M documents and 10K searches/month. Also offers [developer documentation search](https://docsearch.algolia.com/) for free.
  * [bonsai.io](https://bonsai.io/) — Free 1 GB memory and 1 GB storage
  * [CommandBar](https://www.commandbar.com/) - Unified Search Bar as-a-service, web-based UI widget/plugin that allows your users to search contents, navigations, features, etc. within your product, which helps discoverability. Free for up to 1,000 Monthly Active Users, unlimited commands.
  * [searchly.com](http://www.searchly.com/) — Free 2 indices and 20 MB storage

**[⬆️ Back to Top](#table-of-contents)**

## Education and Career Development

  * [Cisco Networking Academy, Skills for All](https://skillsforall.com/) - Offers free certification-aligned courses in topics like cybersecurity, networking, and Python.
  * [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - Free short courses from industry-leading experts to get hands-on experience with the latest generative AI tools and techniques in an hour or less.
  * [DevNet Academy](https://devnet-academy.com/) – Free, self-paced training for the Cisco DevNet Expert / CCIE Automation certification. Covers Python Click and Flask-RESTx.
  * [Django-tutorial.dev](https://django-tutorial.dev) - Free online guides for learning Django as their first framework & gives free dofollow backlink to articles written by users.
  * [edX](https://www.edx.org/) - Offers access to over 4,000 free online courses from 250 leading institutions, including Harvard and MIT, specializing in computer science, engineering, and data science.
  * [Exercism](https://exercism.org) – Free, open-source programming education in over 75 programming languages, with human mentoring. A nonprofit organisation.
  * [Free Professional Resume Templates & Editor](https://www.overleaf.com/latex/templates/tagged/cv) - Free platform with lots of Resume templates of Experienced Professionals, ready to clone and edit fully and download, ATS optimized.
  * [FreeCodeCamp](https://www.freecodecamp.org/) - Open-source platform offering free courses and certifications in Data Analysis, Information Security, Web Development, and more.
  * [Full Stack Open](https://fullstackopen.com/en/) – Free university-level course on modern web development with React, Node.js, GraphQL, TypeScript, and more. Fully online and self-paced.
  * [Interactive CV](https://interactive-cv.com) — AI-powered resume builder with real-time editing and ATS optimization. Free tier includes automatic CV conversion to premium templates (Harvard, Europass), PDF export, job tracker with unlimited job posting insights and CV sharing with chat/voice features.
  * [Khan Academy](https://www.khanacademy.org/computing/computer-programming) - Free online guides for learning basic and advanced HTML/CSS, JavaScript and SQL.
  * [LabEx](https://labex.io) - Develop skills in Linux, DevOps, Cybersecurity, Programming, Data Science, and more through interactive labs and real-world projects.
  * [MIT OpenCourseWare](https://ocw.mit.edu/) - MIT OpenCourseWare is an online publication of materials from over 2,500 MIT courses, freely sharing knowledge with learners and educators around the world. Youtube channel can be found at [@mitocw](https://www.youtube.com/@mitocw/featured)
  * [Roadmap.sh](https://roadmap.sh) - Free learning roadmaps covering all aspects of development from Blockchain to UX Design.
  * [The Odin Project](https://www.theodinproject.com/) - Free, open-source platform with a curriculum focused on JavaScript and Ruby for web development.
  * [W3Schools](https://www.w3schools.com/) - Offers free tutorials on web development technologies like HTML, CSS, JavaScript, and more.

**[⬆️ Back to Top](#table-of-contents)**

## Email

  * [10minutemail](https://10minutemail.com) - Free, temporary email for testing.
  * [AhaSend](https://ahasend.com) - Transactional email service, free for 1000 emails per month, with unlimited domains, team members, webhooks and message routes in the free plan.
  * [AnonAddy](https://anonaddy.com) - Open-source anonymous email forwarding, create unlimited email aliases for free
  * [Antideo](https://www.antideo.com) — 10 API requests per hour for email verification, IP, and phone number validation in the free tier. No Credit Cards are required.
  * [Brevo](https://www.brevo.com/) — 9,000 emails/month, 300 emails/day free
  * [Bump](https://bump.email/) - Free 10 Bump email addresses, one custom domain
  * [Burnermail](https://burnermail.io/) – Free 5 Burner Email Addresses, 1 Mailbox, 7-day Mailbox History
  * [Buttondown](https://buttondown.email/) — Newsletter service. Up to 100 subscribers free
  * [Contact.do](https://contact.do/) — Contact form in a link (bitly for contact forms)
  * [debugmail.io](https://debugmail.io/) — Easy to use testing mail server for developers
  * [dkimvalidator.com](https://dkimvalidator.com/) - Test if the email's DNS/SPF/DKIM/DMARC settings are correct, free service by roundsphere.com
  * [DNSExit](https://dnsexit.com/) - Up to 2 Email addresses under your domain for free with 100MB of storage space. IMAP, POP3, SMTP, SPF/DKIM support.
  * [EmailJS](https://www.emailjs.com/) – This is not an entire email server; this is just an email client that you can use to send emails right from the client without exposing your credentials, the free tier has 200 monthly requests, 2 email templates, Requests up to 50Kb, Limited contacts history.
  * [EmailLabs.io](https://emaillabs.io/en) — Send up to 9,000 Emails for free every month, up to 300 emails daily.
  * [EmailOctopus](https://emailoctopus.com) - Up to 2,500 subscribers and 10,000 emails per month free
  * [Emailvalidation.io](https://emailvalidation.io) - 100 free email verifications per month
  * [EtherealMail](https://ethereal.email) - Ethereal is a fake SMTP service, mainly aimed at Nodemailer and EmailEngine users (but not limited to). It's an entirely free anti-transactional email service where messages never get delivered.
  * [forwardemail.net](https://forwardemail.net) — Free email forwarding for custom domains. Create and forward an unlimited amount of email addresses with your domain name (**note**: You must pay if you use .casa, .cf, .click, .email, .fit, .ga, .gdn, .gq, .lat, .loan, .london, .men, .ml, .pl, .rest, .ru, .tk, .top, .work TLDs due to spam)
  * [Imitate Email](https://imitate.email) - Sandbox Email Server for testing email functionality across build/qa and ci/cd. Free accounts get 15 emails a day forever.
  * [ImprovMX](https://improvmx.com) – Free email forwarding.
  * [Inboxes App](https://inboxesapp.com) — Create up to 3 temporary emails a day, then delete them when you're done from within a handy Chrome extension. Perfect for testing signup flows.
  * [inboxkitten.com](https://inboxkitten.com/) - Free temporary/disposable email inbox, with up to 3-day email auto-deletes. Open source and can be self-hosted.
  * [mail-tester.com](https://www.mail-tester.com) — Test if the email's DNS/SPF/DKIM/DMARC settings are correct, 20 free/month.
  * [Maileroo](https://maileroo.com) - SMTP relay and email API for developers. 5,000 emails per month, unlimited domains, free email verification, blacklist monitoring, mail tester and more.
  * [mailcatcher.me](https://mailcatcher.me/) — Catches mail and serves it through a web interface.
  * [mailchannels.com](https://www.mailchannels.com) - Email API with REST API and SMTP integrations, free for upto 3,000 emails/month.
  * [Mailcheck.ai](https://www.mailcheck.ai/) - Prevent users to sign up with temporary email addresses, 120 requests/hour (~86,400 per month)
  * [Maildroppa](https://maildroppa.com) - Up to 100 subscribers and unlimited emails as well as automations for free.
  * [MailerLite.com](https://www.mailerlite.com) — 1,000 subscribers/month, 12,000 emails/month free
  * [MailerSend.com](https://www.mailersend.com) — Email API, SMTP, 3,000 emails/month free for transactional emails
  * [mailinator.com](https://www.mailinator.com/) — Free, public email system where you can use any inbox you want
  * [Mailjet](https://www.mailjet.com/) — 6,000 emails/month free (200 emails daily sending limit)
  * [mailsac.com](https://mailsac.com) - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
  * [Mailtrap.io](https://mailtrap.io/) — Email API, SMTP, 3,500 emails/month free for transactional and marketing emails. Email Sandbox - fake SMTP server for development, free plan with one inbox, 100 messages, no team member, two emails/second, no forward rules.
  * [Mutant Mail](https://www.mutantmail.com/) – Free 10 Email IDs, 1 Domain, 1 Mailbox. Single Mailbox for All Email IDs.
  * [OneSignal](https://onesignal.com/) — 10,000 emails/month,No Credit Cards are required.
  * [Parsio.io](https://parsio.io) — Free email parser (Forward email, extract the data, send it to your server)
  * [Plunk](https://useplunk.com) - 3K emails/month for free
  * [Postmark](https://postmarkapp.com/) - 100 emails/month free, unlimited DMARC weekly digests.
  * [Proton Mail](https://proton.me/mail) -  Free secure email account service provider with built-in end-to-end encryption. Free 1GB storage.
  * [Resend](https://resend.com) - Transactional emails API for developers. 3,000 emails/month, 100 emails/day free, one custom domain.
  * [Sender](https://www.sender.net) Up to 15,000 emails/month, up to 2,500 subscribers
  * [Sendpulse](https://sendpulse.com) — 500 subscribers/month, 15,000 emails/month free
  * [SimpleLogin](https://simplelogin.io/) – Open source, self-hostable email alias/forwarding solution. Free 10 Aliases, unlimited bandwidth, unlimited reply/send. Free for educational staff (student, researcher, etc.).
  * [Substack](https://substack.com) — Unlimited free newsletter service. Start paying when you charge for it.
  * [Sweego](https://www.sweego.io/) - European transactional emails API for developers. 100 emails/day free.
  * [temp-mail.io](https://temp-mail.io) — Free disposable temporary email service with multiple emails at once and forwarding
  * [Temp-Mail.org](https://temp-mail.org/en/) - Temporary / Disposable Mail Gen Utilizing a range variety of domain. Email Address refreshes everytime, the page is reloaded. It is entirely free and does not include any pricing for their services.
  * [TempMailDetector.com](https://tempmaildetector.com/) - Verify up to 200 emails a month for free and see if an email is temporary or not.
  * [trashmail.com](https://www.trashmail.com) - Free disposable email addresses with forwarding and automatic address expiration
  * [Tuta](https://tuta.com/) - Free secure email account service provider with built-in end-to-end encryption, no ads, no tracking. Free 1GB storage, one calendar (Tuta also have an [paid plan](https://tuta.com/pricing).). Tuta is also partially [open source](https://github.com/tutao/tutanota), so you can self-host.
  * [Verifalia](https://verifalia.com/email-verification-api) — Real-time email verification API with mailbox confirmation and disposable email address detector; 25 free email verifications/day.
  * [verimail.io](https://verimail.io/) — Bulk and API email verification service. 100 free verifications/month
  * [Wraps](https://wraps.dev) - email automation workflows, 5k tracked events and unlimited contacts free.

**[⬆️ Back to Top](#table-of-contents)**

## Feature Toggles Management Platforms

  * [Abby](https://www.tryabby.com) - Open-Source feature flags & A/B testing. Configuration as Code & Fully Typed Typescript SDKs. Strong integration with Frameworks such as Next.js & React. Generous free tier and cheap scaling options.
  * [ConfigCat](https://configcat.com) - ConfigCat is a developer-centric feature flag service with unlimited team size, excellent support, and a reasonable price tag. Free plan up to 10 flags, two environments, 1 product, and 5 Million requests per month.
  * [Flagsmith](https://flagsmith.com) - Release features with confidence; manage feature flags across web, mobile, and server-side applications. Use our hosted API, deploy to your own private cloud, or run on-premise.
  * [GrowthBook](https://growthbook.io) - Open source feature flag and A/B testing provider with built-in Bayesian statistical analysis engine. Free for up to 3 users, unlimited feature flags and experiments.
  * [Hypertune](https://www.hypertune.com) - Type-safe feature flags, A/B testing, analytics and app configuration, with Git-style version control and synchronous, in-memory, local flag evaluation. Free for up to 5 team members with unlimited feature flags and A/B tests.
  * [Statsig](https://www.statsig.com) - A robust platform for feature management, A/B testing, analytics, and more. Its generous free plan offers unlimited seats, flags, experiments, and dynamic configurations, supporting up to 1 million events per month.
  * [Toggled.dev](https://www.toggled.dev) - Enterprise-ready, scalable multi-regional feature toggles management platform. Free plan up to 10 flags, two environments, unlimited requests. SDK, analytics dashboard, release calendar, Slack notifications, and all other features are included in the endless free plan.


**[⬆️ Back to Top](#table-of-contents)**

## Font

  * [Befonts](https://befonts.com/) - Provides several unique fonts for personal or commercial use.
  * [Bunny](https://fonts.bunny.net) Privacy oriented Google Fonts
  * [dafont](https://www.dafont.com/) - The fonts presented on this website are their authors' property and are either freeware, shareware, demo versions, or public domain.
  * [Everything Fonts](https://everythingfonts.com/) - Offers multiple tools; @font-face, Units Converter, Font Hinter and Font Submitter.
  * [Font of web](https://fontofweb.com/) - Identify all the fonts used on a website and how they are used.
  * [Font Squirrel](https://www.fontsquirrel.com/) - Freeware fonts licensed for commercial work. Hand-selected these typefaces and presented them in an easy-to-use format.
  * [FontGet](https://www.fontget.com/) - Has a variety of fonts available to download and sorted neatly with tags.
  * [fonts.xz.style](https://fonts.xz.style/) free and open source service for delivering font families to websites using CSS.
  * [Fontsensei](https://fontsensei.com/) Opensourced Google fonts tagged by users. With CJK (Chinese,Japanese,Korean) font tags.
  * [Fontshare](https://www.fontshare.com/) - is a free fonts service. It’s a growing collection of professional-grade fonts, 100% free for personal and commercial use.
  * [Google Fonts](https://fonts.google.com/) - Many free fonts are easy and quick to install on a website via a download or a link to Google's CDN.

**[⬆️ Back to Top](#table-of-contents)**

## Forms

  * [FabForm](https://fabform.io/) - Form backend platform for intelligent developers. The free plan allows 250 form submissions per month. Friendly modern GUI. Integrates with Google Sheets, Airtable, Slack, Email, and others.
  * [Feathery](https://feathery.io) - Powerful, developer-friendly form builder. Build signup & login, user onboarding, payment flows, complex financial applications, and more. The free plan allows up to 250 submissions/month and five active forms.
  * [feedback.fish](https://feedback.fish/) - Free plan allows collecting 25 total feedback submissions. Easy to integrate with React and Vue components provided.
  * [Form.taxi](https://form.taxi/) — Endpoint for HTML forms submissions. With notifications, spam blockers, and GDPR-compliant data processing. Free plan for basic usage.
  * [Formcarry.com](https://formcarry.com) - HTTP POST Form endpoint, Free plan allows 100 monthly submissions.
  * [Formester.com](https://formester.com) - Share and embed unique-looking forms on your website—no limits on the number of forms created or features restricted by the plan. Get up to 100 submissions every month for free.
  * [FormKeep.com](https://www.formkeep.com/) - Unlimited forms with 50 monthly submissions, spam protection, email notification, and a drag-and-drop designer that can export HTML. Additional features include custom field rules, teams, and integrations to Google Sheets, Slack, ActiveCampaign, and Zapier.
  * [formlets.com](https://formlets.com/) — Online forms, unlimited single page forms/month, 100 submissions/month, email notifications.
  * [forms.app](https://forms.app/) — Create online forms with powerful features like conditional logic, automatic score calculator, and AI. Collect up to 100 responses with a free plan, embed your forms on a website, or use them with a link.
  * [formspark.io](https://formspark.io/) -  Form to Email service, free plan allows unlimited forms, 250 submissions per month, support by Customer assistance team.
  * [Formspree.io](https://formspree.io/) — Send email using an HTTP POST request. The free tier limits to 50 submissions per form per month.
  * [Formsubmit.co](https://formsubmit.co/) — Easy form endpoints for your HTML forms. Free Forever. No registration is required.
  * [HeroTofu.com](https://herotofu.com/) - Forms backend with bot detection and encrypted archive. Forward submissions via UI to email, Slack, or Zapier. Use your own front end. No server code is required. The free plan gives unlimited forms and 100 submissions per month.
  * [HeyForm.net](https://heyform.net/) - Drag and drop online form builder. The free tier lets you create unlimited forms and collect unlimited submissions. Comes with pre-built templates, anti-spam, and 100MB file storage.
  * [Kwes.io](https://kwes.io/) - Feature rich form endpoint. Works great with static sites. The free plan includes up to 1 website with up to 50 monthly submissions.
  * [Pageclip](https://pageclip.co/) - The free plan allows one site, one form, and 1,000 monthly submissions.
  * [SimplePDF.eu](https://simplepdf.eu/embed) - Embed a PDF editor on your website and turn any PDF into a fillable form. The free plan allows unlimited PDFs with three submissions per PDF.
  * [smartforms.dev](https://smartforms.dev/) - Powerful and easy form backend for your website, forever free plan allows 50 submissions per month, 250MB file storage, Zapier integration, CSV/JSON export, custom redirect, custom response page, Telegram & Slack bot, single email notifications.
  * [staticforms.xyz](https://www.staticforms.xyz/) - Integrate HTML forms easily without any server-side code for free. After the user submits the form, an email with the form content will be sent to your registered address.
  * [Survicate](https://survicate.com/) — Pull feedback from all sources and send follow-up surveys with one tool. Automatically analyze feedback and extract insights with AI. Free email, website, in-product or mobile surveys, AI survey creator, and 25 monthly responses.
  * [Tally.so](https://tally.so/) - 99% of all the features are free. The free tier lets you have: unlimited forms, unlimited submissions, email notifications, form logic, collect payments, file upload, custom thank you page, and many more.
  * [Typeform.com](https://www.typeform.com/) — Include beautifully designed forms on websites.  The free plan allows only ten fields per form and 100 monthly responses.
  * [Vidhook](https://vidhook.io/) - Collect feedback using delightful surveys with high response rates. Free plan includes 1 active survey, 25 responses per survey and customizable templates.
  * [WaiverStevie.com](https://waiverstevie.com) - Electronic Signature platform with a REST API. You can receive notifications with webhooks. Free plan watermarks signed documents but allow unlimited envelopes + signatures.
  * [Web3Forms](https://web3forms.com) - Contact forms for Static & JAMStack Websites without writing backend code. The free plan allows Unlimited Forms, Unlimited Domains & 250 Submissions per month.
  * [Wufoo](https://www.wufoo.com/) - Quick forms to use on websites. The free plan has a limit of 100 submissions each month.

**[⬆️ Back to Top](#table-of-contents)**

## Generative AI

  * [Arize AX](https://arize.com) - AI engineering platform that helps AI eng/PMs, evaluate, and observe AI applications and agents with built-in Alyx agent. Free product inlcudes 25k spans and ingestion volume of 1gb per month.
  * [Audio Enhancer](https://voice-clone.org/tools/audio-enhancer) — AI-powered audio enhancer SaaS that removes noise and echo while preserving natural vocal clarity. totally Free: unlimited one-click enhancements, no login required, supports MP3/WAV/FLAC
  * [Braintrust](https://www.braintrustdata.com/) - Evals, prompt playground, and data management for Gen AI. Free plan gives upto 1,000 private eval rows/week.
  * [Clair](https://askclair.ai/) - Clinical AI Reference. Students have free access to the professional tool suite, which includes Open Search, Clinical Summary, Med Review, Drug Interactions, ICD-10 Codes, and Stewardship. Additionally, a free trial for the professional suite is available.
  * [Comet Opik](https://www.comet.com/site/products/opik/) - Evaluate, test, and ship LLM applications across your dev and production lifecycles. [#opensource](https://github.com/comet-ml/opik/)
  * [Keywords AI](https://keywordsai.co) - The best LLM monitoring platform. One format to call 200+ LLMs with 2 lines of code. 10,000 free requests every month and $0 for platform features!
  * [Langfuse](https://langfuse.com/) - Open-source LLM engineering platform that helps teams collaboratively debug, analyze, and iterate on their LLM applications. Free forever plan includes 50k observations per month and all platform features. [#opensource](https://github.com/langfuse/langfuse)
  * [Langtrace](https://langtrace.ai) - enables developers to trace, evaluate, manage prompts and datasets, and debug issues related to an LLM application’s performance. It creates open telemetry standard traces for any LLM which helps with observability and works with any observability client. Free plan offers 50K traces/month.
  * [LangWatch](https://langwatch.ai) - A LLMOps platform helping AI teams measure, monitor, and optimize LLM applications for reliability, cost-efficiency, and performance. With a powerful DSPy component, we enable seamless collaboration between engineers and non-technical teams to fine-tune and productionize GenAI products. Free plan includes all platform features, 1k traces/month and 1 workflow DSPy optimizers. [#opensource](https://github.com/langwatch/langwatch)
  * [Mediaworkbench.ai](https://mediaworkbench.ai) - MediaWorkbench.ai offers 100,000 free words for Azure OpenAI, DeepSeek, and Google Gemini models, enabling users to access powerful tools for code generation, deep research, and image creation.
  * [OpenRouter](https://openrouter.ai/models?q=free) - Provides various free AI models including DeepSeek R1, V3, Llama, and Moonshot AI. These models excel in natural language processing and are suitable for diverse development needs. Note that while these models are free to use, they are subject to rate limits. Additionally, OpenRouter offers paid models for more advanced requirements, for instance Claude, OpenAI, Grok, Gemini, and Nova.
  * [Othor AI](https://othor.ai/) - An AI-native fast, simple, and secure alternative to popular business intelligence solutions like Tableau, Power BI, and Looker. Othor utilizes large language models (LLMs) to deliver custom business intelligence solutions in minutes. The Free Forever plan provides one workspace with five datasource connections for one user, with no limits on analytics. [#opensource](https://github.com/othorai/othor.ai)
  * [Pollinations.AI](https://pollinations.ai/) - easy-to-use, free image generation AI with free API available. No signups or API keys required, and several option for integrating into a website or workflow. [#opensource](https://github.com/pollinations/pollinations)
  * [Portkey](https://portkey.ai/) - Control panel for Gen AI apps featuring an observability suite & an AI gateway. Send & log up to 10,000 requests for free every month.
  * [ReportGPT](https://ReportGPT.app) - AI Powered Writing Assistant. The entire platform is free as long as you bring your own API key.
  * [Zenable](https://zenable.io) - Instantly auto-fix outputs from tools like Cursor, Windsurf, and Copilot to meet your company's quality and compliance standards using guardrails built with Policy as Code. The free tier includes 100 tools calls per day to the MCP server and 25 free automated pull request reviews per day via the GitHub App.

**[⬆️ Back to Top](#table-of-contents)**

## CDN and Protection

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — CDN for bootstrap, bootswatch and fontawesome.io
  * [CacheFly](https://portal.cachefly.com/signup/free2023) - Up to 5 TB per month of Free CDN traffic, 19 Core PoPs , 1 Domain and Universal SSL.
  * [cdnjs.com](https://cdnjs.com/) — Simple. Fast. Reliable. Content delivery at its finest. cdnjs is a free and open-source CDN service trusted by over 11% of all websites, powered by Cloudflare.
  * [developers.google.com](https://developers.google.com/speed/libraries/) — The Google Hosted Libraries is a content distribution network for the most popular Open Source JavaScript libraries
  * [Gcore](https://gcorelabs.com/) Global content delivery network, 1 TB and 1 million requests per month free and free DNS hosting
  * [jsdelivr.com](https://www.jsdelivr.com/) — A free, fast, and reliable open-source CDN. Supports npm, GitHub, WordPress, Deno, and more.
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — The Microsoft Ajax CDN hosts popular third-party JavaScript libraries such as jQuery and enables you to easily add them to your Web application
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — Free DDoS protection
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — Free DDoS protection and SSL certificate
  * [PromoProxy](https://promoproxy.net/) - Free cloud Secure Web Gateway. Free plan includes up to 5 users and 1 GB per day.
  * [raw.githack.com](https://raw.githack.com/) — A modern replacement of **rawgit.com** which simply hosts file using Cloudflare
  * [Skypack](https://www.skypack.dev/) — The 100% Native ES Module JavaScript CDN. Free for 1 million requests per domain per month.
  * [statically.io](https://statically.io/) — CDN for Git repos (GitHub, GitLab, Bitbucket), WordPress-related assets, and images
  * [Stellate](https://stellate.co/) - Stellate is a blazing-fast, reliable CDN for your GraphQL API and free for two services.
  * [toranproxy.com](https://toranproxy.com/) — Proxy for Packagist and GitHub. Never fail CD. Free for personal use, one developer, no support
  * [UNPKG](https://unpkg.com/) — CDN for everything on npm
  * [weserv](https://images.weserv.nl/) — An image cache & resize service. Manipulate images on the fly with a worldwide cache.

**[⬆️ Back to Top](#table-of-contents)**

## PaaS

  * [ampt.dev](https://getampt.com/) - Ampt lets teams build, deploy, and scale JavaScript apps on AWS without complicated configs or managing infrastructure. Free Preview plan includes 500 invocations hourly, 2,500 invocations daily and 50,000 invocations monthly. Custom domains are allowed only in the paid plans.
  * [anvil.works](https://anvil.works) - Web app development with nothing but Python. Free tier with unlimited apps and 30-second timeouts.
  * [Apply.build](https://apply.build/) — Build and deploy your GitHub app for free with 0.5 vCPUs / 512 MiB RAM, European servers, automatic firewall, real-time performance metrics. Run Node.js, Python, Go, Java, static sites, microservices, and more.
  * [appwrite](https://appwrite.io) - Unlimited projects with no project pausing (supports websockets) and authentication service. 1 Database, 3 Buckets, 5 Functions per project in free tier.
  * [Choreo](https://wso2.com/choreo/) - AI-native internal developer platform as a service. The free tier includes up to 5 components and $100 credits per month.
  * [codenameone.com](https://www.codenameone.com/) — Open source, cross-platform, mobile app development toolchain for Java/Kotlin developers. Free for commercial use with an unlimited number of projects
  * [Daestro](https://daestro.com) - Run compute jobs across Cloud Providers & On-Prem. The free tier includes up to 10 concurrent job runs, 2 compute spawns, self-hosted compute, 1 cloud provider, 1 container registry and 1 cron job.
  * [Deno Deploy](https://deno.com/deploy) - Distributed system that runs JavaScript, TypeScript, and WebAssembly at the edge worldwide. The free tier includes 100,000 requests per day and 100 GiB data transfers per month.
  * [domcloud.co](https://domcloud.co) – Linux hosting service that provides CI/CD with GitHub, SSH, and MariaDB/Postgres database. The free version has 1 GB storage and 1 GB network/month limit and is limited to a free domain.
  * [encore.dev](https://encore.dev/) — Backend framework using static analysis to provide automatic infrastructure, boilerplate-free code, and more. Includes free cloud hosting for hobby projects.
  * [flightcontrol.dev](https://flightcontrol.dev/) - Deploy web services, databases, and more on your own AWS account with a Git push style workflow. Free tier for users with 1 developer on personal GitHub repos. AWS costs are billed through AWS, but you can use credits and the AWS free tier.
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir provides one free instance that never sleeps and a free-tier PostgreSQL database limited to 2 connections, 10, 000 rows and no backups for Elixir/Phoenix apps.
  * [Koyeb](https://www.koyeb.com) - Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery. Free Instance lets you deploy a web service in Frankfurt, Germany or Washington, D.C., US. Free Managed Postgres database available in Frankfurt (Germany), Washington, D.C. (US), and Singapore. 512MB memory, 2GB storage, and 0.1 CPU.
  * [leapcell](https://leapcell.io/) - Leapcell is a reliable distributed applications platform, providing everything you need to seamlessly support your rapid growth. The free plan includes 100k service invocations, 10k async tasks and 100k Redis commands.
  * [Northflank](https://northflank.com) — Build and deploy microservices, jobs, and managed databases with a powerful UI, API & CLI. Seamlessly scale containers from version control and external Docker registries. The free tier includes two services, two cron jobs and 1 database.
  * [pipedream.com](https://pipedream.com) - An integration platform built for developers. Develop any workflow based on any trigger. Workflows are code you can run [for free](https://docs.pipedream.com/pricing/). No server or cloud resources to manage.
  * [Railway](https://railway.app/) - Deploy anything with git-based deployments, automatic CI/CD, and built-in databases. Free tier includes $5 of credits each month
  * [pythonanywhere.com](https://www.pythonanywhere.com/) — Cloud Python app hosting. Beginner account is free, 1 Python web application at your-username.pythonanywhere.com domain, 512 MB private file storage, one MySQL database
  * [WunderGraph](https://cloud.wundergraph.com) - An open-source platform that allows you to  quickly build, ship and manage modern APIs. Built-in CI/CD, GitHub integration, and automatic HTTPS. Up to 3 projects, 1GB egress, 300 minutes of build time per month on the [free plan](https://wundergraph.com/pricing)
  * [YepCode](https://yepcode.io) - All-in-one platform to connect APIs and services in a serverless environment. It brings all the agility and benefits of NoCode tools but with all the power of using programming languages. The free tier includes [1.000 yeps](https://yepcode.io/pricing/).
  * [Zeabur](https://zeabur.com) - Deploy your services with one click. Free for three services, with US$ 5 free credits per month.

**[⬆️ Back to Top](#table-of-contents)**

## BaaS

  * [Activepieces](https://www.activepieces.com) - Build automation flows to connect several apps together in your app's backend. For example, send a Slack message or add a Google Sheet row when an event fires in your app. Free up to 5,000 tasks per month.
  * [back4app.com](https://www.back4app.com) - Back4App is an easy-to-use, flexible and scalable backend based on Parse Platform.
  * [backendless.com](https://backendless.com/) — Mobile and Web Baas, with 1 GB file storage free, push notifications of 50,000/month, and 1000 data objects in the table.
  * [bismuth.cloud](https://www.bismuth.cloud/) — Our AI will boostrap your Python API on our function runtime and hosted storage, build and host for free in our online editor or locally with your favorite tools.
  * [Claw.cloud](https://run.claw.cloud) - A PaaS platform offering $5/month in free credits for users with a GitHub account older than 180 days. Perfect for hosting apps, databases, and more. ([Signup Link with free credit](https://ap-southeast-1.run.claw.cloud/signin)).
  * [connectycube.com](https://connectycube.com) - Unlimited chat messages, p2p voice & video calls, files attachments and push notifications. Free for apps up to 1000 users.
  * [convex.dev](https://convex.dev/) - Reactive backend as a service, hosting your data (documents with relationships & serializable ACID transactions), serverless functions, and WebSockets to stream updates to various clients. Free for small projects - up to 1M records, 5M monthly function calls.
  * [ETLR](https://etlr.io) - Define, version, and deploy automation scripts using YAML. A developer-first alternative to drag-and-drop tools. Can be used for scheduled tasks, AI agents, and infrastructure monitoring. Free tier includes 100 credits/month.
  * [Flutter Flow](https://flutterflow.io) — Build your Flutter App UI without writing a single line of code. Also has a Firebase integration. The free plan includes full access to UI Builder and Free templates.
  * [getstream.io](https://getstream.io/) — Build scalable In-App Chat, Messaging, Video and audio, and Feeds in a few hours instead of weeks
  * [IFTTT](https://ifttt.com) — Automate your favorite apps and devices. Free 2 Applets
  * [Integrately](https://integrately.com) — Automate tedious tasks with a single click. Free 100 Tasks, 15 Minute
  * [LeanCloud](https://leancloud.app/) — Mobile backend. 1GB of data storage, 256MB instance, 3K API requests/day, and 10K pushes/day are free. (API is very similar to Parse Platform)
  * [nhost.io](https://nhost.io) - Serverless backend for web and mobile apps. The free plan includes PostgreSQL, GraphQL (Hasura), Authentication, Storage, and Serverless Functions.
  * [onesignal.com](https://onesignal.com/) — Unlimited free push notifications. 10,000 email sends per month, with unlimited contacts and access to Auto Warm Up.
  * [paraio.com](https://paraio.com) — Backend service API with flexible authentication, full-text search and caching. Free for one app, 1GB of app data.
  * [pubnub.com](https://www.pubnub.com/) — Free push notifications for up to 1 million messages/month and 100 active daily devices
  * [pushbots.com](https://pushbots.com/) — Push notification service. Free for up to 1.5 million pushes/month
  * [pusher.com](https://pusher.com/beams) — Free, unlimited push notifications for 2000 monthly active users. A single API for iOS and Android devices.
  * [simperium.com](https://simperium.com/) — Move data everywhere instantly and automatically, multi-platform, unlimited sending and storage of structured data, max. 2,500 users/month
  * [Supabase](https://supabase.com) — The Open Source Firebase Alternative to build backends. Free Plan offers Authentication, Realtime Database & Object Storage.
  * [tyk.io](https://tyk.io/) — API management with authentication, quotas, monitoring and analytics. Free cloud offering
  * [zapier.com](https://zapier.com/) — Connect the apps you use to automate tasks. Five zaps every 15 minutes and 100 tasks/month
Update Time, five active automations, webhooks.


**[⬆️ Back to Top](#table-of-contents)**

## Low-code Platform

  * [appsmith](https://www.appsmith.com/) — Low code project to build admin panels, internal tools, and dashboards. Integrates with 15+ databases and any API.
  * [BudiBase](https://budibase.com/) — Budibase is an open-source low-code platform for creating internal apps in minutes. Supports PostgreSQL, MySQL, MSSQL, MongoDB, Rest API, Docker, K8s
  * [Clappia](https://www.clappia.com) — A low-code platform designed for building business process applications with customizable mobile and web apps. Offers a drag-and-drop interface, features like Offline Support, real-time location tracking and integration with various third-party services
  * [lil'bots](https://www.lilbots.io/) - write and run scripts online utilizing free built-in APIs like OpenAI, Anthropic, Firecrawl and others. Great for building AI agents / internal tooling and sharing with team. Free-tier includes full access to APIs, AI coding assistant and 10,000 execution credits / month.
  * [manubes](https://www.manubes.com) - Powerful no-code cloud platform with a focus on industrial production management. Free for one user with 1 million workflow activities a month ([also available in german](https://www.manubes.de)).
  * [Mendix](https://www.mendix.com/) — Rapid Application Development for Enterprises, unlimited accessible sandbox environments supporting total users, 0.5 GB storage and 1 GB RAM per app. Also, Studio and Studio Pro IDEs are allowed in the free tier.
  * [outsystems.com](https://www.outsystems.com/) — Enterprise web development PaaS for on-premise or cloud, free "personal environment" offering allows for unlimited code and up to 1 GB database
  * [ReTool](https://retool.com/) — Low-code platform for building internal applications. Retool is highly hackable. If you can write it with JavaScript and an API, you can make it in Retool. The free tier allows up to five users per month, unlimited apps and API connections.
  * [ToolJet](https://www.tooljet.com/) — Extensible low-code framework for building business applications. Connect to databases, cloud storages, GraphQL, API endpoints, Airtable, etc., and build apps using drag-and-drop application builder.
  * [UI Bakery](https://uibakery.io) — Low-code platform that enables faster building of custom web applications. Supports building UI using drag and drop with a high level of customization through JavaScript, Python, and SQL. Available as both cloud and self-hosted solutions. Free for up to 5 users.

**[⬆️ Back to Top](#table-of-contents)**

## Web Hosting

  * [Alwaysdata](https://www.alwaysdata.com/) — 1 GB free web hosting with support for MySQL, PostgreSQL, RabbitMQ, .NET, Deno, Elixir, Go, Java, Lua, Node.js, PHP, Python, Ruby, Rust. Custom web servers, access via FTP, WebDAV and SSH. Mailbox, mailing list and app installer included. No custom domain on free plan.
  * [Awardspace.com](https://www.awardspace.com) — Free web hosting + a free short domain, PHP, MySQL, App Installer, Email Sending & No Ads.
  * [Bubble](https://bubble.io/) — Visual programming to build web and mobile apps without code, free with Bubble branding.
  * [dAppling Network](https://www.dappling.network/) - Decentralized web hosting platform for Web3 frontends focusing on increasing uptime and security and providing an additional access point for users.
  * [DigitalOcean](https://www.digitalocean.com/pricing) - Build and deploy three static sites for free on the App Platform Starter tier.
  * [FreeFlarum](https://freeflarum.com/) - Community-powered free Flarum hosting for up to 250 users (donate to remove the watermark from the footer).
  * [Kinsta Static Site Hosting](https://kinsta.com/static-site-hosting/) — Deploy up to 100 static sites for free, custom domains with SSL, 100 GB monthly bandwidth, 260+ Cloudflare CDN locations.
  * [MDB GO](https://mdbgo.com/) - Free hosting for one project with two weeks Container TTL, 500 MB RAM per project, SFTP - 1G disk space.
  * [Neocities](https://neocities.org) — Static, 1 GB free storage with 200 GB Bandwidth.
  * [Netlify](https://www.netlify.com/) — Builds, deploys and hosts static site/app free for 300 credits/month (equals 30 GB bandwidth).
  * [Oaysus](https://oaysus.com) - Visual page builder for developer-built React, Vue, or Svelte components. Free tier includes 1 site with unlimited pages, form submissions, and global CDN hosting.
  * [PandaStack](https://www.pandastack.io/) — An eco-system for developers includes web hosting in different formats (static web hosting, container based web hosting, wordpress and so many other managed apps available in couple of clicks ). One free web hosting (static or containered) and one free database with 100GB Bandwidth and 300 Build mins/month.
  * [pantheon.io](https://pantheon.io/) — Drupal and WordPress hosting, automated DevOps, and scalable infrastructure. Free for developers and agencies. No custom domain.
  * [Qoddi](https://qoddi.com) - PaaS service similar to Heroku with a developer-centric approach and all-inclusive features. Free tier for static assets, staging, and developer apps.
  * [readthedocs.org](https://readthedocs.org/) — Free documentation hosting with versioning, PDF generation, and more
  * [render.com](https://render.com) — Unified cloud to build and run apps and sites with free SSL, a global CDN, private networks, auto-deploys from Git, and completely free plans for web services, databases, and static web pages.
  * [Serv00.com](https://serv00.com/) — 3 GB of free web hosting with daily backups (7 days). Support: Crontab jobs, SSH access, repositories (GIT, SVN, and Mercurial), support: MySQL, PostgreSQL, MongoDB, PHP, Node.js, Python, Ruby, Java, Perl, TCL/TK, Lua, Erlang, Rust, Pascal, C, C++, D, R, and many more.
  * [SourceForge](https://sourceforge.net/) — Find, Create, and Publish Open Source software for free
  * [surge.sh](https://surge.sh/) — Static web publishing for Front-End developers. Unlimited sites with custom domain support
  * [tilda.cc](https://tilda.cc/) — One site, 50 pages, 50 MB storage, only the main pre-defined blocks among 170+ available, no fonts, no favicon, and no custom domain
  * [Vercel](https://vercel.com/) — Build, deploy, and host web apps with free SSL, global CDN, and unique Preview URLs each time you `git push`. Perfect for Next.js and other Static Site Generators.
  * [Versoly](https://versoly.com/) — SaaS-focused website builder - unlimited websites, 70+ blocks, five templates, custom CSS, favicon, SEO and forms. No custom domain.

**[⬆️ Back to Top](#table-of-contents)**

## DNS

  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Free public DNS Resolver, which is fast and secure (encrypt your DNS query), provided by Cloudflare. Useful to bypass your internet provider's DNS blocking, prevent DNS query spying, and [to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families). It can also be used [via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests). Note: Just a DNS resolver, not a DNS hoster.
  * [1984.is](https://www.1984.is/product/freedns/) — Free DNS service with API and lots of other free DNS features included.
  * [cloudns.net](https://www.cloudns.net/) — Free DNS hosting up to 1 domain with 50 records
  * [deSEC](https://desec.io) - Free DNS hosting with API support, designed with security in mind. Runs on open-source software and is supported by [SSE](https://www.securesystems.de/).
  * [dns.he.net](https://dns.he.net/) — Free DNS hosting service with Dynamic DNS Support
  * [dnspod.com](https://www.dnspod.com/) — Free DNS hosting.
  * [duckdns.org](https://www.duckdns.org/) — Free DDNS with up to 5 domains on the free tier. With configuration guides for various setups.
  * [Dynv6.com](https://dynv6.com/) — Free DDNS service with [API support](https://dynv6.com/docs/apis) and management of a lot of dns record types (like CNAME, MX, SPF, SRV, TXT and others).
  * [freedns.afraid.org](https://freedns.afraid.org/) — Free DNS hosting. Also, provide free subdomains based on numerous public user [contributed domains](https://freedns.afraid.org/domain/registry/). Get free subdomains from the "Subdomains" menu after signing up.
  * [Glauca](https://docs.glauca.digital/hexdns/) – Free DNS hosting for up to 3 domains and DNSSEC support
  * [Hetzner](https://www.hetzner.com/dns-console) – Free DNS hosting from Hetzner with API support.
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – Free DNS hosting by Huawei
  * [LocalCert](https://localcert.net) - Free `.localcert.net` subdomains compatible with public CAs for use with-in private networks
  * [luadns.com](https://www.luadns.com/) — Free DNS hosting, three domains, all features with reasonable limits
  * [namecheap.com](https://www.namecheap.com/domains/freedns/) — Free DNS. No limit on the number of domains
  * [nextdns.io](https://nextdns.io) - DNS-based firewall, 300K free queries monthly
  * [noip.at](https://noip.at/) — Free DDNS service without registration, tracking, logging or advertising. No limit to domains.
  * [noip](https://www.noip.com/) — a dynamic DNS service that allows up to 3 hostnames free with confirmation every 30 days
  * [sslip.io](https://sslip.io/) — Free DNS service that when queried with a hostname with an embedded IP address returns that IP address.
  * [VolaryDDNS](https://volaryddns.net) - Free high-performant DDNS with no subscriptions or advertisements
  * [zilore.com](https://zilore.com/en/dns) — Free DNS hosting for 5 domains.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — Free DNS hosting with Dynamic DNS Support.
  * [Zonomi](https://zonomi.com/) — Free DNS hosting service with instant DNS propagation. Free plan: 1 DNS zone (domain name) with up to 10 DNS records.

**[⬆️ Back to Top](#table-of-contents)**

## Domain

  * [DigitalPlat](https://domain.digitalplat.org) — Free subdomains.
  * [isroot.in](https://isroot.in) — Free isroot.in subdomains.
  * [pp.ua](https://nic.ua/) — Free pp.ua subdomains.

**[⬆️ Back to Top](#table-of-contents)**

## IaaS

  * [4EVERLAND](https://www.4everland.org/) — Compatible with AWS S3 - APIs, interface operations, CLI, and other upload methods, upload and store files from the IPFS and Arweave networks in a safe, convenient, and efficient manner. Registered users can get 6 GB of IPFS storage and 300MB of Arweave storage for free. Any Arweave file uploads smaller than 150 KB are free.
  * [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 cloud storage. Free 10 GB (Amazon S3-like) object storage for unlimited time
  * [C2 Object Storage](https://c2.synology.com/en-us/pricing/object-storage) - S3 compatibility object storage. 15 GB free storage and 15 GB downloads per month.
  * [filebase.com](https://filebase.com/) - S3 Compatible Object Storage Powered by Blockchain. 5 GB free storage for an unlimited duration.

**[⬆️ Back to Top](#table-of-contents)**

## Managed Data Services

  * [8base.com](https://www.8base.com/) - 8base is a full-stack low-code development platform built for JavaScript developers built on top of MySQL and GraphQL and serverless backend-as-a-service. It allows you to start building web applications quickly using a UI app builder and scale quickly, The Free tier includes rows: 2,500, Storage: 500, Serverless computing: 1Gb/h, and client app users: 5.
  * [airtable.com](https://airtable.com/) — Looks like a spreadsheet, but it's a relational database unlimited bases, 1,200 rows/base, and 1,000 API requests/month
  * [Aiven](https://aiven.io/) - Aiven offers free PostgreSQL, MySQL and Valkey (Redis compatible) plans on its open-source data platform. Single node, 1 CPU, 1GB RAM, and for PostgreSQL and MySQL, 1GB storage. Easy migration to more extensive plans or across clouds.
  * [CockroachDB Cloud](https://www.cockroachlabs.com/pricing/) — Free tier offers 50 million RUs and 10 GiB of storage (same as 15$ worth) free per month. ([What's the Request Units](https://www.cockroachlabs.com/docs/cockroachcloud/metrics-request-units.html))
  * [codehooks.io](https://codehooks.io/) — Easy to use JavaScript serverless API/backend and NoSQL database service with functions, Mongdb-ish queries, key/value lookups, a job system, realtime messages, worker queues, a powerful CLI and a web-based data manager. Free plan has 5GB storage and 60/API calls per minute. 2 developers included. No credit-card required.
  * [Couchbase Capella](https://www.couchbase.com/products/capella/) - deploy a forever free tier fully managed database cluster with 1 node and 8GB storage, built for developers to create the next generation of applications across IoT to AI
  * [CrateDB](https://crate.io/) - Distributed Open Source SQL database for real-time analytics. [Free Tier CRFREE](https://crate.io/lp-crfree): One-node with 2 CPUs, 2 GiB of memory, 8 GiB of storage. One cluster per organization, no payment method needed.
  * [filess.io](https://filess.io) - filess.io is a platform where you can create two databases with up to 10 MB per database of the following DBMS for free: MySQL, MariaDB, MongoDB, and PostgreSQL.
  * [InfluxDB](https://www.influxdata.com/) — Timeseries database, free up to 3MB/5 minutes writes, 30MB/5 minutes reads and 10,000 cardinalities series
  * [MemCachier](https://www.memcachier.com/) — Managed Memcache service. Free for up to 25MB, 1 Proxy Server, and basic analytics
  * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — free tier gives 512 MB
  * [Neo4j Aura](https://neo4j.com/cloud/aura/) — Managed native Graph DBMS / analytics platform with a Cypher query language and a REST API. Limits on graph size (50k nodes, 175k relationships).
  * [Neon](https://neon.tech/) — Managed PostgreSQL, 0.5 GB of storage (total), 1 Project ,10 branches, Unlimited Databases, always-available primary branch ( Auto suspend after 5 minutes), 20 hours of Active time per month (total) for non-primary branch compute.
  * [Nile](https://www.thenile.dev/) — A Postgres platform for B2B apps. Unlimited databases, Always available with no shutdown, 1GB of storage (total), 50 million query tokens, autoscaling, unlimited vector embeddings
  * [Prisma Postgres](https://prisma.io/postgres) - Super fast hosted Postgres built on unikernels and running on bare metal, 1GB storage, 10 databases, integrated with Prisma ORM.
  * [restdb.io](https://restdb.io/) - a fast and straightforward NoSQL cloud database service. With restdb.io you get schema, relations, automatic REST API (with MongoDB-like queries), and an efficient multi-user admin UI for working with data. The free plan allows 3 users, 2500 records, and 1 API request per second.
  * [scalingo.com](https://scalingo.com/) — Primarily a PaaS but offers a 128MB to 192MB free tier of MySQL, PostgreSQL, or MongoDB
  * [SeaTable](https://seatable.io/) — Flexible, Spreadsheet-like Database built by the Seafile team. unlimited tables, 2,000 lines, 1-month versioning, up to 25 team members.
  * [skyvia.com](https://skyvia.com/) — Cloud Data Platform offers a free tier and all plans are completely free while in beta
  * [StackBy](https://stackby.com/) — One tool that combines spreadsheets' flexibility, databases' power, and built-in integrations with your favorite business apps. The free plan includes unlimited users, ten stacks, and a 2GB attachment per stack.
  * [Tinybird](https://tinybird.co) - A serverless managed ClickHouse with connection-less data ingest over HTTP and lets you publish SQL queries as managed HTTP APIs. There is no time limit on free-tier, 10GB storage + 1000 API requests per day.
  * [Turso by ChiselStrike](https://chiselstrike.com/) - Turso is SQLite Developer Experience in an Edge Database. Turso provides a Free Forever starter plan, 9 GB of total storage, Up to 500 databases, Up to 3 locations, 1 billion row reads per month, and Local development support with SQLite.
  * [Upstash](https://upstash.com/) — Serverless Redis with free tier up to 500K monthly commands, 256MB max database size, and 20 concurrent connections
  * [Xata Lite](https://lite.xata.io/) - Xata Lite is a serverless database with built-in powerful search and analytics. One API, multiple type-safe client libraries, and optimized for your development workflow. The free plan provides 10 branches and 15 GB of storage without pausing or cold starts.

**[⬆️ Back to Top](#table-of-contents)**

## Tunneling, WebRTC, Web Socket Servers and Other Routers

  * [btunnel](https://www.btunnel.in/) — Expose localhost and local tcp server to the internet. Free plan includes file server, custom http request and response headers, basic auth protection and 1 hour tunnel timeout.
  * [cname.dev](https://cname.dev/) — Free and secure dynamic reverse proxy service.
  * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio extension to expose IIS Express to the local network or over a tunnel to a public URL.
  * [Expose](https://expose.dev/) - Expose local sites via secure tunnels. The free plan includes an EU Server, Random subdomains, and Single users.
  * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi is a hosted VPN service that lets you securely extend LAN-like networks to distributed teams with a free plan that allows unlimited networks with up to 5 people
  * [Hookdeck](https://hookdeck.com/pricing) — Develop, test, and monitor your webhooks from anywhere. 100K requests and 100K attempts per month with three days retention.
  * [localhost.run](https://localhost.run/) — Expose locally running servers over a tunnel to a public URL.
  * [localtunnel](https://theboroer.github.io/localtunnel-www/) — Expose locally running servers over a tunnel to a public URL. Free hosted version, and [open source](https://github.com/localtunnel/localtunnel).
  * [LocalXpose](https://localxpose.io) — Reverse proxy that enables you to expose your localhost servers to the internet. The free plan has 15 minutes tunnel lifetime.
  * [ngrok.com](https://ngrok.com/) — Expose locally running servers over a tunnel to a public URL.
  * [Pinggy](https://pinggy.io) — Public URLs for localhost with a single command, no downloads required. HTTPS / TCP / TLS tunnels. The free plan has 60 minutes tunnel lifetime.
  * [Radmin VPN](https://www.radmin-vpn.com/) — Connect multiple computers together via a VPN-enabling LAN-like network. Unlimited peers. (Hamachi alternative)
  * [serveo](https://serveo.net/) — Expose local servers to the internet. No installation, no signup. Free subdomain, no limits.
  * [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp) Twilio STUN
  * [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302) - Google STUN
  * [Tailscale](https://tailscale.com/) — Zero config VPN, using the open-source WireGuard protocol. Installs on MacOS, iOS, Windows, Linux, and Android devices. Free plan for personal use with 100 devices and three users.
  * [webhookrelay.com](https://webhookrelay.com) — Manage, debug, fan-out, and proxy all your webhooks to public or internal (i.e. localhost) destinations. Also, expose servers running in a private network over a tunnel by getting a public HTTP endpoint (`https://yoursubdomain.webrelay.io <----> http://localhost:8080`).
  * [Xirsys](https://www.xirsys.com/pricing/) — Unlimited STUN usage + 500 MB monthly TURN bandwidth, capped bandwidth, single geographic region.
  * [ZeroTier](https://www.zerotier.com) — FOSS managed virtual Ethernet as a service. Unlimited end-to-end encrypted networks of 25 clients on the free plan. Clients for desktop/mobile/NA; web interface for configuration of custom routing rules and approval of new client nodes on private networks

**[⬆️ Back to Top](#table-of-contents)**

## Issue Tracking and Project Management

  * [acunote.com](https://www.acunote.com/) — Free project management and SCRUM software for up to 5 team members
  * [asana.com](https://asana.com/) — Free for private project with collaborators
  * [Backlog](https://backlog.com) — Everything your team needs to release great projects in one platform. The free plan offers 1 Project with ten users & 100MB of storage.
  * [Basecamp](https://basecamp.com/personal) - To-do lists, milestone management, forum-like messaging, file sharing, and time tracking. Up to 3 projects, 20 users, and 1GB of storage space.
  * [bitrix24.com](https://www.bitrix24.com/) — Intranet and project management tool. The free plan has 5GB for unlimited users.
  * [cacoo.com](https://cacoo.com/) — Online real-time diagrams: flowchart, UML, network. Free max. 15 users/diagram, 25 sheets
  * [clickup.com](https://clickup.com/) — Project management. Free, premium version with cloud storage. Mobile applications and Git integrations are available.
  * [Clockify](https://clockify.me) - Time tracker and timesheet app that lets you track work hours across projects. Unlimited users, free forever.
  * [Cloudcraft](https://cloudcraft.co/) — Design a professional architecture diagram in minutes with the Cloudcraft visual designer, optimized for AWS with intelligent components that show live data too. Free plan has unlimited private diagrams for single user.
  * [Confluence](https://www.atlassian.com/software/confluence) - Atlassian's content collaboration tool is used to help teams collaborate and share knowledge efficiently. Free plan for up to 10 users.
  * [Crosswork](https://crosswork.app/) - Versatile project management platform. Free for up to 3 projects, unlimited users, 1 GB storage.
  * [diagrams.net](https://app.diagrams.net/) — Online diagrams stored locally in Google Drive, OneDrive, or Dropbox. Free for all features and storage levels
  * [easyretro.io](https://www.easyretro.io/) — Simple and intuitive sprint retrospective tool. The free plan has three public boards and one survey per board per month.
  * [freedcamp.com](https://freedcamp.com/) - tasks, discussions, milestones, time tracking, calendar, files and password manager. Free plan with unlimited projects, users, and file storage.
  * [GForge](https://gforge.com) — Project Management and issue Tracking toolset for complex projects with self-premises and SaaS options. SaaS free plan offers the first five users free & free for Open Source Projects.
  * [gleek.io](https://www.gleek.io) — Free description-to-diagrams tool for developers. Create informal UML class, object, or entity-relationship diagrams using your keyword.
  * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector outputs a list of changes between two GraphQL schemas. Every difference is precisely explained and marked as breaking, non-breaking, or dangerous.
  * [Helploom](https://helploom.com) - Customer support software that offers a live chat on the free forever plan. Simple, lightweight and beautiful. Setup is a simple copy-paste script. Built by a developer.
  * [Hygger](https://hygger.io) — Project management platform. The free plan offers unlimited users, projects & boards with 100 MB of Storage.
  * [Ilograph](https://www.ilograph.com/)  — interactive diagrams that allow users to see their infrastructure from multiple perspectives and levels of detail. Charts can be expressed in code. The free tier has unlimited private diagrams with up to 3 viewers.
  * [Jira](https://www.atlassian.com/software/jira) — Advanced software development project management tool used in many corporate environments. Free plan for up to 10 users.
  * [kan.bn](https://kan.bn/) - A powerful, flexible kanban app that helps you organise work, track progress, and deliver results—all in one place. Free plan up to 1 user for unlimited boards, unlimited lists, unlimited cards.
  * [kanbanflow.com](https://kanbanflow.com/) — Board-based project management. Free, premium version with more options
  * [kanbantool.com](https://kanbantool.com/) — Kanban board-based project management. The free plan has two boards and two users, without attachments or files.
  * [Kitemaker.co](https://kitemaker.co) - Collaborate through all phases of the product development process and keep track of work across Slack, Discord, Figma, and Github. Unlimited users, unlimited spaces. Free plan up to 250 work items.
  * [Kiter.app](https://www.kiter.app/) - Let anyone organize their job search and track interviews, opportunities, and connections. Powerful web app and Chrome extension. Completely free.
  * [Kumu.io](https://kumu.io/)  — Relationship maps with animation, decorations, filters, clustering, spreadsheet imports, etc. The free tier allows unlimited public projects. Graph size unlimited. Free private projects for students. Sandbox mode is available if you prefer not to leave your file publicly online (upload, edit, download, discard).
  * [leiga.com](https://www.leiga.com/) — Leiga is a SaaS product that uses AI to automatically manage your projects, helping your team stay focused and unleash immense potential, ensuring your projects progress as planned. Free for up to 10 users, 20 custom fields, 2GB of storage space, Video Recording with AI limited to 5 mins/video, Automation Runs at 20/user/month.
  * [Linear](https://linear.app/) — Issue tracker with a streamlined interface. Free for unlimited members, up to 10MB file upload size, 250 issues (excluding Archive)
  * [Lucidchart](https://www.lucidchart.com/) - An online diagram tool with collaboration features. Free plan with three editable documents, 100 professional templates, and basic collaboration features.
  * [MeisterTask](https://www.meistertask.com/) — Online task management for teams. Free up to 3 projects and unlimited project members.
  * [MeuScrum](https://www.meuscrum.com/en) - Free online scrum tool with kanban board
  * [nTask](https://www.ntaskmanager.com/) — Project management software that enables your teams to collaborate, plan, analyze, and manage everyday tasks. The essential plan is free forever with 100 MB storage and five users/teams. Unlimited workspaces, meetings, assignments, timesheets, and issue tracking.
  * [Plane](https://plane.so/) - Plane is a simple, extensible, open-source project and product management tool. Free for unlimited members, up to 5MB file upload size, 1000 issues.
  * [planitpoker.com](https://www.planitpoker.com/) — Free online planning poker (estimation tool)
  * [point.poker](https://www.point.poker/) - Online Planning Poker (consensus-based estimation tool). Free for unlimited users, teams, sessions, rounds, and votes. You don't need to register.
  * [Pulse.red](https://pulse.red) — Free Minimalistic Time Tracker and Timesheet app for projects.
  * [ScrumFast](https://www.scrumfast.com) - Scrum board with a very intuitive interface, free up to 5 users.
  * [Sflow](https://sflow.io) — sflow.io is a project management tool built for agile software development, marketing, sales, and customer support, especially for outsourcing and cross-organization collaboration projects. Free plan up to 3 projects and five members.
  * [Shake](https://www.shakebugs.com/) - In-app bug reporting and feedback tool for mobile apps. Free plan, ten bug reports per app/month.
  * [Shortcut](https://shortcut.com/) - Project management platform. Free for up to 10 users forever.
  * [taiga.io](https://taiga.io/) — Project management platform for startups and agile developers, free for Open Source
  * [taskade.com](https://www.taskade.com/) — Real-time collaborative task lists and team outlines. The free plan has one workspace with unlimited tasks and projects; 1GB file storage; 1-week project history; and five attendees per video meeting.
  * [Teaminal](https://www.teaminal.com) - Standup, retro, and sprint planning tool for remote teams. Free for up to 15 users.
  * [teamwork.com](https://teamwork.com/) — Project management & Team Chat. Free for five users and two projects. Premium plans are available.
  * [teleretro.com](https://www.teleretro.com/) — Simple and fun retrospective tool with icebreakers, gifs and emojis. The free plan includes three retros and unlimited members.
  * [Tenzu](https://tenzu.net/) — Lightweight project management tool for agile teams. The SaaS relies on free contributions; users can always choose to give 0 and there is no features paywall {[more details](https://tenzu.net/pricing/)}
  * [titanapps.io](https://titanapps.io/) — productivity tools for Jira and monday.com offering structured checklists, templates, and approvals inside issues/tasks. Free plan available for small teams.
  * [todoist.com](https://todoist.com/) — Collaborative and individual task management. The free plan has: 5 active projects, five users in the project, file uploading up to 5MB, three filters, and one week of activity history.
  * [Toggl](https://toggl.com/) — Provides two free productivity tools. [Toggl Track](https://toggl.com/track/) for time management and tracking app with a free plan provides seamless time tracking and reporting designed with freelancers in mind. It has unlimited tracking records, projects, clients, tags, reporting, and more. And [Toggl Plan](https://toggl.com/plan/) for task planning with a free plan for solo developers with unlimited tasks, milestones, and timelines.
  * [trello.com](https://trello.com/) — Board-based project management. Unlimited Personal Boards, 10 Team Boards.
  * [Tweek](https://tweek.so/) — Simple Weekly To-Do Calendar & Task Management.
  * [Wikifactory](https://wikifactory.com/) — Product designing Service with Projects, VCS & Issues. The free plan offers unlimited projects & collaborators and 3GB storage.
  * [Yodiz](https://www.yodiz.com/) — Agile development and issue tracking. Free up to 3 users, unlimited projects.
  * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — Free hosted YouTrack (InCloud) for FOSS projects and private projects (free for three users). Includes time tracking and agile boards
  * [zenhub.com](https://www.zenhub.com) — The only project management solution inside GitHub. Free for public repos, OSS, and nonprofit organizations
  * [zenkit.com](https://zenkit.com) — Project management and collaboration tool. Free for up to 5 members, 5 GB attachments.
  * [Zube](https://zube.io) — Project management with free plan for 4 Projects & 4 users. GitHub integration is available.

**[⬆️ Back to Top](#table-of-contents)**

## Storage and Media Processing

  * [AndroidFileHost](https://androidfilehost.com/) - Free file-sharing platform with unlimited speed, bandwidth, file count, download count, etc. It is mainly aimed for Android dev-related files like APK build, custom ROM & modifications, etc. But seems to accept any other files as well.
  * [borgbase.com](https://www.borgbase.com/) — Simple and secure offsite backup hosting for Borg Backup. 10 GB free backup space and two repositories.
  * [cloudinary.com](https://cloudinary.com/) — Image upload, powerful manipulations, storage, and delivery for sites and apps, with Ruby, Python, Java, PHP, Objective-C, and more libraries. The free tier includes 25 monthly credits. One credit equals 1,000 image transformations, 1 GB of storage, or 1 GB of CDN usage.
  * [degoo.com](https://degoo.com/) – AI based cloud storage with free up to 20 GB, three devices, 5 GB referral bonus (90 days account inactivity).
  * [Dropshare](https://dropsha.re) - Zero-knowledge file sharing. End-to-end encrypted file sharing with AES-256-GCM encryption, client-side processing, and zero server-side data access. Free uploads for files up to 1GB with no data collection.
  * [embed.ly](https://embed.ly/) — Provides APIs for embedding media in a webpage, responsive image scaling, and extracting elements from a webpage. Free for up to 5,000 URLs/month at 15 requests/second
  * [Ente](https://ente.io/) - Ente is an end-to-end encrypted cloud for photos, videos and 2FA secrets. Can also be self-hosted along with a generous forever free-tier of 10GB. For free tier users, only single replica of data is kept.
  * [file.io](https://www.file.io) - 2 GB storage of files. A file is auto-deleted after one download. REST API to interact with the storage. Rate limit one request/minute.
  * [freetools.site](https://freetools.site/) — Free online tools. Convert or edit documents, images, audio, video, and more.
  * [getpantry.cloud](https://getpantry.cloud/) — A simple JSON data storage API perfect for personal projects, hackathons, and mobile apps!
  * [GoFile.io](https://gofile.io/) - Free file sharing and storage platform can be used via web-based UI & also API. unlimited file size, bandwidth, download count, etc. But it will be deleted when a file becomes inactive (no download for more than ten days).
  * [gumlet.com](https://www.gumlet.com/) — Image and video hosting, processing and streaming via CDN. Provides generous free tier of 250 GB / month for videos and 30 GB  / month for images.
  * [icedrive.net](https://www.icedrive.net/) - Simple cloud storage service. 10 GB free storage
  * [image-charts.com](https://www.image-charts.com/) — Unlimited image chart generation with a watermark
  * [ImageEngine](https://imageengine.io/) – ImageEngine is an easy to use global image CDN. Sub 60 sec setup. AVIF and JPEGXL support, WordPress-, Magento-, React-, Vue- plugins and more. Claim your free developer account [here](https://imageengine.io/developer-program/).
  * [imagekit.io](https://imagekit.io) – Image CDN with automatic optimization, real-time transformation, and storage that you can integrate with existing setup in minutes. The free plan includes up to 20GB of bandwidth per month.
  * [ImgBB](https://imgbb.com/) — ImgBB is an unlimited image hosting servce. Drag and drop your image anywhere on the screen. 32 MB / image limit. Receive Direct image links, BBCode and HTML thumbnails after uploading image. Login to see the upload history.
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
  * [imgen](https://www.jitbit.com/imgen/) - Free unlimited social cover image generation API, no watermark
  * [imgix](https://www.imgix.com/) - Image Caching, management and CDN. Free plan includes 1000 origin images, infinite transformations and 100 GB bandwidth
  * [internxt.com](https://internxt.com) – Internxt Drive is a zero-knowledge file storage service based on absolute privacy and uncompromising security. Sign up and get 10 GB for free, forever!
  * [kraken.io](https://kraken.io/) — Image optimization for website performance as a service, free plan up to 1 MB file size
  * [LibreQR](https://libreqr.com) — Free QR code generator focused on privacy and no tracking. Free to use with no data collection.
  * [nitropack.io](https://nitropack.io/) - Accelerate your site's speed on autopilot with complete front-end optimization (caching, images and code optimization, CDN). Free for up to 5,000 pageviews/month
  * [npoint.io](https://www.npoint.io/) — JSON store with collaborative schema editing
  * [otixo.com](https://www.otixo.com/) — Encrypt, share, copy, and move all your cloud storage files from one place. The basic plan provides unlimited file transfer with 250 MB max. file size and allows five encrypted files
  * [packagecloud.io](https://packagecloud.io/) — Hosted Package Repositories for YUM, APT, RubyGem and PyPI.  Limited free plans and open-source plans are available via request
  * [pcloud.com](https://www.pcloud.com/) - Cloud storage service. Up to 10 GB of free storage
  * [Pinata IPFS](https://pinata.cloud) — Pinata is the simplest way to upload and manage files on IPFS. Our friendly user interface and IPFS API make Pinata the easiest IPFS pinning service for platforms, creators, and collectors. 1 GB storage free, along with access to API.
  * [plot.ly](https://plot.ly/) — Graph and share your data. The free tier includes unlimited public files and ten private files
  * [podio.com](https://podio.com/) — You can use Podio with a team of up to five people and try out the features of the Basic Plan, except user management
  * [Proton Drive](https://proton.me/drive) - Ultra-secure cloud storage for files and key documents. Free plan offers 5gb of storage space.
  * [QRME.SH](https://qrme.sh) - Fast, beautiful bulk QR code generator – no login, no watermark, no ads. Up to 100 URLs per bulk export.
  * [QuickChart](https://quickchart.io) — Generate embeddable image charts, graphs, and QR codes
  * [redbooth.com](https://redbooth.com) — P2P file syncing, free for up to 2 users
  * [resmush.it](https://resmush.it) — reSmush.it is a FREE API that provides image optimization. reSmush.it has been implemented on the most common CMS such as WordPress, Drupal, or Magento. reSmush.it is the most used image optimization API with more than seven billion images already treated, and it is still Free of charge.
  * [sirv.com](https://sirv.com/) — Smart Image CDN with on-the-fly image optimization and resizing. The free tier includes 500 MB of storage and 2 GB of bandwidth.
  * [SlingSite](https://slingsite.github.io) - Create all the optimized versions of your images and videos. For Free. In bulk. For each image, you get the following formats: AVIF, WEBP and JPG in the three selected resolutions (desktop, tablet, mobile) For videos, you get: WebM (codec VP9), MP4 (codec HEVC aka H.265) and MP4 (codec AVC aka H.264) plus the cover image with the first frame.
  * [sync.com](https://www.sync.com/) - End-to-End cloud storage service. 5 GB of free storage
  * [tinypng.com](https://tinypng.com/) — API to compress and resize PNG and JPEG images, offers 500 compressions for free each month
  * [transloadit.com](https://transloadit.com/) — Handles file uploads and encoding of video, audio, images, documents. Free for Open source, charities, and students via the GitHub Student Developer Pack. Commercial applications get 2 GB free for test driving
  * [twicpics.com](https://www.twicpics.com) - Responsive images as a service. It provides an image CDN, a media processing API, and a frontend library to automate image optimization. The service is free for up to 3GB of traffic/per month.
  * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare provides the media pipeline  with the ultimate toolkit based on cutting-edge algorithms. All features are available for developers absolutely for free: File Uploading API and UI, Image CDN and Origin Services, Adaptive Delivery, and Smart Compression. The free tier has 3000 uploads, 3 GB traffic, and 3 GB storage.
  * [VaocherApp QR Code Generator](https://www.vaocherapp.com/qr-code-generator) – Easily create custom QR codes for gift cards, gift vouchers, and promotions. Support custom styling, color, logo...

**[⬆️ Back to Top](#table-of-contents)**

## Design and UI

  * [AllTheFreeStock](https://allthefreestock.com) - a curated list of free stock images, audio and videos.
  * [Ant Design Landing Page](https://landing.ant.design/) - Ant Design Landing Page provides a template built by Ant Motion's motion components. It has a rich homepage template, downloads the template code package, and can be used quickly. You can also use the editor to quickly build your own dedicated page.
  * [Backlight](https://backlight.dev/) — With collaboration between developers and designers at heart, Backlight is a complete coding platform where teams build, document, publish, scale, and maintain Design Systems. The free plan allows up to 3 editors to work on one design system with unlimited viewers.
  * [BoxySVG](https://boxy-svg.com/app) — A free installable Web app for drawing SVGs and exporting in SVG, PNG, jpeg, and other formats.
  * [Branition](https://branition.com/colors) - Hand-curated color pallets best fitted for brands.
  * [Calendar Icons Generator](https://calendariconsgenerator.app/) -- Generate an entire year's worth of unique icons in a single click, absolutely FREE
  * [Canva](https://canva.com) - Free online design tool to create visual content.
  * [Carousel Hero](https://carouselhero.com/) - Free online tool to create social media carousels.
  * [Circum Icons](https://circumicons.com) - Consistent open-source icons such as SVG for React, Vue, and Svelte.
  * [clevebrush.com](https://www.cleverbrush.com/) — Free Graphics Design / Photo Collage App. Also, they offer paid integration of it as a component.
  * [cloudconvert.com](https://cloudconvert.com/) — Convert anything to anything. Two hundred eight supported formats including videos and gifs.
  * [CMYK Pantone](https://www.cmyktopantone.com/) - Easily convert CMYK values to the closest Pantone colors and other color models in seconds for free.
  * [CodedThemes](https://codedthemes.com/) - Offers a well-crafted admin dashboard & and UI kits designed to simplify and speed up modern web development.
  * [CodeMyUI](https://codemyui.com) - Handpicked collection of Web Design & UI Inspiration with Code Snippets.
  * [ColorKit](https://colorkit.co/) - Create color palettes online or get inspiration from top palettes.
  * [colorr.me](https://colorr.me/) - Color & Gradient Generator
  * [coolors](https://coolors.co/) - Color palette generator. Free.
  * [css-gradient.com](https://www.css-gradient.com/) - Free tool to quickly generate custom cross-browser CSS gradients. In RGB and HEX format.
  * [css.glass](https://css.glass/) -- Free web app for creating glassmorphic designs using CSS.
  * [DaisyUI](https://daisyui.com/) -- Free. "Use Tailwind CSS but write fewer class names" offers components like buttons.
  * [easyvectors.com](https://easyvectors.com/) — EasyVectors.com is a free SVG vector art stock. Download the best vector graphics absolutely for free.
  * [Excalidraw](https://excalidraw.com/) -- A free online drawing document web page with free save to local and export support.
  * [figma.com](https://www.figma.com) — Online, collaborative design tool for teams; free tier includes unlimited files and viewers with a max of 2 editors and three projects.
  * [Float UI](https://floatui.com/) - free web development tool for quickly creating modern, responsive websites with sleek design, even for non-designers.
  * [Flows](https://flows.sh/) -- A fully customizable product adoption platform for building onboarding and user engagement experiences. Free for up to 250 monthly tracked users.
  * [Flyon UI](https://flyonui.com/)- The Easiest Components Library For Tailwind CSS.
  * [framer.com](https://www.framer.com/) - Framer helps you iterate and animate interface ideas for your next app, website, or product—starting with powerful layouts. For anyone validating Framer as a professional prototyping tool: unlimited viewers, up to 2 editors, and up to 3 projects.
  * [freeforcommercialuse.net](https://freeforcommercialuse.net/) — FFCU Worry-free model/property release stock photos
  * [Glyphs](https://glyphs.fyi/) -- Free, The Mightiest Icons on the Web, Fully editable & truly open source design system.
  * [Gradientos](https://www.gradientos.app) - Makes choosing a gradient fast and easy.
  * [Grapedrop](https://grapedrop.com/) — Responsive, powerful, SEO-optimized web page builder based on GrapesJS Framework. Free for the first five pages, unlimited custom domains, all features, and simple usage.
  * [haikei.app](https://www.haikei.app/) - Haikei is a web app to generate unique SVG shapes, backgrounds, and patterns – ready to use with your design tools and workflow.
  * [hypercolor.dev](https://hypercolor.dev/) -- A curated collection of Tailwind CSS color gradients also provides a variety of generators to create your own.
  * [HyperUI](https://www.hyperui.dev/) -- Free Open Source Tailwind CSS Components.
  * [Icon Horse](https://icon.horse) – Get the highest resolution favicon for any website from our simple API.
  * [iconify.design](https://icon-sets.iconify.design/) -- A collection of over 100 icon packs with a unified interface. Allows you to search for icons across packs and export individual icons as SVGs or for popular web frameworks.
  * [Iconoir](https://iconoir.com) – An open-source icons library with thousands of icons, supporting React, React Native, Flutter, Vue, Figma, and Framer.
  * [Icons8](https://icons8.com) — Icons, illustrations, photos, music, and design tools. Free Plan offers Limited formats in lower resolution. Link to Icons8 when you use our assets.
  * [Image BG Blurer](https://imagebgblurer.com/) -- Generate a blurred background frame for an image, using that image source as the background blur, for Notion, Trello, Jira, and more tools
  * [landen.co](https://www.landen.co) — Generate, edit, and publish beautiful websites and landing pages for your startup. All without code. The free tier allows you to have one website, fully customizable and published on the web.
  * [lensdump.com](https://lensdump.com/) - Free cloud image hosting.
  * [Logo.dev](https://www.logo.dev) - Company logo API with 44M+ brands that's as easy as calling a URL. First 10,000 API calls are free.
  * [Lorem Picsum](https://picsum.photos/) - A Free tool, easy to use, stylish placeholders. After our URL, add your desired image size (width & height), and you'll get a random image.
  * [LottieFiles](https://lottiefiles.com/) - The world’s largest online platform for the world’s most miniature animation format for designers, developers, and more. Access Lottie animation tools and plugins for Android, iOS, and Web.
  * [Lucide](https://lucide.dev) - Free customizable and consistent SVG icon toolkit.
  * [Lunacy](https://icons8.com/lunacy) -- Free graphic design tool with offline support, built-in assets (icons, photos, illustrations), and real-time collaboration. The free tier includes 10 cloud documents, a 30-day history, low-res assets, and basic design tools.
  * [MagicPattern](https://www.magicpattern.design/tools) — A collection of CSS & SVG background generators & tools for gradients, patterns, and blobs.
  * [marvelapp.com](https://marvelapp.com/) — Design, prototyping, and collaboration, free plan limited to one user and project.
  * [Mastershot](https://mastershot.app) - Completely free browser-based video editor. No watermark, up to 1080p export options.
  * [MDBootstrap](https://mdbootstrap.com/) - Free for personal & commercial use Bootstrap, Angular, React, and Vue UI Kits with over 700 components, stunning templates, 1-min installation, extensive tutorials & colossal community.
  * [Mindmup.com](https://www.mindmup.com/) — Unlimited mind maps for free and store them in the cloud. Your mind maps are available everywhere, instantly, from any device.
  * [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc is a powerful design collaboration & handoff tool. Free Plan includes three users and five projects with all features available.
  * [mockupmark.com](https://mockupmark.com/create/free) — Create realistic t-shirt and clothing mockups for social media and E-commerce, 40 free mockups.
  * [Modeldraw.com](https://modeldraw.com) — Complete diagramming platform with UML, system architecture, flowcharts, mind maps, and Agile workflows. Real-time collaboration with unlimited team members, no credit card required.
  * [Mossaik](https://mossaik.app) - Free SVG image generator with different tools like waves, blogs and patterns.
  * [movingpencils.com](https://movingpencils.com) — Fast, browser-based vector editor. Completely free.
  * [Nappy](https://nappy.co/) -- Beautiful photos of Black and Brown people, for free. For commercial and personal use.
  * [NextUI](https://nextui.org/) -- Free. Beautiful, fast, and modern React & Next.js UI library.
  * [NSPolygon](https://nspolygon.com) — Free Stock Photos, Icons & Illustrations.
  * [Octopus.do](https://octopus.do) — Visual sitemap builder. Build your website structure in real time and rapidly share it to collaborate with your team or clients.
  * [OKLCH](https://oklch.net/) -- Free OKLCH color picker and converter for web designers and developers.
  * [okso.app](https://okso.app) - Minimalistic online drawing app. Allows to create fast sketches and visual notes. Exports sketches to PNG, JPG, SVG, and WEBP. Also installable as PWA. Free to use for everyone (no registration is needed).
  * [Pencil](https://github.com/evolus/pencil) - Open source design tool using Electron.
  * [Penpot](https://penpot.app) - Web-based, open-source design and prototyping tool. Supports SVG. Completely free.
  * [pexels.com](https://www.pexels.com/) - Free stock photos for commercial use. Has a free API that allows you to search photos by keywords.
  * [photopea.com](https://www.photopea.com) — A Free, Advanced online design editor with Adobe Photoshop UI supporting PSD, XCF & Sketch formats (Adobe Photoshop, Gimp and Sketch App).
  * [Pixelixe](https://pixelixe.com/) — Create and edit engaging, unique graphics and images online.
  * [pixlr.com](https://pixlr.com/) — Free online browser editor on the level of commercial ones.
  * [Plasmic](https://www.plasmic.app/) - A fast, easy-to-use, robust web design tool and page builder that integrates into your codebase. Build responsive pages or complex components; optionally extend with code; and publish to production sites and apps.
  * [PNG to WebP Converter](https://pngtowebpconverter.com/) - Convert PNG images to WebP images directly in your browser. No upload required, fully client-side processing for maximum privacy and security.
  * [Pravatar](https://pravatar.cc/) - Generate a random/placeholder fake avatar whose URL can be directly hot-linked in your web/app.
  * [Proto.io](https://www.proto.io) - Create fully interactive UI prototypes without coding. The free tier is available when the free trial ends. The free tier includes one user, one project, five prototypes, 100MB of online storage, and a preview of the proto.io app.
  * [Quant Ux](https://quant-ux.com/) - Quant Ux is a prototyping and design tool. - It's completely free and also open source.
  * [resizeappicon.com](https://resizeappicon.com/) — A simple service to resize and manage your app icons.
  * [Responsively App](https://responsively.app) - A free dev tool for faster and more precise responsive web application development.
  * [Rive](https://rive.app) — Create and ship beautiful animations to any platform. Free forever for Individuals. The service is an editor that also hosts all the graphics on their servers. They also provide runtimes for many platforms to run representations made using Rive.
  * [SceneLab](https://scenelab.io) - Online mockup graphics editor with an ever-expanding collection of free design templates
  * [Scrollbar.app](https://scrollbar.app) -- Simple free web app for designing custom scrollbars for the web.
  * [Shadcn Studio](https://shadcnstudio.com/theme-editor) — Preview your theme changes across different components and layouts.
  * [ShadcnUI](https://ui.shadcn.com/) -- Beautifully designed components that you can copy and paste into your apps. Accessible. Customizable. Open Source.
  * [smartmockups.com](https://smartmockups.com/) — Create product mockups, 200 free mockups.
  * [storyset.com](https://storyset.com/) — Create incredible free customized illustrations for your project using this tool.
  * [Superdesigner](https://superdesigner.co) - A collection of free design tools to create unique backgrounds, patterns, shapes, images, and more with just a few clicks.
  * [SVG Converter](https://svgconverter.online/) -- Free JPG/PNG to SVG converter with color palette customization
  * [SVGmix.com](https://www.svgmix.com/) - Massive repository of 300K+ of free SVG icons, collections, and brand logos. It has a simple vector editing program right in the browser for quick file editing.
  * [svgrepo.com](https://www.svgrepo.com/) - Explore, search, and find the best-fitting icons or vectors for your projects using various vector libraries. Download free SVG Vectors for commercial use.
  * [tabler-icons.io](https://tabler-icons.io/) — Over 1500 free copy-and-paste SVG editable icons.
  * [Tailark](https://tailark.com/) - A collection of modern, responsive, pre-built UI blocks designed for marketing websites.
  * [Tailcolors](https://tailcolors.com/) -- A beautiful Tailwind CSS v4 color palette. Instantly preview & copy the perfect Tailwind CSS color class.
  * [Tailkits](https://tailkits.com/) -- A curated collection of Tailwind templates, components, and tools, plus useful generators for code, grids, box shadows, and more.
  * [TeleportHQ](https://teleporthq.io/) - Low-code Front-end Design & Development Platform. TeleportHQ is the collaborative front-end platform to instantly create and publish headless static websites. Three free projects, unlimited collaborators, and free code export.
  * [TW Elements](https://tw-elements.com/) - Free Bootstrap components recreated with Tailwind CSS, but with better design and more functionalities.
  * [tweakcn](https://tweakcn.com/) — Beautiful themes for shadcn/ui. Customize colors, typography, and more in real-time.
  * [UI Avatars](https://ui-avatars.com/) - Generate avatars with initials from names. The URLs can be directly hot-linked in your web/app. Support config parameters via the URL.
  * [unDraw](https://undraw.co/) - A constantly updated collection of beautiful SVG images that you can use completely free without attribution.
  * [Unicorn Platform](https://unicornplatform.com/) - Effortless landing page builder with hosting. One website for free.
  * [unsplash.com](https://unsplash.com/) - Free stock photos for commercial and noncommercial purposes (do-whatever-you-want license).
  * [Updrafts.app](https://updrafts.app) - WYSIWYG website builder for tailwindcss-based designs. Free for non-commercial usage.
  * [vector.express](https://vector.express) — Convert your AI, CDR, DWG, DXF, EPS, HPGL, PDF, PLT, PS and SVG vector fast and easily.
  * [vectr.com](https://vectr.com/) — Free Design App for Web + Desktop.
  * [Vertopal](https://www.vertopal.com) - Vertopal is a free online platform for converting files to various formats. Including developer converters like JPG to SVG, GIF to APNG, PNG to WEBP, JSON to XML, etc.
  * [Volume](https://volumecolor.io) — OKLCH color picker and color palette generator.
  * [walkme.com](https://www.walkme.com/) — Enterprise Class Guidance and Engagement Platform, free plan three walk-thru up to 5 steps/walk.
  * [Wdrfree SVG](https://wdrfree.com/free-svg) - Black and White Free SVG Cut files.
  * [Webflow](https://webflow.com) - WYSIWYG website builder with animations and website hosting. Free for two projects.
  * [Webstudio](https://webstudio.is/) -- Open-source alternative to Webflow. The free plan offers unlimited websites on their domain. Five websites with custom domains. Ten thousand page views/month. 2 GB asset storage.
  * [whimsical.com](https://whimsical.com/) - Collaborative flowcharts, wireframes, sticky notes and mind maps. Create up to 4 free boards.
  * [xLayers](https://xlayers.dev) - Preview and convert Sketch design files into Angular, React, Vue, LitElement, Stencil, Xamarin, and more (free and open source at https://github.com/xlayers/xlayers)
  * [Zeplin](https://zeplin.io/) — Designer and developer collaboration platform. Show designs, assets, and style guides. Free for one project.

**[⬆️ Back to Top](#table-of-contents)**

## Design Inspiration

  * [awwwards.](https://www.awwwards.com/) - [Top websites] A showcase of all the best-designed websites (voted on by designers).
  * [Behance](https://www.behance.net/) - [Design showcase] A place where designers showcase their work. Filterable with categories for UI/UX projects.
  * [dribbble](https://dribbble.com/) - [Design showcase] Unique design inspiration, generally not from real applications.
  * [Landings](https://landings.dev/) - [Web screenshots] Find the best landing pages for your design inspiration based on your preference.
  * [Lapa Ninja](https://www.lapa.ninja/) - [Landing page / UI KIts / Web screenshots] Lapa Ninja is a gallery featuring the best 6025 landing page examples, free books for designers and free UI kits from around the web.
  * [LovelyLanding.net](https://www.lovelylanding.net/) - [Landing Page Designs] Frequently updated landing page screenshots. Includes Desktop, Tablet, and Mobile screenshots.
  * [Mobbin](https://mobbin.design/) - [Mobile screenshots] Save hours of UI & UX research with our library of 50,000+ fully searchable mobile app screenshots.
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [Mobile screenshots] A design inspirational library featuring the finest UI UX Patterns (iOS and Android) for designers, developers, and product makers to reference.
  * [Page Flows](https://pageflows.com/) - [Mobile / web videos and screenshots] Videos of full flows across many mobile and web apps. Also includes screenshots. Highly searchable and indexed.
  * [Refero](https://refero.design/) - [Web screenshots] Tagged and searchable collection of design references from great web applications.
  * [Screenlane](https://screenlane.com/) - [Mobile screenshots] Get inspired and keep up with the latest web & mobile app UI design trends. Filterable by pattern and app.
  * [scrnshts](https://scrnshts.club/) - [Mobile screenshots] A hand-picked collection of the finest app store design screenshots.
  * [Uiland Design](https://uiland.design/) - [Mobile screenshots] Explore Mobile and Web UI Designs from Leading Companies in Africa and the world.

**[⬆️ Back to Top](#table-of-contents)**

## Data Visualization on Maps

  * [Clockwork Micro](https://clockworkmicro.com/) — Map tools that work like clockwork. Fifty thousand free monthly queries (map tiles, db2vector, elevation).
  * [Foursquare](https://developer.foursquare.com/) - Location discovery, venue search, and context-aware content from Places API and Pilgrim SDK.
  * [geoapify.com](https://www.geoapify.com/) - Vector and raster map tiles, geocoding, places, routing, isolines APIs. Three thousand free requests/day.
  * [geocod.io](https://www.geocod.io/) — Geocoding via API or CSV Upload. Two thousand five hundred free queries/day.
  * [geocodify.com](https://geocodify.com/) — Geocoding and Geoparsing via API or CSV Upload. 10k free queries/month.
  * [geojs.io](https://www.geojs.io/) - Highly available REST/JSON/JSONP IP Geolocation lookup API.
  * [Geokeo api](https://geokeo.com) - Geocoding API with language correction and more. Worldwide coverage. 2,500 free daily queries
  * [graphhopper.com](https://www.graphhopper.com/) A free developer package is offered for Routing, Route Optimization, Distance Matrix, Geocoding, and Map Matching.
  * [here](https://developer.here.com/) — APIs and SDKs for maps and location-aware apps. 250k transactions/month for free.
  * [IP Geolocation](https://ipgeolocation.io/) — Free DEVELOPER plan available with 30K requests/month.
  * [ipstack](https://ipstack.com/) - Locate and identify Website Visitors by IP Address
  * [locationiq.com](https://locationiq.com/) — Geocoding, Maps, and Routing APIs. Five thousand requests/day for free.
  * [mapbox.com](https://www.mapbox.com/) — Maps, geospatial services and SDKs for displaying map data.
  * [maps.stamen.com](http://maps.stamen.com/) - Free map tiles and tile hosting.
  * [maptiler.com](https://www.maptiler.com/cloud/) — Vector maps, map services and SDKs for map visualization. Free vector tiles with weekly updates and four map styles.
  * [nominatim.org](https://nominatim.org/) — OpenStreetMap's free geocoding service, providing global address search functionality and reverse geocoding capabilities.
  * [opencagedata.com](https://opencagedata.com) — Geocoding API aggregating OpenStreetMap and other open geo sources. Two thousand five hundred free queries/day.
  * [osmnames](https://osmnames.org/) — Geocoding, search results ranked by the popularity of related Wikipedia page.
  * [positionstack](https://positionstack.com/) - Free geocoding for global places and coordinates. 25,000 Requests per month for personal use.
  * [stadiamaps.com](https://stadiamaps.com/) — Map tiles, routing, navigation, and other geospatial APIs. Two thousand five hundred free map views and API requests/day for non-commercial usage and testing.

**[⬆️ Back to Top](#table-of-contents)**

## Package Build System

  * [build.opensuse.org](https://build.opensuse.org/) — Package build service for multiple distros (SUSE, EL, Fedora, Debian, etc.).
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Mock-based RPM build service for Fedora and EL.
  * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu and Debian build service.

**[⬆️ Back to Top](#table-of-contents)**

## IDE and Code Editing

  * [Android Studio](https://developer.android.com/studio) — Android Studio provides the fastest tools for building apps on every type of Android device. Open Source IDE is free for everyone and the best Android app development. Available for Windows, Mac, Linux, and even ChromeOS!
  * [AndroidIDE](https://m.androidide.com/) — An Open Source IDE to develop real, Gradle-based Android applications on Android devices.
  * [Apache Netbeans](https://netbeans.apache.org/) — Development Environment, Tooling Platform and Application Framework.
  * [apiary.io](https://apiary.io/) — Collaborative design API with instant API mock and generated documentation (Free for unlimited API blueprints and unlimited users with one admin account and hosted documentation).
  * [BBEdit](https://www.barebones.com/) - BBEdit is a popular and extensible editor for macOS. Free Mode provides a [powerful core feature set](https://www.barebones.com/products/bbedit/comparison.html) and an upgrade path to advanced features.
  * [Binder](https://mybinder.org/) - Turn a Git repo into a collection of interactive notebooks. It is a free public service.
  * [BlueJ](https://bluej.org) — A free Java Development Environment designed for beginners, used by millions worldwide. Powered by Oracle & simple GUI to help beginners.
  * [Bootify.io](https://bootify.io/) - Spring Boot app generator with custom database and REST API.
  * [Brackets](http://brackets.io/) - Brackets is an open-source text editor specifically designed for web development. It is lightweight, easy to use, and highly customizable.
  * [cacher.io](https://www.cacher.io) — Code snippet organizer with labels and support for 100+ programming languages.
  * [cocalc.com](https://cocalc.com/) — (formerly SageMathCloud at cloud.sagemath.com) — Collaborative calculation in the cloud. Browser access to full Ubuntu with built-in collaboration and lots of free software for mathematics, science, data science, preinstalled: Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn, etc.
  * [code.cs50.io](https://code.cs50.io/) - Visual Studio Code for CS50 is a web app at code.cs50.io that adapts GitHub Codespaces for students and teachers.
  * [Code::Blocks](https://codeblocks.org) — Free Fortran & C/C++ IDE. Open Source and runs on Windows,macOS & Linux.
  * [codepen.io](https://codepen.io/) — CodePen is a playground for the front-end side of the web.
  * [codesandbox.io](https://codesandbox.io/) — Online Playground for React, Vue, Angular, Preact, and more.
  * [codiga.io](https://codiga.io/) — Coding Assistant that lets you search, define, and reuse code snippets directly in your IDE. Free for individual and small organizations.
  * [Components.studio](https://webcomponents.dev/) - Code components in isolation, visualize them in stories, test them, and publish them on npm.
  * [Eclipse Che](https://www.eclipse.org/che/) - Web-based and Kubernetes-Native IDE for Developer Teams with multi-language support. Open Source and community-driven. An online instance hosted by Red Hat is available at [workspaces.openshift.com](https://workspaces.openshift.com/).
  * [ForgeCode](https://forgecode.dev/) — AI-enabled pair programmer for Claude, GPT4 Series, Grok, Deepseek, Gemini and all frontier models. Works natively with your CLI and integrates seamlessly with any IDE. Free tier includes basic AI model access with local processing.
  * [GetVM](https://getvm.io) — Instant free Linux and IDEs chrome sidebar. The free tier includes 5 VMs per day.
  * [JDoodle](https://www.jdoodle.com) — Online compiler and editor for more than 60 programming languages with a free plan for REST API code compiling up to 200 credits per day.
  * [jetbrains.com](https://jetbrains.com/products.html) — Productivity tools, IDEs and deploy tools (aka [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/), etc). Free license for students, teachers, Open Source and user groups.
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) Some REST API endpoints that return some fake data in JSON format. The source code is also available if you would like to run the server locally.
  * [Lazarus](https://www.lazarus-ide.org/) — Lazarus is a Delphi-compatible cross-platform IDE for Rapid Application Development.
  * [MarsCode](https://www.marscode.com/) - A free AI-powered cloud-based IDE.
  * [micro-jaymock](https://micro-jaymock.now.sh/) - Tiny API mocking microservice for generating fake JSON data.
  * [mockable.io](https://www.mockable.io/) — Mockable is a simple configurable service to mock out RESTful API or SOAP web services. This online service allows you to quickly define REST API or SOAP endpoints and have them return JSON or XML data.
  * [mockaroo](https://mockaroo.com/) — Mockaroo lets you generate realistic test data in CSV, JSON, SQL, and Excel formats. You can also create mocks for back-end API.
  * [Mocklets](https://mocklets.com) - an HTTP-based mock API simulator that helps simulate APIs for faster parallel development and more comprehensive testing, with a lifetime free tier.
  * [OneCompiler](https://onecompiler.com/) - Free online compiler supporting 70+ languages including Java, Python, C++, JavaScript.
  * [Paiza](https://paiza.cloud/en/) — Develop Web apps in Browser without needing to set up anything. Free Plan offers one server with 24 24-hour lifetime and 4 hours of running time per day with 2 CPU cores, 2 GB RAM, and 1 GB storage.
  * [PHPSandbox](https://phpsandbox.io/) — Online development environment for PHP
  * [Replit](https://replit.com/) — A cloud coding environment for various program languages.
  * [SoloLearn](https://code.sololearn.com) — A cloud programming playground well-suited for running code snippets. Supports various programming languages. No registration is required for running code, but it is necessary when saving code on their platform. Also offers free courses for beginners and intermediate-level coders.
  * [stackblitz.com](https://stackblitz.com/) — Online/Cloud Code IDE to create, edit, & deploy full-stack apps. Support any popular NodeJs-based frontend & backend frameworks. Shortlink to create a new project: [https://node.new](https://node.new).
  * [Sublime Text](https://www.sublimetext.com/) - Sublime Text is a popular, versatile, and highly customizable text editor used for coding and text editing tasks.
  * [Visual Studio Code](https://code.visualstudio.com/) - Code editor redefined and optimized for building and debugging modern web and cloud applications. Developed by Microsoft.
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
  * [VSCodium](https://vscodium.com/) - Community-driven, without telemetry/tracking, and freely-licensed binary distribution of Microsoft’s editor VSCode
  * [wakatime.com](https://wakatime.com/) — Quantified self-metrics about your coding activity using text editor plugins, limited plan for free.
  * [Wave Terminal](https://waveterm.dev/) - Wave is an open-source, cross-platform terminal for seamless workflows. Render anything inline. Save sessions and history. Powered by open web standards. MacOS and Linux.
  * [WebComponents.dev](https://webcomponents.dev/) — In-browser IDE to code web components in isolation with 58 templates available, supporting stories, and tests.
  * [Zed](https://zed.dev/) - Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.

**[⬆️ Back to Top](#table-of-contents)**

## Analytics, Events and Statistics

  * [amplitude.com](https://amplitude.com/) — 1 million monthly events, up to 2 apps
  * [AppFit](https://appfit.io) - AppFit is a comprehensive analytics and product management tool designed to facilitate seamless, cross-platform management of analytics and product updates. Free plan includes 10,000 events per month, product journal and weekly insights.
  * [Aptabase](https://aptabase.com) — Open Source, Privacy-Friendly, and Simple Analytics for Mobile and Desktop Apps. SDKs for Swift, Kotlin, React Native, Flutter, Electron, and many others. Free for up to 20,000 events per month.
  * [Avo](https://avo.app/) — Simplified analytics release workflow. Single-source-of-truth tracking plan, type-safe analytics tracking library, in-app debuggers, and data observability to catch all data issues before you release. Free for two workspace members and 1 hour data observability lookback.
  * [Beampipe.io](https://beampipe.io) - Beampipe is simple, privacy-focussed web analytics. free for up to 5 domains & 10k monthly page views.
  * [Census](https://www.getcensus.com/) — Reverse ETL & Operational Analytics Platform. Sync 10 fields from your data warehouse to 60+ SaaS like Salesforce, Zendesk, or Amplitude.
  * [Clicky](https://clicky.com) — Website Analytics Platform. Free Plan for one website with 3000 views analytics.
  * [counter.dev](https://counter.dev) — Web analytics made simple and therefore privacy friendly. Free or pay what you want by donation.
  * [DocBeacon](https://docbeacon.io) - Secure document sharing with document tracking and engagement Analytics. Free plan supports up to 20 PDF documents (10 MB max), 10 contacts, and 2 shares per document with basic analytics for views downloads, time and engagement.
  * [Dwh.dev](https://dwh.dev) - Data Cloud Observability Solution (Snowflake). Free for personal use.
  * [Expensify](https://www.expensify.com/) — Expense reporting, free personal reporting approval workflow
  * [getinsights.io](https://getinsights.io) - Privacy-focused, cookie-free analytics, free for up to 3k events/month.
  * [GoatCounter](https://www.goatcounter.com/) — GoatCounter is an open-source web analytics platform available as a hosted service (free for non-commercial use) or self-hosted app. It aims to offer easy-to-use and meaningful privacy-friendly web analytics as an alternative to Google Analytics or Matomo. The free tier is for non-commercial use and includes unlimited sites, six months of data retention, and 100k pageviews/month.
  * [Google Analytics](https://analytics.google.com/) — Google Analytics
  * [heap.io](https://heap.io) — Automatically captures every user action in iOS or web apps. Free for up to 10K monthly sessions.
  * [Hightouch](https://hightouch.com/) - Hightouch is a Reverse ETL platform that helps you sync customer data from your data warehouse to your CRM, marketing, and support tools. The free tier offers you one destination to sync data to.
  * [Hotjar](https://hotjar.com) — Website Analytics and Reports . Free Plan allows 2000 pageviews/day. One hundred snapshots/day (max capacity: 300). Three snapshot heatmaps can be stored for 365 days. Unlimited Team Members. Also in App and standalone surveys, feedback widgets with screenshots. Free tier allows creating 3 surveys & 3 feedback widgets and collecting 20 responses per month.
  * [LogSpot](https://logspot.io) - Full unified web and product analytics platform, including embeddable analytics widgets and automated robots (slack, telegram, and webhooks). Free plan includes 10,000 events per month.
  * [MetricsWave](https://metricswave.com) — Privacy-friendly Google Analytics alternative for developers. Free plan allows 1M pageviews per month without credit card required.
  * [Mixpanel](https://mixpanel.com/) — 100,000 monthly tracked users, unlimited data history and seats, US or EU data residency
  * [Moesif](https://www.moesif.com) — API analytics for REST and GraphQL. (Free up to 500,000 API calls/mo)
  * [PostHog](https://posthog.com) - Full Product Analytics suite free for up to 1m tracked events per month. Also provides unlimited in-App Surveys with 250/month responses.
  * [Repohistory](https://repohistory.com) - Beautiful dashboard for tracking GitHub repo traffic history longer than 14 days. Free Plan allows users to monitor traffic for a single repository.
  * [Row Zero](https://rowzero.io) - Blazingly fast, connected spreadsheet. Connect directly to data databases, S3, and APIs. Import, analyze, graph, and share millions of rows instantly. Three free (forever) workbooks.
  * [Rybbit](https://rybbit.io) - Open-source and cookieless alternative to Google Analytics that is 10x more intuitive. Free plans has 3,000 monthly events.
  * [Seline](https://seline.so) - Seline is a simple & private website and product analytics. Cookieless, lightweight, independent. Free plan includes 3,000 events per month and provides access to all our features, such as the dashboard, user journeys, funnels, and more.
  * [StatCounter](https://statcounter.com/) — Website Viewer Analytics. Free plan for analytics of 500 most recent visitors.
  * [Statsig](https://statsig.com) - All-in-one platform spanning across analytics, feature flagging, and A/B testing. Free for up to 1m metered events per month.
  * [TraceLog](https://tracelog.io/) - AI Analytics for E-commerce. Ask questions in natural language about your analytics, get actionable recommendations and grow your revenue with AI-powered insights. Free for up to 10k events per month.
  * [Trackingplan](https://www.trackingplan.com/) - Automatically detect digital analytics, marketing data and pixels issues, maintain up-to-date tracking plans, and foster seamless collaboration. Deploy it to your production environment with real traffic or add analytics coverage to your regression tests without writing code.
  * [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - Free lightweight privacy-focused alternative to Google Analytics. Unlimited pageviews, unlimited visitor, unlimited page heatmaps & goal tracking. Free for up to 3 domains and 600 session replay per domain.
  * [Umami](https://umami.is/) - Simple, fast, privacy-focused, open-source alternative to Google Analytics.
  * [usabilityhub.com](https://usabilityhub.com/) — Test designs and mockups on real people and track visitors. Free for one user, unlimited tests
  * [Userbird](https://userbird.com) - Google Analytics alternative with heatmaps, session recordings and revenue tracking.

**[⬆️ Back to Top](#table-of-contents)**

## Visitor Session Recording

  * [FullStory.com](https://www.fullstory.com) — 1,000 sessions/month with one month data retention and three user seats. More information [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
  * [howuku.com](https://howuku.com) — Track user interaction, engagement, and event. Free for up to 5,000 visits/month
  * [inspectlet.com](https://www.inspectlet.com/) — 2,500 sessions/month free for one website
  * [LogRocket.com](https://www.logrocket.com) - 1,000 sessions/month with 30-day retention, error tracking, live mode
  * [Microsoft Clarity](https://clarity.microsoft.com/) - Session recording completely free with "no traffic limits", no project limits, and no sampling
  * [mouseflow.com](https://mouseflow.com/) — 500 sessions/month free for one website
  * [OpenReplay.com](https://www.openreplay.com) - Open-source session replay with dev tools for bug reproduction, live session for real-time support, and product analytics suite. One thousand sessions/month with access to all features and 7-day retention.
  * [Reactflow.com](https://www.reactflow.com/) — Per site: 1,000 pages views/day, three heatmaps, three widgets, free bug tracking
  * [smartlook.com](https://www.smartlook.com/) — free packages for web and mobile apps (1500 sessions/month), three heatmaps, one funnel, 1-month data history
  * [UXtweak.com](https://www.uxtweak.com/) — Record and watch how visitors use your website or app. Free unlimited time for small projects

**[⬆️ Back to Top](#table-of-contents)**

## International Mobile Number Verification API and SDK

  * [numverify](https://numverify.com/) — Global phone number validation and lookup JSON API. 100 API requests/month
  * [veriphone](https://veriphone.io/) — Global phone number verification in a free, fast, reliable JSON API. 1000 requests/month

**[⬆️ Back to Top](#table-of-contents)**

## Payment and Billing Integration

  * [Adapty.io](https://adapty.io/) – One-stop solution with open-source SDK for mobile in-app subscription integration to iOS, Android, React Native, Flutter, Unity, or web app. Free up to $10k monthly revenue.
  * [CoinMarketCap](https://coinmarketcap.com/api/) — Provides cryptocurrency market data including the latest crypto and fiat currency exchange rates. The free tier offers 10K call credits/month.
  * [Currencyapi](https://currencyapi.com) — Free currency conversion and exchange rate data API. Free 300 requests per month, 10 requests per minute for private use.
  * [CurrencyApi](https://currencyapi.net/) — Live Currency Rates for Physical and Cryptocurrencies, delivered in JSON and XML. The free tier offers 1,250 API requests/month.
  * [CurrencyFreaks](https://currencyfreaks.com/) — Provides current and historical currency exchange rates. Free DEVELOPER plan available with 1000 requests/month.
  * [currencylayer](https://currencylayer.com/) — Reliable Exchange Rates and Currency Conversion for your Business, 100 API requests/month free.
  * [exchangerate-api.com](https://www.exchangerate-api.com) - An easy-to-use currency conversion JSON API. The free tier updates once per day with a limit of 1,500 requests/month.
  * [FraudLabsPRO](https://www.fraudlabspro.com) — Help merchants to prevent payment fraud and chargebacks. Free Micro Plan available with 500 queries/month.
  * [FxRatesAPI](https://fxratesapi.com) — Provides real-time and historical exchange rates. The free tier requires attribution.
  * [Moesif API Monetization](https://www.moesif.com/) - Generate revenue from APIs via usage-based billing. Connect to Stripe, Chargebee, etc. The free tier offers 30,000 events/month.
  * [ParityVend](https://www.ambeteco.com/ParityVend/) – Automatically adjust pricing based on visitor location to expand your business globally and reach new markets (purchasing power parity). The free plan includes 7,500 API requests/month.
  * [Qonversion](http://qonversion.io/) - All-in-one cross-platform subscription management platform offering analytics, A/B testing, Apple Search Ads, remote configs, and growth tools for optimizing in-app purchases and monetization. Compatible with iOS, Android, React Native, Flutter, Unity, Cordova, Stripe, and web. Free up to $10k in monthly tracked revenue.
  * [RevenueCat](https://www.revenuecat.com/) — Hosted backend for in-app purchases and subscriptions (iOS and Android). Free up to $2.5k/mo in tracked revenue.
  * [vatlayer](https://vatlayer.com/) — Instant VAT number validation and EU VAT rates API, free 100 API requests/month

**[⬆️ Back to Top](#table-of-contents)**

## Docker Related

  * [Container Registry Service](https://container-registry.com/) - Harbor based Container Management Solution. The free tier offers 1 GB of storage for private repositories.
  * [Docker Hub](https://hub.docker.com) — One free private repository and unlimited public repositories to build and store Docker images
  * [Play with Docker](https://labs.play-with-docker.com/) — A simple, interactive, fun playground to learn Docker.
  * [quay.io](https://quay.io/) — Build and store container images with unlimited free public repositories
  * [ttl.sh](https://ttl.sh/) - Anonymous & ephemeral Docker image registry

**[⬆️ Back to Top](#table-of-contents)**

## Dev Blogging Sites

  * [AyeDot](https://ayedot.com/) — Share your ideas, knowledge, and stories with the world for Free in the form of Modern multimedia short-format Miniblogs.
  * [BearBlog](https://bearblog.dev/) - Minimalist, Markdown-powered blog and website builder.
  * [Dev.to](https://dev.to/) - Where programmers share ideas and help each other grow.
  * [Hashnode](https://hashnode.com/) — Hassle-free Blogging Software for Developers!.
  * [Medium](https://medium.com/) — Get more thoughtful about what matters to you.
  * [JustBlogged](https://justblogged.com) — Free blogging platform with custom domain support, and fast global performance.

**[⬆️ Back to Top](#table-of-contents)**

## Commenting Platforms

  * [GraphComment](https://graphcomment.com/) - GraphComment is a comments platform that helps you build an active community from the website’s audience.
  * [IntenseDebate](https://intensedebate.com/) - A feature-rich comment system for WordPress, Tumblr, Blogger, and many other website platforms.
  * [Remarkbox](https://www.remarkbox.com/) - Open source hosted comments platform, pay what you can for "One moderator on a few domains with complete control over behavior & appearance"
  * [Utterances](https://utteranc.es/) - A lightweight comments widget built on GitHub issues. Use GitHub issues for blog comments, wiki pages, and more!

**[⬆️ Back to Top](#table-of-contents)**

## Screenshot APIs

  * [ApiFlash](https://apiflash.com) — A screenshot API based on Aws Lambda and Chrome. Handles full page, captures timing, and viewport dimensions.
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities, or screenshots as a service. 250 requests/day every day free.
  * [PhantomJsCloud](https://PhantomJsCloud.com) — Browser automation and page rendering.  Free Tier offers up to 500 pages/day.  Free Tier since 2017.
  * [screenshotbase.com](https://screenshotbase.com) - 300 free screenshots / month. Take screenshots from any url. Fast, free & scalable.
  * [screenshotlayer.com](https://screenshotlayer.com/) — Capture highly customizable snapshots of any website. Free 100 snapshots/month
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — Capture 100 snapshots/month, png, gif and jpg, including full-length captures, not only home page
  * [thumbnail.ws](https://thumbnail.ws) — API for generating thumbnails of websites. Free 1,000 requests/month.

**[⬆️ Back to Top](#table-of-contents)**

## Flutter Related and Building IOS Apps without Mac

  * [CodeMagic](https://codemagic.io/) - Codemagic is a fully hosted and managed CI/CD for mobile apps. You can build, test, and deploy with a GUI-based CI/CD tool. The free tier offers 500 free minutes/month and a Mac Mini instance with 2.3 GHz and 8 GB of RAM.
  * [FlutLab](https://flutlab.io/) - FlutLab is a modern Flutter online IDE and the best place to create, debug, and build cross-platform projects. Build iOS (Without a Mac) and Android apps with Flutter.
  * [FlutterFlow](https://flutterflow.io/) -  FlutterFlow is a browser-based drag-and-drop interface to build mobile app using flutter.

**[⬆️ Back to Top](#table-of-contents)**

## Browser-based hardware emulation written in Javascript

  * [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) —  an OpenRISC virtual machine capable of running Linux with network support.
  * [JsLinux](https://bellard.org/jslinux) — a really fast x86 virtual machine capable of running Linux and Windows 2k.
  * [v86](https://copy.sh/v86) — an x86 virtual machine capable of running Linux and other OS directly into the browser.

**[⬆️ Back to Top](#table-of-contents)**

## Privacy Management

  * [Bearer](https://www.bearer.sh/) - Helps implement privacy by design via audits and continuous workflows so that organizations comply with GDPR and other regulations. The free tier is limited to smaller teams and the SaaS version only.
  * [Concord](https://www.concord.tech/) - Full data privacy platform, including consent management, privacy request handling (DSARs), and data mapping. Free tier includes core consent management features and they also provide a more advanced plan for free to verified open source projects.
  * [Cookiefirst](https://cookiefirst.com/) - Cookie banners, auditing, and multi-language consent management solution. The free tier offers a one-time scan and a single banner.
  * [Iubenda](https://www.iubenda.com/) - Privacy and cookie policies and consent management. The free tier offers limited privacy and cookie policy as well as cookie banners.
  * [Ketch](https://www.ketch.com/) - Consent management and privacy framework tool. The free tier offers most features with a limited visitor count.

**[⬆️ Back to Top](#table-of-contents)**

## Miscellaneous

  * [BackgroundStyler.com](https://backgroundstyler.com) - Create aesthetic screenshots of your code, text or images to share on social media.
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) — Online free tool for decoding & encoding data.
  * [BinShare.net](https://binshare.net) - Create & share code or binaries. Available to share as a beautiful image e.g. for Twitter / Facebook post or as a link e.g. for chats or forums.
  * [Blynk](https://blynk.io) — A SaaS with API to control, build & evaluate IoT devices. Free Developer Plan with 5 devices, Free Cloud & data storage. Mobile Apps are also available.
  * [Bricks Note Calculator](https://free.getbricks.app/) - a note-taking app (PWA) with a powerful built-in multiline calculator.
  * [Carbon.now.sh](https://carbon.now.sh) - create and share code snippets in an aesthetic screenshot-like image format. Usually used to aesthetically share/show off code snippets on Twitter or blog posts.
  * [Code Time](https://www.software.com/code-time) - an extension for time-tracking and coding metrics in VS Code, Atom, IntelliJ, Sublime Text, and more.
  * [Codepng](https://www.codepng.app) - Create excellent snapshots from your source code to share on social media.
  * [CodeToImage](https://codetoimage.com/) - Create screenshots of code or text to share on social media.
  * [cron-job.org](https://cron-job.org) - Online cronjobs service. Unlimited jobs are free of charge.
  * [Cronhooks](https://cronhooks.io/) - Schedule on-time or recurring webhooks. The free plan allows 5 ad-hoc schedules.
  * [datelist.io](https://datelist.io) - Online booking / appointment scheduling system. Free up to 5 bookings per month, includes 1 calendar
  * [Domain Forward](https://domain-forward.com/) - A straightforward tool to forward any URL or Domain. Free up to 5 domains and 200k requests per month.
  * [Exif Editor](https://exifeditor.io/) — View, Edit, Scrub, Analyze image/photo metadata in-browser instantly - including GPS location and metadata.
  * [Format Express](https://www.format-express.dev) - Instant online format for JSON / XML / SQL.
  * [FOSSA](https://fossa.com/) - Scalable, end-to-end management for third-party code, license compliance and vulnerabilities.
  * [Hook Relay](https://www.hookrelay.dev/) - Add webhook support to your app without the hassles: done-for-you queueing, retries with backoff, and logging. The free plan has 100 deliveries per day, 14-day retention, and 3 hook endpoints.
  * [Hosting Checker](https://hostingchecker.co) - Check hosting information such as ASN, ISP, location and more for any domain, website or IP address. Also includes multiple hosting and DNS-related tools.
  * [newreleases.io](https://newreleases.io/) - Receive notifications on email, Slack, Telegram, Discord, and custom webhooks for new releases from GitHub, GitLab, Bitbucket, Python PyPI, Java Maven, Node.js NPM, Node.js Yarn, Ruby Gems, PHP Packagist, .NET NuGet, Rust Cargo and Docker Hub.
  * [OnlineExifViewer](https://onlineexifviewer.com/) — View EXIF data online instantly for a photo including GPS location and metadata.
  * [PDFMonkey](https://www.pdfmonkey.io/) — Manage PDF templates in a dashboard, call the API with dynamic data, and download your PDF. Offers 300 free documents per month.
  * [Pika Code Screenshots](https://pika.style/templates/code-image) — Create beautiful, customizable screenshots from code snippets and VSCode using the extension.
  * [QuickType.io](https://quicktype.io/) - Quickly auto-generate models/class/type/interface and serializers from JSON, schema, and GraphQL for working with data quickly & safely in any programming language. Convert JSON into gorgeous, typesafe code in any language.
  * [RandomKeygen](https://randomkeygen.com/) - A free mobile-friendly tool that offers a variety of randomly generated keys and passwords you can use to secure any application, service, or device.
  * [ray.so](https://ray.so/) - Create beautiful images of your code snippets.
  * [readme.com](https://readme.com/) — Beautiful documentation made easy, free for Open Source.
  * [redirect.pizza](https://redirect.pizza/) - Easily manage redirects with HTTPS support. The free plan includes 10 sources and 100,000 hits per month.
  * [redirection.io](https://redirection.io/) — SaaS tool for managing HTTP redirections for businesses, marketing and SEO.
  * [Renamer.ai](https://renamer.ai) — AI-powered file renaming tool with OCR, metadata extraction, and automation for 20+ languages. Free tier: 15 files/month, including desktop app, batch rename, auto-rename, and normal support.
  * [ReqBin](https://reqbin.com/) — Post HTTP Requests Online. Popular Request Methods include GET, POST, PUT, DELETE, and HEAD. Supports Headers and Token Authentication. Includes a basic login system for saving your requests.
  * [Smartcar API](https://smartcar.com) - An API for cars to locate, get fuel tank, battery levels, odometer, unlock/lock doors, etc.
  * [snappify](https://snappify.com) - Enables developers to create stunning visuals. From beautiful code snippets to fully fletched technical presentations. The free plan includes up to 3 snaps at once with unlimited downloads and 5 AI-powered code explanations per month.
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - Get sunrise and sunset times for a given longitude and latitude.
  * [superfeedr.com](https://superfeedr.com/) — Real-time PubSubHubbub compliant feeds, export, analytics. Free with less customization
  * [SurveyMonkey.com](https://www.surveymonkey.com) — Create online surveys. Analyze the results online. The free plan allows only 10 questions and 100 responses per survey.
  * [UUID Generator](https://newuuid.com/) - Generate UUID v1, UUID v4, UUID v7, GUID, Nil UUIDs, CUID v1/v2, NanoID, and ULID instantly with enterprise-grade
  * [Versionfeeds](https://versionfeeds.com) — Custom RSS feeds for releases of your favorite software. Have the latest versions of your programming languages, libraries, or loved tools in one feed. (The first 3 feeds are free)
  * [videoinu](https://videoinu.com) — Create and edit screen recordings and other videos online.
  * [Volume Shader BM](https://volumeshaderbm.org) — Free browser-based GPU benchmark (WebGL). Helps developers test and compare shader performance reproducibly across browsers and devices.
  * [Webacus](https://webacus.dev) — Access a wide range of free developer tools for encoding, decoding, and data manipulation.
  * [XKit](https://xkit.io) — A collection of free online tools designed to make life easier for developers, students, and everyday users. Include a wide range of Developer tools, Diff/Compare tools, Calculators, Converters and Generators.
  performance and security

**[⬆️ Back to Top](#table-of-contents)**

## Remote Desktop Tools

  * [AnyDesk](https://anydesk.com) —  Free for 3 devices, no limits on the number and duration of sessions
  * [Getscreen.me](https://getscreen.me) —  Free for 2 devices, no limits on the number and duration of sessions
  * [RemSupp](https://remsupp.com) — On-demand support and permanent access to devices (2 sessions/day for free)
  * [RustDesk](https://rustdesk.com/) - Open source virtual/remote desktop infrastructure for everyone!

**[⬆️ Back to Top](#table-of-contents)**

## Game Development

  * [3Dassets.one](https://3dassets.one/) - Over 8,000 free/paid 3D models, and PBR materials for making textures.
  * [ArtStation](https://www.artstation.com/) - MarketPlace for Free/Paid 2D, 3D assets & audios, icons, tile sets, game kits. Also, It can be used for showcasing your art portfolio.
  * [CraftPix](https://craftpix.net) — Free/Paid assets like 2D, 3D, Audio, GUI, backgrounds, icons, tile sets, game kits.
  * [Freesound](https://freesound.org/) - Free collaborative sound library offerer with different CC licenses.
  * [Game Icons](https://game-icons.net/) - Free styleable SVG/PNG icons provided under a CC-BY license.
  * [GameDevMarket](https://gamedevmarket.net) — Free/Paid assets like 2D, 3D, Audio, GUI.
  * [Gamefresco.com](https://gamefresco.com/) — Discover, collect, and share free game assets from game artists everywhere.
  * [itch.io](https://itch.io/game-assets) — Free/Paid assets like sprites, tile sets, and character packs.
  * [Kenney](https://www.kenney.nl/assets/) - Free (CC0 1.0 Universal licensed) 2D, 3D, Audio, and UI game assets.
  * [LoSpec](https://lospec.com/) — Online tools for creating pixel art and other restrictive digital art, lots of tutorials/pallet list available to choose from for your games
  * [OpenGameArt](https://opengameart.org) — OpenSource Game Assets like music, sounds, sprites, and gifs.
  * [Poliigon](https://www.poliigon.com/) - Free and paid textures (with variable resolution), models, HDRIs, and brushes. Offers free plugins to export to software like Blender.
  * [Poly Pizza](https://poly.pizza/) - Free low poly 3D assets

**[⬆️ Back to Top](#table-of-contents)**

## Other Free Resources

  * [360Converter](https://www.360converter.com/) - Free tier useful website to convert: Video to Text && Audio to Text && Speech to Text && Real-time Audio to Text && YouTube Video to Text && add Video Subtitle. Maybe it will be helpful in a short video conversion or in a short youtube tutorial:)
  * [AdminMart](https://adminmart.com/) — High-Quality Free and Premium Admin Dashboard and Website Templates created with Angular, Bootstrap, React, VueJs, NextJS, and NuxtJS!
  * [Buttons Generator](https://markodenic.com/tools/buttons-generator/) — 100+ buttons you can use in your project.
  * [ElevateAI](https://www.elevateai.com) - Get up to 200 hours of audio transcription for free every month.
  * [Framacloud](https://degooglisons-internet.org/en/) — A list of Free/Libre Open Source Software and SaaS by the French non-profit [Framasoft](https://framasoft.org/en/).
  * [Free Code Tools](https://freecodetools.org/) — Effective code tools which are 100% free. Markdown editor, Code minifier/beautifier, QR code generator, Open Graph Generator, Twitter card Generator, and more.
  * [get.localhost.direct](https://get.localhost.direct) — A better `*.localhost.direct` Wildcard public CA signed SSL cert for localhost development with sub-domain support
  * [GitHub Education](https://education.github.com/pack) — Collection of free services for students. Registration required.
  * [Glob tester](https://globster.xyz/) — A website that allows you to design and test glob patterns. It also provides resources to learn glob patterns.
  * [It tools](https://it-tools.tech/) - Useful tools for developer and people working in IT.
  * [JSON Viewer Tool](https://jsonviewertool.com/) – View, format, validate, minify, and convert JSON data directly in the browser (no API key required).
  * [Killer Coda](https://killercoda.com/)  - Interactive playground in your browser to study Linux, Kubernetes, Containers, Programming, DevOps, Networking
  * [Kody Tools](https://www.kodytools.com/dev-tools) — 100+ dev tools including formatter, minifier, and converter.
  * [Markdown Tools](https://markdowntools.com) - Tools for converting HTML, CSVs, PDFs, JSON, and Excel files to and from Markdown
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) — Get a free sandbox, tools, and other resources you need to build solutions for the Microsoft 365 platform. The subscription is a 90-day [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5) (Windows excluded) which is renewable. It is renewed if you're active in development(measured using telemetry data & algorithms).
  * [MySQL Visual Explain](https://mysqlexplain.com) - Easy-to-understand and free MySQL EXPLAIN output visualizer to optimize slow queries.
  * [PageTools](https://pagetools.co/) - Offers a suite of forever free AI-powered tools to help you generate essential website policies, create social media bios, posts and web pages with a simple one-click interface.
  * [Pyrexp](https://pythonium.net/regex) — Free web-based regex tester and visualizer for debugging regular expressions.
  * [RedHat for Developers](https://developers.redhat.com) — Free access to Red Hat products including RHEL, OpenShift, CodeReady, etc. exclusively for developers. Individual plan only. Free e-books are also offered for reference.
  * [regex101](https://regex101.com/) — Free this website allows you to test and debug regular expressions (regex). It provides a regex editor and tester, as well as helpful documentation and resources for learning regex.
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) — Send and receive test SMS messages for free.
  * [SimpleBackups.com](https://simplebackups.com/) — Backup automation service for servers and databases (MySQL, PostgreSQL, MongoDB) stored directly into cloud storage providers (AWS, DigitalOcean, and Backblaze). Provides a free plan for 1 backup.
  * [SimpleRestore](https://simplerestore.io) - Hassle-free MySQL backup restoration. Restore MySQL backups to any remote database without code or a server.
  * [SnapShooter](https://snapshooter.com/) — Backup solution for DigitalOcean, AWS, LightSail, Hetzner, and Exoscale, with support for direct database, file system and application backups to s3 based storage. Provides a free plan with daily backups for one resource.
  * [Table Format Converter](https://www.tableformatconverter.com) - A free tool to convert table data to different formats, such as CSV, HTML, JSON, Markdown and more.
  * [Themeselection](https://themeselection.com/) — Selected high quality, modern design, professional and easy-to-use Free Admin Dashboard Template,
  * [ToolsHref](https://toolshref.com) - A suite of free developer utilities including Java code generation (JSON-to-POJO, cURL-to-Java), static analysis, and DevOps config builders (Docker, K8s, Nginx).
  * [Utils.fun](https://utils.fun/en) — All offline daily and development tools based on the browser's computing power, including watermark generation, screen recording, encoding and decoding, encryption and decryption, and code formatting, are completely free and do not upload any data to the cloud for processing.
  * [Wikimint Developer](https://developer.wikimint.com/p/tools.html) - Always free tools for web developers that includes CSS minify unminify, image optimizer, image resizer, case convertor, CSS validator, JavaScript compiler, HTML editor, etc.
  * [WrapPixel](https://www.wrappixel.com/) — Download High Quality Free and Premium Admin dashboard template created with Angular, React, VueJs, NextJS, and NuxtJS!
HTML Themes and UI Kits to create your applications faster!

**[⬆️ Back to Top](#table-of-contents)**
