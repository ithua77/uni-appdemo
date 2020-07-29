<script>
export default {
	onLaunch: function() {
		console.log('App Launch');
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style>
/* 解决头条小程序组件内引入字体不生效的问题 */
/* #ifdef MP-TOUTIAO */
@font-face {
	font-family: uniicons;
	src: url('/static/uni.ttf');
}
/* #endif */
</style>
<!-- <style lang="less">
	uni-tabbar {
	        .uni-tabbar { // tab背景
	            background-image: linear-gradient(to top, #FAF8F8, #FFFFFF)!important; // tab背景图片或者渐变色，背景色和背景图片最多选择一个进行设置
	            .uni-tabbar-border { // tabBar上边框
	                background-color: #F7F4F4!important; // tabBar上边框的颜色
	            }
	            .uni-tabbar__bd { // tabBar单项
	                .uni-tabbar__icon { // 图标
	                    width: 48upx!important;
	                    height: 48upx!important;
	                }
	                .uni-tabbar__label { // 文字
	                    font-size: 20upx!important;
	                }
	            }
	        }
	    }
</style> -->
