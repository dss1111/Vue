# component

## global
```javascript
      Vue.component('MyGlobal', {
        template: '<h1>전역 컴포넌트</h1>',
      });
```
## local
```javascript
      new Vue({
        el: '#app1',
        components: {
          'my-local': {
            template: '<h2>지역 컴포넌트</h2>',
          },
        },
      });
```
