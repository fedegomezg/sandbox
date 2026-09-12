# Test de plausibilidad #1 — ¿Pueden las aberturas y materiales sostener 10 personas todo el año?

**Afirmación a testear** `[DICHO por el usuario, fragmento 2]`:
> "Si logramos mantener una cuadrilla de 10 personas todo el año, solo con los ingresos de
> las aberturas y materiales, debería de tener una linda fuente de ingresos."

**Veredicto anticipado: la afirmación es casi con certeza falsa, y falsa por un orden de
magnitud.** El desarrollo sigue.

> ⚠️ Todos los inputs de abajo son **estimaciones no verificadas** que deben reemplazarse
> por datos reales. Están marcados `[E]`. Lo que **sí** es robusto es la conclusión: se
> sostiene en todo el rango razonable de cada input, y eso se demuestra en §4.

---

## 1. Lado del costo — ¿cuánto cuesta realmente la cuadrilla?

### 1.1 Costo del peón, todo incluido

| Concepto | Valor | Nota |
|---|---|---|
| Salario nominal mensual, peón de construcción | `[E]` USD 875 – 1.250 | **VERIFICAR contra laudo del Consejo de Salarios del grupo de construcción vigente.** No es negociable a la baja: es laudo de rama. |
| Factor de carga empresa | `[E]` ×1,55 – 1,70 | Aportes patronales, FONASA, FRL, aguinaldo, licencia + salario vacacional, previsión de despido |
| **Costo empresa mensual por peón** | **`[E]` USD 1.350 – 2.100** | |
| **Costo anual por peón** | **`[E]` USD 16.200 – 25.200** | |

### 1.2 Estructura completa mínima

Una cuadrilla de 10 no opera sola. Lo mínimo viable:

| Ítem | Costo anual estimado | Por qué es obligatorio |
|---|---|---|
| 10 peones | `[E]` USD 162.000 – 252.000 | La cuadrilla |
| 1 capataz / jefe de obra | `[E]` USD 30.000 – 45.000 | Nadie deja una demolición sin conducción técnica |
| 1 responsable técnico (seguridad + residuos) | `[E]` USD 30.000 – 50.000 | Habilitaciones, plan de residuos, seguridad. En demolición no es opcional. |
| **1 coordinador socio-laboral** | `[E]` USD 25.000 – 40.000 | **No es un lujo ni marketing.** Un programa de reinserción sin acompañamiento no es un programa, es contratación de riesgo. Ver §5. |
| Administración / contabilidad / nómina | `[E]` USD 15.000 – 30.000 | |
| EPP, uniformes, herramienta de mano | `[E]` USD 10.000 – 20.000 | Demolición = alto desgaste |
| Seguro de accidentes de trabajo (BSE) | `[E]` USD 15.000 – 35.000 | **Demolición es rama de alto riesgo: prima alta.** VERIFICAR tarifa BSE para la actividad. |
| Transporte diario de cuadrilla a obra | `[E]` USD 12.000 – 25.000 | Las obras están dispersas en el corredor |
| Galpón / playa de acopio (banco de materiales) | `[E]` USD 18.000 – 40.000 | Sin galpón no hay banco de materiales |
| **TOTAL ESTRUCTURA ANUAL** | **`[E]` USD 317.000 – 537.000** | **Antes de maquinaria, antes de comprar nada, antes de comercial** |

**Piso defensivo:** aun tomando el extremo inferior de *cada* variable simultáneamente
(escenario optimista poco realista), el costo anual difícilmente baje de
**~USD 250.000 – 300.000**.

---

## 2. Lado del ingreso — ¿cuánto puede facturar el salvamento?

### 2.1 Precio por pieza recuperada

| Ítem | Precio de venta estimado | Nota |
|---|---|---|
| Puerta de madera maciza restaurada | `[E]` USD 150 – 400 | VERIFICAR contra mercado local de antigüedades / demolición |
| Ventana con marco, restaurada | `[E]` USD 120 – 350 | |
| Herrajes, grifería, luminarias (por lote) | `[E]` bajo | Volumen bajo, precio bajo |
| Piso de madera (m²) | `[E]` USD 20 – 60/m² | Puede ser la fracción más valiosa si hay pinotea/lapacho |
| Ladrillo de campo recuperado (unidad) | `[E]` USD 0,30 – 1,00 | **Requiere descascarado manual — ver §5** |
| Teja recuperada (unidad) | `[E]` USD 0,50 – 2,00 | |
| Chatarra ferrosa (tonelada) | `[E]` bajo | Mercado líquido pero commodity, margen fino |

**Precio promedio ponderado por "pieza equivalente" recuperada:** asumamos generosamente
`[E]` **USD 200 netos de insumos de restauración** (no de mano de obra — la mano de obra es
el costo que estamos tratando de cubrir).

### 2.2 Rendimiento por obra

Una vivienda unifamiliar de demolición completa rinde, estimativamente,
`[E]` **15 – 40 piezas** significativas (aberturas + artefactos + lotes de herrajes).

---

## 3. El cruce: cuántas demoliciones hacen falta

Para cubrir una estructura de **USD 350.000/año** con margen bruto de salvamento del
**50%** (después de restauración, almacenamiento, flete y comisión de venta):

