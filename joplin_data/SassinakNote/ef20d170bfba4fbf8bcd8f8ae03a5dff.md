设备驱动模型

# 设备驱动模型
Zephyr为了支持多种设备，设计了一套设备驱动流程
**应用层**->调用**子系统**下的**通用API**传递结构指针给**设备实例**->实现一套API给上层调用

- 每个I2C，UART 都算一个子系统
- 一个驱动可以有多个实例但API共用
 ![acf3b1ef417584e091295acdfb4b04d0.png](:/83a6ebb0cc8d44d8812bd5e302d47739)


id: ef20d170bfba4fbf8bcd8f8ae03a5dff
parent_id: 78ae4c96c82346bea03245a93f185eff
created_time: 2025-08-13T13:19:32.834Z
updated_time: 2025-08-13T13:28:49.089Z
is_conflict: 0
latitude: 22.28420000
longitude: 114.17590000
altitude: 0.0000
author: 
source_url: 
is_todo: 0
todo_due: 0
todo_completed: 0
source: joplin-desktop
source_application: net.cozic.joplin-desktop
application_data: 
order: 1754834254238.5
user_created_time: 2025-08-13T13:19:32.834Z
user_updated_time: 2025-08-13T13:28:49.089Z
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