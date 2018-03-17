>本编辑器仅可用于手机端，如有Bug反馈和建议请发送邮件至：try@fixel.cn
>官网地址: [https://eleditor.fixel.cn/](https://eleditor.fixel.cn/)
> ![image](https://eleditor.fixel.cn/static/eleditor/images/qrcode.png)

>QQ群: 567594992
>Eleditor其实是为了解决的内部一些特殊编辑需求而开发的一个编辑器，开源出来提供一个简单的富文本编辑方案，首先因为操作问题它并不适合所有业务场景

>文档地址[http://doc.eleditor.fixel.cn/](http://doc.eleditor.fixel.cn/)

更新日志V1.7（2018-03-15）<br>
1.增加clear接口，以正确清空编辑器内容<br>
2.增加revoke撤销接口<br>
3.增加trigger接口，用于直接触发添加逻辑，目前仅支持（insertText, insertLink）<br>
4.增加saveState接口，以便自定义修改内容前保存状态以便撤销<br>
5.upload属性新增formName和accept参数<br>
6.增加初始化属性uploader{Function}，用于取代编辑器自带上传逻辑，必须返回一个Promise对象<br>
7.删除了【难以理解的】删除前、删除后按钮，更换更加直观便捷的批量删除方式<br>
8.修复了iframe和video等标签的编辑选中题<br>
9.修复append方法输入纯文本无法选中编辑问题<br>
10.修复getContent和getContentText会获取placeholder的问题<br>
11.修复插入内容时placeholder遗留的问题<br>
12.修复当内容为空时a链接无法插入的问题<br>
13.文本编辑框placeholder修饰以提示用户可编辑范围<br>
14.修复了旧版撤销的一些bug<br>

目前编辑器还在持续维护，因本人精力有限，群里记录的问题可能本人不能及时回复，但每个问题和意见都会一一记录

开源基于MIT协议，允许自由使用和修改代码
