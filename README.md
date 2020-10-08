# React Forms

Input components with Vue-style two-way data bindings

## Examples

```jsx
import { Checkbox, useModel } from 'react-forms'
function Example() {
  const checkedNames = useModel(null);
  return (
    <Checkbox value={{ name: "Jack" }} model={checkedNames} />
    <label htmlFor="jack">Jack</label>
    <Checkbox value={{ name: "John" }} model={checkedNames} />
    <label htmlFor="john">John</label>
    <Checkbox value={{ name: "Mike" }} model={checkedNames} />
    <label htmlFor="mike">Mike</label>
  )
}
```
