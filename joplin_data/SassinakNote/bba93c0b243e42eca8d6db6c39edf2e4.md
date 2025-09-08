id: bba93c0b243e42eca8d6db6c39edf2e4
parent_id: 
item_type: 1
item_id: 0419b164d66b4fe5bb4dce4414e36f76
item_updated_time: 1754268646087
title_diff: "[{\"diffs\":[[1,\"多态基本知识\"]],\"start1\":0,\"start2\":0,\"length1\":0,\"length2\":6}]"
body_diff: "[{\"diffs\":[[1,\"# 多态基本知识\\\n\\\n## 基本知识\\\n\\\nC++ 多态允许使用基类指针或引用来调用子类的重写方法，从而使得同一接口可以表现不同的行为\\\n\\\n以下是一个多态的表现例子：\\\n~~~\\\n#include <iostream>\\\nusing namespace std;\\\n\\\n// 基类\\\nclass Animal {\\\npublic:\\\n    // 虚方法\\\n    virtual void speak() {\\\n        cout << \\\"Animal speaks.\\\" << endl;\\\n    }\\\n};\\\n\\\n// 派生类1\\\nclass Dog : public Animal {\\\npublic:\\\n    void speak() override {\\\n        cout << \\\"Dog barks.\\\" << endl;\\\n    }\\\n};\\\n\\\n// 派生类2\\\nclass Cat : public Animal {\\\npublic:\\\n    void speak() override {\\\n        cout << \\\"Cat meows.\\\" << endl;\\\n    }\\\n};\\\n\\\nint main() {\\\n    Animal* a1 = new Dog(); // 基类指针指向派生类对象\\\n    Animal* a2 = new Cat();\\\n\\\n    a1->speak(); // 输出: Dog barks.\\\n    a2->speak(); // 输出: Cat meows.\\\n\\\n    delete a1;\\\n    delete a2;\\\n    return 0;\\\n}\\\n~~~\\\n\\\n\"]],\"start1\":0,\"start2\":0,\"length1\":0,\"length2\":692}]"
metadata_diff: {"new":{"id":"0419b164d66b4fe5bb4dce4414e36f76","parent_id":"00cb801523f54b42938806a416f1cb92","latitude":"0.00000000","longitude":"0.00000000","altitude":"0.0000","author":"","source_url":"","is_todo":0,"todo_due":0,"todo_completed":0,"source":"joplin-desktop","source_application":"net.cozic.joplin-desktop","application_data":"","order":1754273162793,"markup_language":1,"is_shared":0,"share_id":"","conflict_original_id":"","master_key_id":"","user_data":"","deleted_time":0},"deleted":[]}
encryption_cipher_text: 
encryption_applied: 0
updated_time: 2025-08-04T02:14:37.920Z
created_time: 2025-08-04T02:14:37.920Z
type_: 13