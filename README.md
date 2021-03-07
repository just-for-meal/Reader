# Reader
A win32 txt/epub file reader

****
最新release版本：`v1.9.2.0`<br/>
(百度网盘)<br/>
链接: [https://pan.baidu.com/s/1j6a57LefHWe_b1w04HacnA](https://pan.baidu.com/s/1j6a57LefHWe_b1w04HacnA)<br/>
提取码: `hm3d`
****
<br/>
<br/>
<br/>
<br/>
# v1.9.2.0 2021/03/07 功能更新<br/>
1. 在线书源支持https(使用openssl)<br/>
   1.1 增加ssl后，软件大小膨胀到了2.7MB<br/>
   1.2 github issue里面反馈的书源，都已经配置到了bs.json内<br/>
   1.3 由于书源网站一直在变，无法保证书源配置一直可用。<br/>
       如果有书源更新时，我会尽量及时更新到<br/>
       https://github.com/binbyu/Reader/blob/main/bs.json<br/>
2. 在线书源支持页面编码自动识别（修复gbk编码方式的问题）<br/>
3. release包内新增Reader_no_network.exe，该版本为无网络版本<br/>
<br/>
<br/>
<br/>
<br/>
# v1.9.1.0 2021/02/03 功能更新<br/>
1. 更新在线书源配置<br/>
   1.1 修改书源配置规则<br/>
   1.2 支持GET和POST，暂时不支持ssl(即https)<br/>
   1.3 修复原在线书源已经失效的问题<br/>
   1.4 由于书源网站一直在变，无法保证书源配置一直可用。<br/>
       如果有书源更新时，我会尽量及时更新到<br/>
       https://github.com/binbyu/Reader/blob/main/bs.json<br/>
2. 新增首行缩进功能<br/>
3. 修复page up/down按键不能设置为快捷键的问题<br/>
版本：`v1.9.1.0`<br/>
链接: https://pan.baidu.com/s/1uRncUXFaKyyHCztgYVQJow<br/>
提取码: bfyr<br/>
<br/>
<br/>
<br/>
<br/>
# v1.9.0.0 2020/12/25 功能更新<br/>
1. 新增在线阅读功能<br/>
   1.1 使用方法，【设置】>【在线小说】内搜索小说并打开<br/>
   1.2 使用前需要先进行书源配置<br/>
   1.3 书源配置位置：【设置】>【在线小说】>【书源管理】<br/>
   1.4 书源配置方式详见：【设置】>【在线小说】>【书源管理】>【配置说明】<br/>
   1.5 如果快速切换章节，可能会出现打开或者获取章节内容失败的情况。<br/>
       遇到时，请多重试几次。一般可以解决。<br/>
       如果实在不行，请使用浏览器访问书源网站<br/>
       按Ctrl+F5强制刷新浏览器，搜索并打开小说。直到正常获取网页内容后，再次使用软件。<br/>
   1.6 所有小说书籍版权归小说作者所有。<br/>
       所有书源归第三方书源网站所有。<br/>
	   本软件获取的内容均为书源网站公开信息，不会对该网站进行大量和快速请求、不会进行暴力破解、无病毒入侵。<br/>
2. 增加【恢复默认设置】确认框，防止误操作<br/>
3. 增加英文文档单词自动换行功能<br/>
   3.1 需要手动启用，【基本设置】勾选【Word wrap】<br/>
4. 其他bug修复。<br/>
5. 1.9版本初次发布，可能会引入一些bug。<br/>
版本：`v1.9.0.0`<br/>
链接: https://pan.baidu.com/s/1w4f_xGrSWvpjGIGED6dnkA<br/>
提取码: v65a<br/>
<br/>
<br/>
<br/>
<br/>
# v1.8.2.0 2020/9/4 bug修复<br/>
1. 修复软件最小化状态关闭时，会导致软件无法再次打开的bug<br/>
2. 增加标题栏显示章节名称<br/>
3. 增加目录字体跟随文本字体设置<br/>
   3.1 菜单【基本设置】<br/>
4. 关于杀毒软件报毒问题：<br/>
   我暂时没有好的处理方法。<br/>
   我只能保证软件没有病毒。<br/>
版本：`v1.8.2.0`<br/>
链接: https://pan.baidu.com/s/1JMd0YroXYbBsSB2f6qv4kg<br/>
提取码: 9r6e<br/>
<br/>
<br/>
<br/>
<br/>
# v1.8.1.0 2020/8/20 功能更新<br/>
1. 修改编辑模式，现支持档页文本修改<br/>
   退出编辑模式时可以选择保存和取消<br/>
2. 新增【高级设置】：<br/>
   可以自定义目录解析方式。<br/>
   支持正则表达式：正则表达式样例：`第.*章\s+.*`<br/>
   切换小说后不要忘记还原为默认解析方式<br/>
   正则表达式解析速度低于默认解析方式<br/>
3. 修复1.8版本xp系统下面目录显示异常问题<br/>
<br/>
版本：`v1.8.1.0`<br/>
链接: https://pan.baidu.com/s/16CXCmfBZyqHfitsteJXedg<br/>
提取码: p6ju<br/>
<br/>
<br/>
<br/>
<br/>
# v1.8.0.0 2020/8/6 功能更新<br/>
1. 修改菜单栏为中文<br/>
2. 适配高清显示器<br/>
   2.1 解决原来在高清显示器上面会出现模糊的问题<br/>
   2.2 由于开发环境有限（没有高清显示器），可能会有一些遗漏场景和bug<br/>
3. 新增快捷键、热键自定义功能<br/>
   3.1 菜单栏 > 设置 > 按键设置：可以自定义<br/>
4. 新增编辑模式<br/>
   4.1 暂时不支持修改操作，仅用于文本拷贝<br/>
   4.2 默认快捷键：Ctrl + E<br/>
5. 原鼠标双击快速隐藏窗口功能，新增开关设置<br/>
   5.1 菜单栏 > 设置 > 基本设置 > 左右键同时按下隐藏窗口：勾选/去勾选<br/>
6. 自动翻页，新增【翻页】与【滚动】两种模式<br/>
   6.1 菜单栏 > 设置 > 基本设置 > 自动翻页模式：翻页/滚动<br/>
7. 修复一些已知bug<br/>
<br/>
版本：`v1.8.0.0`<br/>
链接: https://pan.baidu.com/s/1rfmyIRFHeY_QckXltSgyRA<br/>
提取码: brnj<br/>
<br/>
<br/>
<br/>
<br/>
# v1.7.0.0 2020/3/17 功能更新<br/>
1. 增加鼠标左右键同时点击时，快速隐藏窗口<br/>
   1.1 注意：隐藏后需要使用热键才能再次显示窗口<br/>
2. 增加简单的书签功能<br/>
   2.1 Ctrl + M：添加书签<br/>
   2.2 菜单栏 > Mark：为书签列表<br/>
   2.3 在书签列表上面鼠标右击，可以删除书签<br/>
3. 增加最小化托盘功能<br/>
   3.1 默认不开启此功能<br/>
   3.2 开启方式：菜单栏 > setting > config > 窗口设置 > 勾选“最小化托盘”<br/>
   3.3 如果勾选，点标题栏“X”，不会直接退出程序，而是最小化托盘<br/>
4. 增加隐藏任务栏图标功能（此功能暂不支持windows xp及以下系统）<br/>
   4.1 默认不开启此功能<br/>
   4.2 开启方式：菜单栏 > setting > config > 窗口设置 > 勾选“隐藏任务栏图标”<br/>
   4.3 勾选此功能，会强制勾选“最小化托盘”，方便用户点击打开窗口<br/>
5. 支持窗口背景全透明，而字体不透明功能。<br/>
   5.1 注意：此功能暂时只能在“隐藏边框 或者 全屏模式”下支持<br/>
   5.2 新增 Ctrl + Shift + 鼠标滚动：直接设置最高/最低透明度。方便快速背景全透明<br/>
       5.2.1 向上滚动：透明度直接最低(alpha = 0xff)<br/>
       5.2.2 向下滚动：透明度直接最高(alpha = 0x01)，基本全透明<br/>
   5.3 绘图效率相比有边框时有所下降<br/>
<br/>
版本：`v1.7.1.0`<br/>
链接: https://pan.baidu.com/s/14F5LBqMD3YUnYQYg-WpAlA<br/>
提取码: xnj8<br/>
<br/>
<br/>
<br/>
<br/>
# v1.6.0.0 2020/2/11 bug修复<br/>
1. 修复部分用户电脑再次打开软件时crash bug<br/>
2. 增加版本更新推送功能<br/>
  2.1 如果使用代理上网，需要配置网络代理：菜单help > proxy<br/>
  2.2 由于没有自己的服务器，这里只能使用github中转获取真实下载地址<br/>
<br/>
版本：`v1.6.1.0`<br/>
链接: https://pan.baidu.com/s/1f_vlXXWO3BDEjiLinaOAXg<br/>
提取码: thd7<br/>
<br/>
<br/>
<br/>
# v1.5.3.0 2020/1/16 bug修复<br/>
1. 修复v1.5.0.0版本引入的，Ctrl+F搜索框无焦点bug（搜索框无法使用和关闭）<br/>
2. 修复小说目录部分章节丢失bug<br/>
<br/>
版本：`v1.5.3.0`<br/>
链接: https://pan.baidu.com/s/1vDQCNNK6Z8F4_D-ZzWgTGg<br/>
提取码: zb7d<br/>
<br/>
<br/>
<br/>
# v1.5.0.0 2020/1/9 功能更新<br/>
1. 支持epub电子书<br/>
  1.1 软件里面只是对epub进行解码。<br/>
  1.2 解码后的文本，按照txt的方式显示。额外多了一个封面图片渲染。<br/>
  1.3 软件内不支持html渲染，如果要增加，需要引入webkit，软件会变得很大很臃肿。<br/>
  1.4 此次更新使用了开源库：zlib和libxml2<br/>
2. 修改目录为 TreeView<br/>
  2.1 支持 鼠标滚轮操作<br/>
  2.2 支持 打开时定位到当前章节<br/>
<br/>
版本：`v1.5.0.0`<br/>
链接: https://pan.baidu.com/s/1vDQCNNK6Z8F4_D-ZzWgTGg<br/>
提取码: hf9b<br/>
<br/>
<br/>
<br/>
# v1.4.0.0 2020/1/2 功能更新<br/>
1. 增加全屏显示功能<br/>
  1.1 F11：全屏/退出全屏<br/>
  1.2 Esc: 退出全屏<br/>
2. 增加背景图片设置功能<br/>
  2.1 setting > image 里面可以设置<br/>
3. 增加窗口透明度调节功能<br/>
  3.1 调节方式：Ctrl + “鼠标滚轮”<br/>
4. 增加自动翻页功能<br/>
  4.1 快捷键：“空格键” 开始/停止自动翻页<br/>
  4.2 setting > setting > config > 自动翻页时间间隔，可以配置，默认为3000ms<br/>
<br/>
版本：`v1.4.0.0`<br/>
链接: https://pan.baidu.com/s/1MV8Di5F3Dd1is6vMQaVOZg<br/>
提取码: r994<br/>
<br/>
<br/>
<br/>
# v1.3.1.0 2019/12/23 功能更新<br/>
适配网友windows pad，无法使用鼠标右键的场景，新增鼠标左键点击左右侧翻页<br/>
1.  翻页模式一：(setting > config > 鼠标左右键点击翻页)<br/>
    1.1.  鼠标左键单击：下一页<br/>
    1.2.  鼠标右键单击：上一页<br/>
    1.3.  详见readme.txt使用说明<br/>
2.  翻页模式二：(setting > config > 鼠标左键点击左右侧翻页)<br/>
    2.1.  鼠标左键点击界面右侧：下一页<br/>
    2.2.  鼠标左键点击界面左侧：上一页<br/>
    2.3.  详见readme.txt使用说明<br/>
3. release版本使用MT模式编译。避免出现vs运行时库依赖问题<br/>
<br/>
版本：`v1.3.1.0`<br/>
链接: https://pan.baidu.com/s/1IuIMWKpgyzgUvUzYej_gWw<br/>
提取码: rman<br/>
<br/>
<br/>
<br/>
# v1.3.0.0 2019/12/13 功能更新<br/>
1. 新增逐行翻页<br/>
  1.1 为了支持逐行翻页，重新编写了翻页算法<br/>
  1.2 按键 ↓：下N行 (N: setting > config > 文本滚动速度，默认为1)<br/>
  1.3 按键 ↑：上N行<br/>
  1.4 鼠标向下滚动：下N行<br/>
  1.5 鼠标向上滚动：上N行<br/>
  1.6 取消原鼠标滚动直接翻页<br/>
2. 新增进度百分比跳转功能<br/>
  2.1 快捷键：Ctrl + G<br/>
3. 新增readme.txt，使用说明文档<br/>
  3.1 readme.txt会放在release包内，请参考<br/>
<br/>
版本：`v1.3.0.0`<br/>
链接: https://pan.baidu.com/s/1-SYmA5BmbpU3Kc249fjyow<br/>
提取码: sw6p<br/>
<br/>
<br/>
<br/>
# v1.2.0.0 2019/11/05 功能更新<br/>
1. 新增热键支持<br/>
  1.1 Alt + T ：窗口置顶/取消置顶<br/>
  1.2 Alt + H ：窗口隐藏/显示<br/>
  1.3 支持热键修改：setting > config<br/>
  1.4 热键支持两键组合 和 三键组合<br/>
  1.5 如果发现默认按键(1.1)无效，说明该热键已经被占用，请参照1.3修改热键<br/>
2. 新增章节快速跳转<br/>
  2.1 ctrl + → ：跳转到下一章节<br/>
  2.1 ctrl + ← ：跳转到上一章节<br/>
3. 支持文件拖拽打开<br/>
  3.1 仅支持单个txt文件操作<br/>
4. 修改再次打开程序会出现两个view的bug<br/>
<br/>
版本：`v1.2.0.0`<br/>
链接: https://pan.baidu.com/s/1TZbU0F5qLe53ggoru5LKfQ<br/>
提取码: qj6i<br/>
<br/>
<br/>
<br/>
# v1.1.0.0 2019/09/17 功能更新<br/>
1. 新增设置项：setting > config<br/>
  1.1 行距间隙：显示行高 = 字体默认高度 + ”行距间隙“<br/>
  1.2 内部边框：文本与边框之间的距离<br/>
  1.3 翻页方式：<br/>
      1.3.1 鼠标点击：鼠标左键单击：下一页，  鼠标右键单击：上一页<br/>
      1.3.2 鼠标滚动：向上滚动：上一页， 向下滚动：下一页<br/>
2. 取消原鼠标左键双击打开文件功能<br/>
3. 取消原鼠标右键双击隐藏/显示，改为快捷键F12<br/>
4. 取消原鼠标按住拖动窗口功能，改为在“隐藏边框”模式时，鼠标左键按住窗口上部区域进行拖动。<br/>
<br/>
<br/>
# v1.0.0.3 2019/09/17 bug修复<br/>
1. 修改行距bug<br/>
<br/>
<br/>
# v1.0.0.2 2019/01/02 更新<br/>
1. 增加鼠标翻页支持：<br/>
     使用方法：鼠标滚动事件（向上滚动：上一页， 向下滚动：下一页） 
<br/>
<br/> 
# v1.0.0.0 首次提交<br/>
软件介绍： 这是一款使用VS2010开发的一款win32 txt小说阅读器。<br/>
主要功能和特点如下：<br/>
1. 支持BOM-UTF8/UTF8/UTF16/BOM-UNICODE LE or BE/UNICODE/GB2312/ANSI等txt文本格式<br/>
2. 支持字体设置<br/>
3. 支持背景颜色设置<br/>
4. 支持窗口大小任意调整<br/>
5. 支持关键字查找，并跳转进度（Ctrl+F）<br/>
6. 自动解析生成txt小说章节目录，可跳转到指定章节<br/>
7. 自动保存每本小说阅读进度，多本小说切换互不影响<br/>
8. 支持右键双击隐藏窗体边框，再次右键双击恢复<br/>
<br/>
