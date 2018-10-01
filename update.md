
## Westore 更新日志

### 纯组件、业务组件与单向数据流

#### 纯组件(
  
常见纯组件由很多，如 tip、alert、dialog、pager、日历等，与业务数据无直接耦合关系。
组件的显示状态由传入的 props 决定，与外界的通讯通过内部 triggerEvent 暴露的回调。
triggerEvent 的回调函数可以改变全局状态，实现单向数据流同步所有状态给其他兄弟、堂兄、姑姑等组件。


