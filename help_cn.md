# 软件介绍

软件界面如下：

![image1](https://heart4lor.gitee.io/ob_frontend/image/image/image1.png)

# 软件安装

- 首先我们打开debug下的安装包，俩个安装程序，上面一个是进阶的修复和安装。这里我们选择第二个进行安装。

  ![图片1](https://heart4lor.gitee.io/ob_frontend/image/install/%E5%9B%BE%E7%89%871.png)

- ------

  我们点击下一步。

  ![图片2](https://heart4lor.gitee.io/ob_frontend/image/install/%E5%9B%BE%E7%89%872.png)

  

- ------

  这里建议安装在其他盘符中，C盘可能需要对应的管理员权限。装在C盘的用户需要将程序以管理员模式打开（怎么打开管理员模式？后面会详细介绍）。

  ![图片3](https://heart4lor.gitee.io/ob_frontend/image/install/%E5%9B%BE%E7%89%873.png)

- ------

  然后我们一直点击下一步，等待程序安装完成。

  ![图片4](https://heart4lor.gitee.io/ob_frontend/image/install/%E5%9B%BE%E7%89%874.png)

  ![图片5](https://heart4lor.gitee.io/ob_frontend/image/install/%E5%9B%BE%E7%89%875.png)

  



# 导入数据

- 开始使用：点击open选择对应的病人文件

  ![image1](https://heart4lor.gitee.io/ob_frontend/image/image/image1.png)

- ------

  点击Start并运行。

  ![image2](https://heart4lor.gitee.io/ob_frontend/image/image/image2.png)

# 查看图片

- 正确的图片列表显示如下，下标是图片对应的嗅球体积，可能有一些不满意的结果，这里我们可以右击删除不满意的图片。也可以将这些图片备份至其他盘。

  ![image5](https://heart4lor.gitee.io/ob_frontend/image/image/image5.png)

- ------

  当然，我们可以双击图片进入详细界面，这里open是打开对应图片路径。滑轮滚动是放大或缩小图片。

  ![iamge6](https://heart4lor.gitee.io/ob_frontend/image/image/iamge6.png)

# 处理错误

- 当出现错误时候，我们只需要右击点击选择对应的正确序列并重新运行即可。

  ![image4](https://heart4lor.gitee.io/ob_frontend/image/image/image4.png)

  

# 编辑图片

- 编辑图片主要有拖拽，放大，缩小，创建焦点，编辑焦点，填充，回退，重绘等功能。具体界面如下图所示。

  ![image7](https://heart4lor.gitee.io/ob_frontend/image/image/image7.png)

- ------

  当然我们第一步首先将图片放大至所要绘制嗅球的部位，点击左上角放大镜进行图像放大。为了保证图片不至于失真，不能无限制放大。

- ------

  第二步是创建合适的焦点，点击Create Polygons，在嗅球的附近描绘出对应的轮廓。

  ![image9](https://heart4lor.gitee.io/ob_frontend/image/image/image9.png)

- ------

  第三步点击Edit Polygons按钮，调整焦点区域内位置，使其更能完整描绘出嗅球。

  ![image10](https://heart4lor.gitee.io/ob_frontend/image/image/image10.png)

- ------

  第四步此时可以先Full一下浏览一下再做提交，也可以直接Submit。Submit之后会计算出当时描绘嗅球区域的面积，并保存至相应文件夹中。

  ![image11](https://heart4lor.gitee.io/ob_frontend/image/image/image11.png)

# 常见问题及错误

- 当打开软件时，出现下面的错误时，比如下图所示。

  ![fail1](https://heart4lor.gitee.io/ob_frontend/image/fail/fail1.png)

  **错误原因**

  原因是由于将软件装在C盘，导致权限不够，无法访问。

  **解决方案**

  1.我们首先右击程序图片，选择属性。

  ![fail2](https://heart4lor.gitee.io/ob_frontend/image/fail/fail2.png)

  2.选择兼容性，并将下面的（以管理员身份运行此程序）上打勾，并点击确定。

  ![fail3](https://heart4lor.gitee.io/ob_frontend/image/fail/fail3.png)

  ps:当然你也可以卸载此软件，重新安装在其他盘符，这个问题也能得到解决。

- 在运行软件途中发生意外错误或者长时间没有进行处理。

  **错误原因**

  原因是运行此软件时候，不小心将下方这个软件服务器关闭。如图所示：

  ![fail4](https://heart4lor.gitee.io/ob_frontend/image/fail/fail4.png)

  **解决方案**

  只需要重新启动软件即可，不过放心，该软件将继续上一次的进度开始运行。

- 其他注意事项

  另外，安装或者运行软件过程中，杀毒软件报异常时，一律设置为信任该软件，如以下情况。

  ![fail5](https://heart4lor.gitee.io/ob_frontend/image/fail/fail5.png)