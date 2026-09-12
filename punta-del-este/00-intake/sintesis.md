# Síntesis — de fragmentos a hipótesis de negocio

> Marcas de origen: `[DICHO]` = el usuario lo afirmó · `[INFERIDO]` = deducción mía, requiere
> confirmación · `[HUECO]` = falta información.
>
> **Estado: v0.1 — capturado el fragmento 1 de N. El usuario sigue aportando contexto.**

---

## 1. Qué es el negocio (una frase)

`[DICHO]` Una **empresa premium de demoliciones** en el eje Maldonado / Punta del Este /
La Barra / José Ignacio que recupera el **100% del material demolido** y lo canaliza
"de la manera más efectiva", con estándar de calidad premium.

`[INFERIDO]` Lo que en realidad se está describiendo no es una demolotora: es una
**empresa de gestión de fin de vida de activos construidos**, donde la demolición es el
acceso al flujo de materiales y el negocio real puede estar en tres capas distintas
(servicio, materiales, cumplimiento). Ver §3.

---

## 2. Tesis de mercado declarada

`[DICHO]` Cadena causal propuesta por el usuario:

1. Maldonado en sentido amplio (Punta del Este, José Ignacio, La Barra) crece a ritmo
   acelerado.
2. Parte de ese crecimiento es greenfield (zonas rurales / sin habitar) y parte es
   **redesarrollo sobre zonas ya construidas**.
3. El redesarrollo implica reformas con demoliciones parciales o totales.
4. Entre obra nueva y demolición se genera un flujo crítico de residuos.
5. Ese flujo tiene potencial de aprovechamiento muy alto y hoy no se captura.

### Corrección de encuadre `[INFERIDO — a validar con el usuario]`

El mercado direccionable **no es el crecimiento total de Maldonado**: es únicamente la
**fracción brownfield** (redesarrollo sobre lote ya construido). El crecimiento en zonas
rurales o sin habitar no genera demolición, solo genera residuo de obra nueva — que es
otro flujo, mucho más limpio, más homogéneo y con otra dinámica comercial.
Dimensionar el TAM contra el crecimiento total sobreestima el mercado.

### El motor real del ciclo de demolición `[INFERIDO]`

La demolición se dispara cuando **el valor del suelo supera al valor de la mejora
existente**. En un mercado con precio de suelo en alza y normativa que habilita mayor
edificabilidad (más FOT/FOS o más altura que la construcción original), ese cruce se
acelera y el stock viejo se vuelve económicamente obsoleto aunque esté físicamente sano.

**Esto es testeable, y es el dato #1 a conseguir:** serie histórica de *permisos de
demolición* emitidos por la Intendencia Departamental de Maldonado, desagregada por
padrón/zona y por m². Si esa serie no crece, la tesis se cae en el primer párrafo.

---

## 3. ¿Uno, dos o tres negocios? — la bifurcación estratégica central

`[INFERIDO]` Lo descrito mezcla tres modelos con economía, ciclo de caja y competencias
distintas. Confundirlos es el error clásico de este sector.

| Capa | Qué se vende | Quién paga | Economía | Riesgo principal |
|---|---|---|---|---|
| **A. Servicio de demolición** | Que el edificio desaparezca, seguro, en plazo, con permisos | Desarrollador / propietario | Ingreso por proyecto, cobro contra avance | Ciclo de obra, siniestralidad, capital en maquinaria |
| **B. Banco de materiales** | Materiales recuperados (madera, ladrillo, teja, aberturas, herrajes, sanitarios) | Arquitectos, decoradores, autoconstructores, anticuarios | Margen sobre inventario, **capital de trabajo inmovilizado meses o años** | Logística inversa, almacenamiento, rotación lenta |
| **C. Cumplimiento y trazabilidad** | Certeza jurídica: permisos, retiro legal de peligrosos, certificado de destino, reporte auditable de desvío de vertedero | Desarrollador, estudio de arquitectura, fondo con exigencia ESG | Servicio de alto margen, bajo capex | Depende de que exista exigencia regulatoria o reputacional |

**La pregunta que hay que contestar antes que cualquier otra:** ¿cuál de las tres es el
negocio y cuáles son subproductos? Una empresa que intenta las tres desde el día uno se
queda sin caja en la capa B mientras la capa A le exige capex.

---

## 4. El agujero en la propuesta de valor: ¿quién paga el sobrecosto?

`[HUECO — CRÍTICO]`

La deconstrucción selectiva (desarme ordenado, separación en origen, recuperación) es
estructuralmente **más lenta y más intensiva en mano de obra** que la demolición mecánica
(excavadora + martillo hidráulico). En un país con costo laboral alto como Uruguay, ese
diferencial no se compensa solo.

En los mercados donde la deconstrucción funciona económicamente, funciona por **tres
palancas**, ninguna de las cuales está confirmada en Uruguay:

