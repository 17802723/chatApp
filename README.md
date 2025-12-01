# 基于 Qt/C++的实时多媒体通讯系统



**项目描述**：该系统是一个高并发、低延迟的跨平台即时通讯平台。服务端采用 C++ Asio 异步 I/O 架构，
客户端基于 Qt 实现，功能涵盖用户管理、富文本消息（文本/图片/文件），以及实时语音/视频通话功
能。
**核心技术**： C++, Qt/QML, Boost.Asio, MySQL, CMake
**核心亮点**：

1. 客户端采用 Qt Widgets + QML 混合架构，使用 C++ 处理核心业务逻辑与网络通信，QML 构建现代
   化动态 UI，实现了逻辑与视图的高效分离。
2. 服务端基于 Asio 实现异步 TCP 通信框架，有效解决了多客户端并发连接时的阻塞问题，提升了消
   息吞吐量。
3. 实现了端到端语音/视频通话功能，解决了网络抖动下的卡顿和丢包问题，保障了音画同步。
4. 使用 CMake 管理所有第三方库依赖，实现了服务端与客户端在 Windows/Linux 平台上的标准化编译
   与部署。
5. 设计 MySQL 数据库表结构存储用户信息与聊天记录等数据

**登陆界面**

<img width="396" height="291" alt="image" src="https://github.com/user-attachments/assets/548f6782-6e04-4b4b-bf77-ba2978c2efeb" />

**注册界面**

<img width="391" height="278" alt="image" src="https://github.com/user-attachments/assets/de830775-9cd7-473c-9714-cf3c19ddae46" />

**添加好友**

<img width="838" height="632" alt="image" src="https://github.com/user-attachments/assets/df8ece71-70bb-423f-a2fc-c3e693973024" />

**聊天界面**

<img width="1567" height="966" alt="image" src="https://github.com/user-attachments/assets/c7f57498-fac6-422d-8073-8c658632873c" />

**语音通话**

<img width="360" height="640" alt="image" src="https://github.com/user-attachments/assets/e98bfb9a-8132-414f-9a2f-d8f4b43711d2" />
<img width="360" height="640" alt="image" src="https://github.com/user-attachments/assets/79f728f8-ab6e-42bd-970f-36f804f96c72" />
<img width="360" height="640" alt="image" src="https://github.com/user-attachments/assets/ffc8f2b8-b7bf-4bcf-bca9-61a57de4dcdb" />
<img width="360" height="640" alt="image" src="https://github.com/user-attachments/assets/4545a386-7924-4d7a-a997-3b9995c89f97" />

**视频通话**

<img width="978" height="642" alt="image" src="https://github.com/user-attachments/assets/b6f950a7-c40d-4a31-8a25-159ca4003715" />
<img width="978" height="642" alt="image" src="https://github.com/user-attachments/assets/7d7c53db-c3a0-4ae2-8ffd-3ab542595dc0" />
<img width="1316" height="642" alt="image" src="https://github.com/user-attachments/assets/e4673bc1-7306-41f3-bfde-0df69d595973" />
<img width="1316" height="642" alt="image" src="https://github.com/user-attachments/assets/3e61b6bd-3066-4f21-98fd-5b8f3e32173e" />










