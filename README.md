#### vuejs基础入门
###### vue的生命周期

* new Vue()//创建一个实例对象

* beforeCreate:此方法执行的时候,data和nethods中数据还没有初始化

* created//data和methods已经被初始化好了

* beforeMount:模板已经编译好了,但是尚未挂载到页面中

* mounted:如果要通过某些插件操作页面,最早要在mounted中进行,执行完mounted表示vue已经初始化完毕此时组件脱离了创建阶段,进入到了运行阶段

* > 运行阶段的生命周期,在data改变时调用
  >
  > beforeUpdate
  >
  > update

* beforeDestory

* destroyed

