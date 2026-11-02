# Mi Observatorio Financiero

Aplicación educativa construida con Python y Streamlit en la S23.

## Ejecución

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Funcionalidades

Selección de tickers, comparación de precios, rendimiento, volatilidad y estadística descriptiva.

## Fuente

Yahoo Finance mediante yfinance; si falla, la app informa que utiliza datos simulados.

## Autor e interpretación





#### Millerlay Vélez Sánchez.



A mi diseño en la app Streamlit lo nombré: **MVS Finanzas · Proyecto Financiero**



escribe qué hace la aplicación, de dónde provienen los datos, cómo se ejecuta y qué significan sus indicadores.



Profe, pues acá ejecutando en el Colab, puedo ver en la nueva pestaña (app streamlit) que es un medio que permite diseñar visualmente la información que registramos a través de los códigos. Es decir, refleja gráficamente lo que estamos ejecutando.



Adicional al diseño, también me permite agregar nuevas pestañas, permite visualizar la evolución del valor de las acciones en diferentes períodos de tiempo, puedo ver las tendencias con mi lista de tickers y ejecutar por ejemplo solo algunos (los de mi interés) también sirve para analizar y comparar pérdidas y ganancias a través del comportamiento de los tickers que registramos. En este caso puntual por ejemplo vemos la gráfica BASE100, los RENDIMIENTOS y el VALOR DE INVERSIÓN de esos activos.



Ahora, para estos tickers, se extraen los datos históricos desde Yahoo Finance.



1\.	¿Cuál de los activos obtuvo mayor rendimiento en el período seleccionado?

Seleccioné el período de 1 año, encontrando que el activo con mayor rendimiento fue AAPL, con la media de 0.105%.



2\.	¿Qué activo presentó mayor volatilidad? ¿Cómo lo calculaste?

El activo con mayor volatilidad fue NVDA con 2.356%.



3\.	¿Por qué normalizar los precios a una base común permite compararlos?

La normalización a Base 100 es una herramienta que iguala los puntos de partida de diferentes inversiones en el tiempo. Su objetivo es eliminar la diferencia en el precio en dólares de cada acción, permitiendo comparar directamente qué tan bien rinde una frente a la otra.

Para lograrlo, se elige una misma fecha de inicio y se asume que todos los activos comienzan con un valor de 100. A partir de ese momento, el gráfico ya no muestra el dinero que cuesta la acción, sino el crecimiento o pérdida porcentual que va acumulando cada inversión.



4\.	¿Qué información aportan las medias móviles y qué no permiten asegurar?

Permiten identificar las tendencias y ayudan a reconocer de manera sencilla si un activo se encuentra en una tendencia alcista o bajista. Y no permite asegurar resultados futuros, puesto que está basado en datos históricos y no garantiza hacia donde se moverá el precio en el futuro.



5\.	¿Qué significa una correlación positiva o negativa entre dos activos?

Correlación Positiva: Los rendimientos de ambos activos se mueven en la misma dirección. El impacto en la cartera es que maximiza las ganancias en mercados alcistas, pero incrementa drásticamente el riesgo de pérdida total en mercados bajistas, al no ofrecer protección ante caídas generalizadas.

Correlación Negativa: Los rendimientos de los activos se mueven en direcciones opuestas. El impacto en la cartera es que actúa como un mecanismo de cobertura y amortiguación, reduciendo la volatilidad global y protegiendo el capital, ya que la subida de un activo compensa la caída del otro.







