# sonolumina
Flight Software + Physics Engine. Simulates a main flight computer + GNC hardware. 

This repo will include sims and src sw for:
Main FC
Devices
Physics Engine
```
sonolumina/
├── CMakeLists.txt
├── soc/
│   ├── cpu_a53/
│   ├── cpu_r5/
│   └── fpga_fabric/
├── drivers/
│   ├── rs422/
│   ├── rs485/
│   └── gpio/
├── fsw/
│   ├── mode_manager/
│   ├── navigation/
│   └── control/
├── sim/
│   ├── imu_sim/
│   ├── st_sim/
│   └── rcs_sim/
├── ground/
│   └── ground_client/
├── messages/
│   └── msg_defs.hpp
└── tests/
```