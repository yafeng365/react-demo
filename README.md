
# REACT项目创建，环境
nodejs、webstorm

# 生成项目
## 1、webstorm生成
* File--New--Project；
* React
* Location：填写项目路径和名称
* Node：选本地nodejs
* create-react-app：选本地脚手架 <br>
以上生成一个react项目，需要自己填充js、css、html等。

## 2、指令生成
* 指令生成，可以迅速生成html、css、js等模板，更加方便。
* npm create umi my-app  (my-app为项目名，生成路径按进入路径)
* 这里的umi，是有版本区别的，是对应的类似maven的坐标，可以后续研究如何指定版本

# 碰到的问题
* node的全局global文件设置
* 环境变量的配置问题：可以webstorm指定管理员运行，或者配好全局的环境变量。
* yarn一直有问题，原来是环境变量未配置
* react启动报错： Error: error:0308010C:digital envelope routines::unsupported at new Hash，链接如下，原因是node版本的问题，我用的是18，项目用的是16，降下node版本就可以了，或者升级该包也行。
https://blog.csdn.net/fakerplus/article/details/129694973

# 备注
其实，要简单的话，只需要安装好node就行了。其余的yarn、cnpm、tnpm什么的，也没必要非要用。
