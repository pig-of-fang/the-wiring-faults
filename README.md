# wiring-fault user location
Wiring faults error refers to reverse connection of neutral line and PE line in user's panel box. This problem commonly existed in the LVDS(low-votage distribution system), we find that the load current of anomaly user with wiring fault will cause certain change of residual current in LVDS. At the follows, we conducted relative analysis using multi-linear regression in SPSS.

The experiment of load current and residual current of LVDS with/without wiring fault are implemented in distribution automation lab to obtain the current data. Load current of each user and natural residual current of LVDS are measured once the LVDS operates without wiring fault. Then，neutral line of No.10 user is connected to PE ground and its ground is connected to the neutral line to simulate wiring fault.

specific data has recorded in an excel file

Firstly, imported the data into SPSS:
![SPSS导入数据](https://user-images.githubusercontent.com/93078282/195973649-d1a4307b-b4a3-4540-b472-6b6a2631ad41.jpg)

Then, performed the regression analysis:
![线性回归](https://user-images.githubusercontent.com/93078282/195973753-fc493392-c114-4cdf-afb3-099d1fd3aadd.jpg)

Thus, a certain result can be obtained:

![回归分析结果](https://user-images.githubusercontent.com/93078282/195973785-530e7fa6-3bb3-4e36-a1a9-45ac0f961cb9.jpg)
![直方图](https://user-images.githubusercontent.com/93078282/195973788-3b756b59-cacc-4ce0-b42d-793c925f85b3.jpg)
