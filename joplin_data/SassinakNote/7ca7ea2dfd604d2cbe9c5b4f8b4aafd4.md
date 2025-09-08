创建分支并上传代码

# 创建分支并上传代码

1. 拉取具有子模块的仓库

可以分**初始化**和**更新子模块**两步走的方式来下载子模块仓库的内容：
`$ git submodule init`	# 初始化子模块
`$ git submodule update`	# 更新子模块
但是，如果你是**第一次使用** `git clone` 下载主仓库的所有项目内容的话，我建议你可以使用如下的代码格式来把主仓库和其中子模块的所有内容，都一步到位的下载下来：
`$ git clone --recursive <project url>`

2. 查看子模块
`git submodule`

会显示如下内容
>e33f854d3f51f5ebd771a68da05ad0371a3c0570 assets (heads/master)
 

3. 更新子模块
`git submodule update`

`Git submodule update --remote  "子模块名"`


4. 在子模块中创建分支
`git checkout -b new-feature-branch`


5. 在子模块内修改了文件需要上传
```git add .
git commit -m "Add new feature in submodule"
git push origin new-feature-branch
```
⚠️ **注意**，如果你跳过这一步，主仓库更新了子模块的指针，其他人拉不到你刚创建的分支内容。

push完之后必须更新你的子模块commit
```cd ..
git add submodule
git commit -m "Update submodule to new-feature-branch commit"
```
这样主项目就记录了子模块的新状态（一个特定 commit）。



id: 7ca7ea2dfd604d2cbe9c5b4f8b4aafd4
parent_id: bcf537d96b944aa0a7d2188410a5df51
created_time: 2025-08-07T14:27:29.764Z
updated_time: 2025-08-07T14:27:29.765Z
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
order: 1754577300193
user_created_time: 2025-08-07T14:27:29.764Z
user_updated_time: 2025-08-07T14:27:29.765Z
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