# Sweeping Robot AI - 自主真空机器人路径规划与强化学习

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Status](https://img.shields.io/badge/status-Active-green)

## 📖 项目概述

本项目是一套**完整的单智能体扫地机器人自主路径规划解决方案**，整合了地图构建、路径规划、强化学习、避障和充电策略等核心模块。算法设计专注于在**有限计算资源**（仅CPU）环境下实现高效的清扫任务完成。

### ✨ 核心特性

- ✅ **完全自主探索**：实时构建和更新栅格地图
- ✅ **智能路径规划**：基于A*算法和优先级加权的全覆盖路径规划
- ✅ **动态避障**：静态障碍物识别和官方机器人趋势预测规避
- ✅ **充电策略**：能量管理和智能充电桩利用
- ✅ **强化学习集成**：DQN深度强化学习代理进行策略优化
- ✅ **实时可视化**：Matplotlib可视化地图、轨迹、性能指标
- ✅ **CPU友好**：轻量化设计，无需GPU即可高效运行

## 🏗️ 项目结构
