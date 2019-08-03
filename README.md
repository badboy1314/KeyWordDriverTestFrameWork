关键字驱动测试框架案例
    
    框架分析：
        1.使用外部测试数据文件，使用Excel管理测试用例的集合和每个测试用例的所有测试步骤
          ，实现一个文件中完成测试用例的维护
        2.每个测试用例的测试结果在一个文件中查看和统计
        3.通过定义关键字，操作元素的定位方式及定位表达式和操作值就可以实现每个测试用例步
          骤的执行，可以更加灵活地实现自动化测试的需求
        4.实现定位表达式和测试代码的分离，实现定位表达式直接在测试数据文件中进行维护。
        5.框架提供日志功能，方便调试和监控自动化测试程序的执行
        6.基于关键字测试框架，即使不懂开发技术的测试人员也可以实施自动化测试，便于在整个
          测试团队中推广和使用自动化测试技术，降低自动化测试实施的技术门槛
        7.基于关键字的方式，可以进行任意关键字的扩展，以满足更加复杂项目的自动化测试需求
    
    
    运行框架：
        1.运行环境需要安装了python3.x+selenium2.x；第三方模块openpyxl,pypiwin32,
          win32api, win32con
        2.本地已配置chrome/firefox/ie浏览器及对应版本驱动
        3.需要修改Excel文件中对应的用户名和密码
        4.直接运行RunTest.py文件即可执行整个框架
   