1. **Costo de disposición alto.** Si tirar escombro al vertedero es caro, evitar tirarlo
   vale plata. `[VERIFICAR — dato #2: ¿cuál es la tarifa efectiva de disposición de RCD en
   Maldonado, y existe disposición informal tolerada que la vuelva irrelevante?]`
2. **Incentivo fiscal a la donación de material recuperado.** (Existe en EE.UU. vía
   deducción por donación tasada; **no me consta que exista en Uruguay**.)
   `[VERIFICAR]`
3. **Obligación normativa.** Ordenanzas que exigen deconstrucción o plan de gestión de
   residuos como condición del permiso de demolición. `[VERIFICAR — dato #3]`

**Si ninguna de las tres aplica, el "premium" tiene que pagarlo el cliente por motivos
no económicos** (estética, valores, marca, reporte ESG). Eso es posible — pero restringe
brutalmente el mercado a un segmento específico, y hay que decirlo explícitamente en la
memoria en lugar de asumir que la circularidad se paga sola.

---

## 5. Composición del flujo y dónde está realmente el valor

`[INFERIDO — órdenes de magnitud a verificar con caracterización real de obra local]`

| Fracción | % del peso (aprox.) | Valor de recuperación | Comentario |
|---|---|---|---|
| Hormigón, mampostería, escombro | 60-80% | **Bajo o negativo** | Se puede triturar a árido reciclado, pero compite contra árido virgen de canteras locales — y Maldonado es zona de canteras de granito. Competir contra piedra barata y abundante es mala idea. |
| Metales (acero, hierro de armadura, cobre, aluminio, bronce) | 1-3% | **Alto por kg** | Ya existe mercado de chatarra y actores informales que lo capturan. Margen real pero disputado. |
| Madera estructural y pisos (lapacho, pinotea, eucalipto) | variable | **Alto** | Probablemente la fracción de mayor margen dado el mercado de diseño local. |
| Ladrillo de campo, tejas, piedra | variable | **Alto en nicho** | El estético "rústico chic" de José Ignacio/Garzón le da prima real al material recuperado con pátina. |
| Aberturas, herrajes, sanitarios, artefactos, luminarias | bajo % | **Medio-alto, si hay canal** | Sin canal de reventa establecido, es inventario muerto. |
| Peligrosos: fibrocemento/amianto, pinturas con plomo, tanques de combustible, transformadores | <1% | **Negativo (costo)** | **Pero es el foso competitivo.** Ver §6. |
| Yeso, vidrio, plásticos, aislantes, mixto contaminado | 5-15% | **Negativo** | La fracción que hace imposible el "100%". |

**Ancla de magnitud** `[MEDIA — VERIFICAR]`: una demolición de estructura de
mampostería/hormigón genera del orden de **1 a 1,5 toneladas de residuo por m² construido**.
Una casa de 300 m² ≈ 300-450 t. Una torre de 5.000 m² ≈ 5.000-7.500 t. Sirve para
dimensionar logística y trituración, no para el modelo financiero sin verificar.

---

## 6. Dónde puede estar el foso competitivo real `[INFERIDO]`

No está en "recuperar materiales" — eso lo copia cualquiera con un obrero más y buena
voluntad. Los candidatos a barrera defendible son:

1. **Manejo legal de residuos peligrosos.** El amianto/fibrocemento es el caso testigo:
   requiere habilitación, protocolo, EPP, disposición certificada y seguro. El demoledor
   informal **no puede prestar ese servicio legalmente**. Eso convierte un costo en una
   barrera de entrada y en un argumento de transferencia de riesgo para el cliente.
   `[VERIFICAR: régimen uruguayo de amianto — tengo entendido que su uso fue prohibido a
   comienzos de los 2000, lo que implicaría que prácticamente todo el stock anterior a esa
   fecha es sospechoso. Confirmar norma, año y obligaciones del generador.]`
2. **Trazabilidad documentada y auditable.** Vender el certificado, no el gesto.
3. **Relación con los estudios de arquitectura.** Ver §7.
4. **Licencia social y relación con la Intendencia.** En un mercado chico, ser el operador
   con el que el gobierno departamental quiere trabajar es un activo real.

---

## 7. Canal de venta: no se le vende al propietario `[INFERIDO]`

En el segmento alto de la costa (José Ignacio, La Barra, Manantiales, Garzón), quien
decide no es el dueño: es **el estudio de arquitectura**. Son pocos, están identificados,
y controlan un porcentaje muy alto de la obra de alto standing del corredor.

Implicancia: esto **no es un negocio de marketing, es un negocio de relaciones B2B con un
universo de decisores de dos dígitos**. Eso abarata radicalmente el costo de adquisición
y hace que la estrategia comercial sea: mapear los estudios, elegir 10, y ganarse a 3.

