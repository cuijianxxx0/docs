---
id: compatibility.md
---

# 版本兼容性说明



- 0.6.0: 该版本不再维护。
- 0.7.0 ~ 0.91: 该版本不再维护。建议数据迁移至 v0.10.x。在数据迁移前需要：
  1. 删除 **/db/wal** 目录。
  2. 更新 SDK 包到匹配的版本。
  3. 参考 API 文档更新客户端代码。
  4. 重新下载并更新服务端配置文件。