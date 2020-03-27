# 过渡态方法理论

> 转载自 计算化学公社http://sobereva.com/44 卢天老师的文章

1. [过渡态](./5-8-1.html)

2. [过渡态搜索算法](./5-8-2.html)

    2.1 基于初猜结构的算法

    ​	2.1.1 牛顿-拉弗森法(Newton-Raphson,NR)与准牛顿法(quasi-Newton,QN)

    ​	2.1.2 AH方法(augmented Hessian)

    ​		2.1.2.1 RFO法(Rational Function Optimization，有理函数优化)

    ​		2.1.2.2 P-RFO法(Partitioned-RFO)

    ​		2.1.2.3 QA法(Quadratic Approximation，二次逼近)

    ​		2.1.2.4 TRIM法(trust-region image minimization，置信区域镜像最小化)

    ​		2.1.2.5 在高斯中的常见问题

    ​	2.1.3 GDIIS法(Geometry Direct Inversion in the Iterative Subspace)

    ​	2.1.4 梯度模优化(gradient norm minimization)

    ​	2.1.5 Dimer方法

    2.2 基于反应物与产物结构的算法

    ​	2.2.1 同步转变方法(synchronous transit,ST)
    2.2.2 STQN方法(Combined Synchronous Transit and Quasi-Newton Methods)
    2.2.3 赝坐标法(pseudo reaction coordinate)
    2.2.4 DHS方法(Dewar-Healy-Stewart，亦称Saddle方法)与LTP方法(Line-Then-Plane)
    2.2.5 Ridge方法
    2.2.6 Step-and-Slide方法
    2.2.7 Müller-Brown方法
    2.2.8 CI-NEB、ANEBA方法
    2.3 基于反应物结构的算法
    2.3.1 最缓上升法(least steep ascent,shallowest ascent)
    2.3.2 本征向量/本征值跟踪法(eigenvector/eigenvalue following,EF。也称mode walking/mode following/Walking up valleys)
    2.3.3 ARTn(activation-relaxation technique nouveau)
    2.3.4 梯度极值法(Gradient extremal,GE)
    2.3.5 约化梯度跟踪(reduced gradient following,RGF)
    2.3.6 等势面搜索法(Isopotenial Searching)
    2.3.7 球形优化(Sphere optimization)
    2.4 全势能面扫描

3. [过渡态相关问题](./5-8-3.html)
    3.1 无过渡态的反应途径(barrierless reaction pathways)
    3.2 Hammond-Leffler假设
    3.2 对称性问题
    3.3 溶剂效应
    3.4 计算过渡态的建议流程

4. [内禀反应坐标(intrinsic reaction coordinate,IRC)](./5-8-4.html)

5. [IRC算法](./5-8-5.html)
    5.1 最陡下降法(Steepest descent)
    5.2 IMK方法(Ishida-Morokuma-Kormornicki)
    5.3 Müller-Brown方法
    5.4 GS(Gonzalez-Schlegel)方法

6. [chain-of-states方法](./5-8-6.html)
    6.1 Drag method方法
    6.2 PEB方法(plain elastic band)
    6.3 Elber-Karplus方法
    6.4 SPW方法(Self-Penalty Walk)
    6.5 LUP方法(Locally Updated planes)
    6.6 NEB方法(Nudged Elastic Band)
    6.7 DNEB方法(Double Nudged Elastic Band)
    6.8 String方法
    6.9 Simplified String方法
    6.10 寻找过渡态的chain-of-state方法
    6.10.1 CI-NEB方法
    6.10.2 ANEBA方法(adaptive nudged elastic band approach)
    6.11 chain-of-states方法的一些特点
    6.12 高斯中opt关键字的path=M方法
    6.13 CPK方法(Conjugate Peak Refinement)