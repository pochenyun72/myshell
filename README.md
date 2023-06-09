## 自用shell脚本

| 脚本                 | 功能                                        | 查看文档                                                     | 相关程序                                                  |
| :------------------- | ------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| gitspite.sh          | 将大于100M的文件分割打包成tar方面上传github |                                                              |                                                           |
| mktmp.sh             | 创建自定义临时文件                          |                                                              |                                                           |
| mountGoogledriver.sh | 挂载Google云盘于指定位置                    | [google-drive-ocamlfuse](https://github.com/astrada/google-drive-ocamlfuse) | google-drive-ocamlfuse                                    |
| ocr.sh               | orc识别                                     | [一键OCR识别图片截图文字转文本](https://blog.csdn.net/weixin_39949673/article/details/111116693) | tesseract-ocr<br>imagemagick<br>gnome-screenshot<br>xclip |

##  Linux 命令行编辑快捷键

[引用文档](https://gist.github.com/zhulianhua/befb8f61db8c72b4763d)

初学者在Linux命令窗口（终端）敲命令时，肯定觉得通过输入一串一串的字符的方式来控制计算是效率很低。
但是Linux命令解释器（Shell）是有很多快捷键的，熟练掌握可以极大的提高操作效率。
下面列出最常用的快捷键，这还不是完全版。

* 命令行快捷键：
    * 常用：
        * **Ctrl L** ：清屏
        * **Ctrl M**、**Enter** ：等效于回车
        * **Ctrl C** : 中断正在当前正在执行的程序
    * 历史命令：
        * **Ctrl R**，再按历史命令中出现过的字符串：按字符串寻找历史命令（重度推荐）
        * ~~**Ctrl P** : 上一条命令，可以一直按表示一直往前翻（zsh不适用）~~
        * ~~**Ctrl N** : 下一条命令（zsh不适用）~~
    * 命令行编辑：
        * **Tab** : 自动补齐（重度推荐）
        * **Ctrl A** ： 移动光标到命令行首
        * **Ctrl E** :  移动光标到命令行尾
        * **LeftArrow**、**Ctrl B** :  光标后退
        * **RightArrow**、**Ctrl F** : 光标前进
        * **Ctrl LeftArrow**、**Alt F**  : 光标前进一个单词
        * **Ctrl RightArrow**、**Alt B**  : 光标后退一格单词
        * **Backspace**、**Ctrl H** : 删除光标的前一个字符
        * **Delete**、**Ctrl D** : 删除当前光标所在字符
        * **Ctrl K** ：删除光标之后所有字符
        * **Ctrl U** : 清空当前键入的命令
        * **Ctrl W** : 删除光标前的单词(Word, 不包含空格的字符串)
        * **Ctrl Y** : 粘贴**Ctrl W**或**Ctrl K**删除的内容
        * **Alt .**  : 粘贴上一条命令的最后一个参数（很有用）
        * **Alt [0-9] Alt .**  粘贴上一条命令的倒数第[0-9]个参数
        * **Alt [0-9] Alt . Alt [0-9]  Alt.**  粘贴上上一条命令的倒数第[0-9]个参数
        * ~~**Ctrl ]** : 从当前光标往后搜索字符串，用于快速移动到该字符串（zsh不适用）~~
        * ~~**Ctrl Alt ]** : 从当前光标往前搜索字符串，用于快速移动到该字符串（zsh不适用）~~
        * ~~**Ctrl \\** : 删除光标前的所有空白字符（zsh不适用）~~
        * ~~**Ctrl X Ctrl E** : 调出系统默认编辑器编辑当前输入的命令，退出编辑器时，命令执行（zsh不适用）~~
     * 其他：
        * **Ctrl Z** : 把当前进程放到后台（之后可用''fg''命令回到前台） 
        * **Shift Insert** : 粘贴（相当于Windows的**Ctrl V**）
        * 在命令行窗口选中即复制
        * 在命令行窗口中键即粘贴，可用**Shift Insert**代替
        * **Ctrl PageUp** : 屏幕输出向上翻页
        * **Ctrl PageDown** : 屏幕输出向下翻页
