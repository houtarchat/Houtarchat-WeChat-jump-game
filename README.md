# wechat_jump_game
微信跳一跳Python辅助
Windows 免添加配置 adb 环境变量方式
注意：如果你不想在 windows 下面配置 adb，也可以使用不需要配置的 adb 环境变量方式，但是需要在Tool/adb文件下操作，至于如何自动跳转，只需改变执行脚本即可，这里只做演示

1.在Tools/adb文件下操作：按住 shift + 右键 选择在该文件夹下打开命令窗口<br/>
2.打开安卓手机的 usb 调试，并连接电脑，在终端输入 adb devices 进行测试，如果有连接设备号则表示成功<br/>
3.打开微信小游戏，点击开始游戏，然后在cmd中运行代码 python wechat_jump_py3.py，点击出现的图形起点和终点，棋子自动跳转
