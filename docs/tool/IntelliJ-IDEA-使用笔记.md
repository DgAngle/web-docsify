# IntelliJ IDEA 使用笔记
> 上传时间 2020/10/08

## 软件下载

> **开发工具 ideaIU-2019.2.3 【https://pan.baidu.com/s/1WJjP8OjwPynNtT3DxeFdLg 激活码```m708```】**  
> **软件激活 jetbrains-agent 【https://pan.baidu.com/s/1JXVB7NG2l4855_BjsRRePQ 激活码```f07h```】（内含激活教程）**  

## 如何激活

1. **先下载压缩包解压后得到jetbrains-agent.jar，把它放到你认为合适的文件夹内。**

  > 下载页面：https://zhile.io/2018/08/17/jetbrains-license-server-crack.html

2. **启动你的IDE，如果上来就需要注册，选择：试用（Evaluate for free）进入IDE**

3. **点击你要注册的IDE菜单："Configure" 或 "Help" -> "Edit Custom VM Options ..." ，如果提示是否要创建文件，请点"Yes"。**

  > 参考文章：https://intellij-support.jetbrains.com/hc/en-us/articles/206544869

4. **在打开的vmoptions编辑窗口末行添加：-javaagent:/absolute/path/to/jetbrains-agent.jar**

  > 一定要自己确认好路径(不要使用中文路径)，填错会导致IDE打不开！！！最好使用绝对路径。  
  > 一个vmoptions内只能有一个-javaagent参数。  
  > 示例:  
  >   mac:      -javaagent:/Users/neo/jetbrains-agent.jar  
  >   linux:    -javaagent:/home/neo/jetbrains-agent.jar  
  >   windows:  -javaagent:C:\Users\neo\jetbrains-agent.jar  
  > 如果还是填错了，参考这篇文章编辑vmoptions补救：  
  > https://intellij-support.jetbrains.com/hc/en-us/articles/206544519

5. **重启你的IDE。**

6. **点击IDE菜单 "Help" -> "Register..." 或 "Configure" -> "Manage License..."**

  > 支持两种注册方式：License server 和 Activation code:  
  > 1). 选择License server方式，地址填入：http://jetbrains-license-server （应该会自动填上）  
  >    或者点击按钮："Discover Server"来自动填充地址。  
  > 2). 选择Activation code方式离线激活，请使用：ACTIVATION_CODE.txt 内的注册码激活   
  >    如果激活窗口一直弹出（error 1653219），请去hosts文件里移除jetbrains相关的项目  
  >    如果你需要自定义License name，请访问：https://zhile.io/custom-license.html  

****
本项目在最新2019.2上测试通过。  
理论上适用于目前Jetbrains全系列所有新老版本（这句话是瞎说的，如有问题请给我issue或进QQ群：30347511讨论）。  
IDE升级会从旧版本导入以上设置，导入配置后可能提示未注册（因为刚导入的vmoptions未生效），直接重启IDE即可，无需其他操作。  

本项目只做学习研究之用，不得用于商业用途！  
若资金允许，请点击 [https://www.jetbrains.com/idea/buy/] 购买正版，谢谢合作！  
学生凭学生证可免费申请 [https://sales.jetbrains.com/hc/zh-cn/articles/207154369-学生授权申请方式] 正版授权！  
创业公司可5折购买 [https://www.jetbrains.com/shop/eform/startup] 正版授权！  
