
# FPGA Architectures for InfiniTAM

This repository contains a modified version of [InfiniTAM v2](https://github.com/victorprad/InfiniTAM) that can run on an Intel FPGA platform using OpenCL. The OpenCL are optimized to take advantage of the shared memory of an SoC platform, but the code can also run on a PCIe FPGA board.

The repository is organized as follows:

* [Modified InfiniTAMv2 source code](src/InfiniTAM)
	* [OpenCL kernels](src/InfiniTAM/ITMLib/Engine/DeviceSpecific/OpenCL)
* [Program to read recorded data and send them to InfiniTAM](src/ReadData)
* [Design Space Exploration Results](results)
* [SD Card Image](sd_card_image) to run the code on the Terasic DE1 board.


## Paper

```
FPGA Architectures for Dense SLAM
Quentin Gautier, Alric Althoff and Ryan Kastner
ASAP 2019
```


## License

TODO

Note that the InfiniTAM source code retains its original license, copyright Isis Innovation Limited 2014.

