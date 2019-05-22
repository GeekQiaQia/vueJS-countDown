v0.3-alpha:

利用localStorage存储倒计时状态；

使用方式；
main.js

    import countDown from './components/common/countDown'
    Vue.use(countDown);

xxx.vue

     <count-down @onTimeout="handleTimeout" seconds="60" name="myCountDown" tips="后重新发送"></count-down>
