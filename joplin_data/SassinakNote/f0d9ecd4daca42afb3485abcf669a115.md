id: f0d9ecd4daca42afb3485abcf669a115
parent_id: cfda2835a8e540b2a2b2f945cb91364f
item_type: 1
item_id: 4acfddf6a89e49e29ee2410f762c22d4
item_updated_time: 1756691749863
title_diff: "[{\"diffs\":[[1,\"进程 ps\"]],\"start1\":0,\"start2\":0,\"length1\":0,\"length2\":5}]"
body_diff: "[{\"diffs\":[[0,\" `ps`\\\n- \"],[1,\"**退出进程**：`exit`\\\n***\\\n- **挂起前台进程** `ctrl+z`\\\n- **恢复前台运行** `fg`,如果有多个可以指定 `fg %1`\\\n- **继续在后台运行** `bg`，同样可以指定\\\n- **查看挂起的进程** `jobs`\\\n***\\\n进程有很多种状态：\\\n- `R`（Running）\\\n运行状态（正在运行或可运行）\\\n\\\n- `S`（Sleeping）\\\n睡眠状态（可中断的睡眠，等待某事件完成）\\\n\\\n- `D`（Uninterruptible sleep）\\\n不可中断的睡眠状态（一般在等待IO）\\\n\\\n- `T`（Stopped）\\\n停止状态（被终止或暂停，如收到SIGSTOP信号）\\\n\\\n- `Z`（Zombie）\\\n僵尸状态（进程已终止，但尚未被父进程回收）\\\n\\\n- `X`（Dead）\\\n死亡状态（极少见，进程已死亡）\\\n\\\n- `I`（Idle）\\\n空闲状态（内核线程专用，表示空闲）\\\n\\\n- `W`（Paging）\\\n正在交换内存（较老的内核中，现代系统很少见）\\\n***\\\n\\\n**参数**\\\n- `-a`（all processes with tty except session leaders）  \\\n显示所有有终端的进程（不包括会话首进程）  \\\n> ps -a\\\n\\\n- `-u`（user-oriented format）  \\\n以用户为中心的格式显示进程信息  \\\n> ps -u\\\n\\\n- `-x`（processes without controlling terminal）  \\\n显示没有控制终端的进程  \\\n> ps -x\\\n\\\n- `-e`（every process）  \\\n显示所有进程（等同于 `-A`）  \\\n> ps -e\\\n\\\n- `-A`（all processes）  \\\n显示所有进程（等同于 `-e`）  \\\n> ps -A\\\n\\\n- `-f`（full-format listing）  \\\n以完整格式显示进程信息  \\\n> ps -f\\\n\\\n- `-l`（long format）  \\\n以长格式显示进程信息  \\\n> ps -l\\\n\\\n- `-o`（user-defined format）  \\\n自定义显示内容  \\\n> ps -o pid,ppid,cmd\\\n\\\n- `-p`（by pid）  \\\n显示指定PID的进程信息  \\\n> ps -p 1234\\\n\\\n- `-t`（by tty）  \\\n显示指定终端的进程  \\\n> ps -t pts/0\\\n\\\n- `-C`（by command name）  \\\n按命令名显示进程  \\\n> ps -C sshd\\\n\\\n- `-r`（running processes）  \\\n只显示正在运行的进程  \\\n> ps -r\\\n\\\n- `-n`（numeric wchan and userids）  \\\n以数字方式显示 wchan 和用户ID  \\\n> ps -n\\\n\\\n- `-s`（session leaders）  \\\n显示会话首进程  \\\n> ps -s\\\n\\\n- `-N`（negate selection）  \\\n显示不符合条件的进程  \\\n> ps -N\\\n\\\n- `-H`（process hierarchy）  \\\n以层级结构显示进程关系  \\\n> ps -H\\\n\\\n- `-w`（wide output）  \\\n宽输出格式，显示更多内容  \\\n> ps -w\\\n\\\n- 多参数合用  \\\n显示所有进程，包含完整格式  \\\n> ps -ef\"]],\"start1\":20,\"start2\":20,\"length1\":8,\"length2\":1417}]"
metadata_diff: {"new":{},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2025-09-01T01:59:06.851Z
created_time: 2025-09-01T01:59:06.851Z
type_: 13