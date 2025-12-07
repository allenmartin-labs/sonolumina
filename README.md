# sonolumina
Flight Software + Physics Engine. Simulates a main flight computer + GNC hardware. 

This repo will include sims and src sw for:
Main FC
Devices
Physics Engine

File-Tree
sonolumina/
    CMakeLists.txt
    soc/
        cpu_a53/
        cpu_r5/
        fpga_fabric/
        bootloader/
        linker_scripts/
    drivers/
        rs422/
        rs485/
        gpio/
        timers/
        rtos_port/
        fpga_ip/
    middleware/
        ccsds/
        serial/
        scheduler/
        timebase/
    fsw/
        mode_manager/
        services/
            cmd_service/
            tlm_service/
            fault_mgmt/
            time_service/
        navigation/
        control/
        guidance/
        config/
    sim/
        imu_sim/
        st_sim/
        rcs_sim/
        physics_bridge/
        sim_bus/
    physics/
        core/
        disturbances/
        atmosphere/
        celestial/
    ground/
        ground_client/
        proto_defs/
        dashboards/
            localhosts
    messages/
        msg_defs.hpp
    tools/
        log_tools/
        packet_inspector/
    tests/