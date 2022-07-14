# axt1800-cdt
- 备份/升级
![image](https://user-images.githubusercontent.com/74764072/178956477-865cc7c3-777c-4556-9458-f1948336b763.png)
看看CDT是第几个分区
图下面找到了mtd5是CDT分区
![image](https://user-images.githubusercontent.com/74764072/178981069-da2c9e4b-1552-4061-8dbc-4682538502d6.png)

接下来执行下载包是 dt-AXT1800_1G.bin 丢到当前目录，如图所示
![image](https://user-images.githubusercontent.com/74764072/178981531-70c89040-6530-4d20-b228-c27e2c269625.png)

然后执行mtd write t-AXT1800_1G.bin /dev/mtd5 

![image](https://user-images.githubusercontent.com/74764072/178981816-6284f331-e391-4518-8f3b-3d98e683aa4f.png)

然后reboot重启,开机直接识别1GB内存了
![image](https://user-images.githubusercontent.com/74764072/178982144-23832918-eece-4c16-901d-d13aa4a1604a.png)
