在项目的pages文件配置condition list属性后，如果项目存在nvue页面编译时会出现此错误
Uncaught ReferenceError: WeexPlus is not defined at __uniappview.html:1781
Uncaught TypeError: Cannot read property 'stack' of null at uniapp://ready:182

解决方案: 删掉此配置，试着用条件编译去解决这个问题，但无效

![image](https://user-images.githubusercontent.com/31914597/66907406-de033680-f03b-11e9-8119-ff40288ef0e2.png)
