# 一些设置的记录

#### 搜索 font （设置字体）

- 在Appearance下的font，是在UI options下，是设置菜单栏等的字体。

- 在 Editor 的 General 下的 mouse选项下：Change font size (Zoom) with Ctrl+Mouse 是Ctrl 键配置鼠标滚轮来设置字体大小
- 在 Editor 的 Font下，设置的是写代码窗口的字体大小：大小 18就可以，字体可以使用 Source Code Pro
- 在 Editor 的 Color Scheme 下的 Color Scheme Font下是设置编辑器字体是否使用主题的字体
- console font 是控制台的字体设置

#### 搜索scheme（设置主题）

- Editor下的Color Scheme 来设置主题，主题去：www.themesmap.com 下载

- 别的都是不同文件格式的 scheme，基本不用动

#### 搜索 wrap（取消右侧边线）

- 在 Editor 下的Appearance 下的： show hard wrap guide。。。取消这个配置就是 取消代码编辑框的最右边的竖线的
- 在Editor的General下的 console 中：use soft wraps in console 就是让输出的日志自动换行。

#### 搜索auto或者import（自动导包）

- 找到 Editor下的 auto import  ，设置insert imports on paste 为all。勾选：Add unambiguous 。。。和 Optimize 。。。

#### 搜索encoding（设置编码格式）

- 找到 Editor下的 file encodings修改：Global Encoding 和 Project Encoding 都为UTF-8，还有下面的 Default Encoding for properties files 也为UTF-8，并把后面的勾选上。

#### 搜索completion（设置忽略大小写）

- 找到 Editor 下的 General 下的 Code Completion ，找到 ：case sensitive completion，这句话翻译是：区分大小写的完成。修改为None即可忽略大小写，如果是 fist letter的话，就是首字母要区分大小写，也就是说：如果大小写不对的话，提示的代码补全就没有。
- 找到：insert selected vairant by typing dot。。。当输入点，空格等，就会提示代码补全。

#### 搜索 method （设置方法间的分隔线）

- 找到 Editor 下的Appearance ，找到选项：show method separators。勾选就会有方法分隔线。

#### 搜索tab（设置多行tab标签）

- 找到 Editor下的Editor Tabs ：取消 show tabs in single row，就会显示多个标签页了，调节下面的 tab limit 为一个大的数即可。

#### 搜索 caret row （设置光标所在行的颜色）

- 在 Editor的General 下面，就可以设置光标所在行的颜色了，适用于黑色主题

#### 搜索 background（设置背景图）

- 在Appearance下，找到background image ，选一张照片，最后一个是图片的主体位置，一般选择中间就行，还有透明度的设置等。

#### 搜索 explorer （设置在资源管理器中打开该文件的快捷键）

- 修改为F12即可，占用的快捷键remove就行了。

#### 搜索 toggle（设置进入/退出全屏模式的快捷键）

- 找到 toggle presentation mode 设置快捷键即可

#### 搜索rename（定义重命名的快捷键）

- 找到 Refactor 下面的 rename 设置为F2即可。

#### 搜索mouse（设置移动到单词上就显示文档）

- 找到Editor下的General 下，有个 show quick documentation on mouse move. 打开即可。后面是显示延迟。

#### 搜索weak warning（取消警告线-波浪线）

- 在 General 下，找到weak warning，在下面的演示代码中写着weak warning，取消右边的选项，确定就可以了。
- 找到 unused symbol ，右边取消，就可以去除未使用的变量警告的下划线了。

#### 搜索typo （取消拼写检查）

- 拼写检查有波浪线，鼠标放上去会有提示的：typo xxx，直接找到 Editor 下的 Inspectons 下面的 Spelling 下面的 typo，取消掉这个勾就可以了。typo 翻译为印刷工。