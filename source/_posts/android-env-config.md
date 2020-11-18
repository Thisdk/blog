---
title: Android 开发环境
tags: 默认
categories: 默认
date: 2020-11-18 11:26:00
---

#### 记录安装开发环境的配置

```
D:\Android\Android Studio
D:\Android\SDK
D:\Android\Home
D:\Android\Gradle
```

#### Java环境配置

```
JAVA_HOME=D:\Android\Android Studio\jre
JRE_HOME=D:\Android\Android Studio\jre\jre
CLASSPATH=.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar
```

#### Android环境配置

```
Android_SDK_HOME=D:\Android\Home
ANDROID_HOME=D:\Android\SDK
GRADLE_USER_HOME=D:\Android\Gradle
```

> PATH

```
%JAVA_HOME%\bin
%JRE_HOME%\bin
%ANDROID_HOME%\platform-tools
```

#### Gradle 下载代理
>D:\Android\Gradle\gradle.properties
```
systemProp.http.proxyHost=127.0.0.1
systemProp.http.proxyPort=1080
systemProp.https.proxyHost=127.0.0.1
systemProp.https.proxyPort=1080
```