id: c18aec8dcd444a3ca9da701cb3cfc3dd
parent_id: 27f98b9030dc4653a5800a4bb5c7fa29
item_type: 1
item_id: 1a9119b677cc4961a0bb75be18ef5e5d
item_updated_time: 1755437286735
title_diff: "[]"
body_diff: "[{\"diffs\":[[0,\" `struct\"],[1,\" \"],[0,\"task_str\"]],\"start1\":2308,\"start2\":2308,\"length1\":16,\"length2\":17},{\"diffs\":[[0,\"访问当前进程的 `struct task_struct`\"],[1,\"\\\n\\\n为了在多处理器配置中实现快速访问，每个 CPU 中都有一个共同的变量，这个变量可用来存储和检索指向当前 `struct task_struct `的指针\\\n![bfeefa4a94727d8381e3416b8e0e035c.png](:/b8405fa110ba415d9f670e411aad872c)\\\n\\\n***\\\n## 上下文切换\\\n![136b5d2aa0132184db03a023c0381a49.png](:/d1eb64144c26481880a5db77e280d208)\\\n请注意，在发生上下文切换之前，我们必须进行**内核转换**，这可以通过**系统调用**或**中断**来实现。此时，用户空间的寄存器会保存在内核堆栈上。在某个时刻，可能会调用` schedule()` 函数，该函数决定从线程 T0 切换到线程 T1（例如，因为当前线程正在阻塞等待 I/O 操作完成，或者因为它的时间片已经耗尽）。\\\n\\\n##\"]],\"start1\":2301,\"start2\":2301,\"length1\":28,\"length2\":441}]"
metadata_diff: {"new":{},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2025-08-17T13:35:36.653Z
created_time: 2025-08-17T13:35:36.653Z
type_: 13