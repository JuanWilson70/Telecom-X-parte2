Proyecto : Análisis de renuncia de clientes 
Empresa : Telecom X

Se realizará el análisis de datos extraidos de la limpieza de datos anteriormente realizada en proyecto

Descripción:
   El proyecto será dividido en las siguientes partes:

- Preparación de los Datos
- Modelado Predictivo
- Interpretación y Conclusiones

Enlace de archivos: En GitHub sed selecciona el archivo y se copia el enlace Raw

'https://raw.githubusercontent.com/JuanWilson70/Telecom-X-parte2/refs/heads/main/datos_normalizados_TelecomX.csv'


Tecnologias
Para realizar este proyecto se utilizaran las siguientes tecnologias:

- Python
- Notebook electronico de Google Colab
- numpy
- plotly
- matplotlib
- seaborn
- sklearn
- imblear
- statsmodels



Cronograma del trabajo
- Se comienza extrayendo los datos csv guardados anteriomente y se crea en un dataframe
- Se realiza un Análisis previo de los datos
- Se realizar el reemplazo de datos y Eliminación de Columnas Irrelevantes
- Se Codifican los datos (Transformar todo a números)
- Se realiza la Verificación de la Proporción de Cancelación (Evasion)
- Balanceo de Clases (Oversample, undersample)
- Normalización o Estandarización de datos
- Análisis de Correlación cde datos 
- Análisis de Variación de inflación de la varianza (VIF)
- Separación de Datos (originales, correlación, vif)
- Creación de Modelos: Árbol, Random Forest, KNN
- Evaluación de los Modelos (Analizando otras métricas)
- Validación cruzada con Balanceo de datos usando la pipeline
- Resumen de modelos y sus métricas
- Análisis de modelo Champion 
- Interpretación, Conclusiones y recomendaciones 
- Guardando el modelo 

Anexos
#### Diccionario de datos 

- Contrato 1 anno: Tiempo de Contrato
- Contrato 2 annos': Tiempo de Contrato
- Pago tarjeta credito: Tipo de pago
- Pago chequera electronica: Tipo de pago
- Pago cheque: Tipo de pago
- Evasion: si el cliente dejó o no la empresa
- Adulto Mayor:información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- Conyuge: Si el cliente es o no casado 
- Cargas: si el cliente tiene o no cargas 
- contrato: tipo de contrato
- Servicio telefonico: suscripción al servicio telefónico
- Multiples lineas: suscripción a más de una línea telefónica
- Internet: suscripción a un proveedor de internet
- Seguridad online: suscripción adicional de seguridad en línea
- Respaldo online: suscripción adicional de respaldo en línea
- Proteccion equipo: suscripción adicional de protección del dispositivo
- Soporte_tecnico: suscripción adicional de soporte técnico
- TVcable: suscripción de televisión por cable
- Peliculas_online: suscripción de streaming de películas
- Factura_online: si el cliente prefiere recibir la factura en línea
- Factura_mes: total de todos los servicios del cliente por mes
- Total: total gastado por el cliente
- Cuentas diarias: Total de gastos del mes dividido por cantidad de dias (30)