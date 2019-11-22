# next-js-core2
> A javascript OOP toolkit for mobile.

## installation
```bash
npm install --save @feizheng/next-js-core2
```

## node
```js
import nx from 'next-js-core2';

const MyClass = nx.declare({
  statics:{
    init: function(){
      console.log('hello next!')
    }
  }
})
```

## browser
```html
<script type="text/javascript" src="../libs/next-js-core2/dist/next-js-core2.js"></script>
<script type="text/javascript">
(function (nx, global) {
  nx.declare('myApp', {
    statics: {
      init: function () {
        alert('hello next!');
      }
    }
  });
}(nx, nx.GLOBAL));
</script>
```
