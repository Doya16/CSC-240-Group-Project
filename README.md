<!-- README language switch -->
[![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-1677ff?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-555555?style=for-the-badge)](README.en.md)
<!-- /README language switch -->

# CSC-240-Group-Project

一个 C++ 课程小组项目，当前代码实现了巫师、敌方生物与法术的基础交互。

## 代码结构

| 文件 | 内容 |
| --- | --- |
| `Wizard.h` / `Wizard.cpp` | 巫师的名字、生命值、法力值与治疗方法 |
| `Creature.h` / `Creature.cpp` | 生物的生命值、攻击力、抗性与受伤判定 |
| `Spell.h` / `Spell.cpp` | 法术的法力消耗、伤害及治疗效果 |
| `main.cpp` | 创建 Merlin 和 Goblin，演示 Fireball 与 Healing Light |
| `GroupDriver.cpp` | 小组驱动文件 |

阅读入口为 [`main.cpp`](main.cpp)。当前仓库包含基础演示代码；尚未提供独立的构建配置或完整游戏说明。
