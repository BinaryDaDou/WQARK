这是一个免费的内核工具,请自行对驱动进行签名。若发现bug或有其他建议请联系我

支持1709系统-24H2系统

![image](https://github.com/user-attachments/assets/7269dfe4-16da-4b58-9e7c-392417eabe7b)


![image](https://github.com/user-attachments/assets/323a966d-b9ea-4dd0-9bd1-cc7407f79571)

![image](https://github.com/user-attachments/assets/b4fbbdeb-f6c5-4f02-b58e-9a87decd765f)

![image](https://github.com/user-attachments/assets/e73cf645-ca34-46ea-832d-500ef1e8e35f)

![image](https://github.com/user-attachments/assets/2fc236b1-7561-4339-b2a9-9abb9501f45a)
![image](https://github.com/user-attachments/assets/04bf2967-c3a7-4f92-9c44-4f1fd493d6fa)

![image](https://github.com/user-attachments/assets/18762234-1427-4c57-b98d-10ec96f5e66a)

![image](https://github.com/user-attachments/assets/94433b7d-6d8b-4e13-90e2-7ed91e1159c9)





已支持功能:

1.进程:
遍历进程 遍历隐藏进程 挂起/恢复进程 结束进程 注入进程(支持被权限保护的进程注入) 进程校验
遍历线程 遍历隐藏线程 挂起/恢复线程 结束线程
遍历模块 拷贝模块内存 隐藏模块 卸载模块 提取扫描字符串
遍历内存 修改保护属性  提取内存字符串
遍历句柄 关闭句柄

2.驱动
遍历驱动 遍历隐藏驱动 遍历内存驱动(支持多块内存区域) 拷贝驱动模块 拷贝内核内存 查看IRP函数 提取驱动字符串 驱动加载与卸载痕迹 驱动校验

3.钩子
遍历SSDT,Inline,Iat钩子  恢复Inline,Iat钩子
遍历ShaowSSDT,Inline,Iat钩子 恢复Inline,Iat钩子
遍历Object对象钩子 恢复Object对象钩子
遍历进程钩子Inline,Iat,Eat钩子 恢复Inline,Iat,Eat钩子
遍历驱动钩子Inline,Iat,Eat钩子 恢复Inline,Iat,Eat钩子

4.内核层
系统回调遍历(进程,线程,模块,注册表,关机回调,蓝屏回调,文件回调) 系统回调删除(进程,线程,模块,注册表,关机回调,蓝屏回调,文件回调)
DPC定时器遍历 DPC定时器删除
IO定时器开启 IO定时器停止 IO定时器删除  IO定时器校验
系统线程遍历 系统线程挂起 系统线程恢复 系统线程结束 系统线程校验
工作线程遍历 工作线程挂起
设备树遍历 Attach设备删除
扫描内核内存 
Nmi遍历  Nmi删除

5.监控
监控内核ShellCode运行(模糊定位运行中无模块驱动)
监控进程创建  线程创建行为 监控注入操作
监控驱动创建
监控注册表行为
监控网络行为
监控文件行为

6.文件
遍历MiniFilter回调

7.网络
遍历WfpCallBack
遍历WfpFilter
遍历连接中的网络(BUG)

