# SUSTECH-AcceTech
This repository provides the public references for accelerating AI SOC with high energy-efficient performance.
The main applications are focusing on HPC (high performance computing), NAS (neural architecture search) and low-power edge computing.


# Table of Contents
+ [Papers](#papers)
  - [Computing](#computing)
  - [NAS](#nas)
+ [Hardware implementation](#hardware-implementation)


# Papers
### Computing 
#### Mixed-Precision
+ 2018 | BISMO: A Scalable Bit-Serial Matrix Multiplication Overlay for Reconfigurable Computing | NTNU Group | FPL | [`PDF`](https://arxiv.org/pdf/1806.08862.pdf)
+ 2018 | Bit Fusion: Bit-Level Dynamically Composable Architecture for Accelerating Deep Neural Networks | H. Sharma, et al. | ISCA | [`PDF`](https://arxiv.org/pdf/1712.01507.pdf)
+ 2018 | Harnessing GPU Tensor Cores for Fast FP16 Arithmetic to Speed up Mixed-Precision Iterative Refinement Solvers | A. Haidar, et al. | Supercomputing | [`PDF`](http://www.netlib.org/utk/people/JackDongarra/PAPERS/haidar_fp16_sc18.pdf)
+ 2018 | Mixed-precision in-memory computing | Manuel Le Gallo, et al. | Nature Electronics | [`PDF`](https://arxiv.org/pdf/1701.04279.pdf)
+ 2018 | DNPU: An Energy-Efficient Deep-Learning Processor with Heterogeneous MultiCore Architecture | KAIST Group | Micro | [`PDF`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8474942) `look-up Table`
+ 2018 | DNPU: An 8.1TOPS/W Reconfigurable CNN-RNN Processor for General-Purpose Deep Neural Networks | KAIST Group | ISSCC | [`PDF`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7870350) `look-up Table`
+ 2018 | Efficient Fixed/Floating-Point Merged Mixed-Precision Multiply-Accumulate Unit for Deep Learning Processors | H. Zhang, et al. | ISCAS | [`PDF`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8351354)
+ 2018 | Mixed Precision Training | Baidu | ICLR | [`PDF`](https://arxiv.org/pdf/1710.03740.pdf)
+ 2017 | Bit-Pragmatic Deep Neural Network Computing | UToronto Group | Micro | [`PDF`](https://arxiv.org/pdf/1610.06920.pdf) 
+ 2016 | Stripes: Bit-Serial Deep Neural Network Computing | UToronto Group | Micro | [`PDF`](http://www.ece.ubc.ca/~taylerh/doc/stripes_micro16.pdf) 
#### Multiplication
+ 2015 | Performance Analysis of Karatsuba Multiplication Algorithm for Different Bit Lengths | C. Eyupoglu | [`PDF`](https://reader.elsevier.com/reader/sd/pii/S1877042815038999?token=EB87D381723B92FB151FC26BE96E0B744C951A87F571460B2C7668FD0D2F59872C6C38AC5E7E494E9DC8E236AA565DC7)
+ 2015 | An Efficient Floating Point Multiplier Design for High Speed Applications using Karatsuba Algorithm and Urdhva-Tiryagbhyam Algorithm | S. Arish, et al. | ICSC | [`PDF`](https://arxiv.org/ftp/arxiv/papers/1910/1910.00976.pdf)
+ 2014 | An Efficient Baugh-Wooley Multiplication Algorithm for 32-bit Synchronous Multiplication | [`PDF`](https://pdfs.semanticscholar.org/b90b/552371ec9e0bb807e660899d84e78e548c48.pdf)
+ 2013 | Implementation of Baugh-Wooley Multiplier Based on Soft-Core Processor | [`PDF`](https://pdfs.semanticscholar.org/08f4/be48e73961111d58525b6d57574b5fbb1cb0.pdf)
+ 2012 | An Efficient Baugh-Wooley Architecture for Both Signed & Unsigned Multiplication | [`PDF`](http://www.ijcset.com/docs/IJCSET12-03-04-057.pdf)
+ 2012 | A High Speed Wallace Tree Multiplier Using Modified Booth Algorithm for Fast Arithmetic Circuits | [`PDF`](https://pdfs.semanticscholar.org/af1d/7fe13296a9309deacbc72d137804bd4de947.pdf)

+ 201x | title | author, et al. | conf. or Journal | [`PDF`](link)

### NAS
+ 2019 | HAQ: Hardware-Aware Automated Quantization with Mixed Precision | Song Han Group | CVPR | [`PDF`](https://arxiv.org/pdf/1811.08886.pdf)


# Hardware implementation
+ Berkeley HardFloat is a hardware implementation of binary floating-point that conforms to the IEEE Standard for Floating-Point Arithmetic. | [link](http://www.jhauser.us/arithmetic/HardFloat-1/doc/HardFloat-Verilog.html)
+ IEEE 745 floating point from wiki.(ole edition) | [link](https://en.wikipedia.org/wiki/IEEE_754-1985.html)
+ IEEE 745 floating point from wiki.(new edition) | [link](https://en.wikipedia.org/wiki/IEEE_754)


