# Vue 学习笔记

### Vue 属性
* el   elementId
* data  该 element(this) 下的数据字段
* methods 该 element(this) 下的所有函数
* filters 该 element(this) 下的所有过滤器， 在指令中或字符串模板中 通过 `|` 使用
* computed 可以使用 methods 替代，但是 computed 更优，只有相关依赖改变，该函数才执行

### Vue 指令
> 指令都必须在标签中使用

* v-model 可用于双先绑定
* v-on
* v-bind
* v-click 可简写为 @click
* v-if v-else-if v-else
* v-show 是否显示元素
* v-for


### 字符串模板
