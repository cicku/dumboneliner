# dumboneliner
We are noobs, we prefer one-line solution!

# Steamcmd 来战：

1. 查看国区命令：cat licenses.txt | egrep 'State.*CN' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*CN' | wc -l
     1520
这个1520就是数量，你的肯定和我的不一样。

2. 查看E区命令：cat licenses.txt | egrep 'State.*RU' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*RU' | wc -l
       8

我有E区我自豪！不过别太多就是了...

3. 查看澳区：cat licenses.txt | egrep 'State.*AU' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*AU' | wc -l
       1

我也不知道我买了什么...

4. 查看日区：cat licenses.txt | egrep 'State.*JP' | wc -l

例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*JP' | wc -l
       14

同上，不知道为啥有日区的东西...

5. 没区域的：cat licenses.txt | egrep 'State.*\"-' | wc -l
例：imsb-iMac:steamcmd noob$ cat licenses.txt | egrep 'State.*\"\-' | wc -l
       8

同上，不知道买了啥奇葩。

------------------------------------------------------------折腾------------------------------------------------------------

1.  输出每个游戏信息(忽略 packageID)：

cat licenses.txt | awk '/State.*RU/{x=NR+2}(NR<=x){print}'  | sed '1s/\,/ ||/' | egrep -v '\-\-|License'

2. 三行1输出E区游戏详细信息(别的区自行替换RU为XX)：
cat licenses.txt | egrep 'State.*RU' -b2 |  egrep -v '\-\-|License' | awk '1;!(NR%3){print "\n----------分割线----------\n";}'

cat licenses.txt | egrep 'State.*RU' -b2 | sed '1s/\,/ ||/' | egrep -v '\-\-|License' | awk '1;!(NR%3){print "\n----------萌之分割线----------\n";}'

perl -ne '$s=1 if /State/; if($s){push @R,$_; $s++ if /Active.*RU/; if(/Apps/){print "@R\n-------我是分割线，我很萌-------\n" if $s>1; @R=""; $s=0;}}' licenses.txt
