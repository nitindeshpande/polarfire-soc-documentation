## Welcome to PolarFire SoC

PolarFire SoC is Industry’s First RISC-V SoC FPGA Architecture bringing Real-Time capability to Linux, enabling the freedom to innovate in _Low-Power_, _Secure_ and _reliable_ programmable solutions.

## Quick start
To start exploring and evaluating PolarFire SoC features, you can start using the [icicle kit](https://www.microsemi.com/products/fpga-soc/polarfire-soc-icicle-quick-start-guide#hardware) hardware platform. The PolarFire SoC FPGA device on the icicle kit is pre-programmed with a SoC FPGA reference design and a yocto linux image. Follow the [instructions](https://www.microsemi.com/products/fpga-soc/polarfire-soc-icicle-quick-start-guide#getting-started) and power up the icicle kit to see Linux booting up out of the box.

### Updating the pre-programmed FPGA design and the linux image
The PolarFire SoC FPGA reference design and the linux image get updated and released on github regularly. To upgrade the PolarFire SoC FPGA design running on your icicle kit,  [download](https://github.com/polarfire-soc/icicle-kit-reference-design/releases) the reference design programming file and follow the [instructions](https://github.com/polarfire-soc/polarfire-soc-documentation/blob/master/boards/mpfs-icicle-kit-es/updating-icicle-kit/updating-icicle-kit-design-and-linux.md#programming-the-polarfire-soc-design) to program it on your kit.

To upgrade the Yocto Linux image running on your icicle kit with the latest available pre-built images, [download](https://github.com/polarfire-soc/meta-polarfire-soc-yocto-bsp/releases) and follow the [istructions](https://github.com/polarfire-soc/polarfire-soc-documentation/blob/master/boards/mpfs-icicle-kit-es/updating-icicle-kit/updating-icicle-kit-design-and-linux.md#programming-the-linux-image) to program it on your kit.
 
## What do you want to do next?
Choose a starting point from the following list depending on what do you want to do next.

### FPGA designers
If you want to view the the PolarFire SoC reference design and modify it, please click [here](https://github.com/polarfire-soc/icicle-kit-reference-design). 
### Linux application developers
Choose your favaourite build system from the following list.
* Yocto
   For guidelines on building and using yocto, Click [here](https://github.com/polarfire-soc/meta-polarfire-soc-yocto-bsp#microchip-polarfire-soc-yocto-bsp)
* Buildroot
   For guidelines on building and using buildroot, Click [here](https://github.com/polarfire-soc/polarfire-soc-buildroot-sdk#microchip-polarfire-soc-linux-software-development-kit)
### Bare metal and RTOS application developers
For guidelines on runnning bare metal and RTOS applications on the PolarFire SoC, Click [here](https://github.com/polarfire-soc/polarfire-soc-bare-metal-library#polarfire-soc-bare-metal-library)

## Further reading
Detailed documentation on all aspects of the PolarFire SoC FPGA systems can be found [here](https://github.com/polarfire-soc/polarfire-soc-documentation)


