记录一些工作上和看见的BUG。 
-----------------------------------------------------------------------------------------------------------------------------------------
vue-awesome-swiper   上下轮播轮播距离无限叠加。需要设置高度，配置里 height : window.innerHeight。https://segmentfault.com/q/1010000011692769
-----------------------------------------------------------------------------------------------------------------------------------------
safari上点击失效
-----------------------------------------------------------------------------------------------------------------------------------------
华为手机自带浏览器flex失效
-----------------------------------------------------------------------------------------------------------------------------------------
ios安卓margin失效
-----------------------------------------------------------------------------------------------------------------------------------------
iview modal的显示隐藏问题
iview 提供了全局关闭对话框 this.$Modal.remove()
但是这个方式只能用this.$Modal.confirm在modal里生成元素才能使用
直接在modal里放元素的话只能通过其他方式如vuex 改变v-model来控制显示隐藏
转载：https://www.jianshu.com/p/09d922e388b8   iview的一些坑
-----------------------------------------------------------------------------------------------------------------------------------------






