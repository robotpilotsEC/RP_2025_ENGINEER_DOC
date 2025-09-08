搜索文件命令 find

# 搜索文件命令 find
搜索文件不一定是 `find`，也可以用 `locate`(基于数据库)
`find`基本格式：
>find [搜索路径] [搜索条件] [操作]

~~~
find /path/to/search -name "filename"
find . -name "*.txt"
find / -type d -name "test"
find /home/user -size +10M
~~~

**参数**
- `-name "pattern"`  
  按文件名查找（支持通配符）

- `-iname "pattern"`  
  按文件名查找，忽略大小写

- `-type [f|d|l|c|b|s|p]`  
  按类型查找  
  - `f` 普通文件  
  - `d` 目录  
  - `l` 符号链接  
  - 其它：`c` 字符设备，`b` 块设备，`s` 套接字，`p` 管道

- `-size [+|-]N[cwbkMG]`  
  按文件大小查找  
  - `+N` 大于N  
  - `-N` 小于N  
  - 单位：`c`字节, `k`KB, `M`MB, `G`GB
  
  - `-user 用户名`  
  按属主查找

- `-group 组名`  
  按属组查找

- `-perm mode`  
  按权限查找（如 644、/u=x）

- `-mtime [+|-]N`  
  按修改时间查找（N天，`+`大于，`-`小于）

- `-atime [+|-]N`  
  按访问时间查找

- `-ctime [+|-]N`  
  按状态更改时间查找

- `-newer file`  
  比指定文件新的文件

- `-empty`  
  查找空文件或空目录

- `-maxdepth N`  
  限定最大查找深度

- `-mindepth N`  
  限定最小查找深度

- `-path "pattern"`  
  路径匹配

- `-prune`  
  排除目录

- `-regex "pattern"`  
  用正则表达式匹配
  ***
**可用操作**
- `-delete`  
直接删除查找到的文件

- `-ls`  
类似`ls -l`方式显示结果

- `-exec command {} \;`  
  对查找到的每个文件执行 command  
> find . -name "*.log" -exec rm {} \;


id: ec88bdda73614aea961fd2e7f6de4aa1
parent_id: b89232cf4bc240708b9c46d4062e5965
created_time: 2025-09-01T08:37:05.754Z
updated_time: 2025-09-01T08:51:15.792Z
is_conflict: 0
latitude: 22.27602200
longitude: 114.17514710
altitude: 0.0000
author: 
source_url: 
is_todo: 0
todo_due: 0
todo_completed: 0
source: joplin-desktop
source_application: net.cozic.joplin-desktop
application_data: 
order: 1675269.8683338165
user_created_time: 2025-09-01T08:37:05.754Z
user_updated_time: 2025-09-01T08:51:15.792Z
encryption_cipher_text: 
encryption_applied: 0
markup_language: 1
is_shared: 0
share_id: 
conflict_original_id: 
master_key_id: 
user_data: 
deleted_time: 0
type_: 1