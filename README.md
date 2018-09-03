**sec_interview_know_list**

**知识清单**

- **xss防御相关**
    - 编码防御
        - html实体编码
        - js编码
        - url编码
        - **三种编码的关系，以及什么地方用到什么编码**
        - **浏览器解码的过程**

- **CSRF相关**
    - 只校验Refer可以吗
    - token放在哪里？放在cookie里可以吗？不失效可以吗？
    
- **XXE漏洞相关**
    - XML文件格式
    - XXE漏洞利用的方式
    - XXE漏洞修复方案
    - XXE漏洞
    
- **sql注入漏洞相关**
    - 注入的类型
    - 检查注入的思路
    - 方案(参数化查询会有问题吗？)
    
- **SSRF**
    - 说一个容易出现SSRF漏洞的场景
    
- **CSP浏览器内容安全**
    - 略
    
- **DDOS防御相关**
    - DDOS攻击的类型
    - DDOS云防御的方案
    - DDOS反射攻击基于的协议？为什么基于这个协议？
    
- **加密与解密**
    - https协议握手过程
    - burp 中间人攻击的原理
    - 分别说3个对称加密 非对称加密 哈希算法 
    
- **android逆向相关**
    - 脱壳的原理
    - 如何查壳
    - smali语法
    - davilk指令
    - 如何防打包
    - 如何防签名校验
    - Android App加固原理分析(说一个加固的思路)
    - 防御思路
        - 对抗静态分析
            - 代码混淆技术 ProGuard
            - NDK保护
            - 壳
        - 对抗动态调试 
            - android:debuggable="false"，让程序不可调试
            - android.os.Debug.isDebuggerConnected()
            - 检测模拟器
        - 防止重编译
            - 检查签名 Eclipse自带的调试版密钥文件生成的apk文件的hash值,与上面的函数获取的hash比较
            - 检测Dex文件的Hash
            - 
    
    


