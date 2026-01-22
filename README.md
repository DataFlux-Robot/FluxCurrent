# FluxCurrent ⚡️｜统一供电与多路母线 / Unified Power + Multi-Rail Bus

FluxCurrent 是 Flux 模块化具身系统的 **供电与母线底座**：面向“乐高式机体”，用一套统一的供电与分配架构，让不同的手臂/关节/传感器/计算模块能够 **即插即用、稳定供电、可监控可保护**，并为家庭远程具身（VR + 五指遥操作）场景提供更可靠的电力基础。

FluxCurrent is the **power + bus backbone** of the Flux modular embodiment stack. It enables “LEGO-style bodies” by delivering **stable, protected, telemetry-ready power rails** across interchangeable arms/joints/sensors/compute modules—built for real-world teleoperation in home environments.

---

## 项目初衷 | Motivation

在模块化人形/具身系统里，硬件最容易被忽略、但最容易“翻车”的往往不是控制算法，而是供电与布线：  
当你允许用户在几年内逐步升级（换手、换臂、换关节、加传感器），如果没有统一的供电与母线规范，系统就会迅速变成“线束地狱”，并在瞬态负载、插拔、散热与故障保护上埋雷。

FluxCurrent 的目标是把供电这件事做成模块化体系的一等公民：  
**统一接口、统一母线、统一保护与监控**，让“先用得起，再逐步升级”在电力层面也成立。

In modular humanoids, the fastest way to break reliability is messy power and wiring.  
If users can upgrade over years (hands/arms/joints/sensors), a system without a unified power/bus standard quickly becomes a harness nightmare—fragile under transients, hot under sustained loads, and unsafe under faults.

FluxCurrent makes power a first-class citizen:  
**one interface, one bus philosophy, built-in protection and telemetry**, so gradual upgrades remain safe and maintainable.

---

## 核心特性 | Highlights

- **多路母线供电 / Multi-rail power distribution**：为执行器、计算、传感器与外设提供分层供电与分配策略。  
  Delivers layered rails for actuators, compute, sensors, and peripherals.

- **GaN 电源原型方向 / GaN-based prototype direction**：面向更高功率密度与更优效率的家庭机体形态。  
  Targets better power density and efficiency for compact home humanoid builds.

- **模块复用友好 / Modularity-first**：面向可插拔部件，减少“每换一个模组就重做线束”的成本。  
  Designed for plug-in modules to avoid “rewire every upgrade.”

- **保护与可观测性 / Protection & telemetry**（路线核心）：过流/欠压/过压/过温等保护逻辑 + 关键电参监控接口。  
  Fault protection (OCP/UVP/OVP/OTP) + telemetry hooks.

---

## 近期进展 | Recent Progress

- **完成 FluxCurrent GaN 电源原型与多路母线设计**，并在多种机械臂与关节模组上完成兼容性测试，验证“乐高式机体”的电源兼容性。  
  Completed a GaN power prototype and multi-rail bus design, validated via compatibility tests across multiple arm/joint modules.

---

## 后续计划 | Roadmap

### 1) 缩小体积 / Shrink the footprint
- 优化功率级与母线接口布局，适配躯干/底座更紧凑的安装空间  
  Optimize power stage + bus layout for tighter torso/base mounting.
- 线束与连接器体积控制，兼顾可维护性与装配效率  
  Reduce harness/connector bulk while keeping serviceability.

### 2) 提升效率 / Improve efficiency
- 在典型具身负载（待机 + 间歇动作峰值）下提升转换效率与温升表现  
  Improve efficiency/thermals under real embodied workloads (idle + burst motion).
- 增强动态响应，降低瞬态压降对控制稳定性的影响  
  Better transient response to reduce control issues from voltage droop.

### 3) 外壳设计 / Enclosure & industrial design
- 家庭场景触碰安全、走线应力释放、防尘与抗误插  
  Touch-safe, strain relief, dust resistance, anti-misplug design.
- 增加状态指示与故障可视化（电源/母线/热/保护状态）  
  Clear indicators for power/bus/thermal/fault states.

---

## 购买方式 | How to Get One

> 我们采用“社区优先 / 先内测再公开”的硬件发布模式。  
> We follow a community-first hardware release model.

- **[2026.01.22]** FluxCurrent v0.x 内测版本开放，QQ用户群已开启！请扫描二维码加入：  
  **[2025.01.22]** FluxCurrent v0.x early access is live — QQ group is now open! Scan the QR code to join:

 ![QQ Group QR](./f3ab9fa9516dabcfc82e65fb7f163d21.jpg)

- **[2025.01.21]** 加入我们一起打造 FluxCurrent，推动模块化人形具身系统落地。我们正在招聘全职 / 校招 / 实习。  
  简历请发送至：**17792404420@163.com** ：  
  **[2025.01.21]** Join us to build FluxCurrent and shape the future of modular humanoid embodiment. We’re hiring full-time / new grads / interns.  
  Send your resume to: **17792404420@163.com**.
---

## 相关仓库 | Related Repos
- FluxTendril: https://github.com/DataFlux-Robot/FluxTendril  
- FluxWeave: https://github.com/DataFlux-Robot/FluxWeave  
- FluxPulse: https://github.com/DataFlux-Robot/FluxPulse

---

## License
TBD
