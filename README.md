# Arknights Auto Chess
一款基于 Qt6 + C++17 开发的明日方舟主题自走棋游戏。

## 项目介绍
本项目复刻了明日方舟的职业体系与对战规则，实现了网格战场、干员部署、敌人行进、自动战斗等核心玩法，采用模块化架构设计，界面与逻辑解耦，具备良好的可扩展性。

## 开发环境
- 语言：C++17
- 框架：Qt 6.x
- 构建工具：CMake 3.16+
- 平台：Windows / Linux / macOS

## 功能列表
- [x] 网格战场与基础交互
- [x] 干员与敌人基础数据模型
- [ ] 多职业干员特性与技能系统
- [ ] 敌人路径与波次刷新
- [ ] 羁绊效果与阵容搭配
- [ ] 多关卡与难度系统

## 构建与运行
```bash
# 克隆仓库
git clone https://github.com/你的用户名/arknights-auto-chess.git
cd arknights-auto-chess

# 创建构建目录
mkdir build && cd build
cmake ..
make -j4

# 运行程序
./arknights-auto-chess
