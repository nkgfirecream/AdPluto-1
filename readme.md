## 运行环境

运行该项目需要JDK 1.8或以上版本，请确认系统已安装JDK1.8或以上版本并配置好JAVA_HOME、PATH等环境变量。
使用Eclipse的导入maven项目功能导入下载的代码后，在Maven菜单中点击Update Project即可下载所需的依赖。
在项目上点击右键，弹出菜单中选择Run As，再选择Maven Package，即可完成编译打包工作，生成的jar包在项目目录下的target文件夹中。

## config.json 配置文件
本项目的配置全部由JSON文件完成，配置文件名为config.json，请不要随意修改。
配置文件由9大项配置组成，其中"basic"为基本的配置，包括需要刷的UV数、及其他指标与之的比例；"url"为需要刷UV的广告主落地页，可以包括宏；"size"为需要遍历的创意尺寸；"camp"中包含为需要遍历的渠道（ADX）ID，及对应的需要遍历的活动ID；"ctid"为需要遍历的创意包ID；"spotid"为需要遍历的广告位ID；"tag"为需要遍历的人群标签值/ID，替换{tag}；"mysql"为MySQL配置，一般情况下不需要改动。
具体请参考config.json文件中的注释。

## 执行
在Windows命令行或Linux终端中进入jar包所在的目录，执行：`java -jar AdPluto.jar`

> 开发文档：`\datas\*`
