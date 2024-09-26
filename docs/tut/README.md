# Tutorial I: On-board Implementation of Case Study I (Matrix Multiplication): 

## Part 1 : 

```
make vitis
```

Invoke Vivado by simply typing vivado in the terminal
```
vivado
```

![1](./assets/fig/1.png)
![1](./assets/fig/2.png)
![1](./assets/fig/3.png)
![1](./assets/fig/4.png)
![1](./assets/fig/5.png)
![1](./assets/fig/6.png)
![1](./assets/fig/7.png)
![1](./assets/fig/8.png)
![1](./assets/fig/9.png)
![1](./assets/fig/10.png)
![1](./assets/fig/11.png)
![1](./assets/fig/12.png)
![1](./assets/fig/13.png)
![1](./assets/fig/14.png)
![1](./assets/fig/15.png)
![1](./assets/fig/16.png)
![1](./assets/fig/17.png)
![1](./assets/fig/18.png)
![1](./assets/fig/19.png)
![1](./assets/fig/20.png)
![1](./assets/fig/21.png)
![1](./assets/fig/22.png)
![1](./assets/fig/23.png)
![1](./assets/fig/24.png)
![1](./assets/fig/25.png)
![1](./assets/fig/26.png)
![1](./assets/fig/27.png)
![1](./assets/fig/28.png)
![1](./assets/fig/29.png)
![1](./assets/fig/30.png)
![1](./assets/fig/31.png)
![1](./assets/fig/32.png)
![1](./assets/fig/33.png)
![1](./assets/fig/34.png)
![1](./assets/fig/35.png)
![1](./assets/fig/36.png)
![1](./assets/fig/37.png)
![1](./assets/fig/38.png)
![1](./assets/fig/39.png)
![1](./assets/fig/40.png)
![1](./assets/fig/41.png)
![1](./assets/fig/42.png)
![1](./assets/fig/43.png)



```
$ find . -type f -name "*.hwh"
```
$ ./project_1/project_1.gen/sources_1/bd/design_1/hw_handoff/design_1.hwh

```
cp ./project_1/project_1.gen/sources_1/bd/design_1/hw_handoff/design_1.hwh .
```

```
find . -type f -name "*.bit"
```
./project_1/project_1.runs/impl_1/design_1_wrapper.bit

```
cp ./project_1/project_1.runs/impl_1/design_1_wrapper.bit .
```

```
mv design_1.hwh matmul.hwh
mv design_1_wrapper.bit design_1.bit
```

```
scp -rP 1588 matmul.hwh matmul.bit matmul.ipynb xilinx@216.47.144.102:/home/xilinx/
```

```
$ xilinx@216.47.144.102's password:
```
