## Props

-> props -> property

- Props is an object

- All components have properties whether you define them or not.

- Write `this.props` can get really annoying. We can use `es6` `let` to limit the scope to the block.


```javascript
  let name = this.props.name;
  let location = this.props.location;
```

Now we can just call  `name ` and `locatoin` as follows:

```html
  <p>Hello, { name }</p>
  <p>I live in { location }</p>
```
