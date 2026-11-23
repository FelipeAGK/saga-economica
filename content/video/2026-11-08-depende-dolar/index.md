+++
date = '2026-11-08T14:00:00-05:00'
draft = false
title = '¿Sube el dólar esta semana? Depende.'
slug = 'depende-dolar'
resaltado = 'Depende.'
summary = 'Depende explica de qué depende el dólar: esta semana, de las tasas y del miedo (los factores push y pull); a la larga, de cuánta más inflación tenemos que Estados Unidos. Un video corto, con la TRM de las últimas siete semanas.'
tags = ['dolar', 'tasas', 'depende']
tema = 'Dólar y tasas'
youtube = 'Hq1aVee83OA'    # Short «¿Sube o baja el dólar?» en el canal de Angélica, 23-nov-2026 (v4 con su voz). El mp4 vive en D:\saga-economica-media\depende\
poster = 'poster.jpg'
formato = 'vertical'
duracion = '0:47'
publicado = '23 de noviembre de 2026'
lastmod = '2026-11-23T10:00:00-05:00'

# Lo que el video no muestra: cada cifra con corte y fuente (S1).
[[cifras]]
valor = '$ 3.316,70'
dato = 'TRM vigente del 14 al 17 de noviembre de 2026'
corte = 'Publicada el 13 nov 2026'
fuente = 'Banco de la República, vía datos.gov.co'
url = 'https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3'

[[cifras]]
valor = '3,75–4,00 %'
dato = 'Tasa de la Reserva Federal (rango objetivo)'
corte = 'Decisión del 28 de octubre de 2026'
fuente = 'FOMC'
url = 'https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm'

[[cifras]]
valor = 'US$ 96'
dato = 'Brent, el petróleo de referencia: venía de US$ 104 el 3 de noviembre'
corte = '13 nov 2026'
fuente = 'Trading Economics'
url = 'https://tradingeconomics.com/commodity/brent-crude-oil'

[[cifras]]
valor = '6,30 % vs 3,7 %'
dato = 'Inflación anual en Colombia (octubre) y en Estados Unidos (septiembre; el BLS no publica la anual de octubre por falta del dato de 2025)'
corte = 'DANE 9 nov 2026 · BLS 14 oct 2026'
fuente = 'DANE · BLS'
url = 'https://www.dane.gov.co/index.php/estadisticas-por-tema/precios-y-costos/indice-de-precios-al-consumidor-ipc'

[[fuentes]]
titulo = 'Bofinger (2001), Monetary Policy, capítulo 12'
url = '/video/depende-dolar/#el-marco'
nota = 'Paridad descubierta de tasas (corto plazo) y paridad de poder adquisitivo (largo plazo).'

[[fuentes]]
titulo = 'Calvo, Leiderman y Reinhart (1993)'
url = 'https://www.elibrary.imf.org/view/journals/024/1993/001/article-A004-en.xml'
nota = 'De aquí vienen los nombres push y pull: factores externos e internos de los flujos de capital.'

[[fuentes]]
titulo = 'La TRM, serie completa'
url = 'https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3'
nota = 'Banco de la República en datos abiertos; el CSV del video sale de aquí.'

[[fuentes]]
titulo = 'El tablero de indicadores de Saga'
url = '/'
nota = 'TRM, tasa de política e inflación, con corte y fuente, arriba de cada página.'
+++

Primer video de Depende. Le preguntan si el dólar sube esta semana y contesta lo
de siempre, pero esta vez explica de qué depende: de lo que pase afuera (los
factores *push*: la Fed, el miedo en los mercados, el petróleo), de lo que pase
adentro (los factores *pull*: la tasa del Banco, el déficit, lo que el mercado
espera del peso) y, a la larga, de una sola cosa: cuánta más inflación tenemos
que Estados Unidos.

## El marco

Las dos ideas del video salen del capítulo 12 de *Monetary Policy* de Peter
Bofinger (2001). La primera es la **paridad descubierta de tasas de interés**: si
el capital se mueve libremente, la diferencia entre la tasa de aquí y la de
afuera tiene que igualar lo que el mercado espera que se deprecie el peso, más
una prima por el riesgo de tenerlo. Por eso la tasa del Banco jala dólares hacia
adentro, la de la Fed los empuja hacia afuera, y el déficit cobra en la prima.

La segunda es la **paridad de poder adquisitivo** en su versión relativa: con el
tiempo, la tasa de cambio se mueve lo que la inflación de un país le saca a la
del otro. Bofinger advierte que se cumple mal en el corto plazo y mejor en el
largo. Es la pendiente de fondo que ningún dato de la semana cambia.

Los nombres *push* y *pull* no son de Bofinger: vienen de Calvo, Leiderman y
Reinhart (1993), que así separaron los factores externos e internos detrás de
las entradas de capital a América Latina.

## Cómo se hizo

La animación está escrita en Python con Manim; el retrato de Depende es el mismo
de la carátula del boletín, vectorizado a partir de su foto. La serie de la
{{< termino "trm" >}}TRM{{< /termino >}} se descargó de datos abiertos el 15 de
noviembre y está en el CSV del video.
