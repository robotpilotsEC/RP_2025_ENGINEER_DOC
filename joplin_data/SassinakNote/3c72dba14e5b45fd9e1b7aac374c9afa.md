移动文件命令 mv

# 移动文件命令
- `mv` (move)    用于移动文件或目录，也可用于重命名文件或目录
>mv 源文件 目标路径/

>mv 原文件名 新文件名

### 参数
- `-f` (force)              强制执行，若目标文件已存在则直接覆盖，不提示
- `-i` (interactive)        覆盖前进行确认提示
- `-n` (no-clobber)         不覆盖已存在的文件
- `-u` (update)             只移动比目标文件新的文件或目标文件不存在的文件
- `-v` (verbose)            显示详细操作过程
- `-b` (backup)             覆盖前备份目标文件
- `-S SUFFIX` (suffix)      指定备份文件的后缀（与 b 配合使用）
- `-t DIRECTORY` (target-directory)  把所有源文件移动到指定目录
- `-T` (no-target-directory)把目标当作普通文件而非目录

备份的文件会保存在目标目录下，备份文件后缀**缺省**是 ~，也可以通过 `-S` 选项自定义


id: 3c72dba14e5b45fd9e1b7aac374c9afa
parent_id: b89232cf4bc240708b9c46d4062e5965
created_time: 2025-08-31T14:56:00.546Z
updated_time: 2025-08-31T15:04:06.180Z
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
order: 857738172.5869141
user_created_time: 2025-08-31T14:56:00.546Z
user_updated_time: 2025-08-31T15:04:06.180Z
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