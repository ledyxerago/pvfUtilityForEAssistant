# pvfUtilityForEAssistant
pvfUtility链接易语言源码

pvfUtility官方文档链接：
https://gitee.com/icshare/pvfUtilityWebApi

使用了zyjson和鱼刺的http模块
原因是打算后续开发和api调用更好使用多线程操作


调用方式：

.版本 2

' 初始化PU链接 (“27019”)

' 调试输出 (“-------------------------------------获取文件Icon图标--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取文件Icon图标 (“equipment/character/fighter/weapon/tonfa/102030149.equ”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------批量代码获取详细信息--------------------------------------------”)
' 加入成员 (lst名字数组, “equipment”)
' 加入成员 (lst名字数组, “stackable”)
' 加入成员 (代码数组, 202028002)
' 加入成员 (代码数组, 20216923)
' 调试输出 (编码_utf8到gb2312 (批量代码获取详细信息 (lst名字数组, 代码数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------代码获取详细信息--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (代码获取详细信息 (“equipment”, “202028002”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取当前载入的封包文件路径--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取当前载入的封包文件路径 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------pvf封包另存为--------------------------------------------”)
' ' 调试输出 (编码_utf8到gb2312 (pvf封包另存为 (“E:\Script.pvf”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取查找面板文件资源管理器选中文件集合--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取查找面板文件资源管理器选中文件集合 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取文件资源管理器选中文件集合--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取文件资源管理器选中文件集合 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------确认文件是否存在--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (确认文件是否存在 (“equipment/character/fighter/weapon/tonfa/102030149.equ”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取文件list集合--------------------------------------------”)
' 加入成员 (获取文件list集合文件路径数组, “equipment/character/fighter/weapon/tonfa/102030149.equ”)
' 加入成员 (获取文件list集合文件路径数组, “equipment/character/fighter/weapon/tonfa/baikanfu_used.equ”)
' 加入成员 (获取文件list集合文件路径数组, “equipment/character/fighter/weapon/tonfa/baikanfu.equ”)
' 调试输出 (编码_utf8到gb2312 (获取文件list集合 (获取文件list集合文件路径数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取当前正在编辑的文档--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取当前正在编辑的文档 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取查找面板文件资源管理器具有焦点的文件路径--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取查找面板文件资源管理器具有焦点的文件路径 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取文件资源管理器具有焦点的文件路径--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取文件资源管理器具有焦点的文件路径 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------批量获取物品信息--------------------------------------------”)
' 加入成员 (批量获取物品信息文件路径数组, “equipment/character/fighter/weapon/tonfa/baikanfu.equ”)
' 加入成员 (批量获取物品信息文件路径数组, “equipment/character/fighter/weapon/tonfa/baikanfu_used.equ”)
' 调试输出 (编码_utf8到gb2312 (批量获取物品信息 (批量获取物品信息文件路径数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取物品信息--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取物品信息 (“equipment/character/fighter/weapon/tonfa/baikanfu_used.equ”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------批量上传新的文件内容--------------------------------------------”)
' 加入成员 (批量上传新的文件内容文件路径数组, “nexon/1.txt”)
' 加入成员 (批量上传新的文件内容文件路径数组, “nexon/2.txt”)
' 加入成员 (批量上传新的文件内容文件内容数组, “//111”)
' 加入成员 (批量上传新的文件内容文件内容数组, “//222”)
' 调试输出 (编码_utf8到gb2312 (批量上传新的文件内容 (批量上传新的文件内容文件路径数组, 批量上传新的文件内容文件内容数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------上传新的文件内容--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (上传新的文件内容 (“nexon/3.txt”, “//333”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------批量删除文件--------------------------------------------”)
' 加入成员 (批量删除文件文件路径数组, “nexon/1.txt”)
' 加入成员 (批量删除文件文件路径数组, “nexon/2.txt”)
' 调试输出 (编码_utf8到gb2312 (批量删除文件 (批量删除文件文件路径数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------删除文件--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (删除文件 (“nexon/3.txt”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取主要的lst文件列表--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取主要的lst文件列表 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------批量获取文件内容--------------------------------------------”)
' 加入成员 (批量获取文件内容文件路径数组, “equipment/2022skin/at_fighter/1680100.equ”)
' 加入成员 (批量获取文件内容文件路径数组, “equipment/2022skin/at_fighter/1680101.equ”)
' 调试输出 (编码_utf8到gb2312 (批量获取文件内容 (批量获取文件内容文件路径数组)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取文件内容--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取文件内容 (“equipment/2022skin/at_fighter/1680100.equ”, 真)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取Pvf根目录列表--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取Pvf根目录列表 ()))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取文件列表--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取文件列表 (“town”, “.twn”)))

' 调试输出 (“”)
' 调试输出 (“-------------------------------------获取pvfUtility版本号--------------------------------------------”)
' 调试输出 (编码_utf8到gb2312 (获取pvfUtility版本号 ()))

