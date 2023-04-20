# 前端小项目练习笔记

## 1.slideBusinessCard

- 纯css声明变量 https://zhuanlan.zhihu.com/p/65082165
- background-image: url("") //这里最好都把双引号加上

## 2.dynamicSearchBox

- 输入框清空样式

  ```css
  border: none;
  background: none;
  outline: none;
  ```
  
  background: none; 
  
  等价于
  
  1. background-color: initial;
  2. background-image: none;
  3. background-repeat: initial;
  4. background-attachment: initial;
  5. background-position: initial;
  
- 在transition当中 , 4个单属性值其中的每个都是可以省略的，但通常不会省略持续时间 , 因为省略之后就看不到动画的效果了。***<span style="color: red">property的默认值是all，duration默认值为0，timing-function默认值是ease，delay默认值是0</span>***

  **https://www.cnblogs.com/programInit/p/6863885.html**

## 3.nutritionLabels

```css
font: 700 32px/1.1 '思源宋体', 'Microsoft Yahei', sans-serif;
```

font的简写，对于字体备用的写法
