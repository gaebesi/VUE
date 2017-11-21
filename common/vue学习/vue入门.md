# vue

## 申明式渲染 文本插值
```
<body>
    <!-- 声明vue的挂载 里面所有的元素全部被vue接管 -->
    <div id="app"> 
        <!-- 文本插值 -->
        {{name}}
    </div>
</body>

<script>
    // 声明式渲染 
    var vm = new Vue({
        el: "#app",
        data: {
            name: "yuan",
            age: "18"
        }
    })
</script>
```

## 使用 vm.name 在浏览器控制台中使用时  这体现了MVVM框架中的数据的双向绑定

##使用文本插值运算
```
 <div id="app">{{num>5?"yes":"no"}}</div>
```