# Zeroth Sim Lab

用于 Zeroth-01 机器人的仿真与机器学习实验。

## 简介
本项目旨在在仿真环境中复现 Zeroth-01 机器人的动力学与控制接口，并探索基于强化学习、模仿学习等方法的动作策略训练。

## 内容规划
- 机器人模型导入与仿真验证  
- 控制接口封装（基于 K-Sim / MuJoCo）  
- 训练与评估脚本  
- 结果可视化与性能指标  

## 核心框架与版本
| 模块 | 说明 | 版本 |
|------|------|------|
| Python | 语言环境 | 3.11 |
| JAX | 数值计算与加速 | 0.4.33 |
| jaxlib | GPU 后端（CUDA 12） | 0.4.33 |
| MuJoCo | 物理引擎 | 3.2 |
| Gymnasium | 环境封装 | 0.29 |
| Optax | 优化器库 | 0.2 |
| Flax | 神经网络框架 | 0.8 |
| K-Sim | 仿真与训练接口 | 最新版（自动随 pip 安装） |
| TensorBoard | 训练可视化 | 2.17 |
| TQDM | 训练进度显示 | 4.66 |

## 环境要求
- Distributor ID: Ubuntu  
- Description: Ubuntu 22.04.5 LTS  
- Release: 22.04  
- Codename: jammy  
- Python = 3.11  

## 使用
克隆仓库并进入：
```bash
git clone https://github.com/<你的用户名>/zeroth-sim-lab.git
cd zeroth-sim-lab
