# useForm

Usage example:

```javascript
const initialForm = {
  name: "",
  age: 0,
  email: "",
  moreFields,
};

const [formValues, handleInputChange, reset] = useForm(initialForm);
```

Returns the form state and two basic functions
