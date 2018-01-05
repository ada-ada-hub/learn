<center><font color=#DC143C size=4>matlab"   "python3</font></center>

#编程注意规范
MATLAB句末需要加   <font color=#DC143C size=4>**;**</font>，否则会在命令窗口输出结果。   
 
* **例**    
<code>  <font color=#006400>a=[1 2 3];  
b=a(2)，c=a(3)；</font> </code>   
运行后：b=2  c=3且会在命令窗口输出b=2

python句末无添加，在同一行中使用多条语句，语句之间使用分号<font color=#DC143C size=4>**;**</font>  

* **例**    
<code>  <font color=#006400>a=[1，2，3]  
b=a(2);c=a(3)</font> </code>   
运行后：b=3 c报错  python下标从0开始。

数据结构
=============
**1**、MATLAB：**矩阵**。  
**2**、Python：Python中常见的数据结构可以统称为**容器**（container）。  
序列（如列表和元组）、映射（如字典）以及集合（set）是三类主要的容器。


* **列表** 
</style>
<table width="800" class="table table-bordered table-striped table-condensed">

  <tr>
    <th colspan="2", bgcolor=yellow><strong>列表</strong></th>
  </tr>
 
  <tr>
    <td width="50%"><strong>MATLAB</strong>(行矩阵)</td>
    <td width="50%"><strong>pyhton</strong>(list)</td>
  </tr>

  <tr>
    <td>A=[1 2 3]</td>
    <td>A=[1,2,3]</td>
  </tr>


</table>

