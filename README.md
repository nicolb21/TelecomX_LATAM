# TelecomX_LATAM
Desafio Telecom X - Análisis de Evasión de Clientes  - Alura Latam


> ***Telecom X - Análisis de Evasión de Clientes***


---



He sido contratado como asistente de análisis de datos en Telecom X y formo parte del proyecto "Churn de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

Recopile, procese y analice los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. 

Extraje los datos de una api en formato JSON y le di formato normalizando algunas columnas, luego cuando tenia todos los valores, los unifique en una sola tabla en la cual estarian vinculados.
Realice algunas transformaciones de datos como por ejemplo en entero o en flotante para poder trabajar correctamente con la biblioteca numpy.

Analice y busque los valores nulos que me darian un error estadistico al realizar los analisis y graficos y elimine esas filas.

Luego realice diversos graficos para poder ayudar a la empresa a tomar deciciones de porque sus clientes evaden/cancelan sus suscripciones a la empresa.

***Realice 7 graficos.***




---


> ***Proporcion de cliente con evacion:***


El cual nos muestra una tasa de evacion del 26.6% del total de sus clientes. 



---


> ***Antiguedad de los clientes***


El cual nos muestra que el 50% esta por encima de los 30 meses y el otro 50% por debajo. Que como maximi los clientes se quedan un poco mas de 72 meses pero siempre mas de un mes.

---


> ***Antiguedad vs costo diario***


No se aprecia una relacion entre el costo diario que paga el cliente y su antiguedad. La empresa podria dar promociones a medida que aumenta la antiguedad del cliente para tratar de mantenerlos y que no se vayan.



---


> ***Distribucion de evacion por genero***


No se aprecia evidencia notoria en la tasa de evacion segun el genero.

---

> ***Distribucion de evacion por tipo de contrato***



Aqui se puede ver un gran problema. La mayor evacion por baste se da en los clientes que tienen un contrato mensual, mientras que los que tienen un contrato por dos años practicamente no cancelan su suscripcion.




---


> ***Distribucion de evacion por metodo de pago***


Aqui se puede ver que los clientes que pagan con cheque electronico tienen una tasa de cancelacion aproximadamente 5 veces mayor que los clientes que pagan con otros metodos de pago.


---


> ***Distribucion de evacion por Antiguedad/Cargas mesuales/Cargas totales/Cargos diaros por evacion***


En estos 4 graficos se puede comparar y apreciar los clientes que abandonan el servicio vs los que no abandonan el servicio. 
Se puede leer facilmente que el 50% los clientes que abandonan estan por debajo de 10 meses; ademas los clientes que abandonan el servicio pagan mensualmente una sifra practicamente mayor que el 50% de los clientes que no abandonan, pero en gastos totales, terminana paragando menos que el 50% de los que no abandona.


---

***Recomendaciones:***

La recomendacion para que los clientes no abandonen el servicio podria ser, no brindar el servicio de cheque electronico, o realizar ofertas y descuentos en el servicio con los otros metodos de pago para que los clientes no elijan pagos con cheques electronicos.
Ademas ofreceria descuentos, por contratar el servicio por año y si es por mas tiempo un descuento aun mayor.
A los clientes que superen los seis meses le daria incentivos (como mayor velocidad de internet, telefono, o algun descuento en su pago, para fortalcer el vinculo con la empresa y que no decida dejarnos y a su vez empiece a recomendarnos.

