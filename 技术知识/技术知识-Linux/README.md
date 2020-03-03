### deb文件安装方式

`sudo dpkg -i linuxidc.deb`

### 查看Linux已经安装的软件包

`sudo dpkg -l`





### 随机密码产生

 -c或——complerment：取代所有不属于第一字符集的字符；
 -d或——delete：删除所有属于第一字符集的字符；

1. 生成10个小写字母
   [root@kafka60 shell]# < /dev/urandom tr -dc a-z|head -c ${1:-10};echo
    iprnfrqlhr
2. 生成10个大写字母
   [root@kafka60 shell]# < /dev/urandom tr -dc A-Z|head -c ${1:-10};echo
    PSKSFZYQPH
3. 生成10个数字
   [root@kafka60 shell]# < /dev/urandom tr -dc 0-9|head -c ${1:-10};echo
    7341384592
4. 生成10个数字和大写字母的组合字符串
   [root@kafka60 shell]# < /dev/urandom tr -dc 0-9-A-Z|head -c ${1:-10};echo
    M6HP4LHTNJ
5. 生成10个随机字符（包含数字，大写字母，小写字母）
   [root@kafka60 shell]# < /dev/urandom tr -dc 0-9-A-Z-a-z|head -c ${1:-10};echo
    79JUYcjrjx
6. 生成10个随机字符（包含数字，大写字母，小写字母）
   [root@kafka60 shell]# < /dev/urandom tr -dc 0-9-A-Z-a-z-|head -c ${1:-10};echo
    JdOi4TMmZD
7. 生成10个随机字符（包含数字，大写字母，小写字母，特殊字符）
   [root@kafka60 shell]# < /dev/urandom tr -dc 0-9-A-Z-a-z-/|head -c ${1:-10};echo
    s5-yTgMa8Gk