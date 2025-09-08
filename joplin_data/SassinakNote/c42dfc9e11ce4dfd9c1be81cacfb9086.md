内核的基本知识

# 内核的基本知识

## 内核的组成
![088b66fddd19d774990c514be707b300.png](:/bd312b4cc62942579ae406d8c3b18f6f)
![e7c996622cb28b565011f95dd3ae1a87.png](:/9b1f00ff67ea4385bfcd37d6f792a27f)

### `Process Scheduler` 也叫做**进程管理，调度**，这是内核中最重要的子系统。包括四个子模块
![402cf15afd29b27c0b132341cafc58a2.png](:/d97d3d82b609422aabd5d8853fc1d762)
- `Scheduling Policy` 进程策略。
-  `Architecture-specific Schedulers` **体系结构相关部分**。用于将对不同CPU的控制，抽象为统一的接口。这些控制主要在 `suspend` 和 `resume` 进程时使用
- `Architecture-independent Scheduler` **体系结构无关的部分**。它会和`Scheduling Policy`模块”沟通，决定接下来要执行哪个进程，然后通过`Architecture-specific Schedulers`模块`resume`指定的进程。
- `System Call Interface` 系统调用接口

### `Memory Manager` **内存管理**
![199e1480c4e657c59dc424c92d15df8b.png](:/341173779fd645418bf727108ed7b9a1)

### `Virtual Filesystem` 虚拟文件系统
VFS的功能就是管理各种各样的文件系统，屏蔽它们的差异，以统一的方式，为用户程序提供访问文件的接口
![b54141c2c968dc7d06840fab68d6e770.png](:/b9d302ff2cfa44408a87702d97c9c55a)

### `Net` 网络子系统
![e958a5728c049e4e2e0ab3912e1911cd.png](:/7b05a9e9f9eb4f54b220be195cb62856)

***
 ## 源码的组织结构
 ![97c693a465012fe7d9a4046f4da1bb0d.png](:/603b327003b14229a45e0c1fcc940012)


id: c42dfc9e11ce4dfd9c1be81cacfb9086
parent_id: 3f641110328e4044a4c055754d2e677d
created_time: 2025-08-14T13:27:28.195Z
updated_time: 2025-08-14T13:52:50.642Z
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
order: 438794512048.75
user_created_time: 2025-08-14T13:27:28.195Z
user_updated_time: 2025-08-14T13:52:50.642Z
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