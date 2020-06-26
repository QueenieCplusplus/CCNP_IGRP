# CCNP IGRP
Interior Gateway Routing Protocol

# Convergence, 收斂的方法

* Split Horizon Update, 水平分割

 水平分割使指閘道器會紀錄所接收到的路徑資訊是由哪一個網路介面而來的，同時不可將此路徑傳回給同樣的網路介面，避免造成迴圈。
 
 
                                                  Routing Table A
                                                  
 
 
 
                                  Router A           
                                  
                                 s0      s1
                                 /         \
                                /           \
                               /             \
                              /               \
                            s1   s0 ----- s1   s0   
                           
                       Router B             Router C    E0 ----- E0  Router D
 
 


* Poison Reverse, 毒性逆向

* Hold Down Timer

* Triggered Updates, 觸發更新




