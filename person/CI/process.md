流程描述：
我之前接触到的前端网站部署流程是Github + Jenkins + EC2.实现自动化部署的流程。
以测试分支为例：
我本地代码开发完后push到远程的test分支，github触发更新事件，webhook就会给Jenkins发请求，告诉它我这边有新的变动。Jenkins Job实例收到通知之后，就会自动执行部署脚本。比如先从github test分支拉下最新的代码，执行job编写好的 shell 脚本，比如先pnpm install, 在pnpm run test 最后通过当前部署任务的节点状态来判断是否成功部署，如果没有成功，可以查看部署任务的log来追踪部署的问题。
CI 在 Jenkins 上把 test 分支拉下来跑测试；过了才进入 CD，把源码同步到 EC2 并重启 Node。如果只有 CI，我仍然能安全合代码，但测试站要自己登录服务器发。用户不会自动看到新功能。