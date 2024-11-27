|     |            |     |       |      |           |     |     |
|-----|------------|-----|-------|------|-----------|-----|-----|
| 301 | 05/04/2023 | 501 | Juan  | 1001 | Lápiz     | 10  | 0.5 |
| 301 | 05/04/2023 | 501 | Juan  | 1002 | Cuaderno  | 5   | 1.5 |
| 302 | 06/04/2023 | 502 | María | 1003 | Bolígrafo | 8   | 0.8 |
| 303 | 07/04/2023 | 503 | Luis  | 1001 | Lápiz     | 12  | 0.5 |
| 303 | 07/04/2023 | 503 | Luis  | 1004 | Borrador  | 4   | 0.3 |

Primera Forma Normal (1FN)

Esta tabla cumple con la 1FN ya que todos los valores son atómicos

Segunda Forma Normal (2FN)

Tabla del pedido

|     |            |     |
|-----|------------|-----|
| 301 | 05/04/2023 | 501 |
| 301 | 05/04/2023 | 501 |
| 302 | 06/04/2023 | 502 |
| 303 | 07/04/2023 | 503 |
| 303 | 07/04/2023 | 503 |

Tabla de los clientes

|     |       |      |
|-----|-------|------|
| 501 | Juan  | 1001 |
| 501 | Juan  | 1002 |
| 502 | María | 1003 |
| 503 | Luis  | 1001 |
| 503 | Luis  | 1004 |

Tabla del producto comprado

|      |           |     |     |
|------|-----------|-----|-----|
| 1001 | Lápiz     | 10  | 0.5 |
| 1002 | Cuaderno  | 5   | 1.5 |
| 1003 | Bolígrafo | 8   | 0.8 |
| 1001 | Lápiz     | 12  | 0.5 |
| 1004 | Borrador  | 4   | 0.3 |

Tercera Forma Normal (3FN)

Tabla del pedido claves primarias: PedidoID

Tabla de los clientes claves primarias: ClienteID

Tabla del producto comprado claves primarias: ProductoID
