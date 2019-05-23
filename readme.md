版本：v0.3-alpha:

原理：刷新不影响倒计时，利用localStorage存储倒计时状态；

使用方式；
- 在main.js注册组件；

        import countDown from './components/common/countDown'
        Vue.use(countDown);

- 在使用组件中xxx.vue引用组件标签即可；

         <count-down @onTimeout="handleTimeout" seconds="60" name="myCountDown" tips="后重新发送"></count-down>
        
        接口定义：
        onTimeout         当倒计时结束以后调用的函数
        seconds           自定义倒计时时间
        name              当前倒计时名称
        tips              自定义提示内容
        
        类定义：
        counter           根据UI设计需求自定义样式
