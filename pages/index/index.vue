<template>
	<view>
		<cu-custom bgColor="bg-gradual-blue">
			<block slot="content" class="text-xl">健康上报</block>
		</cu-custom>
		<view class="flex flex-wrap justify-center margin-xs">
			<view class="flex-sub margin-xs padding-lg radius shadow-blur bg-gradual-blue">
				<view class="cu-item justify-center">
					<text class="cuIcon-profile"></text>
					<text class="text-xl margin-left-sm">个人信息 </text>
					<text class="margin-left-sm cuIcon-right"></text>
				</view>
				<view class="text-lg margin-top">展示用户的相关信息</view>
				<button class="cu-btn block lines-white lg text-lg margin-top">
					查看自己创建的社区或公司 <text class="margin-left-sm cuIcon-right"></text>
				</button>
			</view>
		</view>
		<view class="flex flex-wrap justify-center margin-xs">
			<view class="flex-sub margin-xs padding-lg radius text-center shadow-blur bg-gradual-purple">
				<view class="text-xl">创建社区或公司</view>
			</view>
		</view>
		<view class="flex flex-wrap justify-center margin-xs">
			<view class="flex-sub margin-xs padding-lg radius text-center shadow-blur bg-gradual-green">
				<view class="text-xl">一键健康上报</view>
			</view>

			<view class="flex-sub margin-xs padding-lg radius text-center shadow-blur bg-gradual-red">
				<view class="text-xl">异常状况上报</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				ColorList: this.ColorList
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>

</style>
