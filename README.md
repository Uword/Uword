# 嗨，我是Uword 👋
我在网上找的教程不知道为什么和我的页面相差很大，所以我就干脆使用穷举法了。

连这个页面都是我一个一个点试出来的，所以制作的会有点简陋。（）    

* ## About me
正在学习数字媒体技术。

* ## Interests
绘画，游戏引擎，3D建模，视频剪辑，摄影，以及网页搭建。

* ## Current skills/Current learning
会使用PS的基本操作，有专业的绘画屏（不过目前还在上手操作阶段,后面绘画方面会下载csp），不排斥AI,下一阶段打算了解unity的基本应用以及如何使用AI对代码进行编写。

* ## I wanna...
未来能够制作自己OC相关的游戏

* ## Preferred Role
没有一定的指向，我都可以干

* ## Strengths
逻辑思维强 / 搜商高 / 擅长沟通协调 / 色彩敏感

* ## Contact：
QQ：1839790936


# 二、 二选一：编程与算法方向（或视觉设计方向）



### ① 编程与算法方向

**原数组：** 8 3 6 2 7 1

**代码实现（C++）：**
```cpp
#include <iostream>
using namespace std;

int main() {
    int arr[] = {8, 3, 6, 2, 7, 1};
    int n = sizeof(arr) / sizeof(arr[0]);
    
    // 冒泡排序
    for (int i = 0; i < n - 1; i++) {
        for (int j = 0; j < n - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                // 交换元素
                int temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
            }
        }
    }
    
    // 输出排序后的结果
    cout << "排序后结果: ";
    for (int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;
    
    return 0;
}



<!--
**Uword/Uword** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