```
Ingreso bruto de salvamento necesario  = 350.000 / 0,50  = USD 700.000/año
Piezas necesarias a USD 200/pieza      = 700.000 / 200   = 3.500 piezas/año
Obras necesarias a 25 piezas/obra      = 3.500 / 25      = 140 demoliciones/año
```

**140 demoliciones de vivienda por año.** Eso es más de **una demolición completa cada dos
días hábiles**, todo el año, por una sola empresa.

`[INFERIDO — con alta convicción]` Eso excede con holgura el mercado total de demoliciones
del corredor Punta del Este – La Barra – José Ignacio. Y aunque existiera, una cuadrilla de
10 personas es físicamente incapaz de ejecutarlo: una demolición selectiva de vivienda
lleva semanas, no dos días.

---

## 4. ¿La conclusión aguanta si me equivoqué en los números?

Test de robustez con el escenario **más favorable posible** en todas las variables
simultáneamente:

```
Estructura anual (piso absoluto)       = USD 250.000
Margen de salvamento (optimista)       = 60%
Ingreso de salvamento necesario        = 250.000 / 0,60 = USD 417.000
Precio por pieza (optimista)           = USD 300
Piezas necesarias                      = 417.000 / 300  = 1.390 piezas/año
Rendimiento por obra (optimista)       = 40 piezas
Obras necesarias                       = 1.390 / 40     = 35 demoliciones/año
```

**Incluso apilando todos los supuestos a favor, hacen falta ~35 demoliciones completas al
año, y el salvamento no deja *ninguna* utilidad — apenas paga la nómina.** Y ese escenario
requiere precios de venta de anticuario sobre *todo* el inventario, rotación completa sin
stock muerto, y cero costo de capital sobre inventario que rota en meses o años.

En el escenario central, la afirmación falla por **4 a 5 veces**.

---

## 5. La inversión de la conclusión: qué significa esto para el modelo

**El salvamento no es el motor de ingresos. Es el condimento del margen y el activo de
marketing.**

La reestructuración correcta:

| Fuente | Rol | % estimado del ingreso |
|---|---|---|
| **Honorario de demolición** (contrato con desarrollador/propietario) | **Motor** — paga la nómina y la maquinaria | `[E]` 65 – 80% |
| **Servicio de retiro de peligrosos** (fibrocemento/amianto) | Alto margen, foso competitivo | `[E]` 5 – 15% |
| **Venta de material recuperado** | Kicker de margen + activo narrativo | `[E]` 10 – 25% |
| **Ahorro capturado in situ** (trituración para relleno propio de obra) | Reduce costo, se factura como servicio | variable |
| **Chatarra** | Commodity, cobertura de costo variable | `[E]` bajo |

**Y esto reordena la pregunta central:** no es "¿cuánto material puedo recuperar?", es
**"¿cuánto me paga un cliente por demoler, y por qué me pagaría más a mí que al de al
lado?"**. La respuesta a esa segunda pregunta está en el componente social + trazabilidad,
no en el volumen de puertas.

---

## 6. El hallazgo operativo que sí cierra: el taller como amortiguador

El descascarado de ladrillo, el desclavado de madera, el lijado y restauración de aberturas
es trabajo **intensivo en mano de obra, de baja barrera de entrada, sin urgencia temporal y
deslocalizable**. Con mano de obra de mercado a costo uruguayo, esa actividad **destruye
valor**: el tiempo-hombre cuesta más que el ladrillo limpio.

Pero ese perfil de tarea es exactamente el que encaja en un **taller de oficios dentro de
unidad penitenciaria** (formación, ocupación, redención de pena por trabajo) o en un
esquema de formación pre-egreso.

**Consecuencia estructural doble:**

1. El componente social **vuelve viable el banco de materiales**, que con costo laboral de
   mercado no cierra.
2. El banco de materiales **vuelve operativamente viable el componente social todo el año**:
   la obra de campo se detiene en enero-febrero (contraestación turística), pero el taller
   sigue procesando el stock acumulado. **Ahí está la respuesta a "qué hace la cuadrilla en
   enero".**

Esto no es un adorno del modelo. Es probablemente **el encastre que hace que el proyecto
exista**.

---

## 7. Datos que hay que conseguir para reemplazar los `[E]`

- [ ] Laudo vigente del Consejo de Salarios del grupo de construcción — categoría peón y capataz
- [ ] Factor de carga empresa real, calculado por contador uruguayo para esta actividad
- [ ] Tarifa BSE de seguro de accidentes para demolición `[probablemente el costo más subestimado]`
- [ ] Precios reales de reventa de material de demolición en Uruguay (relevar corralones,
      anticuarios, mercados de usados, estudios de arquitectura que ya compran reciclado)
- [ ] Rendimiento real de piezas por obra — relevar 3-5 demoliciones reales
- [ ] Honorario de mercado de una demolición convencional en Maldonado (USD/m² demolido)
      ← **este es el dato que define todo el modelo y todavía no lo tenemos**
- [ ] Tiempo real de ejecución de demolición selectiva vs. mecánica, en jornadas-hombre/m²
