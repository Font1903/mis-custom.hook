# useForm Hook


Ejemplo de uso:
```
    const initialForm = {
        nombre: '',
        age: 0,
        email: ''
    }
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```