# IA Resumen Bancario (moneyfix)
- Sube un PDF, extrae movimientos por TEXTO (no por tablas).
- Montos con dos decimales separados por coma: tolera espacios y signos al final (p.ej. `1 . 234 , 00 -`).
- Toma **penúltimo** monto como Importe y **último** como Saldo.
- Regla: Crédito RESTA, Débito SUMA.
