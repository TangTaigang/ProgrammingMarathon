#Hero

##题目描述

    500年前，redraiment是我国最卓越的剑客。他英俊潇洒，而且机智过人^_^。 突然有一天，redraiment心爱的公主被魔王困在了一个巨大的迷宫中。
    redraiment听说这个消息已经是两天以后了，他知道公主在迷宫中还能坚持T天，他急忙赶到迷宫，开始到处寻找公主的下落。 时间一点一点的过去，
    redraiment还是无法找到公主。最后当他找到公主的时候，美丽的公主已经死了。从此redraiment郁郁寡欢，茶饭不思，一年后追随公主而去了。T_T
    500年后的今天，redraiment托梦给你，希望你帮他判断一下当年他是否有机会在给定的时间内找到公主。 他会为你提供迷宫的地图以及所剩的时间
    T。请你判断他是否能救出心爱的公主。
##输入描述:
    题目包括多组测试数据。
    每组测试数据以三个整数N,M,T(00)开头，分别代表迷宫的长和高，以及公主能坚持的天数。
    紧接着有M行，N列字符，由"."，"*"，"P"，"S"组成。其中
    "." 代表能够行走的空地。
    "*" 代表墙壁，redraiment不能从此通过。
    "P" 是公主所在的位置。
    "S" 是redraiment的起始位置。
    每个时间段里redraiment只能选择“上、下、左、右”任意一方向走一步。
    输入以0 0 0结束。


##输出描述:
    如果能在规定时间内救出公主输出“YES”，否则输出“NO”。

##输入例子:
    4 4 10
    ....
    ....
    ....
    S**P
    0 0 0

##输出例子:
    YES