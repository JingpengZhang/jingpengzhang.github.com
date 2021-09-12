# <center>第一章：计算机系统概述</center>
&emsp;&emsp;每个二进制数位称为1 bit（比特）<br/>
&emsp;&emsp;计算机系统=硬件+软件<br/>
&emsp;&emsp;硬件：计算机的实体，如主机、外设等。
&emsp;&emsp;软件：由具有各类特殊功能的程序组成。
&emsp;&emsp;&emsp;&emsp;系统软件：用来管理整个计算机系统。（Eg：操作系统、数据库管理系统（DBMS）、标准程序库、网络软件、语言处理程序、服务程序）
&emsp;&emsp;&emsp;&emsp;应用软件：按任务需要编制成的各种程序。
&emsp;&emsp;计算机性能的好坏取决于“软”、“硬”件功能的总和。<br/>
&emsp;&emsp;机器字长：计算机一次整数运算所能处理的二进制位数。<br/>
&emsp;&emsp;摩尔定律：揭示了信息技术进步的速度，集成电路上可容纳的晶体管数目，约每隔18个月便会增加一倍，整体性能也将提升一倍。<br/>
&emsp;&emsp;硬件的发展：
&emsp;&emsp;&emsp;&emsp;第一代：电子管时代
&emsp;&emsp;&emsp;&emsp;第二代：晶体管时代
&emsp;&emsp;&emsp;&emsp;第三代：中小规模集成电路时代
&emsp;&emsp;&emsp;&emsp;第四代：大规模、超大规模集成电路时代<br/>
&emsp;&emsp;目前的发展趋势：
&emsp;&emsp;&emsp;&emsp;更微型、多用途；
&emsp;&emsp;&emsp;&emsp;更巨型、超高速。<br/>
&emsp;&emsp;“存储程序”的概念是指将指令以二进制代码的形式事先输入计算机的主存储器，然后按其在存储器中的首地址执行程序的第一条指令，以后就按该程序的规定顺序执行其他指令，直至程序执行结束。<br/>
&emsp;&emsp;在计算机系统中，软件和硬件在逻辑上是等效的。<br/>
&emsp;&emsp;冯诺依曼计算机的特点：
&emsp;&emsp;&emsp;&emsp;1.计算机由五大部件组成
&emsp;&emsp;&emsp;&emsp;2.指令和数据以同等地位存于存储器，可按地址寻访
&emsp;&emsp;&emsp;&emsp;3.指令和数据用二进制表示
&emsp;&emsp;&emsp;&emsp;4.指令由操作码和地址码组成
&emsp;&emsp;&emsp;&emsp;5.存储程序
&emsp;&emsp;&emsp;&emsp;<font color="red">6.以运算器为中心</font><font color="#8f8f8f">(输入/输出设备与存储器之间的数据传送通过运算器完成）</font><br/>
&emsp;&emsp;计算机硬件的基本组组成：
&emsp;&emsp;&emsp;&emsp;五大部分：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;输入设备：将信息转换成机器能识别的形式。
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;输出设备：将结果转换成人们熟悉的形式。
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font color="red">主存储器</font>：存放数据和程序
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font color="red">运算器</font>：算数运算、逻辑运算
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font color="red">控制器：</font>：指挥各部件，使程序运行
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<font color="red">（注：主存储器+运算器+控制器=主机）</font>
&emsp;&emsp;&emsp;&emsp;现代计算机结构：
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;以存储器为中心；
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;CPU=运算器+控制器

&emsp;&emsp;Memory Address Register —— 存储地址寄存器
&emsp;&emsp;Memory Data Register —— 存储数据寄存器

&emsp;&emsp;数据在存储体内按地址存储
&emsp;&emsp;每个地址对应一个存储单元
&emsp;&emsp;<font color="red">存储单元</font>：每个存储单元存放一串二进制代码
&emsp;&emsp;<font color="red">存储字（word）</font>：存储单元中二进制代码的组合
&emsp;&emsp;<font color="red">存储字长</font>：存储单元中二进制代码的位数
&emsp;&emsp;存储元：即存储二进制的电子元件，每个存储元可存1bit
&emsp;&emsp;例：
&emsp;&emsp;&emsp;&emsp;MAR=4位→总共有2^4个存储单元
&emsp;&emsp;&emsp;&emsp;MDR=16位→每个存储单元可存放16bit
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1个字（word）=16bit
&emsp;&emsp;易混淆：1个字节（Byte)=8bit
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1B=1个字节，1b=1个bit

&emsp;&emsp;<font color="red">CPU区分指令和数据的依据：指令周期的不同阶段</font>