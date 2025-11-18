# XGao免杀工具1.0
工具实测目前可绕过火绒、360、百度杀毒、深信服EDR其他没测，持续更新，请多多关注，采用以下技术：

1. 多层加密混淆
三层加密: AES-256 + 多重XOR + Base64编码
动态变量名: 每次生成随机标识符增加分析难度

2. 增强反分析能力
高级反调试: 时间检测、PEB检查、远程调试检测
智能反沙箱: 运行时间、内存、CPU、磁盘空间检测
延迟执行: 绕过自动化行为分析

3. 执行技术优化
间接调用: 使用函数指针执行shellcode
多种内存分配: VirtualAlloc + HeapAlloc 混合使用
内存保护: 动态修改内存权限

使用方法：

1.下载mingw64到本地
<img width="1236" height="114" alt="image" src="https://github.com/user-attachments/assets/6f731d34-473c-46e5-8458-8cf36be77be0" />

2.把cs生成的shellcode放在里面
<img width="1210" height="938" alt="image" src="https://github.com/user-attachments/assets/27b27f45-5431-4d2d-877d-a52b5bce09bb" />

3.选择生成位置点击生成生成免杀的exe程序
<img width="1192" height="976" alt="image" src="https://github.com/user-attachments/assets/a52aa7b5-a901-4f78-a02e-60c40c982c04" />

实测：
<img width="2174" height="1092" alt="image" src="https://github.com/user-attachments/assets/26e66c1c-021d-4722-99b8-baf177df2bb6" />
<img width="752" height="880" alt="7ae4f8ee-3a51-43cb-aa2b-593c7799b0d1" src="https://github.com/user-attachments/assets/005cb5bb-33d3-4565-98c3-333f65e6055d" />

