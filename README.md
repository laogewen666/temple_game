# Temple_Game游戏设计核心思路
**首先将游戏的核心功能进行实现，接着场景设计遵循从大到小的设计思路，通过megascan中的素材库选取适合游戏风格的资产，并将大致总体大致场景设计出来**
## 最终结果
**最终运行结果在视频中显示了整个游戏流程，视频链接：https://www.bilibili.com/video/BV1zT4y1B7Jv?share_source=copy_web**
## 部分功能实现蓝图
### 激光发射器
![image](https://user-images.githubusercontent.com/73890243/168422219-0ac4b030-9654-4eb5-ac44-a3a842440397.png)
![image](https://user-images.githubusercontent.com/73890243/168422297-ce1a322a-3b20-46cf-9e4b-bf7264944d8a.png)
![image](https://user-images.githubusercontent.com/73890243/168422340-d773914d-2328-4c5b-8dc2-4e13e23e1ce6.png)
![image](https://user-images.githubusercontent.com/73890243/168422352-c91e71b6-aea2-4db1-8a3d-2f88218be726.png)
### 激光发射器蓝图中封装好的函数
![image](https://user-images.githubusercontent.com/73890243/168422465-5dd47b22-21eb-4897-9fe6-1129b9b52a1a.png)
![image](https://user-images.githubusercontent.com/73890243/168422520-029ee8ad-61b1-46d7-84e3-72456c9638dd.png)
![image](https://user-images.githubusercontent.com/73890243/168422596-90d1b51b-d4ab-44f0-a4a6-21387c9d2165.png)


## 核心功能
![image](https://user-images.githubusercontent.com/73890243/168419071-f6c79afa-55ca-4601-913f-eb192d670822.png)
**通过判断激光是否击中触发球体以及机关按钮是否受到物体碰撞，来控制各种旋转，开关门**  
![image](https://user-images.githubusercontent.com/73890243/168419245-8cd5841b-af1b-4d35-a0e9-b6a334d6dee8.png)
**通过碰撞体积来记录玩家出生点信息，当玩家重新开始时能够从存档点继续游戏，并通过播放准备好的音频进行指引**  
![image](https://user-images.githubusercontent.com/73890243/168420068-3f8a68e3-a123-403e-85f3-035ca314ddb8.png)
**黄色门能够防止玩家将上一关卡的反射块带入下一关进行使用，蓝色门能够阻挡激光**
![image](https://user-images.githubusercontent.com/73890243/168420129-78011204-7685-48a8-95af-1eca506eec4c.png)
**三角块能够对激光进行反射从而激活触发球体**
## 场景设计
![image](https://user-images.githubusercontent.com/73890243/168420176-c797380a-0cdd-4ff4-81d2-2eff8541a10e.png)
**整个场景关卡设计如图所示**
![image](https://user-images.githubusercontent.com/73890243/168420217-ca72822f-d467-4497-a109-6163a5b65afe.png)
**通过使用megascan上的免费资产以及激活nanite功能提高画质来进行场景搭建**

## 游戏文件
**因为文件比较大就没上传，只放到了网盘上，贴个网盘链接：https://pan.baidu.com/s/1zIz1JYuV9i2I5_EFmZFohA?pwd=sz3b**



