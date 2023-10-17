# 安装JDK

1. 在https://www.oracle.com/index.html（或百度直接搜索JDK8）找到下再地址下载对应版本
2. 安装JDK
3. 记住安装路径（最好自行设置）
4. 配置环境变量
   1. 我的电脑-->高级系统设置-->环境变量-->系统变量：变量名：JAVA_HOME；变量值：安装路径
   2. 环境变量-->Path-->新建：
      1. %JAVA_HOME%\bin
      2. %JAVA_HOME%\jre\bin
5. 测试Java是否下载成功：cmd-->java -version

# 卸载JDK

1. 删除Java安装目录
2. 删除JAVA_HOME
3. 删除path下关于Java的目录
4. 确认Java卸载成功：cmd-->java -version