<template>
	<view>
		<h1>该页面不存在</h1>
	</view>
</template>

<script setup lang="ts">
import { onLoad } from "@dcloudio/uni-app";
onLoad(() => {
  const timer = setTimeout(()=> {
	  clearTimeout(timer)
	  uni.navigateTo({
		url:'/pages/index/index'
	  })
  },2000)
});
</script>

<style>
</style>   