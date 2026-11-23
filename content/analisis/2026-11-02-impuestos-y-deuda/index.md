+++
date = '2026-11-02T20:00:00-05:00'
lastmod = '2026-11-21T13:30:00-05:00'
draft = false
title = 'Por cada 100 pesos de impuestos, 47 de deuda'
slug = 'impuestos-y-deuda-2019-2026'
resaltado = '47 de deuda'
summary = 'En 2025 la Nación recibió tanto crédito como en la pandemia, mientras el recaudo tributario real sigue por debajo de 2023. Lo dicen 1,4 millones de registros mensuales del presupuesto entre 2019 y septiembre de 2026.'
tags = ['fiscal', 'deuda', 'impuestos', 'presupuesto']
tema = 'Finanzas públicas'
datos = 'impuestos-vs-deuda-2019-2026.csv'
serie = 'Impuestos y deuda de la Nación, 2019–2026'
estado = 'cerrada'
datos_nota = '2026 cubre enero–septiembre; sin deflactor ni PIB para ese año.'

[ficha]
fuente = 'MinHacienda (datos.gov.co) · DIAN'
deflactor = 'DANE'
metodologia = 'Recaudo efectivo en caja, acumulado a diciembre'
cobertura = '2019–sep. 2026'

[validacion]
contra = 'Recaudo bruto mensual de la DIAN, corte 23-oct-2026'
cifra = '4–7 %'
alcance = 'de diferencia anual, explicada por los pagos en TIDIS; misma trayectoria en las dos series'
+++

En 2019, por cada $100 que la Nación recibió en impuestos, recibió $25 en
préstamos. En 2020, el año de la pandemia, fueron $68. En 2025, sin pandemia,
fueron $47. Y este año, con corte a septiembre, ha recibido $44 en crédito por
cada $100 que los colombianos pagamos por impuestos.

Esa cifra resume este análisis. Sale de un registro poco usado, el detalle
mensual de los ingresos del Presupuesto General de la Nación entidad por
entidad y rubro por rubro, que el Ministerio de Hacienda publica en datos
abiertos. Son 1,4 millones de filas desde enero de 2019. Aquí se leen dos de
sus ramas: lo que entra por impuestos y lo que entra por crédito.

## El récord que no es

![Impuestos y deuda de la Nación como porcentaje del PIB, 2019-2025](impuestos-deuda-pib.svg)

En pesos corrientes, 2025 fue el año de mayor recaudo tributario de la
historia: **$272 billones**, descontando devoluciones. Pero cada peso de 2025
alcanza para menos que en 2023 por el avance de la inflación, y el PIB también
creció. El recaudo de 2025 no es un récord.

Si lo igualamos todo a {{< termino "pesos-constantes" >}}pesos de 2025{{< /termino >}},
el recaudo de 2023 fue de $295 billones y el de 2025 fue de $272 billones, un
**8 % menos** que dos años antes, y apenas por encima de 2022. Como porcentaje
del PIB, los impuestos fueron 16,6 % en 2023, cayeron a 14,3 % en 2024 y se
recuperaron a 14,7 % en 2025. En 2019 eran 14,3 %, es decir que seis años
después la Nación recauda en impuestos la misma proporción de la economía.

El pico de 2023 se debe a la declaración anual de renta. La serie de la DIAN
separa el impuesto de renta en dos partes: las retenciones, que se cobran mes a
mes sobre la actividad del año corriente, y las cuotas, que se pagan al
declarar las utilidades del año anterior. Las retenciones crecieron parejo:
$79 billones en 2022, $96 billones en 2023, $98 billones en 2024. En cambio,
las cuotas saltaron de $24 billones en 2022 a **$51 billones en 2023** y
volvieron a $30 billones en 2024. Lo que se declaró en 2023 fueron las
utilidades de 2022, el año de los precios altos del petróleo y el carbón, con
las tarifas de la reforma de ese año. En 2024 esa base desapareció, y la caída
del recaudo ($12 billones) se debe por completo a la caída de cuotas
($21 billones), el resto subió.

La serie oficial de la DIAN cuenta la misma historia: −4,3 % en 2024 y +10 % en
2025, con un cierre de **$294,5 billones brutos (sin descuentos)**. Este año, a
septiembre, los impuestos crecen: 5,5 % según la DIAN, 9,4 % según el registro
presupuestal.

## 2025 igualó a la pandemia

En otra parte del presupuesto están los
{{< termino "recursos-de-credito" >}}recursos de crédito{{< /termino >}}, lo
que la Nación recibe cuando se endeuda con la venta de TES en el mercado
interno y los desembolsos de préstamos y bonos en el exterior. No son ingresos
en el sentido corriente, porque hay que devolverlos, pero el presupuesto los
registra como si lo fueran y con ellos se paga parte del gasto.

En 2019 la Nación recibió $38 billones de crédito y al año siguiente recibió
$89 billones. Luego bajó: $72 billones, $57 billones, $66 billones y
$75 billones entre 2021 y 2024. **En 2025 recibió $129 billones,** que en pesos
de 2025 es lo mismo que en 2020 (127). Como porcentaje del PIB es 6,9 %, el
segundo registro más alto de la serie después del 8,9 % de la pandemia.

El salto se explica principalmente por la subida en el crédito interno:
**$86 billones en 2025 contra $48 billones en 2024**, un 80 % más. El crédito
externo también subió, de $27 billones a $43 billones.

