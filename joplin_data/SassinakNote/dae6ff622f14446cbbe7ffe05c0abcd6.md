id: dae6ff622f14446cbbe7ffe05c0abcd6
parent_id: 
item_type: 1
item_id: 93a6d69d33f74685a37c55a6ea426257
item_updated_time: 1754576983960
title_diff: "[{\"diffs\":[[1,\"34b7e3a844ec451ba53f3f1ce2e3405b\"]],\"start1\":0,\"start2\":0,\"length1\":0,\"length2\":32}]"
body_diff: "[{\"diffs\":[[1,\"指向类的指针\\\n\\\n# 指向类的指针\\\n\\\n## 基本知识：\\\n与结构体类似，可以使用一个指针指向一个对象\\\n\\\n>// 声明和初始化指向类的指针\\\n    MyClass *ptr = &obj;\\\n\\\n***\\\n## 动态分配内存\\\n\\\n指向类的对象可以用于动态分配内存和创建类的对象\\\n\\\n~~~\\\n#include <iostream>\\\n\\\nclass MyClass {\\\npublic:\\\n    int data;\\\n\\\n    void display() {\\\n        std::cout << \\\"Data: \\\" << data << std::endl;\\\n    }\\\n};\\\n\\\nint main() {\\\n    // 动态分配内存创建类对象\\\n    MyClass *ptr = new MyClass;\\\n    ptr->data = 42;\\\n\\\n    // 通过指针调用成员函数\\\n    ptr->display();\\\n\\\n    // 释放动态分配的内存\\\n    delete ptr;\\\n\\\n    return 0;\\\n}\\\n~~~\\\n\\\n***\\\n还可以作为函数参数\\\n\\\nid: 34b7e3a844ec451ba53f3f1ce2e3405b\\\nparent_id: 5d2ae685eba14dab9db7583913a9e47c\\\ncreated_time: 2025-07-26T12:17:16.617Z\\\nupdated_time: 2025-07-26T14:09:02.871Z\\\nis_conflict: 0\\\nlatitude: 1.35520000\\\nlongitude: 103.88590000\\\naltitude: 0.0000\\\nauthor: \\\nsource_url: \\\nis_todo: 0\\\ntodo_due: 0\\\ntodo_completed: 0\\\nsource: joplin-desktop\\\nsource_application: net.cozic.joplin-desktop\\\napplication_data: \\\norder: 0\\\nuser_created_time: 2025-07-26T12:17:16.617Z\\\nuser_updated_time: 2025-07-26T14:09:02.871Z\\\nencryption_cipher_text: \\\nencryption_applied: 0\\\nmarkup_language: 1\\\nis_shared: 0\\\nshare_id: \\\nconflict_original_id: \\\nmaster_key_id: \\\nuser_data: \\\ndeleted_time: 0\\\ntype_: 1\"]],\"start1\":0,\"start2\":0,\"length1\":0,\"length2\":1122}]"
metadata_diff: {"new":{"id":"93a6d69d33f74685a37c55a6ea426257","parent_id":"c1fdd44bbf44482c9bc772c90e1085f1","latitude":"0.00000000","longitude":"0.00000000","altitude":"0.0000","author":"","source_url":"","is_todo":0,"todo_due":0,"todo_completed":0,"source":"joplin-desktop","source_application":"net.cozic.joplin-desktop","application_data":"","order":1754576624379,"user_updated_time":1754573824587,"markup_language":1,"is_shared":0,"share_id":"","conflict_original_id":"","master_key_id":"","user_data":"","deleted_time":1754576983960},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2025-08-07T14:39:39.003Z
created_time: 2025-08-07T14:39:39.003Z
type_: 13