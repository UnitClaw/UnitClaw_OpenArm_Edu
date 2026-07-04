# UnitClaw_OpenArm_Edu

OpenArm 双臂协作机械臂全套教学开源代码

## 硬件适配

| 硬件平台 | 适配状态 |
|---------|---------|
| 对应 UnitClaw 硬件 | ✅ 完整支持 |

## 环境部署

```bash
# Ubuntu 一键部署
chmod +x install_env.sh
./install_env.sh

# 手动安装 Python 依赖
pip install -r requirements.txt
```

## 目录结构

```text
UnitClaw_OpenArm_Edu/
├── 01_底层运动控制与动作库/
├── 02_ROS2_MoveIt2运动规划/
├── 03_双目视觉与VLA抓取/
├── 04_数字孪生虚实同步/
├── 05_语音LLM整机智能控制/
├── 06_Isaac_Lab_Sim2Real强化学习/
├── 07_Optional_LinkerHand末端灵巧手拓展（高阶选修）/
├── scripts/
├── .gitignore
├── install_env.sh
├── requirements.txt
├── 素材归档索引.md
└── README.md
```

## 素材归档

教学视频、数据集、3D 模型等大文件**不纳入 Git 仓库**，统一存放在外部归档目录：
`C:\2. WWNT\0.1 素材归档\OpenArm双臂配套素材`

详见 `素材归档索引.md`。

## 开源协议

本仓库代码遵循 **GNU General Public License v3.0 (GPLv3)**

1. 校内实验室自用、课堂教学、毕业设计研究无强制开源约束；
2. 若修改本代码后对外销售硬件设备、交付商用实训平台，全部衍生源码必须完整公开；
3. 禁止闭源封装本代码作为同类教学产品对外售卖；
4. 如需商用闭源授权，请联系广东省万物拟态机器人股份有限公司商务渠道申请商业授权。

---

© 广东省万物拟态机器人股份有限公司 | 官网：[UnitClaw.cn](https://UnitClaw.cn)
