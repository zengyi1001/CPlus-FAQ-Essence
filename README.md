# CPlus-FAQ-Essence 
https://isocpp.org/wiki/faq

## 语法
### “const X* p”, “X* const p” 和 “const X* const p”的区别是什么?
https://isocpp.org/wiki/faq/const-correctness#const-ptr-vs-ptr-const

### 什么是 “const成员函数”?
https://isocpp.org/wiki/faq/const-correctness#const-member-fns

### 为什么尝试将Foo**转换为const Foo**会产生错误?
https://isocpp.org/wiki/faq/const-correctness#constptrptr-conversion

### 表达式!(a < b) 和 a >= b 在逻辑上是等价的吗?
https://isocpp.org/wiki/faq/newbie#comparisons-with-nan

### 什么是NaN?
https://isocpp.org/wiki/faq/newbie#nan
附加阅读理解：https://www.geeksforgeeks.org/nan-in-cpp-what-is-it-and-how-to-check-for-it/

### 为什么浮点型数据会有精度不足问题？
https://isocpp.org/wiki/faq/newbie#floating-pt-errs

### 为什么不能直接比较两个浮点数？
https://isocpp.org/wiki/faq/newbie#floating-pt-errs

### 如何在C代码里调用C++库函数
https://isocpp.org/wiki/faq/mixing-c-and-cpp#call-cpp

### 什么时候应该使用引用，什么时候应该使用指针？
https://isocpp.org/wiki/faq/references#refs-vs-ptrs

### \<cxxx> 和 <xxx.h> 头文件的区别是什么？
https://isocpp.org/wiki/faq/coding-standards#std-headers

### 为什么这段代码会在输入非数字字符后陷入死循环
https://isocpp.org/wiki/faq/input-output#stream-input-failure

### 什么是 tuple
https://isocpp.org/wiki/faq/cpp11-library#tuple

### std::function 和 std::bind
https://isocpp.org/wiki/faq/cpp11-library#std-function

### time相关工具
https://isocpp.org/wiki/faq/cpp11-library#std-duration

### 随机数生成
https://isocpp.org/wiki/faq/cpp11-library#std-random

### 构造函数可以调用本类的另一个构造函数吗？
https://isocpp.org/wiki/faq/ctors#init-methods

## 内存管理
### 可以free一个new出来的指针吗？或者可以delete一个malloc出来的指针吗？
https://isocpp.org/wiki/faq/freestore-mgmt#mixing-malloc-and-delete

### delete语句执行前需要判断指针是否为nullptr吗？
https://isocpp.org/wiki/faq/freestore-mgmt#delete-handles-null

### 使用new创建对象时，如果构造函数抛出异常会不会产生内存泄漏？
https://isocpp.org/wiki/faq/freestore-mgmt#new-doesnt-leak-if-ctor-throws

### 如何让对象只能通过new创建，而不是local、global、namespace-scope、static等
https://isocpp.org/wiki/faq/freestore-mgmt#static-create-methods

### 什么是unique_ptr？
https://isocpp.org/wiki/faq/cpp11-library#unique-ptr

### 什么是shared_ptr？
https://isocpp.org/wiki/faq/cpp11-library#shared-ptr

### 什么是weak_ptr？
https://isocpp.org/wiki/faq/cpp11-library#weak-ptr
辅助阅读：https://en.cppreference.com/w/cpp/memory/weak_ptr

### 指定范围的内存分配
https://isocpp.org/wiki/faq/cpp11-library#scoped-allocator

## 设计思想
### C++ 和 C 语言的区别是什么?
https://isocpp.org/wiki/faq/c#c-diffs

### 可以认为C是C++的子集吗? 
https://isocpp.org/wiki/faq/c#is-c-a-subset

### 设计类应该从外向内（接口优先）还是从内向外（数据优先）? 
https://isocpp.org/wiki/faq/operator-overloading#design-interfaces-first

### 如何降低内存泄漏风险
https://isocpp.org/wiki/faq/freestore-mgmt#memory-leaks

### 需要检查new返回的结果是否为nullptr吗？
https://isocpp.org/wiki/faq/freestore-mgmt#new-never-returns-null
