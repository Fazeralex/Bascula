Báscula · Panel de peso y grasa corporal

Panel personal de seguimiento de peso, % de grasa (bioimpedancia), masa magra y cintura. Un solo archivo HTML, sin servidores, sin cuentas y sin APIs: todos los datos viven en el localStorage del navegador del usuario.


Privacidad por diseño: este repositorio solo contiene el visor, vacío. Los datos personales nunca se suben a GitHub. Cada persona importa su propio JSON o empieza a registrar de cero, y todo queda en su dispositivo.



Funciones


Registro diario en dos toques: fecha de hoy, campos prellenados con el último valor, botones ±0,1, coma decimal, cintura y nota opcionales.
Entrada por lotes: pega varias líneas tipo 12/07 73,4 18,6 84,5 # nota y las procesa de golpe.
Gráficas (canvas propio, sin librerías):

Serie: peso, tendencia EMA tipo Hacker's Diet, grasa % con banda objetivo, masa magra, cintura e hitos anotados.
Comparar años: media móvil 7d superpuesta por día del año.
Composición: área apilada de masa magra + masa grasa en kg.



Conclusiones automáticas: ritmo de cambio (kg/semana) y déficit/superávit calórico implícito, detector de recomposición (60 días), detector de meseta, efecto día de la semana, proyección de hitos de grasa y semáforo de objetivo con fecha.
KPIs: peso, tendencia, grasa (% y kg), masa magra, cintura, IMC, mínimo histórico.
Datos: exportar/importar JSON (backup completo), exportar CSV, importar CSV/XLSX (detección automática de columnas y conversión de libras), recordatorio de copia de seguridad a los 30 días.
PWA instalable: manifest incrustado + service worker; funciona sin conexión una vez instalada.
