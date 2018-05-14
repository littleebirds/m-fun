### 模块文档
- getStyle1:getStyle1,    两个参数(elem[目标元素],name(目标属性))
                            已知bug 不能获取边框属性
- getStyle2:getStyle2,    两个参数(elem[目标元素],name(目标属性))
- getClass1:getClass1,    两个参数(name[获取的类名],type(获取元素的类型))
- getClass2:getClass2,    两个参数(parent[获取元素的父级],cls[获取元素的类名])
- addEvent1:addEvent1,    三个参数(elem[添加事件的元素],type[添加的事件类型],fn[事件发生的执行函数])
- removeEvent1:removeEvent1, 与添加事件相对应
- addEvent2:addevent2,    三个参数(element[添加事件的元素],type[添加的事件类型],handle[事件发生的执行函数])
- removeEvent2:removeevent,
- hasFlash:hasFlash,      检查浏览器是否支持Flash，直接调用即可
- hasQt:hasQt,            检查浏览器是否支持QuickTime，直接调用即可
- createTable:createTable,两个参数(row[行],col[列])   动态添加表格
                          默认表格内部内容为乘法口诀
- Ajax:Ajax               四个参数(method[请求方法],url[请求地址],data[请求数据],success[成功的回调函数])
- moveDir:moveDir         五个参数(elem[目标元素],cbR(右滑回调),cbT(上滑回调),cbL(左滑回调),cbB(下滑回调))

* 内容多为从网络，书籍总结而来