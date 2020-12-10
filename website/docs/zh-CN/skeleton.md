## Skeleton 骨架屏

在需要等待加载内容的位置设置一个骨架屏, 某些场景下比Loading的视觉效果更好。

### 基础用法

基础的骨架效果。

:::demo
```html
<template>
  <el-skeleton />
</template>
```
:::

### 更多参数

可以配置骨架屏段落数量, 以便更接近真实渲染效果。


:::demo
```html
<el-skeleton :rows="5" />
```
:::

### 动画效果

显示动画效果。

:::demo
```html
<el-skeleton :rows="5" loading="true" />
```
:::

### Skeleton Attributes
| 参数          | 说明            | 类型            | 可选值                 | 默认值   |
|-------------  |---------------- |---------------- |---------------------- |-------- |
| rows      | 骨架屏段落数量  | number  |           正整数          |    3     |
| loading      | 是否展示动画效果 | boolean  |  true / false  |  false |