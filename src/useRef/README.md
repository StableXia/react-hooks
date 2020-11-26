### useRef

useRef 创建一个引用的关系存放数据，在组件的整个生命周期中只会创建一次（引用不变，值可变）

### ref（属性）/createRef（api）/useRef（api）

> 我们试着从他们的目的、使用规范、原理来分析

1. 目的  
   useRef：创建一个可变的引用对象，存放一些数据，可以再组件整个生命周期使用,在组件的整个生命周期中只会创建一次  
   createRef：创建一个可变的引用对象，存放一些数据，随着组件的更新会重新创建  
   ref：用于获取 dom、组件实例

2. 使用规范
   useRef：只能用在 function 组件中  
   createRef：function 和 class 组件均可  
   ref：function 和 class 组件均可
