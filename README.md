# Hi, 我是武佳乐 (@DanMo661)

嵌入式开发 / 机器人 / 机器学习。五邑大学。

## 🐕 宇树机器狗 Unitree Go2 专区

机器狗链路的全部仓库都打了 `unitree` / `unitree-go2` / `robot-dog` 标签，
**点任一仓库的标签即可聚合同类仓库**（GitHub 的"文件夹"）。

| 仓库 | 是什么 |
|---|---|
| [Unitree-Dog-WalnutPi-Setup](https://github.com/DanMo661/Unitree-Dog-WalnutPi-Setup) | **主仓库**：Go2 × 核桃派 1B × G12 遥控链路配置流程——从空 TF 卡到遥控器直控机器狗的完整 SOP（烧卡/部署/WiFi 双档案/狗联调/遥控器标定/验证清单）+ 全套源码，三套实机验证 |
| [unitree_webrtc_connect](https://github.com/DanMo661/unitree_webrtc_connect) (fork) | 宇树官方 WebRTC SDK 驱动（Go2/G1/R1），链路的"SDK 转发层"本体；fork 带 Windows 中文环境与分块传输修复 |
| [MissionPlanner](https://github.com/DanMo661/MissionPlanner) (fork) | ArduPilot 地面站；fork 自修了安卓版启动崩溃（TypeConverter 补丁，上游 issue #3620 验证），机器狗配飞控导航用 |

链路一句话：**任意 SBUS 遥控器 → 主控板（跑宇树 WebRTC SDK 转发层）→ 交换机 → 狗主控**。
三个角色均可替换（核桃派↔树莓派、G12↔任意 SBUS 遥控器），详见主仓库 README。

## 其他项目

ROS 2 策略桥 [pusht_ros_bridge](https://github.com/DanMo661/pusht_ros_bridge) ·
AI 日报 [AI-DailyPulse](https://github.com/DanMo661/AI-DailyPulse) ·
交付审计技能 [nitpick](https://github.com/DanMo661/nitpick) ·
学习通 MCP [Xuexitong-mcp](https://github.com/DanMo661/Xuexitong-mcp)
