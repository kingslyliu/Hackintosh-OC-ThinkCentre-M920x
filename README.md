 **Hackintosh-OC-ThinkCentre-M920x** 
+ 准系统：Lenovo ThinkCentre M920x  
+ CPU：Intel Core i5-8500T (Coffee Lake)  
+ iGPU：Intel UHD Graphics 630  
+ 网卡：DW1560  
+ 内存：16GB DDR4 2666MHz  
**特性**  
+ 仿冒机型：iMac19,1（SN已去除，需自行补充）  
+ 系统版本：Big Sur 11.3.1  
+ 核显正常，编解码加速正常，显卡FB：3E9B0007，VRAM：1536MB  
+ 内置扬声器、前置耳机、麦克风输出正常，声卡ID：17  
+ WiFi正常，需要加载博通驱动  
+ 蓝牙正常，支持接力，支持随航  
+ 睡眠正常，支持电能小憩  
+ USB端口正常，端口属性正确修正  
+ CPU电源管理正常，支持功率报告  
+ 电源按钮正常，短按1S睡眠，长按>3S弹出关机对话框  
+ EC（SuperIO）正常，支持风扇转速报告  
**已知问题**  
无  
**BIOS配置（版本：M1UKT65A）**  
+ 恢复出厂设置（推荐使用主板CMOS跳线进行完全复位）  
+ 关闭VT-d  
+ 关闭CFG Lock：0x721 0x0  
