# QEMU Board

This is a QEMU board test case repository.

# Test the xilinx-zynq board

1. setup the environment
```bash
export QEMU_PATH=<your qemu path>
```
2. run the test
```bash
./qemu-zynq-test
```

3. check the result
```bash
Test Project: <your path>/qemu-board/hw/arm/xilinx-zynq
    Start 1: xilinx-zynq.zc702
1/3 Test #1: xilinx-zynq.zc702 ......................   Passed
    Start 2: xilinx-zynq.zc706
2/3 Test #2: xilinx-zynq.zc706 ......................   Passed
    Start 3: xilinx-zynq.zed  
3/3 Test #3: xilinx-zynq.zed   ......................   Passed

All tests passed
```