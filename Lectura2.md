# 2023-02-2018191805-IC4302-Lectura2

Alexander Brenes Garita - 2018191805

---------------------------------------------------------------------------------------------

1. ¿En qué consisten los datos timeseries?
Los timeseries temporales son conjuntos de observaciones ordenadas cronológicamente que se utilizan para analizar y comprender cómo cambian los fenómenos a lo largo del tiempo y para hacer predicciones sobre su comportamiento futuro.

2. ¿Qué son métricas?
Las métricas son medidas que se utilizan para evaluar y cuantificar  sistema o conjunto de datos, por eso se utilizan con los datos timeseries.

3. ¿Explique en que consiste la Observabilidad?
La observabilidad se centra en la capacidad de comprender y supervisar efectivamente el comportamiento interno y el rendimiento de un sistema en tiempo real. La observabilidad detectan un sistema está en funcionamiento o no.
Para lograr esto, se recopilan y analizan diversos tipos de datos lo cual se agrupan en tres ideas principales: **Logs, Metricas y Traces.**

4. ¿Por qué los tags en métricas permiten generar mejores gráficos en Grafana?
Los tags son las métricas permiten generar mejores gráficos y mejorar la organización y filtrado de los datos en los paneles. Los tags son metadatos o información adicional que se asocian a las métricas y que pueden ser utilizados para agregar contexto y detalles a los datos.

5. Suponiendo que se están recolectando datos IoT (Internet of Things) de miles de dispositivos, los mismos generan una métrica cada 15 segundos con el consumo de energía y temperatura, explique:

- ¿Porque una base de datos relacional no es una buena opción para almacenar esta información?
Una base de datos relacional puede no ser la mejor opción para almacenar información de IoT en ciertos casos debido a la estructura rigida ya que requieren un esquema predefinido en el que se definen tablas, columnas y tipos de datos. Tambien por su latencia debido a su naturaleza transaccional y la necesidad de mantener la integridad de los datos, las operaciones de escritura pueden tener una latencia más alta y el costo ya que el escalado y mantenimiento para grandes espacios puede resultar costoso.

- Dada la naturaleza de datos timeseries, ¿De qué forma la localidad puede ayudarnos a ahorrar dinero?
La localidad es importante en la optimización y ahorro de dinero al analizar en timeseries y algunas de los conceptos para ahorar dinero son las Detecciones de anomalias ya que analizar los datos de timeseries a nivel local, es más fácil detectar anomalías y desviaciones en el consumo de energía y temperatura en una ubicación específica y tambien la optimización de recursos locales, al analizar los datos a nivel local, es posible ajustar los sistemas de manera más precisa para optimizar el uso de recursos.

