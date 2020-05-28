# agoob-icon

> 一群老男人使用的图标组件库

## installation
```js
# install
npm install --save agoob-icon
```
## vueZsqIcon 引入方式
``` js
//全局引入
import Vue from 'vue'
import agoobIcon from 'agoob-icon'

Vue.use(agoobIcon)
```
## 页面使用方式
```html
<agoob-icon :size="size" :icon-name="name"></agoob-icon>

export default {
  data () {
    return {
		name:'auto',// 图标名称
        size:16,//图标大小
    }
  },
  methods:{
  	
  }
}
```