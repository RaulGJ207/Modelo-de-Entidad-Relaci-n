|     |            |     |        |                         |                |
|-----|------------|-----|--------|-------------------------|----------------|
| 101 | 10/03/2023 | 201 | Carlos | \"Sedán, SUV\"          | \"50, 70\"     |
| 102 | 12/03/2023 | 202 | Laura  | \"Convertible, Pickup\" | \"80, 65\"     |
| 103 | 15/03/2023 | 203 | Pedro  | \"SUV, Van, Sedán\"     | \"70, 60, 50\" |
| 104 | 18/03/2023 | 204 | Ana    | \"Sedán\"               | \"50\"         |

Primera forma Normal

Los valores ya son atómicos

Segundo forma Normal

Tabla de vehículos

|     |            |     |
|-----|------------|-----|
| 101 | 10/03/2023 | 201 |
| 102 | 12/03/2023 | 202 |
| 103 | 15/03/2023 | 203 |
| 104 | 18/03/2023 | 204 |

Tabla de clientes y sus vehículos en alquiler

|     |        |                         |                |
|-----|--------|-------------------------|----------------|
| 201 | Carlos | \"Sedán, SUV\"          | \"50, 70\"     |
| 202 | Laura  | \"Convertible, Pickup\" | \"80, 65\"     |
| 203 | Pedro  | \"SUV, Van, Sedán\"     | \"70, 60, 50\" |
| 204 | Ana    | \"Sedán\"               | \"50\"         |

Tercera forma Normal

Clave primaria de tabla de vehículos: AlquilerID

Clave primario de tabla de clientes y sus vehículos en alquiler:
ClienteID
