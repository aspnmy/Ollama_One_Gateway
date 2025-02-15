# Ollama_One_Gateway
Dr.aspnmy 手术视频文献查询 @faka2040_bot, [2025-02-15 9:18]
## 工作原理：
- 1、使用Ollama Scanner扫描Ollama公共服务
- 2、使用Ollama One Gateway作为调度中间层，需要one api配合
- 3、用户查询Ollama One Gateway公共网关时，Ollama One Gateway根据后端-Ollama公共服务最快响应模型进行自动调度问询

## 优点：
- 1、客户端只需要配置一条访问入口
- 2、自行部署方便更快的蒸馏模型
- 3、多后端查询形成一个伪·分布式模式

## 讨论组：
- https://t.me/Ollama_Scanner
