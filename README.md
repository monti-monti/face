云计算部署docker  
先进入你的主机  
## 1.复制文件  
$ `git clone https://github.com/jtshinn/test2.git`  
$ `cd test2`  
$ `cd opencv`  
## 2.构建docker镜像  
$ `docker build -t moting_app .`  
## 3.创建容器  
$ `docker run -it --rm -p 8888:8888 moting_app`  
## 使用方法：  
在浏览器里输入：  
`localhost:8888`

***
## 备注
>  
>  
>  
