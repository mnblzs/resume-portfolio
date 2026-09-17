# 刘积铭 · 简历与项目作品集

> 硬件工程师 · 具身智能机器人 / 消费级外骨骼 / 机器人主控与电源
> ✉️ 2030146103@qq.com ｜ 📍 深圳
> 开源合集：https://oshwhub.com/donnan

本仓库收录本人最新的简历与项目作品集，用于在 GitHub 上集中保存与版本管理。

## 目录

- [简历（resume.md）](./resume/resume.md) ｜ [PDF](./resume/resume.pdf)
- [项目作品集（portfolio.md）](./portfolio/portfolio.md) ｜ [PDF](./portfolio/portfolio.pdf)

## 简历

- **教育**：厦门大学嘉庚学院 · 电气工程及其自动化（2022.09 – 2026.08）
- **实习**：
  - 深圳市亦方创新科技有限公司 · 硬件工程师实习（2025.11 – 2026.05）— 消费级下肢外骨骼
  - 深圳未来动力科技有限公司 · 硬件工程师实习（2026.05 – 至今）— 双臂具身智能机器人 + 可移动底盘
- **项目**：RM 步兵 / 工程机器人（硬件负责人）、电赛循迹小车（省一）、STM32+DRV8303 FOC 驱动器（毕设）
- **核心技能**：Altium Designer / KiCad / 嘉立创 EDA、2–8 层板、电源树、FOC、CAN / RS485

详细版见 [resume/resume.md](./resume/resume.md)。

## 作品集

包含 2 段企业实习经历、5 个代表性硬件项目与在校竞赛获奖 / 社团经历，覆盖消费级外骨骼、具身智能机器人、RoboMaster 竞赛机器人、能源 / 储能小车与无刷电机 FOC 驱动器方向。

**工作经历与项目**

| # | 类别 | 项目 / 经历 | 角色 | 周期 |
| :---: | :---: | :--- | :--- | :---: |
| 01 | 企业实习 | 深圳未来动力科技 · 双臂具身智能机器人 + 可移动底盘 | 硬件工程师（实习） | 2026.05 – 至今 |
| 02 | 企业实习 | 深圳市亦方创新科技 · 消费级运动下肢外骨骼 | 硬件工程师（实习） | 2025.11 – 2026.05 |
| 03 | 硬件项目 | RoboMaster 步兵机器人 | 硬件负责人 | 2023.09 – 2025.09 |
| 04 | 硬件项目 | RoboMaster 工程机器人 | 硬件负责人 | 2024.09 – 2025.09 |
| 05 | 硬件项目 | 工训竞赛太阳能小车 | 硬件核心成员 | 2024.09 – 2025.06 |
| 06 | 硬件项目 | 灰度循迹与 IMU 惯性导航小车 | 硬件核心开发者 | 2024.05 – 2024.09 |
| 07 | 硬件项目 | 基于 ODrive 的 FOC 驱动器 | 毕业设计 | 2026.01 – 2026.06 |
| 08 | 在校经历 | 校 RM 机器人战队 · 工训协会 ｜ 竞赛获奖与社团任职 | 硬件组队员 / 副部长 | 2023.06 – 2025.10 |

> 未来动力实习条目下附 3 张工作成果原理图（整机电源 + 下位机控制、电池电量显示 + 功率开关、USB 3.0 信号整形），点击图片可查看高清版。

详细版见 [portfolio/portfolio.md](./portfolio/portfolio.md)。

## 文件结构

```
resume-portfolio/
├── README.md                 # 本页
├── .gitignore                # 忽略临时文件
├── resume/
│   ├── resume.md             # 简历 Markdown 源文件
│   └── resume.pdf            # 简历 PDF
└── portfolio/
    ├── portfolio.md          # 作品集 Markdown
    ├── portfolio.html        # 作品集 HTML（用于生成 PDF）
    ├── portfolio.pdf         # 作品集 PDF（含全部图片）
    └── imgs/                 # 作品集图片（19 张，统一 400×285）
        ├── img_01.png ... img_19.png
        └── full/             # 高清原图（长边 1400，缩略图可点击放大）
            └── img_17.png ... img_19.png
```

## 使用说明

- 浏览体验推荐直接打开 `portfolio/portfolio.md`（已嵌入图片）。
- 需要分享 / 投递时使用 PDF 版本。
- 修改 `portfolio.md` / `portfolio.html` 后，可用 Edge 无头模式重新生成 PDF：

```bash
"C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" \
  --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf="portfolio\portfolio.pdf" \
  "file:///C:/Users/admin/Desktop/resume-portfolio/portfolio/portfolio.html"
```

## 许可

- 简历与作品集内容仅作为个人求职 / 作品展示使用，**All Rights Reserved**。
- 如需引用或转载，请通过邮箱联系本人。
