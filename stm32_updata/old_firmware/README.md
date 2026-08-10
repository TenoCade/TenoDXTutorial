# 旧固件更新方式

[← 返回 STM32 固件更新](../README.md)


## 注意事项

插拔一定要完全断电(主控不亮灯才是断电)

## 更新

### 进入BL

给主控断电，按着主控上面的小按钮，然后插电，接着松开按钮

![alt text](./resources/bl_button.png)

### 启动更新器

在售后群下`SetupSTM32CubeProgrammer_win64.exe`安装  
![alt text](./resources/SetupSTM32CubeProgrammer_win64.png)  
打开更新器  
![alt text](./resources/SetupSTM32CubeProgrammer_win64.ico.png)  
按照图示操作(要先进BL)
![alt text](./resources/updata.png)

完成图中步骤之后插拔主控，看到主控有LED闪烁即为更新成功

---

### 配置主控

1. 群内下载配置工具  
![alt text](./resources/tools1.png)  
2. 解压出内容，选择TenoDXConfig打开  
3. 软件内选择有Aime标识的串口连接
![alt text](./resources/tools2.png)
4. 更改数据格式
![alt text](./resources/tools3.png)