# cfd
url是05.16获取的，应该能用半个多月

ck格式pt_key=xxx;pt_pin=xxx;cid=1;  中间不能有空格

环境变量名CFD_COOKIE

# 拉库命令
ql repo https://github.com/djxyy5505/0516-cfd.git "js" "" "py"

拉库完后，手动添加任务  

task djxyy5505_0516-cfd/jx_cfd_dh.py

50 59 * * * *

# 拉库失败

1.拉取这位大佬的库ql repo https://github.com/mixingh/Script.git "jx_" "" "ql_"

2.替换我改好的jx_cfd_dh.py


# 关于
