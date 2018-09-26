**Vue省市县插件**


> 引入：

    <script src="vue.js"></script>
    <script src="places.js" ></script>
    

> Demo

    <div id="app">
        <place :p__="p" :c__="c" :a__="a" place_class=""></place>
    </div>

    <script>
    let vm = new Vue({
        el: "#app",
        data: {
            p: "湖北",
            c: "武汉",
            a: "江汉区",
      
        },
    });


    </script>
