最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.4bmje2.asia/blog/538681.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.4bmje2.asia/blog/100810.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.4bmje2.asia/blog/058510.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.4bmje2.asia/blog/828882.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.4bmje2.asia/blog/911635.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.4bmje2.asia/blog/814041.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.4bmje2.asia/blog/940594.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.4bmje2.asia/blog/180940.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.4bmje2.asia/blog/058492.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.4bmje2.asia/blog/018844.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.4bmje2.asia/blog/388107.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.4bmje2.asia/blog/730993.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.4bmje2.asia/blog/843703.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.4bmje2.asia/blog/257658.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.4bmje2.asia/blog/988077.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.4bmje2.asia/blog/203070.Doc

原标题：浏览器本地存储安全使用技巧
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.4bmje2.asia/blog/009559.Doc

原标题：golang grafana 面板变量模板制作
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.4bmje2.asia/blog/080996.Doc

原标题：golang 优雅处理数据库事务
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.4bmje2.asia/blog/744499.Doc

原标题：golang viper 配置热更新实操
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.4bmje2.asia/blog/267135.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.4bmje2.asia/blog/473570.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.4bmje2.asia/blog/335062.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.4bmje2.asia/blog/505563.Doc

原标题：golang k8s liveness readiness 探针
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.4bmje2.asia/blog/558258.Doc

原标题：大文件导出内存溢出防护
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.4bmje2.asia/blog/041701.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.4bmje2.asia/blog/233063.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.4bmje2.asia/blog/265292.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.4bmje2.asia/blog/390262.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.4bmje2.asia/blog/651141.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.4bmje2.asia/blog/122065.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.4bmje2.asia/blog/487073.Doc

原标题：GET POST 接口请求参数处理
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.4bmje2.asia/blog/824665.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.4bmje2.asia/blog/378711.Doc

原标题：全量回归测试提升代码质量
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.4bmje2.asia/blog/283595.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.4bmje2.asia/blog/384692.Doc

原标题：golang 系统设计短信发送限流降级
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.4bmje2.asia/blog/239585.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.4bmje2.asia/blog/347109.Doc

原标题：golang redis lua 脚本开发调试
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.4bmje2.asia/blog/476771.Doc

原标题：业务错误码体系设计方案
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.4bmje2.asia/blog/851266.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.4bmje2.asia/blog/717972.Doc


二、踩坑排错｜Troubleshooting
原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.4bmje2.asia/blog/021811.Doc

原标题：文件句柄耗尽资源泄露处理
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.4bmje2.asia/blog/903936.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.4bmje2.asia/blog/651394.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.4bmje2.asia/blog/890477.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.4bmje2.asia/blog/043209.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.4bmje2.asia/blog/520776.Doc

原标题：Git 分支切换合并删除完整操作
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.4bmje2.asia/blog/606338.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.4bmje2.asia/blog/209167.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.4bmje2.asia/blog/244516.Doc

原标题：golang 系统设计短链接服务实现思路
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.4bmje2.asia/blog/864429.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.4bmje2.asia/blog/566989.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.4bmje2.asia/blog/015655.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.4bmje2.asia/blog/932946.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.4bmje2.asia/blog/963152.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.4bmje2.asia/blog/301661.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.4bmje2.asia/blog/114171.Doc

原标题：前端静态缓存更新生效处理
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.4bmje2.asia/blog/138616.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.4bmje2.asia/blog/613004.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.4bmje2.asia/blog/822228.Doc

原标题：项目构建脚本编译打包解析
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.4bmje2.asia/blog/604041.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.4bmje2.asia/blog/435626.Doc

原标题：缓存穿透防护保护数据库
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.4bmje2.asia/blog/533696.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.4bmje2.asia/blog/127812.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.4bmje2.asia/blog/705727.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.4bmje2.asia/blog/347970.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.4bmje2.asia/blog/466300.Doc

原标题：golang context 上下文传参讲解
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.4bmje2.asia/blog/380688.Doc

原标题：golang 容器健康检查接口开发
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.4bmje2.asia/blog/321433.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.4bmje2.asia/blog/195401.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://book.4bmje2.asia/blog/857444.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.4bmje2.asia/blog/819841.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.4bmje2.asia/blog/537777.Doc

原标题：nodejs 多进程任务分发处理
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.4bmje2.asia/blog/522486.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.4bmje2.asia/blog/192929.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.4bmje2.asia/blog/796656.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.4bmje2.asia/blog/617992.Doc

原标题：前端打包分包加载提速方案
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.4bmje2.asia/blog/315962.Doc

原标题：前端骨架屏提升页面体验
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.4bmje2.asia/blog/088131.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.4bmje2.asia/blog/232739.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.4bmje2.asia/blog/387796.Doc

三、实战开发｜Practice
原标题：分布式事务最终一致性实现
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.4bmje2.asia/blog/868518.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.4bmje2.asia/blog/758137.Doc

原标题：golang 系统设计埋点数据上报方案
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.4bmje2.asia/blog/759286.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.4bmje2.asia/blog/506493.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.4bmje2.asia/blog/433668.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.4bmje2.asia/blog/909283.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.4bmje2.asia/blog/429153.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.4bmje2.asia/blog/904708.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.4bmje2.asia/blog/011816.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.4bmje2.asia/blog/946113.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.4bmje2.asia/blog/454071.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.4bmje2.asia/blog/014740.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.4bmje2.asia/blog/704138.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.4bmje2.asia/blog/384995.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.4bmje2.asia/blog/318003.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.4bmje2.asia/blog/371737.Doc

原标题：ORM 框架数据库增删改查实操
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.4bmje2.asia/blog/939403.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.4bmje2.asia/blog/351142.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.4bmje2.asia/blog/087486.Doc

原标题：简易网关请求路由过滤模拟
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.4bmje2.asia/blog/010447.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.4bmje2.asia/blog/215414.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.4bmje2.asia/blog/177565.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.4bmje2.asia/blog/285577.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.4bmje2.asia/blog/725846.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.4bmje2.asia/blog/421258.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.4bmje2.asia/blog/359525.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.4bmje2.asia/blog/016030.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.4bmje2.asia/blog/712187.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.4bmje2.asia/blog/969261.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.4bmje2.asia/blog/048344.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.4bmje2.asia/blog/422096.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.4bmje2.asia/blog/522920.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.4bmje2.asia/blog/465868.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.4bmje2.asia/blog/550847.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.4bmje2.asia/blog/813197.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.4bmje2.asia/blog/961275.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.4bmje2.asia/blog/477787.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.4bmje2.asia/blog/927791.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.4bmje2.asia/blog/059084.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.4bmje2.asia/blog/037380.Doc

四、架构设计｜Architecture
原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.4bmje2.asia/blog/640140.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.4bmje2.asia/blog/559686.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.4bmje2.asia/blog/885427.Doc

原标题：预编译 SQL 防注入实现
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.4bmje2.asia/blog/783631.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.4bmje2.asia/blog/081821.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.4bmje2.asia/blog/963175.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.4bmje2.asia/blog/217990.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.4bmje2.asia/blog/523194.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.4bmje2.asia/blog/890486.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.4bmje2.asia/blog/777924.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.4bmje2.asia/blog/122209.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.4bmje2.asia/blog/718728.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.4bmje2.asia/blog/299919.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.4bmje2.asia/blog/341151.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.4bmje2.asia/blog/635347.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.4bmje2.asia/blog/010869.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.4bmje2.asia/blog/716381.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.4bmje2.asia/blog/234369.Doc

?
