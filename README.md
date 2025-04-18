# 基础知识

热升华再转写式打印：比起热升华转印（使用热量在卡上直接进行CMYK印刷）多出了一些步骤，首先将CMYK转印至胶片，然后再将胶片转印至卡片上。

再转写需要消耗转写胶片，因此印刷成本较高，但对于卡片有凹凸不平的情况，印刷效果更稳定

CP500的一次转印部（色带->胶片）在胶片和色带之间进行，使用右侧的热感打印头和左侧的胶轮夹住胶片和色带进行打印。

二次转印部在胶片上部和卡盒底板之间，卡片会一直在这个部分传输和翻转。

# 基本操作

## 打印

安装驱动程序以后，可用Windows默认打印设置进行打印

- 右键图片文件，选择“打印”
- 最大打印尺寸2028*1300，勾选自适应可防止白边
- 多选图片后选择打印，并在首选项中设置双面，即可双面打印

## 拆机顺序

- 按压开门键可打开前板
  - 左侧为转印胶片，右侧为色带
  - 右上角蓝色手柄为清洁滚轮可拉出（更换胶片和色带时同时更换）
- 从上方打开卡盒罩，取出卡盒
- 前板打开的状态取出卡盒后，用手抬起卡盒槽的底板（二次转印部上盖），即可看到印刷（二次转印和翻转）部分
  - 将左侧的二次转印轮固定手柄向左拉，解除锁定后可抬起并支撑上盖
  - 塞卡时，可以转动前面板中间的蓝绿色转轮来移动卡片
  - 转动前面板右侧的蓝绿色转轮，可以操作反转部的转轮（清理时使用）
  - 转动卡盒槽后面的蓝绿色转轮，可以操作进卡转轮和反转部的送卡转轮（清理时使用）

![image](https://github.com/user-attachments/assets/7b758097-b7a9-4d3a-bb26-2902cc7a5c33)
![image](https://github.com/user-attachments/assets/edd42c5d-044f-452d-adea-7c4fe61e0c66)
![image](https://github.com/user-attachments/assets/31b4e75b-720b-42f7-bb7f-be3e5ef86974)
![image](https://github.com/user-attachments/assets/a2fe30e7-6413-4708-ac89-62dc03e68201)
![image](https://github.com/user-attachments/assets/f474605c-bfaa-453a-a7c5-538b7f77649c)



## 维护菜单
- 待机时按下MENU键可进入 User Menu。
  - User Menu 中可以进行清理（Cleaning）：开始后等待冷却；然后根据提示拔出二次转印胶片；然后移除所有卡，放入清洁卡（不干胶朝右）
  - 可以调节二次转印速度和温度（见下）
- 待机时按住MENU键，再按↑↓↑↓，然后松开MENU键即可进入 Service Menu
  - 可以调节打印的各种校准数据（见下）

# 推荐设置

## User Menu > Card Setup

用于设置二次转印的速度和温度，在Service Menu中不可设置

复旦08（F08）自定义卡类型并设置速度20，温度+3：
`Card Type: CARD1(20, +03)`

按下SET键可以分别调节数值

## Service Menu > Adjustment 

### Position

- Print Pos VTC (垂直打印位置) +12
- Print Pos HRZ (水平打印位置) +13
- Print Pos CARD (二次转印开始位置) 0
- Print Pos WIDTH (图像水平拉伸) 0

### Color Shift

各个颜色的打印偏移量
- VTC (C, M, Y): (9, 10, 12)
- HRZ (C, M, Y): (0, 0, 0)

