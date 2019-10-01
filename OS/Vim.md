# Vi/Vim

![img](assets/vi-vim-cheat-sheet-sch.gif)

## 安装

所有的类Unix系统都会内置Vi编辑器，但是不一定内置Vim编辑器。

## 使用模式

![img](assets/vim-vi-workmodel.png)

### 命令模式

### 插入模式

在`命令模式`下，输入`i`/`a`/`o`皆可进入`输入模式`。

在`输入模式`中，可以使用以下按键：

- **字符按键以及Shift组合**，输入字符
- **ENTER**，回车键，换行
- **BACK SPACE**，退格键，删除光标前一个字符
- **DEL**，删除键，删除光标后一个字符
- **方向键**，在文本中移动光标
- **HOME**/**END**，移动光标到行首/行尾
- **Page Up**/**Page Down**，上/下翻页
- **Insert**，切换光标为输入/替换模式，光标将变成竖线/下划线
- **ESC**，退出输入模式，切换到命令模式

### 底线模式

在`命令模式`下，按下`:`即可进入`底线命令模式`。

| command        | function                                       |
| -------------- | ---------------------------------------------- |
| :q             | 在未作改动的情况下，退出vi/vim程序             |
| :q!            | 忽略改动，强制退出程序                         |
| :w             | 保存改动                                       |
| :wq            | 保存本次改动后退出程序                         |
| :/query-string | 在文件中到定位`<query-string>`第一次出现的位置 |

按**ESC**可随时退出`底线模式`返回到命令模式。在按**ENTER**后，视输入的具体命令来决定跳转到哪一个模式。