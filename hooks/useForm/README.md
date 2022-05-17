# useForm Hook

## Ejemplo de uso:


```

  const initialState = {
    id: 1,
    name: "mock-name",
    email: "mock-email",
    ...
  }

  const [ values, handleInputChange, resetAllValues ] = useForm(initialState);
  
```

useForm() // recibe un valor por defecto de {}