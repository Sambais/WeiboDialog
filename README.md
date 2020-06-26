# WeiboDialog

模仿微博APP的网络加载弹窗，实现效果是微博的样式 



## 如何加入到项目中

**步骤1.**  将JitPack存储库添加到您的构建文件中 

将其添加到存储库末尾的root build.gradle中：

```java
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

 **步骤2.** 添加依赖项 

```java
dependencies {
    		//其中latest.release指代最新版本号，如：1.0.2
	        implementation 'com.github.Sambais:WeiboDialog:latest.release'
	}
```



##  使用

开启弹窗加载：

```java
WeiboDialogUtil.createLoadingDialog(getActivity(), "记载中...");
```

关闭弹窗：

```java
if (WeiboDialogUtil.isShow()) WeiboDialogUtil.closeDialog();
```

 

## 效果

<img src="https://raw.githubusercontent.com/Sambais/WeiboDialog/master/images/weibodialog.gif" style="zoom:67%;" />

------



若有错误或可以改进,欢迎指出,相互学习

  <img src="https://raw.githubusercontent.com/Sambais/WeiboDialog/master/images/8D7A37EAEECB1ED8C7DE294C22DEF74D.jpg" style="zoom: 25%;" />

