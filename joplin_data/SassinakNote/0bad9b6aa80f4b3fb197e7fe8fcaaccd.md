类的成员函数

# 类的成员函数

## 基本知识：

1. 类的成员函数是定义在**类的内部**的函数，成员函数可以**直接访问**类的成员变量和其他成员函数，包括私有类

2. 成员函数被隐式传递一个指向当前对象的指针（**即this指针**），可以对对象进行操作和访问。

3. 静态函数是属于某个类的函数，可以通过类名**直接调用**，而不需要通过对象来访问
必须注意：静态函数**只能访问**静态成员变量和其他静态成员函数，**不能访问**非静态的成员变量和成员函数

4. 值得注意的是，即便我们的类是一个**空类**，也会默认生成6个成员函数

![efd87b3b9c6c6f393aa270b1ec03f666.png](:/6256fe6e1c6b4fa2ba44cd9cc656a696)

类里面的成员函数是放在**公共的代码段**的，也就是说在内存的角度来说，一个对象的大小只包括了其成员变量，并不包括它的成员函数。

5. 需要注意的是：形参传递权限**可以缩小或者不变，但不能放大**，比如 `int*` 允许被传递给`int*`和`const int*`，但是`const int*`不允许传递到`int*`
在成员函数的参数列表中，`this`是不能显示的用const写出来的，但是可以在成员函数之后用`const`修饰以告诉编译器

>void Print() const// 编译器默认处理成：void Print(const Date* const this)




id: 0bad9b6aa80f4b3fb197e7fe8fcaaccd
parent_id: dd57862bb29c4ba88e2b03b9af44d814
created_time: 2025-08-07T14:27:07.414Z
updated_time: 2025-08-07T14:27:07.414Z
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
order: 1754577292017
user_created_time: 2025-08-07T14:27:07.414Z
user_updated_time: 2025-08-07T14:27:07.414Z
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