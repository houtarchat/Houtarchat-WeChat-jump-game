# wechat_jump_game
_微信跳一跳Python辅助_<br/>
<h3>Windows 免添加配置 adb 环境变量方式</h3>
<img src="http://nzr2ybsda.qnssl.com/images/74643/FgUPXs0kHPOf4r4YUaHYI8acZ1et.JPG?imageMogr2/strip/thumbnail/1920x9000%3E/quality/90!/interlace/1/format/jpg">
<h4>物质需求：</h4>
1.一台Windows电脑（我用的是Windows 10）
2.一部安卓手机
3.Houtarchat.kuaizhan.com
<h4>使用说明：</h4>
1.下载Python3(Houtarchat.kuaizhan.com)记得勾选 "Add Python 3.5 to PATH" 选项哦<br>
2.把本文件下载至桌面,并将下载的文件夹名称改为wechat_jump_game<br>
3.安装依赖文件<br>
打开cmd，依次输入<br/>
cd Desktop/wechat_jump_game/Tools<br>
pip install -r requirements.txt<br>
4.打开安卓手机的 usb 调试(不会的话自行百度)，并连接电脑，在终端输入<br>
adb devices<br>
进行测试，如果有连接设备号则表示成功<br/>
5.打开跳一跳，然后在cmd中运行<br>
python wechat_jump_auto.py<br>
6.慢慢跳吧~~~<br>
7.在跳的时候偶尔快速点击屏幕，向前跳动一点儿，预防微信在结束时显示“分数可疑，不显示在排行榜中”<br>
8.享受朋友们的惊讶吧！<br>
