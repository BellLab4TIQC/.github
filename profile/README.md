# BellLab4TIQC

**面向离子阱量子计算的软件与实验工具。**

Software and tooling for trapped-ion quantum computing.

[组织主页](https://belllab4tiqc.github.io/) · [浏览仓库](https://github.com/orgs/BellLab4TIQC/repositories)

我们维护离子阱实验相关的控制软件、设备接口和数据采集工具。

部分仓库为私有仓库，访问代码需要相应权限。

## 实验软件

| 仓库 | 简介 |
| --- | --- |
| [bell](https://github.com/BellLab4TIQC/bell) | 用 Python 编写实验序列，完成编译、执行和数据读回。 |
| [bellhelper](https://github.com/BellLab4TIQC/bellhelper) | Bell Workbench 桌面工作台及配套实验工具，从 helper_418trap 开发分支独立维护。 |
| [helper_418trap](https://github.com/BellLab4TIQC/helper_418trap) | 参数扫描、数据处理、光谱标定和实验记录工具。 |
| [bell-driver](https://github.com/BellLab4TIQC/bell-driver) | Windows 驱动库，通过 XDMA 与控制板卡通信。 |
| [risqc-fpga](https://github.com/BellLab4TIQC/risqc-fpga) | DDS、TTL 和 TCM 板卡的 FPGA 逻辑与 Vivado 工程。 |
| [bell-inspector](https://github.com/BellLab4TIQC/bell-inspector) | JupyterLab 扩展，用于查看 Bell 对象和实验变量。 |

## 设备与采集

| 仓库 | 简介 |
| --- | --- |
| [Devices](https://github.com/BellLab4TIQC/Devices) | 管理设备进程，通过 MQTT 调用设备接口。 |
| [DeviceWeb](https://github.com/BellLab4TIQC/DeviceWeb) | 在浏览器中操作设备、查看状态和监测信息。 |
| [monitor](https://github.com/BellLab4TIQC/monitor) | 定期采集仪器与环境数据，保存记录并处理报警。 |
| [cxp_camera](https://github.com/BellLab4TIQC/cxp_camera) | CXP 相机控制、图像采集与离子图像检测。 |

## 文档与维护

| 仓库 | 简介 |
| --- | --- |
| [docs](https://github.com/BellLab4TIQC/docs) | 成员知识库，整理仓库说明、入门和排障文档。 |
| [belllab4tiqc.github.io](https://github.com/BellLab4TIQC/belllab4tiqc.github.io) | 组织官网，介绍软件方向并提供项目入口。 |
| [.github](https://github.com/BellLab4TIQC/.github) | 维护这份组织公开简介。 |
| [.github-private](https://github.com/BellLab4TIQC/.github-private) | GitHub 组织首页的成员简介与导航。 |
| [demo-repository](https://github.com/BellLab4TIQC/demo-repository) | GitHub 练习仓库，用于熟悉文件编辑、PR 和 Actions。 |

## 开始参与

- **了解项目**：从对应仓库的 README 开始，了解用途、环境要求与使用方式。
- **交流问题**：使用对应仓库的 Issues 记录问题、复现步骤或改进建议。
- **贡献修改**：通过 Pull Request 提交变更，并同步更新相关说明。
- **组织成员**：登录 GitHub 后访问已有权限的仓库；需要额外访问权限时，请联系组织管理员。

## 项目文档

各项目的使用说明与代码一起维护。组织成员可在已授权的仓库中查看详细的开发与实验文档。

---

[访问网站](https://belllab4tiqc.github.io/) · [GitHub 组织](https://github.com/BellLab4TIQC)
