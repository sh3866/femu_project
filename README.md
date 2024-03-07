# Project for Adding and Improving Features in FEMU

<img width="794" alt="image" src="https://github.com/sh3866/data_analytics_project/assets/86151442/d225ec88-615b-4b7b-aafb-e104202cbc50">

## 🖥️ 프로젝트 설명
Implementing new features to FEMU

## 💻 프로젝트 내용
- Implementation of new I/O statistics module in FEMU
- Performance analysis (IOPS adn GC) using benchmarks
- Implementation of a new (WL-aware) GC mechanism
- Evaluation of the modified GC mechanism (in terms of the device lifetime)

<img width="429" alt="image" src="https://github.com/sh3866/data_analytics_project/assets/86151442/6d0c2d1b-213a-4625-a77e-f48a6fb77351">

## 🥅 프로젝트 목표
Understanding of
- The underlying geometry of your emulated device (LUN, line, block, page, OP, …)
- How a read or a write request is processed (separate paths, address mapping, …)
- How GC is invoked (triggering condition, detailed operation, …)
- How IOPS and WAF are obtained
- How wear imbalance shortens the device lifetime
- Modify the existing GC mechanism to take wear leveling into account
- Explore the impact of varying a parameter of your modified GC mechanism

## ⏰ 개발 기간
23.06.10 ~ 23.08.10

## ⚙️ 개발 환경 및 도구
- C
- FEMU
- LINUX
