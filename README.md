# Gadget
日常小工具

## nmap_xml.py

来源：网上大佬，不满足需求，缺少服务产品名称和版本信息，以及xml中部分端口ssl会单独一个字段，不和服务在一块。

作用：解析namp -oG/-oA 输出的xml文件，输出IP、服务、端口开发状态、产品名称、服务版本。

使用：``python.exe .\nmap_xml.py ./ filenamae.xml.\``

结果如图

![image](https://github.com/yanggeya/Gadget/assets/39549253/70e5fb49-45c5-4297-83c6-5f6fc9960dbe)

