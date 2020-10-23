# JitPackTest
测试提交库到jitpack。

本仓库的意义在于记录和测试发布自己的开源库到JitPack。

### 第一步  在 github 创建开源库的仓库

### 第二步 在项目build.gradle中 引入android-maven-gradle-plugin插件

![1](.\static\1.png)

[android-maven-gradle-plugin](https://github.com/dcendents/android-maven-gradle-plugin) 最新版本号点击查看

### 第三步   在你的lib build.gradle文件中 配置如图所示

![2](.\static\2.png)

其中group='com.github.TooWhiteHeroic'  这一段是根据你自身的github用户名来配置的

### 第四步  上传本地代码到github的创建的远程仓库

### 第五步 为你的远程仓库添加一个Tag

先点这![3](.\static\3.png)然后点 Draft a new release or create a new release   我这截图是因为已经添加过![4](D:\WorkCode\AndroidCode\JitPackTest\static\4.png)好的 我们继续往下![5](.\static\5.png)即将接近尾声

### 第六步  切会到你的刚创建仓库的主目录

复制仓库主目录地址路径![image-20201024003618103](D:\WorkCode\AndroidCode\JitPackTest\static\6.png)然后打开[jitpack](https://jitpack.io/)![image-20201024003934527](D:\WorkCode\AndroidCode\JitPackTest\static\7.png)

### 最后补充一点  开源库升级只需将代码上传  然后新建一个tag 就行啦 