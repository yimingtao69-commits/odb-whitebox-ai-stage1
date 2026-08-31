# ODB White-Box AI — Stage 1

这是 ODB（可验证、可恢复、可审计的分层智能系统）第一阶段的公开规范包。

本发布只包含白盒 AI 的理论、状态机语法、形式化对象模型、职责边界和公开方法学。它不是可运行产品，不包含第二阶段晶格运行代码、第三阶段防越狱实现、客户数据、生产数据库、模型凭据、私钥或历史测试包。

## 包含内容

- `docs/01_DS_POLISHED_MANUAL.md`：设计动机与物理类比；
- `docs/02_PLAIN_LANGUAGE_MANUAL.md`：面向普通读者的使用语义；
- `docs/03_FORMAL_MANUAL_AND_SPEC.md`：对象、状态、树、凭证和不变量；
- `docs/04_PUBLIC_CONSTITUTION_FIVE_DEPARTMENTS.md`：公开职责与权限边界；
- `docs/05_PUBLIC_EVIDENCE_AND_CONTEXT.md`：脱敏证据与研究背景。

## 明确边界

本包不能直接启动 ODB，也不声称已经实现通用自然语言推理、防篡改主机安全或生产级审计。第二、三阶段会作为独立版本开发和发布。

## 许可证

本包整体采用 Creative Commons Attribution-NonCommercial 4.0 International（CC BY-NC 4.0）。允许署名、非商业复制和改编；禁止以商业优势或金钱补偿为主要目的的使用。请保留版权、NOTICE 和许可证文本，并在衍生版本中说明修改内容。完整法律文本见 `LICENSE`，许可摘要见 https://creativecommons.org/licenses/by-nc/4.0/ 。本许可证适用于本阶段理论/规范材料，不是软件运行时许可证。

## 版本与时间见证

建议将本目录作为独立 Git 仓库或 Git tag `stage1-v1.0.0` 发布。发布前对本目录生成 SHA-256 清单，并将提交哈希或发布哈希作为公开时间见证。不要上传客户材料、令牌、密码、私钥或未脱敏日志。

## 引用

参见 `CITATION.cff`。如果你希望讨论理论或验证某一部分，请引用版本号和提交哈希，不要把未发布的内部实现当作本公开规范的一部分。
