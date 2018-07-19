**修复apktool重打包时APK由于AndroidResGuard处理报错问题：**

具体报错信息
No resource identifier found for attribute 'layout' in package 'com.tencent.mm'

No resource identifier found for attribute 'key' in package 'com.tencent.mm'


No resource identifier found for attribute...

No resource found that matches the given name.....

.......


使用apktool-2.0.3也可以回编译，但是比如微信回编译后会增加到110M左右，很不友好。

而使用apktool-2.3.2和原包大小一样，65M左右。

基于**apktool 2.3.2**源码进行了一些处理。
