|     |     |         |                          |               |            |             |
|-----|-----|---------|--------------------------|---------------|------------|-------------|
| 1   | 201 | Alicia  | \"Matemáticas, Física\"  | \"Dr. Pérez\" | \"85, 90\" | Ciencias    |
| 2   | 202 | Roberto | \"Matemáticas, Química\" | \"Dr. Pérez\" | \"78, 88\" | Ciencias    |
| 3   | 203 | Julia   | \"Historia, Literatura\" | \"Dr. Gómez\" | \"92, 80\" | Humanidades |
| 4   | 204 | Mario   | \"Química\"              | \"Dr. Pérez\" | \"75\"     | Ciencias    |

Primera Forma Normal (1NF)

Segunda Forma Normal (2NF)

Tabla de registro de estudiantes

|     |     |
|-----|-----|
| 1   | 201 |
| 2   | 202 |
| 3   | 203 |
| 4   | 204 |

Tabla de Estudiantes

|     |         |                          |            |
|-----|---------|--------------------------|------------|
| 201 | Alicia  | \"Matemáticas, Física\"  | \"85, 90\" |
| 202 | Roberto | \"Matemáticas, Química\" | \"78, 88\" |
| 203 | Julia   | \"Historia, Literatura\" | \"92, 80\" |
| 204 | Mario   | \"Química\"              | \"75\"     |

Table de Profesores de asignaturas

|                          |               |             |
|--------------------------|---------------|-------------|
| \"Matemáticas, Física\"  | \"Dr. Pérez\" | Ciencias    |
| \"Matemáticas, Química\" | \"Dr. Pérez\" | Ciencias    |
| \"Historia, Literatura\" | \"Dr. Gómez\" | Humanidades |
| \"Química\"              | \"Dr. Pérez\" | Ciencias    |

Tercera Forma Normal (3NF)

Tabla de registro de estudiantes claves primarias: Registro ID

Tabla de Estudiantes claves primarias: EstudianteID

Table de Profesores de asignaturas claves primarias: Cursos
