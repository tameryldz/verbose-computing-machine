| Clave          | Tipo        | Descripción                                                                                                                                                                                           |
| -------------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Acción`       | `secuencia` | La acción que se realizó. Puede ser uno de entre `requested` o `completed`.                                                                                                                           |
| `workflow_run` | `objeto`    | La ejecución del flujo de trabajo. Muchas claves de `workflow_run`, tales como `head_branch`, `conclusion`, y `pull_requests` son las mismas que aquellas en un objeto [`check_suite`](#check_suite). |