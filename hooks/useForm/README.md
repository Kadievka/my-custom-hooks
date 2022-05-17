# useForm Hook

## Ejemplo de uso:


```

  const initialState = {
    id: 1,
    name: "mock-name",
    email: "mock-email",
    ...
  }

  const { data, loading, error } = useForm(initialState);
```

useForm() // recibe un valor por defecto de {}