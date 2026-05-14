## Lecture 1 Learnings

I learned that JavaScript contains an infamous bug that originates from its creation in 1995. The bug is that `typeof null` returns `'object'` which would break the internet if it were to be fixed since a large amount of code would become outdated instantaneously.

Other interesting learnings:
- Node.js and React.js are the most popular frameworks
- JSON is used as the packaging for sending data between the front-end and back-end
- There are no quotations around object keys in JavaScript 

### Input
```javascript
typeof null
0.1 + 0.2
5/0
parseInt("eva", 10)
Number.isNaN(parseInt("eva", 10));
const user = { name: "eva", age: "19" }
user.age
user.name
```

### Output
```
'object'
0.30000000000000004
Infinity
NaN
true
undefined
'19'
'eva'
```




