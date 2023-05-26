# burgos-estadosbrasil
#### A hook with a list of every state of the country, each being an object with id, value and label.

##### Usage

```jsx
import { useEstadosBrasil } from 'burgos-estadosbrasil'

export const App = () => {
    const estados = useEstadosBrasil()

    console.log(estados) 
    ## [
        {id: 1, value:"AC", label: "Acre"},
        {id: 2, value:"AL", label: "Alagoas"},
        {id: 3, value:"AP", label: "Amapá"},
        {id: 4, value:"AM", label: "Amazonas"},
        {id: 5, value:"BA", label: "Bahia"},
        {id: 5, value:"CE", label: "Ceará"},
        {id: 6, value:"DF", label: "Distrito Federal"},
        {id: 7, value:"ES", label: "Espírito Santo"},
        {id: 8, value:"GO", label: "Goiás"},
        {id: 9, value:"MA", label: "Maranhão"},
        {id: 10, value:"MT", label: "Mato Grosso"},
        {id: 11, value:"MS", label: "Mato Grosso do Sul"},
        {id: 12, value:"MG", label: "Minas Gerais"},
        {id: 13, value:"PA", label: "Pará"},
        {id: 14, value:"PB", label: "Paraíba"},
        {id: 15, value:"PR", label: "Paraná"},
        {id: 16, value:"PE", label: "Pernambuco"},
        {id: 17, value:"PI", label: "Piauí"},
        {id: 18, value:"RJ", label: "Rio de Janeiro"},
        {id: 19, value:"RN", label: "Rio Grande do Norte"},
        {id: 20, value:"RS", label: "Rio Grande do Sul"},
        {id: 21, value:"RO", label: "Rondônia"},
        {id: 22, value:"RR", label: "Roraima"},
        {id: 23, value:"SC", label: "Santa Catarina"},
        {id: 24, value:"SP", label: "São Paulo"},
        {id: 25, value:"SE", label: "Sergipe"},
        {id: 26, value:"TO", label: "Tocantins"},
    ]
}
```
