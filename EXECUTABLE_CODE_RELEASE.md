# Executable code release

公开代码包：`odb-whitebox-ai-v1.0.1-code.zip`

SHA-256：`20849B87C52E4AB2D1FB2315F6BE8D2814D56217F5E59A12B7BFA7322A20BBF9`

这是第一阶段白盒 AI 的可运行参考代码，不是完整 ODB 工厂。下载后解压，在包根目录运行：

```powershell
python tools/run_aaai27_1914_core_reproduction.py
python -m unittest discover -s tests -p "test_*.py"
```

代码使用一个人工结构化的 July 1914 状态/动作 fixture，执行确定性的 branch-and-prune replay，并输出可读重建和机器摘要。它不包含自然语言端到端解析、第二阶段晶格运行时、第三阶段防越狱、客户数据、运行数据库、密钥或凭据。

许可沿用包内 `CC BY-NC 4.0`：允许署名和非商业复制/改编，禁止商业使用。该许可不是 OSI 软件许可证；商业使用需另行书面许可。
