# arrow

## arrow에서 this사용시 주의점
```javascript
    methods: {
        addTodo: function () {
            console.log(this.newTodo)
        }
    }
    
    methods: {
        addTodo: () => {
            console.log(this.newTodo) // arrow에 this가 없으므로에러. arrow는 this 가 없어서 상위스코프의 this를 찾는다.
        }
    }
```
