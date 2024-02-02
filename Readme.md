# clash使用教程
reference: https://www.hengy1.top/article/3dadfa74.html https://blog.iswiftai.com/posts/clash-linux/ https://github.com/JXCrazy/Clash-for-ubuntu

1. 按照上述参考链接在服务器中安装clash.
2. config.yaml配置文件先从PC端安装clash, 让其自动根据梯子的url生成config.yaml，然后复制到服务器中.
3. 执行: cd clash & ./clash -d .
显示以下内容：
    INFO[0000] Start initial compatible provider 故障转移       
    INFO[0000] Start initial compatible provider 自动选择       
    INFO[0000] Start initial compatible provider Pluto      
    INFO[0000] Start initial compatible provider Test       
    INFO[0000] Mixed(http+socks) proxy listening at: 127.0.0.1:17890 
    INFO[0000] RESTful API listening at: 127.0.0.1:8765
表示连接成功. 此时可以无障碍访问GitHub.