# Linux 中用xmodmap 修改键位
1. 首先安装xorg组
1. 写入文件
1. xmodmap -pke > ~/.xmodmap
1. 修改.xmodmap文件

修改步骤：
1. 找出需要修改的键位
1. 替换=后的名称
1. 刷新配置文件 xmodmap "文件名"  
注：使用xev可以查看按的键的keycode

例如修改Caps Lock和Esc键
1. 找出两个键位的keycode
1. 交换keycode后的名称
1. 刷新文件
1. 特殊：需要在文件开头添加clear lock
1. 其他键位修改类似
