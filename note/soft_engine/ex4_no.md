1.  
    参与者: 供应商,邮购公司,客户,货运公司

2. 用例图:



3. 
    提交订单用例
    ​用户通过身份认证系统
    ​用户
    ​邮购公司
    ​用户
    ​用户
    ​用户
    邮购公司
    ​用户
    不保存订单,向用户发出错误提示
    7
    系统保存订单并标记为已确认

4.  
    可选路径2: 不正确的信息
        1.当系统检测到有不正确的信息时,可选路径从基本路径7开始.
        2.系统提示用户重新输入信息.
        3.基本路径从第7步开始继续执行.

    可选路径3: 选择修改信息
        1.当用户选择修改信息时,可选路径从基本路径8开始.
        2.系统提示用户修改信息.
        3.基本路径从第7步开始继续执行.

    可选路径4: 用户取消
        1.当用户选择取消时,可选路径从基本路径8开始.
        2.用户确认取消.
        3.系统结束用例.

5.  
    增加订单,修改订单
    包含关系

    用户通过身份认证
    系统完成订单显示

    用户通过身份认证
    客户选择需要取消的订单
    系统完成订单取消

   
    


