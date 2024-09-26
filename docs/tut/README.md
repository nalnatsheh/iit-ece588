# Tutorial I: On-board Implementation of Case Study I (Matrix Multiplication): 

## Part 1 : 

```
make vitis
```

Invoke Vivado by simply typing vivado in the terminal
```
vivado
```


```
find . -type f -name "*.hwh"
```
./project_1/project_1.gen/sources_1/bd/design_1/hw_handoff/design_1.hwh

```
cp ./project_1/project_1.gen/sources_1/bd/design_1/hw_handoff/design_1.hwh .
mv design_1.hwh matmul.hwh
```

```
scp -rP 1588 matmul.hwh xilinx@216.47.144.102:/home/xilinx/
```

```
find . -type f -name "*.bit"
```
./project_1/project_1.runs/impl_1/design_1_wrapper.bit

```
cp ./project_1/project_1.runs/impl_1/design_1_wrapper.bit .
mv design_1_wrapper.bit design_1.bit
```

```
scp -rP 1588 mamtmul.bit xilinx@216.47.144.102:/home/xilinx/
```
```
xilinx@216.47.144.102's password:
matmul.hwh                                                                                                                                                                       100%  299KB   6.8MB/s   00:00    
matmul.bit                                                                                                                                                                       100% 3951KB   7.9MB/s   00:00    
```
