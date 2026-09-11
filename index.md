# 欢迎来到我的作品集

你好！我是 **123cqz**，一名专注于嵌入式开发、音视频流媒体以及系统架构的嵌入式爱好者。

为了保护商业机密与代码隐私，本页面的核心项目源代码均存放于私有仓库。这里将为您展示我的项目架构设计、技术栈以及核心攻坚成果。

---

## 一、 嵌入式与边缘计算应用

### 1. 振动测量FFT算法处理平台 (MeasuredVibrationDemo_RK3568)
**技术栈**：C/C++, 迅为 RK3568 开发板, Linux
* **底层性能优化**：针对迅为 RK3568 硬件平台进行底层性能调优，打通从底层硬件到上层多设备网关连接数据链路。
* **视觉算法部署**：独立完成FFT算法对数据计算在 RK3568 平台的交叉编译与环境配置，支撑实时振动加速度采集与处理模块，以及积分算法得到振动速度。
* **实时数据采集**：实现了传感器数据的实时采集与分析，保证了测量系统的低延迟与高稳定性。
* 运行实况图如下：

> <img width="1206" height="2622" alt="2b1c5bac864343c6c6a9cb99a8481171" src="https://github.com/user-attachments/assets/85b79c2e-d18b-426a-a897-902a02ba1c5c" />
<img width="1206" height="2622" alt="449887eb0660ac083dc47c2145745848" src="https://github.com/user-attachments/assets/66cd6e82-dc6e-4b5a-8b95-e7e91933dc97" />
<img width="1206" height="2622" alt="c1ab47ab91772066e20c0a692329f115" src="https://github.com/user-attachments/assets/54b6835c-3b7c-4a47-ab9c-366b39a0b6b5" />
<img width="1206" height="2622" alt="bf7d652d9f30d2cf29ea8980b5dffa86" src="https://github.com/user-attachments/assets/c1c390e6-2938-404d-962b-0aede0c69dc7" />
<img width="904" height="1966" alt="56dc93e84d9d2f99c91cdefcd18c3bb3" src="https://github.com/user-attachments/assets/c5f970bc-1df7-45a2-b634-01b6c219effd" />


### 2. 全志 T113 平台开发 (T113)
**技术栈**：嵌入式 Linux, C
* **系统级定制**：深入操作系统的内核与外设接口，完成系统级定制与硬件模块适配。
* **驱动调试**：基于 T113 芯片的底层驱动调试，保障工控主板的稳定运行与外部设备通信。
作为测振仪的图形界面，适合传感器的调试与算法更新优化
运行实况图如下：
<img width="1206" height="2622" alt="6ec3ada57906b11dbf6505a2c6d79208" src="https://github.com/user-attachments/assets/5a9ce0c8-81fe-426f-b499-4723a17a2323" />
<img width="904" height="1966" alt="523dce5f1baee1b2d6c0df6f84364386" src="https://github.com/user-attachments/assets/d493c2e2-25d4-42e2-8a44-999dc79eda51" />

---

## 二、 视音频流媒体与客户端开发

### 1. 流媒体播放与多平台客户端 (MukunTV / QTproject)
**技术栈**：C++, Qt, FFmpeg, 网络编程
* **跨平台客户端**：基于 Qt 框架开发跨平台视音频客户端界面，底层深度封装媒体解析引擎。
* **底层媒体流控制**：深入应用 FFmpeg 核心结构体（如 `AVInputFormat` 与 `AVStream`），实现对复杂视频流的精准解析与遍历。
* **动态推拉流**：完成网络地址的动态打开与推拉流控制，优化流媒体在不同网络环境下的缓冲策略与解码效率。

---

## 三、 工业测试与标定系统

### 1. 轨道交通测试系统 (MetroTestSystem)
**技术栈**：C++/C#, 数据库, 串口/网络通信
* **自动化测试**：针对轨道交通场景开发自动化测试与状态监测上位机软件。
* **高可靠通信**：设计高可靠性通信协议处理模块，并发处理多路传感器反馈状态，确保工业级数据记录的完整性与安全性。

### 2. 高精度传感器标定工具 (SensorCalibration)
**技术栈**：数据处理算法, 可视化框架
* **算法工程化**：将原始传感器数据进行滤波、拟合与误差补偿等算法工程化落地。
* **自动化标定**：实现多维度数据的自动化标定流程，提供直观的误差分析图表，大幅降低硬件设备的量产调试成本。

---

## 四、 算法与系统架构探索

### 1. 神经网络与深度学习模型 (neural-network)
**技术栈**：Python, PyTorch/TensorFlow, 计算机视觉/NLP
* **模型搭建与调优**：负责特定场景下的网络模型搭建、训练与超参数调优。
* **工程落地**：具备从算法原型设计到实际工程落地的全流程转换与部署能力。

### 2. 微服务架构后台 (ZhongChaCould)
**技术栈**：Java/Go, Spring Cloud / 分布式架构, 数据库
* **云端中台构建**：构建云端业务中台，处理复杂业务逻辑与海量数据存储。
* **高并发接口**：设计 RESTful API 为前端和 APP 端提供高并发接口支持，实现服务解耦。
