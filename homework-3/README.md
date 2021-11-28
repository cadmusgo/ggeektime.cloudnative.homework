## 课后作业（第一部分）
现在你对 Kubernetes 的控制面板的工作机制是否有了深入的了解呢？
是否对如何构建一个优雅的云上应用有了深刻的认识，那么接下来用最近学过的知识把你之前编写的 http 以优雅的方式部署起来吧，你可能需要审视之前代码是否能满足优雅上云的需求。

## 作业要求：编写 Kubernetes 部署脚本将 httpserver 部署到 kubernetes 集群，以下是你可以思考的维度

1. 优雅启动 ✔
2. 优雅终止
3. 资源需求和 QoS 保证 ✔
4. 探活 ✔
5. 日常运维需求，日志等级
6. 配置和代码分离


作业提交链接： https://jinshuju.net/f/OfIY3L
提交截止时间：11 月 28 日 23:59



## notes

### 探活
curl -I 172.17.0.3/healthz