`oninput`,onpropertychange,onchange的用法
`onchange`触发事件必须满足两个条件：
a）当前对象属性改变，并且是由键盘或鼠标事件激发的（脚本触发无效）
b）当前对象失去焦点(onblur)；
onpropertychange的话，只要当前对象属性发生改变，都会触发事件，但是它是IE专属的；
`oninput`是onpropertychange的非IE浏览器版本，支持firefox和opera等浏览器，但有一点不同，它绑定于对象时，并非该对象所有属性改变都能触发事件，它只在对象value值发生改变时奏效。