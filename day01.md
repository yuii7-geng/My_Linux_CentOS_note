ls [选项] [路径]  查看目录内容
  -a 显示隐藏
  -l 列表显示
  -h显示文件大小的单位（需和-l搭配使用）


cd [路径]  切换工作目录
pwd  查看当前工作目录


touch 创建空文件
  例：touch /home/geng/note.txt
  （在路径/home/geng的目录下创建note.txt文件）


mkdir [选项]  创建目录
  -p 创建多层目录
    例：mkdir -p /home/geng/目录1/目录2
    （在geng目录下创建目录1，从目录1下面再 创建 目录2）


rmdir [路径]  删除空目录
  例：rmdir /home/geng/目录1/目录2
  （删除为空的目录2）


rm -rf [路径]  强制删除并不提示
  例：rm -rf /home/geng
  (强制删除目录geng以及里面的所有目录、文件)


cp [参数] 文件 目录    拷贝文件到指定目录
  -r 递归复制整个文件夹
    例：cp -r /home/geng /opt
      (将home目录下的geng文件夹 拷贝到根目录下的opt里面)
      注意：如果目标目录有相同命名的文件或文件夹会提示是否覆盖
      \cp  强制覆盖不提示  例：\cp -r /home/geng /opt


rm  删除文件或目录
  语法：rm [选项] 文件或目录
    -r 递归删除整个文件夹
    -f 强制删除不提示
      例： rm -rf /opt/geng
      （直接删除opt目录下的geng文件夹，没有确认提示）


mv  移动文件和目录或重命名
  语法：mv 旧路径 新路径
    例：mv /opt/geng /opt/geng1
    （对opt下的geng重命名为geng1）
