<!-- <template>
	<view>
		<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
			<view style="height: 100rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院</view>
			<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
		</view>
		<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
			<view style="height: 100rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院</view>
			<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
		</view>
		<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
			<view style="height: 100rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院</view>
			<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
		</view>
		<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
			<view style="height: 100rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院</view>
			<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {

		},
		components: {
			uniBadge
		}
	}

	import uniBadge from "@/components/uni-badge/uni-badge.vue"
</script> -->

<template>
	<view>
		<view style="margin: 20rpx">
			<u-search placeholder="请输入你想搜索的学院" v-model="keyword" :animation="true"></u-search>			
		</view>
		<view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
			<view style="display: flex; direction: row; flex: 3; margin: 5rpx;">
				<view style="height: 200rpx; width: 100rpx; flex: 1; border: 1px solid red; margin-right: 5rpx;">学院
				</view>
				<view style="flex: 2; border: 1px solid red; margin-left: 5rpx;">详细信息</view>
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		data() {
			return {
				keyword: '',
			}
		},
	}
</script>