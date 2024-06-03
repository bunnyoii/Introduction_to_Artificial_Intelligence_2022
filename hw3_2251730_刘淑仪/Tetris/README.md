# Tetris Based on DQN

## 项目简介

Reinforcement Learning Lab: Tetris Game Based on Deep Q-Network.

强化学习实验：基于 Deep Q-Network 的俄罗斯方块游戏。

![](assets/model_3000.gif)

## 项目运行

* 测试模型

  ```bash
  python test.py
  ```

* 训练模型

  ```bash
  python train.py
  ```

* 查看训练数据

  ```bash
  tensorboard --logdir=tensorboard
  ```

## 不同迭代次数表现

<p align="center">
  <img src="assets/model_300.gif" width="19%">
  <img src="assets/model_600.gif" width="19%">
  <img src="assets/model_900.gif" width="19%">
  <img src="assets/model_1200.gif" width="19%">
  <img src="assets/model_1500.gif" width="19%">
  <br>300 / 600 / 900 / 1200 / 1500 Iterations<br>
  <img src="assets/model_1800.gif" width="19%">
  <img src="assets/model_2100.gif" width="19%">
  <img src="assets/model_2400.gif" width="19%">
  <img src="assets/model_2700.gif" width="19%">
  <img src="assets/model_3000.gif" width="19%">
  <br>1800 / 2100 / 2400 / 2700 / 3000 Iterations<br>
</p>