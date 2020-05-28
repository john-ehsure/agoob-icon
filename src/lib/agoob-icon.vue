<template>
	<div class="agoobIcon-page">
		<span class="icon iconfont" :style="{fontSize:size+'px'}" :class="'icon-'+IconName"></span>
	</div>
</template>
<script >
export default {
	name:'agoobIcon',
	props: {
		size:{
			type: [String,Number],
			default: 14,
		},
        IconName: {
            type: String,
            default: 'auto'
        },
    },
	data() {
		return {

		};
	},
	methods:{

	},

}

</script>
<style lang='scss' scoped>
	@import "./styles/iconfont.css";
	.agoobIcon-page{
		display: inline-block;
		padding:5px 5px;
		line-height: 1;
	}

</style>