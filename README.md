## 0. 准备
在项目根路径打开cmd  
*** 将cmd最大化 ***  

## 1. 编译
```shell script
mvn package
```

## 2. 进去jar包文件夹
```shell script
cd target
```

## 3. 运行
```shell script
java -jar -Xmx10240m -Xms1024m hongbin-bad-apple-1.0.0.jar
```
或者
```shell script
java -jar -Xmx10240m -Xms1024m hongbin-bad-apple-1.0.0.jar -config=C:\Users\Lee\Desktop\my-config.properties
```
