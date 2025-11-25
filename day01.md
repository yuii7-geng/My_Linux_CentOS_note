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
    
          
