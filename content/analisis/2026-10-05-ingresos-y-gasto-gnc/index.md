+++
date = '2026-10-05T14:30:00-05:00'
draft = true
title = 'Los ingresos subieron. El gasto subió más.'
slug = 'ingresos-y-gasto-gnc'
resaltado = 'El gasto subió más.'
summary = 'Veinte años de cuentas del Gobierno Nacional Central en una sola imagen: el recaudo creció 2,8 puntos del PIB desde 2005 y el gasto sin intereses creció 5,3. La brecha no se cerró ni en el mejor año de recaudo de toda la serie.'
tags = ['fiscal', 'gnc', 'deficit', 'series-historicas']
tema = 'Finanzas públicas'
datos = 'ingresos-gasto-gnc.csv'

[ficha]
fuente = 'MinHacienda · Banco de la República'
deflactor = 'DANE'
metodologia = 'Caja, totales anuales'
cobertura = '2005–2025'

[validacion]
contra = 'ESPE 90 y Borrador de Economía 1136 del Banco de la República'
cifra = '≤ 0,2 pp'
alcance = 'de diferencia en ingresos, gastos y balance total'
+++

Buena parte de la discusión fiscal colombiana se juega sobre una premisa que
rara vez se verifica: que el déficit existe porque el Estado no recauda lo
suficiente. La premisa contraria circula con la misma soltura: que el recaudo
está en máximos y el problema es exclusivamente de gasto.

Las series del Ministerio de Hacienda desde 2005 permiten revisar las dos. Lo
que muestran no favorece a ninguna del todo, pero sí ordena las magnitudes.

## Dos líneas que dejaron de moverse juntas

![Ingresos y gasto primario del Gobierno Nacional Central como porcentaje del PIB, 2005-2025](ingresos-gasto-primario.svg)

Los ingresos del {{< termino "gnc" >}}Gobierno Nacional Central{{< /termino >}} pasaron de **13,5% del PIB en 2005 a
16,3% en 2025**: 2,8 puntos más en veinte años. No es estancamiento. Es un
crecimiento lento pero sostenido, con reformas tributarias de por medio.

El {{< termino "gasto-primario" >}}gasto primario{{< /termino >}} —el gasto total menos los intereses de la deuda— pasó de
**14,6% a 19,9% del PIB** en el mismo periodo: 5,3 puntos. Casi el doble.

Hasta 2019 las dos líneas se persiguen. La brecha entre ellas se mantiene
dentro de un punto del PIB y **cambia de signo siete veces**: en 2006, 2007,
2008, 2011, 2012, 2013 y 2019 el Gobierno gastó menos de lo que recaudó, antes
de pagar intereses. Eso es un superávit primario, y durante buena parte de dos
décadas fue algo ordinario.

En 2020 las líneas se separan. El gasto primario salta a 20,7% del PIB y los
ingresos caen a 15,3%. Hasta ahí, nada sorprendente: así se ve una pandemia en
las cuentas públicas de cualquier país.

Lo que importa es lo que pasó después.

## La prueba de 2023

![Balance primario del Gobierno Nacional Central como porcentaje del PIB, 2005-2025](balance-primario.svg)

Los ingresos se recuperaron. Más que eso: **2023 fue el mejor año de recaudo de
toda la serie**, con 18,7% del PIB, dos puntos por encima del promedio de las
dos décadas anteriores.

Y aun así el {{< termino "balance-primario" >}}balance primario{{< /termino >}} de 2023 fue negativo: −0,35% del PIB. En el año
de mayor recaudo registrado, el Gobierno todavía gastó más de lo que recibió,
sin contar un solo peso de intereses.

Para 2025 los ingresos volvieron a su nivel habitual, 16,3% del PIB, mientras
el gasto primario se quedó en 19,9% —prácticamente el pico pandémico—. La
brecha es de 3,6 puntos del PIB y lleva seis años consecutivos sin cerrarse: la
racha de déficit primario más larga de la serie.

Conviene insistir en que todo esto excluye los intereses. El déficit total es
mayor. En 2025, en {{< termino "metodologia-de-caja" >}}metodología de caja{{< /termino >}}, fue de 107,6 billones de pesos. Y la
deuda bruta del Gobierno Nacional Central pasó de 32,7% del PIB en 2012 —su
mínimo— a **62,9% en 2025**.

## Lo que la aritmética no dice

Estas cifras establecen una magnitud, no un diagnóstico. No dicen *en qué*
creció el gasto, y esa es la pregunta que decide el debate: pensiones,
transferencias, nómina, subsidios y salud se comportan de maneras muy
distintas, y agregarlos en una sola línea los vuelve indistinguibles.

Tampoco dicen qué debería hacerse. Que la brecha sea de 3,6 puntos del PIB es
un hecho; si se cierra por el lado del recaudo, por el del gasto o por ninguno
es una decisión política sobre la que estos datos no opinan. Lo único que la
aritmética impone es que las tres opciones existen y que la brecha no se cerró
sola en seis años.

Y hay una lectura que estos números sí descartan: la de que el recaudo se quedó
quieto. No lo hizo. Creció. Simplemente no al ritmo del gasto.

## Cómo se construyeron estas cifras

Las series provienen del Ministerio de Hacienda y Crédito Público, en
**metodología de caja**, consultadas en el sistema de información estadística
del Banco de la República. Los totales anuales son la suma de los doce meses;
el PIB nominal y el IPC son del DANE.

Los cálculos se contrastaron contra dos documentos del Banco de la República
—el ESPE 90 y el Borrador de Economía 1136—. Ingresos, gastos y balance total
coinciden con **diferencias menores o iguales a 0,2 puntos porcentuales**, lo
que valida tanto la agregación mensual como el PIB usado como denominador.

Hay cuatro advertencias que conviene no saltarse:

**Caja no es causación.** Las cifras oficiales de sostenibilidad usan
contabilidad de {{< termino "causacion" >}}causación{{< /termino >}}; estas registran cuándo entra y sale el dinero. La
diferencia es pequeña en ingresos y gastos totales, pero alcanza algunas
décimas en el balance primario: en 2011 incluso cambia de signo. Para
afirmaciones sobre sostenibilidad de la deuda, las cifras oficiales mandan.

**Los intereses de 2025 no son comparables.** La serie de caja registra valores
negativos en agosto y octubre de 2025, típicos de operaciones de tesorería que
netean contra el costo de la deuda. Por eso este artículo trabaja con gasto
primario: como el gasto primario es el gasto total menos los intereses, la
cifra no depende de cómo se clasifiquen esas operaciones entre un rubro y otro.
El déficit total de 2025 sí las incorpora y debe leerse con esa salvedad.

**2004 y 2026 quedan fuera.** Para 2004 el DANE no publica PIB en la base
vigente; 2026 solo tiene seis meses.

**Los años recientes son provisionales.** El PIB nominal de los últimos
ejercicios es preliminar y se revisa, lo que mueve ligeramente todas las
razones calculadas sobre él.
