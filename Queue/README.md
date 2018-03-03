## 队列

特点：先进先出

基本结构：

```c
struct queue
{
    int data[100];//队列的主体，用来存储内容
    int head;//队首
    int tail;//队尾
};
```