`[HUECO]` ¿El usuario ya tiene esa red? Es determinante para la viabilidad y el timing.

---

## 8. El hallazgo contra-intuitivo: **este negocio es anti-estacional**

`[INFERIDO — el punto más fuerte a favor de la tesis]`

El documento `01-contexto/contexto-estructural.md` identifica la estacionalidad extrema
como el riesgo dominante de cualquier negocio en Punta del Este. **Una demoledora lo
esquiva por construcción:**

- No se demuele en enero al lado de un hotel lleno. La obra en balnearios se concentra
  entre marzo/abril y noviembre/diciembre — **exactamente la contraestación del turismo**.
- Es habitual que los gobiernos departamentales de balnearios **restrinjan obra ruidosa
  durante la temporada alta**. `[VERIFICAR si la Intendencia de Maldonado tiene una
  restricción formal de este tipo, en qué fechas y con qué excepciones — dato #4]`

Esto significa que el proyecto **no compite por mano de obra ni por alojamiento de
personal en el pico de enero**, que es donde se mueren los negocios de servicios locales.

**Pero no lo convierte en un negocio anual:** se invierte la curva, no se aplana. Sigue
habiendo ~2-3 meses muertos, y con activos de capital intensivo parados.
`[HUECO]` ¿Qué hace la maquinaria en enero-febrero? Candidatos a explorar: mantenimiento
programado, trituración de stock acumulado en playa de acopio, obra pública, trabajos en
zonas no turísticas de Maldonado/San Carlos, alquiler de equipos.

---

## 9. El problema del "100%"

`[DICHO]` El usuario propone recuperar **el 100%** de la demolición.

**Objeción directa:** el 100% es técnicamente casi imposible y comercialmente peligroso.

- ¿100% medido en qué? ¿Peso, volumen, número de materiales, valor?
- ¿"Recuperación" incluye el downcycling a relleno? ¿Incluye valorización energética?
  ¿Incluye la fracción contaminada y los peligrosos, que por definición van a disposición
  final controlada y **no se recuperan**?
- Si prometés 100% y entregás 92%, sos un mentiroso ante un cliente sofisticado. Si
  prometés "desvío de vertedero >90% verificado por peso con trazabilidad documentada por
  corriente", sos un profesional.

**Recomendación fuerte:** reemplazar la promesa absoluta por una **métrica auditable,
definida y contractualizable**. El absolutismo publicitario es exactamente lo que erosiona
la credibilidad de las propuestas de circularidad, y en un cliente ESG sofisticado (fondo,
corporativo, family office europeo) te descalifica en la primera pregunta técnica.

---

## 10. Preguntas abiertas acumuladas

### Sobre el negocio
- [ ] ¿Cuál de las tres capas (A/B/C de §3) es el negocio principal?
- [ ] ¿Qué pone el usuario: capital, maquinaria, red de contactos, know-how técnico,
      tiempo full-time? ¿Es fundador operativo o inversor?
- [ ] ¿Tiene socio local? ¿Tiene la red con los estudios de arquitectura?
- [ ] ¿Modelo capital-intensivo (maquinaria propia) o capital-liviano (subcontratación de
      equipos, propiedad solo de la capa de inteligencia y logística)?
- [ ] ¿Horizonte y objetivo: flujo de caja, construir un activo vendible, plataforma
      replicable a Montevideo / Rocha / región?

### Datos duros a conseguir (ordenados por criticidad)
- [ ] **#1** Serie de permisos de demolición de la Intendencia de Maldonado por año, zona y m².
- [ ] **#2** Tarifa efectiva de disposición de RCD en Maldonado + existencia de disposición
      informal tolerada.
- [ ] **#3** Marco normativo de RCD en Uruguay. Punto de partida: **Ley N° 19.829 de Gestión
      Integral de Residuos (2019)** `[MEDIA — verificar número, alcance y reglamentación
      por corriente]` y competencias del **Ministerio de Ambiente** (creado en 2020)
      `[MEDIA]`. Verificar si existe decreto específico de RCD y si la Intendencia exige
      plan de gestión de residuos como condición del permiso de demolición.
- [ ] **#4** Restricciones departamentales de obra en temporada alta.
- [ ] **#5** Régimen de amianto/fibrocemento: prohibición, año, obligaciones del generador,
      operadores habilitados existentes.
- [ ] **#6** Mapa de competidores: demoledoras formales operando en Maldonado y Montevideo,
      empresas de volquetas (incumbente clave del flujo logístico), chatarreros.
- [ ] **#7** Precio de árido virgen de cantera en Maldonado (define el techo del árido reciclado).
- [ ] **#8** Elegibilidad COMAP: el indicador de *producción más limpia* + *descentralización*
      + *empleo* hace a este proyecto un candidato fuerte al crédito fiscal contra IRAE.

