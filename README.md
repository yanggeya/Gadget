# Gadget
日常小工具

## nmap_xml.py

来源：网上大佬，不满足需求，缺少服务名称和版本信息，以及nmap中部分端口ssl会单独一个字段，不和服务在一块。

作用：解析namp -oG/-oA 输出的xml文件，输出IP、服务、端口开发状态、产品名称、服务版本。

使用：``python.exe .\nmap_xml.py ./ filenamae.xml.\``
