#GTool For FlexSim


##欢迎使用

欢迎使用 `GTool`， 致力于解决 FlexSim 建模过程中的痛点，减少苦力劳作，使得建模工程师能够将更多的时间用于实现模型、优化流程等高层次工作。

> 让建模更简单、更快乐 :)

##安装/导入

###全局模式

- 将 `GTool.fsl` 复制到对应 FlexSim 版本安装目录下的`libraries` 文件夹，例如`C:\Program Files\FlexSim7.5\libraries`文件夹下；
- 打开任意FlexSim模型，选择 `File` - `Global Preferences`-`UserLibraries`，将`Number of libraries to open at startup`值设置为 1 ，单击apply，修改下方的文件名为`GTool.fsl`;
- 再次打开模型，即可看到左边`Library`中多了一个 `GTool Library` ,说明配置成功。

###单模型配置

- 打开 FlexSim 模型后，选择`File` - `Open User Libraries` 选中`GTool.fsl`即可。
- 即可看到左边`Library`中多了一个 `GTool Library` ,说明配置成功。

##使用

###打开GTool

- 将GTool 从左方库中拖到某个实体上替换其默认GUI；
- 双击该实体，即可打开；
- 打开后，可以拖动使用Dock GUI 将GTool 贴合在Quick Properties 边上，类似打开User Manual的效果。

###RGB颜色

- 没啥好说，一目了然。

###空间方位

黄选任意实体后，可以：
- 多步进更改实体大小；
- 对实体放大/缩小 10倍；
- 复制实体位置信息，直接黏贴到代码框内。

###更多功能

>COMMING SOON!

##其他信息

###GTool版本

**v1.0**

###版本支持

- GTool 目前支持 FlexSim 版本：7.0+ 
- 7.7+ 提示为老版本制作的用户库，单击确定，继续即可，不影响使用。或者也可以使用`GTool for 7.7+.fsl`。

###反馈/联系

如有任何 BUG 或建议，欢迎发送邮件到 `tsgaozhipeng@163.com`；或在 `https://github.com/FrenkGao/GTool` 下载历史版本、反馈信息。
