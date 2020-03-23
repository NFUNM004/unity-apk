# unity-apk

## 前情提要
- 安装好unity

## 安装Java
1. ![1.PNG](https://upload-images.jianshu.io/upload_images/9779994-65e0fd8e71505b31.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. **（非必要步骤）** 更安装目录，记住文件的安装位置
![2.PNG](https://upload-images.jianshu.io/upload_images/9779994-5381c610ace485da.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 安装成功
![2.8.PNG](https://upload-images.jianshu.io/upload_images/9779994-37a2dddc863e2160.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
## 配置环境变量
1. “在控制面板 → 系统与安全 → 系统 ” 中点击 “高级系统设置”
![3.PNG](https://upload-images.jianshu.io/upload_images/9779994-6e493927dd8819aa.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 在“高级”中点击“环境变量”
![4.PNG](https://upload-images.jianshu.io/upload_images/9779994-b0454b040ba4a406.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 新建一个用户变量，变量名为 **JAVA_HOME** ，变量值为JDK的安装路径，点击确定
![5.PNG](https://upload-images.jianshu.io/upload_images/9779994-05db9d433534d48f.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.编辑PATH的用户变量，在原变量值的后面加上 **%JAVA_HOME%\bin** ，点击确定
![6.PNG](https://upload-images.jianshu.io/upload_images/9779994-a0dd26c87a994f4c.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
## 安装Android SDK
1. ![8.PNG](https://upload-images.jianshu.io/upload_images/9779994-6b98022cb2ba804f.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. ![9.PNG](https://upload-images.jianshu.io/upload_images/9779994-5956065537d4a9f0.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
## 配置unity环境
1.在unity的菜单栏中找到 edit，下拉找到 preferences，如果是如下图所示找不到Android填写路径，可[点击这里进行参考](https://blog.csdn.net/sunbowen63/article/details/86735488)，如无此问题请跳至下一步
![10.PNG](https://upload-images.jianshu.io/upload_images/9779994-0f34376a82ad2742.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 在external tools 中的Android，点击browse浏览选择相对应的文件目录，SDK对应安卓开发平台路径，JDK对Java的路径
![12.PNG](https://upload-images.jianshu.io/upload_images/9779994-f7114f0a4487fc25.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 在菜单栏找到 Build Settings,在Platform 中选中 Android，点击Add Open Scenes
![13.PNG](https://upload-images.jianshu.io/upload_images/9779994-36ca36e896229b82.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 点击Other Settings ,将Package Name 修改为 com.humei.sj，在 Build Settings中点击Build
![14.PNG](https://upload-images.jianshu.io/upload_images/9779994-a1c18592b273ba72.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5. 打包好的apk如图所示：
![15.PNG](https://upload-images.jianshu.io/upload_images/9779994-aaa2c139d3c72f2f.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6. 在手机模拟器打开apk
![16.PNG](https://upload-images.jianshu.io/upload_images/9779994-dc00b2b0249540ee.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

