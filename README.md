u# Shipping-Logistics-Management-System
This project helps manage shipping and logistics operations by organizing data for senders, receivers, packages, deliveries, billing, and tracking. It uses a database to make managing and tracking shipments simple and efficient
LPSPI/
│
├── Includes/
│
├── Project_Settings/
│
├── SDK/
│   └── platform/
│       ├── devices/
│       │   ├── common/
│       │   └── S32K144/
│       │       ├── include/
│       │       │   ├── callbacks.h
│       │       │   ├── devassert.h
│       │       │   ├── device_registers.h
│       │       │   ├── status.h
│       │       └── startup/
│       │           ├── startup.c
│       │           └── startup.h
│       │
│       ├── drivers/
│       │   ├── inc/
│       │   │   ├── clock.h
│       │   │   ├── clock_manager.h
│       │   │   ├── edma_driver.h
│       │   │   ├── interrupt_manager.h
│       │   │   ├── lpspi_master_driver.h
│       │   │   ├── lpspi_shared_function.h
│       │   │   ├── lpspi_slave_driver.h
│       │   │   └── pins_driver.h
│       │   │
│       │   └── src/
│       │       └── clock/
│       │           └── S32K1xx/
│       │               ├── clock_S32K1xx.c
│       │               └── clock_S32K1xx.h
│       │
│       ├── clock_S32K1xx.h
│       ├── pcc_hw_access.h
│       ├── pmc_hw_access.h
│       ├── scg_hw_access.h
│       ├── sim_hw_access.h
│       └── smc_hw_access.h
│
├── edma/
│
├── interrupt/
│
├── lpspi/
│   ├── lpspi_hw_access.c
│   ├── lpspi_hw_access.h
│   ├── lpspi_irq.c
│   ├── lpspi_master_driver.c
│   ├── lpspi_shared_function.c
│   └── lpspi_slave_driver.c
│
├── pins/
│
├── rtos/
│
├── board/
│   ├── clock_config.c
│   ├── clock_config.h
│   ├── peripherals_lpspi_1.c
│   ├── peripherals_lpspi_1.h
│   ├── peripherals_osif_1.c
│   ├── peripherals_osif_1.h
│   ├── pin_mux.c
│   ├── pin_mux.h
│   └── sdk_project_config.h
│
└── src/
    ├── icm20948.c
    ├── icm20948.h
    └── main.c
