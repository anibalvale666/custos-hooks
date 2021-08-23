# useForm de objetos anidados
Funciona igual que el useform pero soporta objetos anidados

Ejemplo:


```

    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [ formValues, handleInputchange, reset ] = useForm( initialForm );

```