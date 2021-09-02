# useForm hook

Ejemplo:
```
    const initialForm = {
        name: '',
        age: 0,
        eail: ''
    };
    
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```