Una explicación posible era que el Gobierno hubiera adelantado en noviembre y
diciembre de 2025 deuda destinada a 2026, pero los datos mensuales lo
descartan: el último bimestre de 2025 aportó el 11 % del crédito del año,
contra el 26 % en 2023 y en 2024. De hecho, el endeudamiento de 2025 se
repartió a lo largo del año, con picos en abril y septiembre.

Y 2026 empezó más rápido, con **$40 billones de crédito en enero y febrero**,
el doble que en el mismo bimestre de 2025; a septiembre lleva $101 billones, la
misma cifra que 2025 a esa altura.

## La razón entre las dos

![Pesos de deuda recibidos por cada 100 pesos de impuestos, 2019-2026](deuda-por-100-impuestos.svg)

Poner una cifra sobre la otra tiene una ventaja: no hace falta deflactar ni
dividir por el PIB, porque las dos están en los mismos pesos del mismo año.
Por cada $100 de impuestos, la Nación recibió $25 de deuda en 2019, $68 en
2020, $44 en 2021, $27 en 2022, $25 en 2023, $30 en 2024, **$47 en 2025** y
$44 en lo que va de 2026.

Entre 2022 y 2024 la proporción volvió al nivel de antes de la pandemia, pero
en 2025 se fue a $47 y en 2026 se sostiene en $44. Dos años seguidos con la
deuda cerca de la mitad de los impuestos, sin un choque externo que lo
explique, es un cambio de régimen.

## Lo que estas cifras no dicen

En junio de 2025 el Gobierno activó la
{{< termino "clausula-de-escape" >}}cláusula de escape{{< /termino >}} de la
{{< termino "regla-fiscal" >}}regla fiscal{{< /termino >}}, que suspende por
tres años las metas de déficit y deuda. El Comité Autónomo de la Regla Fiscal
emitió concepto desfavorable pues, en su lectura, la situación no era el evento
extraordinario que la ley exige para suspender la regla, y el plan de ajuste
del Ministerio no bastaba para estabilizar la deuda. Además, el déficit
proyectado para 2025 era de 7,1 % del PIB.

Estos registros muestran la contraparte de ese déficit en la caja, el crédito
que entró para cubrirlo, pero no muestran en qué se gastó, ni si la deuda de
2025 fue cara o barata, ni cuánto de ella vence pronto. Tampoco dicen si el
recaudo debería ser mayor, eso depende de qué impuestos crecen con la economía
y cuáles dependen de un buen año del petróleo.

Pero sí nos permiten establecer una proporción. En 2025 y 2026, de cada tres
pesos que entraron a la Nación por impuestos y crédito, un peso era prestado.

Hace falta toda una lectura de contexto y mucha atención al comportamiento del
gasto para afirmar si hubo un cambio de régimen. Lo que los datos nos permiten
pensar es que la estructura fiscal colombiana requiere una modificación
profunda, y esto no es un descubrimiento nuevo: hay consenso entre académicos
y se puede decir que incluso el fenómeno está suficientemente diagnosticado.
Lo preocupante es la velocidad a la que está subiendo la deuda y la
participación que tiene sobre el total de ingresos que financian el gasto
público. Si la decisión es mantener los ingresos constantes como proporción
del PIB, el recorte presupuestal es de un tamaño considerable y habrá que
revisar un par de actos legislativos que tienen que ver con la
descentralización (el Sistema General de Participaciones); si la decisión es
aumentar el gasto, es importante que la reforma sea ambiciosa; y si es una
combinación de las dos, es importante que se piense una nueva estructura
tributaria de largo plazo.

## Cuatro advertencias

**Caja no es lo que publica la DIAN.** La serie oficial de
{{< termino "recaudo-bruto" >}}recaudo bruto{{< /termino >}} de la DIAN da
294,5 billones para 2025; este análisis, 273,1 brutos. La diferencia es
estructural, de entre 4 % y 7 % cada año desde 2019, y la explicación
consistente está en la definición: la DIAN cuenta el recaudo «en efectivo y en
papeles», es decir, incluye los pagos con
{{< termino "tidis" >}}TIDIS{{< /termino >}}, que no entran como efectivo a la
Tesorería. No se verificó cifra por cifra contra el monto de TIDIS de cada año.
Las dos series tienen la misma forma: pico en 2023, caída en 2024, rebote en
2025.

**2026 crece distinto en cada fuente.** A septiembre, la DIAN crece 5,5 % y el
registro presupuestal 9,4 %; la brecha entre ambas se redujo a 3,6 %. Es rezago
de caja o menos pagos en papeles, y no se puede distinguir todavía. Para el
crecimiento de 2026, la cifra de la DIAN es la prudente.

**2026 va solo en pesos corrientes.** No hay IPC ni PIB completos del año, así
que 2026 aparece en la razón deuda/impuestos, que no los necesita, y en pesos
corrientes comparados contra enero–septiembre de 2025.

**Esto no es todo lo que entra.** Quedan fuera los ingresos propios de los
establecimientos públicos, los fondos especiales (donde se registró el FOME en
2020 y 2021), las contribuciones parafiscales y los
{{< termino "recursos-de-capital" >}}recursos de capital{{< /termino >}}
distintos del crédito: dividendos de Ecopetrol, excedentes, reintegros.
