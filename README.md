# Vue Scroller Extend ![version](https://img.shields.io/badge/version-%20v1.1.0%20-green.svg) ![vue](https://img.shields.io/badge/vue-%20v2.1%20-green.svg) 
## 原作者
[Vue Scroller](https://github.com/wangdahoo/vue-scroller) 

## How to use

```bash
npm i vue-scroller-extend
```

```js
import Vue from 'vue'
import VueScroller from 'vue-scroller-extend'
Vue.use(VueScroller)
```

```html
<scroller :on-scroll="onscroll">
  <!-- content goes here -->
</scroller>
```

#### Add scroller vm instance methods:

- `getScrollMax :Object` get max offset of scroller content
