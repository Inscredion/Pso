# PSO
加权粒子群算法函数求极值c语言代码
迭代次数100次
种群数量50

经典公式如下
ν_ⅈd^(k+1)=ν_ⅈd^k+c_1 r_1 (pbest_ⅈd^k- x_ⅈd^k )+c_2 r_2 (gbest_ⅈd^k- x_ⅈd^k )
                             x_ⅈd^(k+1)=ν_ⅈd^(k+1)+x_ⅈd^k.      
加权算法如下
ν_ⅈd^(k+1)=w*ν_ⅈd^k+c_1 r_1 (pbest_ⅈd^k- x_ⅈd^k )+c_2 r_2 (gbest_ⅈd^k- x_ⅈd^k )           
                             x_ⅈd^(k+1)=ν_ⅈd^(k+1)+x_ⅈd^k.     

上式c1 ， c2取0.5时收敛效果较好，与MATLAB的最优值相比，误差较小，但任然存在。
将c1，c2设置为3时，误差达到最小。


