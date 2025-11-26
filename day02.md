cat  查看文件内容（不能修改）
  语法：cat [选项] 文件
    -n 显示行号
  为浏览方便会加管道命令  more
    例：cat /etc/profile | more
      more的交互命令：
        ctrl+F 滚动一屏  ctrl+B 返回上一屏
        回车：向下一行   空格：下一页
        :f 显示文件名和当前行号
        q 退出

more也可以单独使用
  例：more /home/日报.txt

less 与 more相似 （适合查看较大文件）
  例：less /home/pig.txt


history 查看已执行过的命令
  例：history 33  (最近33条历史命令)
      !77  (再次执行编号为77的历史命令)


head 显示文件开头内容
  例：head -n 6 hello.txt  (显示hello.txt的前6行内容)

tail 显示文件尾部内容 与head用法一致

tail -f 实时监控文件变化


find [查找目录] [选项]    查找
  -name 文件名
  -user 用户名
  -size 文件大小
    例： find / -name hello.txt
        find /opt -user root
        find /home -size +1M


locate 文件名   快速查找（要先updatedb创建locate库，并且需要定期更新）


grep 查找文件内的内容
  语法：grep [选项] 内容 文件
    -n 显示行号
    -i 忽略大小写
      例：grep -n "hello" /root/abc.txt
