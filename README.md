# Vue Scroller Extend
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
