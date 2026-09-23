# AI Infra 面经合集

> AI 基础设施面试经验整理，涵盖训练框架、推理引擎、GPU 加速、分布式系统等方向。

## 岗位方向细分

| 方向 | 高频考点 | 代表公司 |
| :--- | :--- | :--- |
| GPU 加速 | CUDA/ROCm、Kernel 优化 | AMD、NVIDIA、字节跳动 |
| 推理引擎 | TensorRT、vLLM、Triton | NVIDIA、月之暗面、智谱 |
| 分布式训练 | Megatron、DeepSpeed、NCCL | 零一万物、面壁智能 |
| 系统设计 | 推理服务、显存管理 | 阿里巴巴、腾讯 |

## 面经列表

| 公司 | 方向 | 轮次 | 亮点 | 链接 |
| :--- | :--- | :--- | :--- | :--- |
| AMD | GPU 加速 | 3轮技术+HR | CUDA/ROCm+系统设计 | [查看](../../by-company/AMD/) |

## 高频面试问题清单

### GPU 编程
- [ ] CUDA 线程层次模型（Thread/Block/Grid/Warp）
- [ ] GPU 内存层次（Global/Shared/Register）
- [ ] Bank Conflict 与优化
- [ ] Memory Coalescing
- [ ] Occupancy 计算
- [ ] Warp Divergence
- [ ] ROCm / HIP 与 CUDA 区别

### 推理优化
- [ ] KV Cache 原理与优化
- [ ] PagedAttention
- [ ] Continuous Batching
- [ ] 模型量化（INT8/INT4/FP8）
- [ ] Speculative Decoding
- [ ] TensorRT-LLM
- [ ] vLLM 架构

### 分布式训练
- [ ] 数据并行 / 模型并行 / 流水线并行
- [ ] ZeRO 优化（ZeRO-1/2/3）
- [ ] Megatron-LM 张量并行
- [ ] DeepSpeed 架构
- [ ] 通信原语（AllReduce/AllGather/ReduceScatter）
- [ ] 混合精度训练
- [ ] 梯度累积与检查点

### 系统设计
- [ ] 大规模推理服务设计
- [ ] 多模型部署与调度
- [ ] 显存管理与多租户隔离
- [ ] 推理延迟排查（profiling）
- [ ] Roofline Model

---

> 📌 欢迎投稿你的 AI Infra 面经！请使用 [面经模板](../../templates/interview-template.md) 提交 PR。
