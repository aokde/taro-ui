# Card 卡片

---

提供常见的卡片样式

## 使用指南

在 Taro 文件中引入组件

:::demo

```js
import { AtCard } from 'taro-ui'
```

:::

## 一般用法

:::demo

```html
<AtCard
  note='小Tips'
  extra='额外信息'
  title='这是个标题'
  thumb='http://www.logoquan.com/upload/list/20180421/logoquan15259400209.PNG'
>
  这也是内容区 可以随意定义功能
</AtCard>
```

:::

## AtCard 参数

| 参数    | 说明                 | 类型     | 可选值 | 默认值 |
| ------- | -------------------- | -------- | ------ | ------ |
| title   | 元素的标题           | String   | -      | -      |
| note    | 元素的辅助信息       | String   | -      | -      |
| thumb   | 元素的缩略图         | String   | -      | -      |
| extra   | 元素的额外信息       | String   | -      | -      |
| onClick | 元素被点击触发的事件 | Function | -      | -      |
