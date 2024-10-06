# NRF24L01-for-STM32
NRF24 library for STM32s. This library is built upon [nrf24l01-lib](https://github.com/elmot/nrf24l01-lib) by [elmot](https://github.com/elmot), and enables the use of multiple NRF24 modules on the same SPI bus.
## IMPROVEMENTS
- Allows using multiple NRF modules on the same SPI bus
- Removed the need for external ```support.h``` file
## Key files
- [nrf24l01/nrf24.h](nrf24l01/nrf24.h) - main header file
- [nrf24l01/nrf24.c](nrf24l01/nrf24.c) - nrf module support code
