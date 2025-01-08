# MAME SL GameList编辑器

<<<<<<< HEAD
如果需要汉化中文家用机游戏列表，需要修改mame/hase/文件夹内的.xml文件内的description标签内容，基于此设计了一个简单的编辑器。
=======
| 文件夹名称         | 工具介绍                    |
| ------------------ | --------------------------- |
| MAME-SL-GameList    | MAME SL 游戏列表编辑器      |
| RetroArch-GameList  | RetroArch 游戏列表排序工具  |
| CheatCodeTranslator | RetroArch 金手指汉化工具    |

>>>>>>> 1acded64d119674e8db71bd8789bfa82fa9c5ff3

**以下介绍如何使用此编辑器：**

1. 第一行第一个上传xml文件建议选择最新英文描述的.xml家用机游戏列表文件。其余三个上传文件分别为导入XML文件、LST文件、CSV文件，导入后会把已经汉化的描述填充到Input框内。

2. 注意导入CSV文件会以第一个上传的.xml文件带下划线作为前缀拼接到name名称前和CSV表格的第一列数据比对，CSV文件编码需要时UTF-8。

3. 四个导出按钮只有MMO没有完成。input右边有两个按钮，置顶就是把input为空的数据行置顶，还原就是按照NO.排序显示。

![](https://wolffy1998.github.io/Simulator-Tools/MAME-SL-GameList/image/image.png)
