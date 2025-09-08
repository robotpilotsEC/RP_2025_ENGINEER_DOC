建立软链接和硬链接 ln

# 建立软链接和硬链接 ln
>ln -s 原文件或目录 软链接名
>ln 原文件 硬链接名

`ln`命令参数
- `-s` (symbolic)           创建软链接（符号链接）
- `-f` (force)              强制执行，若目标文件已存在则覆盖
- `-i` (interactive)        覆盖前进行确认提示
- `-n` (no-dereference)     目标若是软链接，则不跟随目标，仅覆盖链接本身
- `-v` (verbose)            显示详细操作过程
- `-b` (backup)             覆盖前备份目标文件
- `-S SUFFIX` (suffix)      指定备份文件的后缀（与 b 配合使用）
- `-T` (no-target-directory)把目标当作普通文件而非目录

上述命令可以嵌套使用
>ln -sf 源文件 目标链接
>ln -sv 源文件 目标链接

id: 1e3ddadcdff84a11a799eaa56e17dba0
parent_id: b89232cf4bc240708b9c46d4062e5965
created_time: 2025-08-31T14:40:38.065Z
updated_time: 2025-08-31T14:48:06.564Z
is_conflict: 0
latitude: 0.00000000
longitude: 0.00000000
altitude: 0.0000
author: 
source_url: 
is_todo: 0
todo_due: 0
todo_completed: 0
source: joplin-desktop
source_application: net.cozic.joplin-desktop
application_data: 
order: 3430952690.3476562
user_created_time: 2025-08-31T14:40:38.065Z
user_updated_time: 2025-08-31T14:46:51.710Z
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