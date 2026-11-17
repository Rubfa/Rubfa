### 冉怀武 / RAN HUAIWU

2026 届 · 大模型应用开发方向。格拉斯哥大学 MSc Information Technology，本科国际经济与贸易。

关注点：RAG 检索链路（混合检索 / 融合 / 精排）与 LLM 应用工程化（LangGraph 编排、流式服务、失败降级）。

#### 项目

| 仓库 | 一句话 | 技术要点 |
| --- | --- | --- |
| [product-manual-rag](https://github.com/Rubfa/product-manual-rag) | 商品说明书 RAG 问答：图文混排 PDF → 可检索切片 → 混合检索 → 精排 → 流式回答 | LangGraph · Milvus 稠密+稀疏双索引 · BGE-M3 · HyDE · RRF(k=60) · BGE-Reranker + 断崖动态 TopK · 召回率评测 R@5=96.4% |
| [nl2sql-data-agent](https://github.com/Rubfa/nl2sql-data-agent) | 电商经营数据问答：自然语言 → SQL，自动召回表/列/指标/枚举值后生成并校验 | LangGraph 12 节点 · Qdrant 语义召回 + ES 精确值召回 · 三路并行 · EXPLAIN 校验 + 单次纠错 · SSE 流式 |

两个项目均附有架构说明、关键取舍与已知短板清单。

#### 联系方式

- 邮箱：18203885370@163.com
- 电话：19254571529
