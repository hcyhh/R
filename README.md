# R test for github \
#Rstudio上如何关联GitHub教程 \

##1、背景 \
Mac电脑  Rstudio 以及R安装完毕 GitHub建立账号 \

##2、确认是否Mac上安装成功git，如果更新过系统可能会出问题 \
打开终端  输入git version  没问题的话应该输出版本如下： \
![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic.png)
如果更新过系统一般出现报错 \
![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%201.png)￼
解决：终端中输入：xcode-select --install 即可解决（时间会显示需要很久，但其实也就十来分钟）

再重复git version 检查是否正常

3、一系列复杂操作
打开Rstudio-tools-global options-Git/SVN-View public key-复制 \
![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%203.png)
￼
打开GitHub 点击右上角头像 - setting-左边栏SSH and GPG keys-New SSH key
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%204.png)
左边栏Developer settings-左上角Personal access tokens-tokens(classic)-Generate new token
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%206.png)
生成-复制下来给出的token-保存到记事本里后面备用

在GitHub里面新建一个库

Rstudio中新建一个项目
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%207.png)
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%208.png)
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%209.png)
![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%2010.png)
￼
Token是你之前输入的

生成一个R项目

新建一个R脚本输入代码 
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%2011.png)
点击保存
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%2012.png)
发现多了一个R脚本
点击commit
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%2013.png)
注意：此时只是上传到了git的本地库还要上传到GitHub上的远程库才行

再点击push
￼![image](https://github.com/hcyhh/R/blob/main/Pasted%20Graphic%2014.png)
在GitHub上查看更新的代码
OVER

感谢🙏其他大佬提供的帮助！
https://www.imangodoc.com/191031.html
将您的 GitHub 帐户与 R Studio 相关联 - 芒果文档 (imangodoc.com)
https://zhuanlan.zhihu.com/p/30335806
RStudio Git GitHub配合使用 - 知乎 (zhihu.com)



可能是我直接在GitHub上传图的原因 导致了未知的bug哈哈哈哈哈 
提醒就拿来更新代码 复杂操作以待后续研究
