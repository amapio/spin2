# vue-spin2

> 基于ant design的vuejs loading组件

## Build Setup

``` bash
# 引入
import Spin2 from '**/spin2'

# 注册
Vue.component('Spin2', Spin2)

# 调用
<Spin2></Spin2>
```

## API

### String size
提供3个尺寸，默认不填为中，small，large

### String tip
loading时显示的文字，可以为空

### Boolean spinning
控制loading的开关

### Boolean noDot
不显示图标

## Demo

``` bash
# 正常调用
<Spin2 :spinning="loader" tip="加载图表中"></Spin2>

# 组件中加入内容，自动出蒙层
<Spin2 :spinning="loader">
  <div>
    ...
  </div>
</Spin2>
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2017, zhangzuo
