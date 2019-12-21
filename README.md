###   :triangular_flag_on_post:SpringBoot-Study
​		SpringBoot-Study仓库是一个记录学习本人SpringBoot的过程，基本上都是简单的小案例，每个小案例有配套的图文博文，同时配套一个独立的Module放在github上，在学习的过程中会参考网上他人的博文及视频等资料，这个过程可能会有写的内容跟其他的博主的博文类似。即使是相同的内容，每个人的理解是不同，记录和叙述的方式都是不同，只要怀着对知识敬畏的态度，那么站在巨人的肩膀上摘苹果可能成功的概率会大很多，所以博文有侵权的地方请告知，本人会及时处理。

> #### 本项目搭建的环境及工具🚀

| 环境/工具  | 版本   | 说明                            |
| ---------- | ------ | ------------------------------- |
| Java       | 8+     | jdk1.8及以上                    |
| Maven      | 3.3+   | 3.3版本及以上                   |
| SpringBoot | 2.2.2  | 当前发行的版本                  |
| IDEA       | 2019.1 | 这个要求不大也可以用eclipse工具 |

> #### IDEA项目导入及初始化🎫

​		克隆好项目后，打开idea，点击File-->Open..-->找到SpringBoot-Study文件夹-->点击🆗

![](D:\markdown\SpringBoot-Study\SpringBoot-Study-OpenStudy.png)

​		按需导入对应的模块的Pom.xml后，设置Maven的Enable Import Auto自动导入依赖，运行单个模块如果自动导入依赖出现失败，可以点击对应右边的Maven对应模块的pom.xml下的Lifecycle依次运行clean命令和install命令也可以实现手动刷新Maven导入依赖

![](D:\markdown\SpringBoot-Study\SpringBoot-Study-RunStudy.png)

​		打开每个模块下的src下的main下的Java下xxxApplication文件，确认环境无误后，点击绿色按钮启动即可，这里完全可以按照自己需要，单独导入运行单个模块，节省Maven导入多个模块的依赖的时间。

>#### 每个模块对应的博文🔗

SpringBoot快速入门案例：[springboot-start]( https://www.jianshu.com/p/25e5ed5e6058 )
