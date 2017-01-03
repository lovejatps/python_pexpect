# python_pexpect
# 准备 
pip install pexpect 
如果出现了 错误： No module named ptyprocess
解决方案：pip install ptyprocess
测试:

import pexpect 

print pexpect.run('ping localhost -c 3')
