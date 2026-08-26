最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang etcd 分布式锁实现原理
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.t55d91.asia/arts/234140.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.t55d91.asia/arts/420695.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.t55d91.asia/arts/316663.Doc

原标题：Fork 开源项目同步上游代码
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.t55d91.asia/arts/607077.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.t55d91.asia/arts/614149.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.t55d91.asia/arts/426899.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.t55d91.asia/arts/189306.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.t55d91.asia/arts/864356.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.t55d91.asia/arts/089167.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.t55d91.asia/arts/125188.Doc

原标题：消息队列消费堆积扩容处理
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.t55d91.asia/arts/850391.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.t55d91.asia/arts/217197.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.t55d91.asia/arts/483029.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.t55d91.asia/arts/850493.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.t55d91.asia/arts/930051.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.t55d91.asia/arts/539602.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.t55d91.asia/arts/751476.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.t55d91.asia/arts/085986.Doc

原标题：数据库索引重建提升查询速度
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.t55d91.asia/arts/460361.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.t55d91.asia/arts/906473.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.t55d91.asia/arts/330847.Doc

原标题：react 状态管理方案选型对比
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.t55d91.asia/arts/875079.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.t55d91.asia/arts/850738.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.t55d91.asia/arts/330336.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.t55d91.asia/arts/273888.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.t55d91.asia/arts/716871.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.t55d91.asia/arts/450680.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.t55d91.asia/arts/267898.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.t55d91.asia/arts/267908.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.t55d91.asia/arts/760105.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.t55d91.asia/arts/153689.Doc

原标题：golang 项目 docker compose 本地调试
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.t55d91.asia/arts/298032.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.t55d91.asia/arts/391135.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.t55d91.asia/arts/312463.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.t55d91.asia/arts/355886.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.t55d91.asia/arts/281463.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.t55d91.asia/arts/377508.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.t55d91.asia/arts/964184.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.t55d91.asia/arts/906699.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.t55d91.asia/arts/484759.Doc


二、踩坑排错｜Troubleshooting
原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.t55d91.asia/arts/127450.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.t55d91.asia/arts/653504.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.t55d91.asia/arts/546645.Doc

原标题：容器资源限制防止宿主机过载
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.t55d91.asia/arts/389909.Doc

原标题：golang docker 部署 es 本地开发
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.t55d91.asia/arts/501397.Doc

原标题：golang 系统设计错误码体系完整设计
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.t55d91.asia/arts/126647.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.t55d91.asia/arts/961257.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.t55d91.asia/arts/682843.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.t55d91.asia/arts/490721.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.t55d91.asia/arts/311066.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.t55d91.asia/arts/915517.Doc

原标题：golang redis pipeline 批量操作
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.t55d91.asia/arts/922957.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.t55d91.asia/arts/382643.Doc

原标题：依赖安装失败全方位排错
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.t55d91.asia/arts/290729.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.t55d91.asia/arts/990637.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.t55d91.asia/arts/208863.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.t55d91.asia/arts/774270.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.t55d91.asia/arts/786945.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.t55d91.asia/arts/755546.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.t55d91.asia/arts/374431.Doc

原标题：从零学习基础的接口请求与参数处理
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.t55d91.asia/arts/125475.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.t55d91.asia/arts/679219.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.t55d91.asia/arts/724399.Doc

原标题：nodejs 集群模式多核利用实现
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.t55d91.asia/arts/839032.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.t55d91.asia/arts/493141.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.t55d91.asia/arts/453657.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.t55d91.asia/arts/671002.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.t55d91.asia/arts/808721.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.t55d91.asia/arts/267708.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.t55d91.asia/arts/696523.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.t55d91.asia/arts/290912.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.t55d91.asia/arts/293253.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.t55d91.asia/arts/504175.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.t55d91.asia/arts/729129.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.t55d91.asia/arts/049836.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.t55d91.asia/arts/379512.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.t55d91.asia/arts/128042.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.t55d91.asia/arts/932301.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.t55d91.asia/arts/126863.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.t55d91.asia/arts/416300.Doc

三、实战开发｜Practice
原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.t55d91.asia/arts/617855.Doc

原标题：golang 静态文件服务搭建教程
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.t55d91.asia/arts/467638.Doc

原标题：golang redis 缓存击穿防护实现
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.t55d91.asia/arts/792939.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.t55d91.asia/arts/453909.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.t55d91.asia/arts/193264.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.t55d91.asia/arts/256283.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.t55d91.asia/arts/421964.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.t55d91.asia/arts/618896.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.t55d91.asia/arts/591515.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.t55d91.asia/arts/043105.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.t55d91.asia/arts/484764.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.t55d91.asia/arts/615338.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.t55d91.asia/arts/318139.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.t55d91.asia/arts/828966.Doc

原标题：读懂开源项目 README 实用技巧
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.t55d91.asia/arts/645138.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.t55d91.asia/arts/471887.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.t55d91.asia/arts/937001.Doc

原标题：golang docker 部署 es 本地开发
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.t55d91.asia/arts/463322.Doc

原标题：golang 数据库慢查询监控实现
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.t55d91.asia/arts/359280.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.t55d91.asia/arts/563684.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.t55d91.asia/arts/860943.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.t55d91.asia/arts/861994.Doc

原标题：golang 优雅停机服务关闭实现
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.t55d91.asia/arts/200604.Doc

原标题：golang docker 基础命令实操汇总
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.t55d91.asia/arts/785265.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.t55d91.asia/arts/599240.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.t55d91.asia/arts/643116.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.t55d91.asia/arts/124486.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.t55d91.asia/arts/377416.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.t55d91.asia/arts/597721.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.t55d91.asia/arts/372585.Doc

原标题：前端权限路由动态生成实现
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.t55d91.asia/arts/784399.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.t55d91.asia/arts/588102.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.t55d91.asia/arts/525079.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.t55d91.asia/arts/201768.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.t55d91.asia/arts/031790.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.t55d91.asia/arts/506197.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.t55d91.asia/arts/168396.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.t55d91.asia/arts/995027.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.t55d91.asia/arts/689743.Doc

原标题：开源源码阅读拆解学习思路
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.t55d91.asia/arts/426253.Doc

四、架构设计｜Architecture
原标题：调优方案：Web服务内核socket参数调优
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.t55d91.asia/arts/352226.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.t55d91.asia/arts/759589.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.t55d91.asia/arts/768377.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.t55d91.asia/arts/576047.Doc

原标题：golang docker compose 本地开发最佳实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.t55d91.asia/arts/756925.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.t55d91.asia/arts/259973.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.t55d91.asia/arts/320461.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.t55d91.asia/arts/704166.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.t55d91.asia/arts/421795.Doc

原标题：golang gin 路由分组权限管控
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.t55d91.asia/arts/018035.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.t55d91.asia/arts/072069.Doc

原标题：golang redis lua 脚本原子操作
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.t55d91.asia/arts/312248.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.t55d91.asia/arts/297507.Doc

原标题：vue pinia 状态管理实战教程
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.t55d91.asia/arts/052992.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.t55d91.asia/arts/608507.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.t55d91.asia/arts/723000.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.t55d91.asia/arts/101272.Doc

原标题：golang goroutine 协程基础实操
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.t55d91.asia/arts/046996.Doc

?
