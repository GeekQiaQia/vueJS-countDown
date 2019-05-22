v0.1-alpha:

利用localStorage存储倒计时状态；

使用方式；
main.js

    import countDown from './components/common/countDown'
    Vue.use(countDown);

xxx.vue

     <count-down seconds="60" name="myCountDown"></count-down>
