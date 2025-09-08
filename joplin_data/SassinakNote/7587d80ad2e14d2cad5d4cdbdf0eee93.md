id: 7587d80ad2e14d2cad5d4cdbdf0eee93
parent_id: 0f3700d837294a489644ffa9f7bbc532
item_type: 1
item_id: edb9b1f671954234bb9086c0492485e6
item_updated_time: 1755000974603
title_diff: "[]"
body_diff: "[{\"diffs\":[[0,\"备树的加载流程\\\n\"],[1,\"- **地址设置**\\\n一般通过 `Bootloader` 引导启动 `Kernel`，在启动 `Kernel` 之前，`Bootloader` 必须将 `dtb` 文件的**首地址**传输给 `Kernel`，以供使用。\\\n\\\n\\t1. `Bootloader` 将 `dtb` **二进制文件**的**起始地址**写入 `r2` 寄存器中\\\n\\t2. `Kernel` 在第一个启动文件 `head.S/head-common.S` 中，读取 `r2` 寄存器中的值，获取 `dtb` 文件起始地址\\\n\\t3. 跳转入口函数 `start_kernel` 执行C语言代码\\\n\\\n- **获取平台信息  --machine_desc**\\\n\"]],\"start1\":1059,\"start2\":1059,\"length1\":8,\"length2\":318}]"
metadata_diff: {"new":{},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2025-08-12T12:18:40.633Z
created_time: 2025-08-12T12:18:40.633Z
type_: 13