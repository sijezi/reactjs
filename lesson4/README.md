## Props

-> props -> property

- Props is an object

- All components have properties whether you define them or not.

- Write `this.props` can get really annoying. We can use `es6` `let` to limit the scope to the block.


```javascript
  let name = this.props.name;
  let location = this.props.location;
```

Now we can just call  `name ` and `location` as follows:

```html
  <p>Hello, { name }</p>
  <p>I live in { location }</p>
```

### Property or Props Validation

We can define `propTypes`

PropTypes can be declared outside of the component class.

* One way to avoid errors is to provide a default PropTypes as in the following:

```javascript
getDefaultProps: function() {
  return {
    name: 'Simba',
    location: 'WA'
  }
}
```

Interestingly, PropTypes only working during development mode.
