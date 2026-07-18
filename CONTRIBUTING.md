# WildSyn 研发协作

WildFlow 研发任务以 GitHub Issue 和组织级 `WildFlow Development` Project 为唯一执行来源。

1. 未确认的需求进入 `Draft`。
2. 范围、验收和依赖确认后进入 `Ready`。
3. 每位成员同时只领取一张主任务。
4. 开发使用独立分支，并通过 Pull Request 合入默认分支。
5. Pull Request 必须关联 Issue，并提供可复查的验证证据。
6. 合并后进入测试或回归，验证通过后才进入 `Done`。
7. 生产部署必须使用仓库内规定的部署脚本，并分别记录构建、迁移、健康检查和公共访问结果。

不要在 Issue、Pull Request、日志或截图中提交密钥、访问令牌、Cookie、用户隐私数据或生产环境文件。
