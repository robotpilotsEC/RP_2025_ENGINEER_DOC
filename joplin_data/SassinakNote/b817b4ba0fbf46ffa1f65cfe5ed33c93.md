( )

# ( )
- **表示配置项的帮助说明、默认值等辅助内容**
- 在 Kconfig 文件或配置界面中，圆括号通常用于包裹**说明文字**、**默认值**、**依赖关系**等
	- `(NEW)`：表示该选项是新加的，还未配置过。
	- `(depends on XYZ)`：表示此选项依赖于某项（XYZ）已启用。
	- `(default Y)`：显示选项的默认值。
	- `(selected by ABC)`：表示该选项是被其他项 ABC 选择。

~~~
[ ] Enable GPIO (NEW)
[*] Enable SPI (depends on GPIO)
<M> Enable I2C (default M)
[*] Enable CAN (selected by ADVANCED_FEATURE)
~~~

id: b817b4ba0fbf46ffa1f65cfe5ed33c93
parent_id: 8b861dac917547faa158f73fa5e8d3bf
created_time: 2025-09-06T12:16:53.132Z
updated_time: 2025-09-06T12:34:33.720Z
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
order: 439290253283
user_created_time: 2025-09-06T12:16:53.132Z
user_updated_time: 2025-09-06T12:34:33.720Z
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