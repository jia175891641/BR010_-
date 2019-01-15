# 简介
通用步进/伺服数控钻床控制器的源代码，控制器为[BR010可编程一体机],厂家可自主二次编程，最为关键的是全中文编程，而且带用户界面和自定义
用户菜单，而不需要像G代码控制器，用户修改一个简单的速度，必须去修改源代码，此控制器使用简单
，性价比高，性能稳定，全国各地都有使用者,部分已出口，稳定性经得起考验!!
现在开源，供大家学习和参考！！
# 程序预览
![image](https://github.com/jia175891641/BR010_-/blob/master/单轴打孔.PNG)
# 打孔流程
分为4段,每段深度和速度可以通过用户的中文菜单调整(不像蛋疼的G语言，改个速度，还要改源程序)。
其中第3段可以设置循环打孔，循环次数可调，比如第3段深度为9mm 用户设定分3次打，那么系统会自动均分为每次打3mm ,并每次均分都有自动退出排削 
适合打长孔。
查看详细说明书
# 程序下载
  点击 右上方 绿色的  【Clone or download】 再点 Download Zip 下载后解压 
  直接双击 .bent  文件，上位机会自动识别或打开，如果需要烧录进控制器，还需要购买烧录器,烧录器驱动
  温馨提示:厂家发货时候，能提供免费烧录服务，欢迎有志之仕在Github上分享您的作品
