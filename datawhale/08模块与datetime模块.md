# 08：模块与datetime模块  
## 1.练习题：  
1、怎么查出通过 from xx import xx导⼊的可以直接调⽤的⽅法？  
2、了解Collection模块，编写程序以查询给定列表中最常见的元素。  
题目说明：   
输入：language = ['PHP', 'PHP', 'Python', 'PHP', 'Python', 'JS', 'Python', 'Python','PHP', 'Python']    
输出：Python  

"""  
Input file  
language = ['PHP', 'PHP', 'Python', 'PHP', 'Python', 'JS', 'Python', 'Python','PHP', 'Python']  
Output file  
Python  
"""  

* def most_element(language):  
    """ Return a list of lines after inserting a word in a specific line. """  
    #your code here  
    
## 2.练习题：      
1、假设你获取了用户输入的日期和时间如2020-1-21 9:01:30，以及一个时区信息如UTC+5:00，均是str，请编写一个函数将其转换为timestamp：  

题目说明:  
"""  
Input file  
example1: dt_str='2020-6-1 08:10:30', tz_str='UTC+7:00'  
example2: dt_str='2020-5-31 16:10:30', tz_str='UTC-09:00'  
Output file  
result1: 1590973830.0  
result2: 1590973830.0  
"""

* def to_timestamp(dt_str, tz_str):  
    #your code here  
        pass  

2、编写Python程序以选择指定年份的所有星期日。  
题目说明:  
"""  
Input file  
   2020   
Output file  
   2020-01-05                           
   2020-01-12                 
   2020-01-19                  
   2020-01-26                 
   2020-02-02       
   -----  
   2020-12-06                 
   2020-12-13                  
   2020-12-20                  
   2020-12-27   
"""  
   
* def all_sundays(year):  
    #your code here  
