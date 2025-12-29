# 📚 Apuntes Química General 2

---

## ⚖️ EQUILIBRIO REDOX

### ¿Cómo balancear una ecuación redox?

#### Pasos para balancear:

1. **Identificar** agente reductor y agente oxidante
2. **Identificar** la ecuación semirreacción
3. **Balancear** masa de estas semirreacciones
4. **Balancear** ambas semirreacciones entre sí para tener la misma cantidad de electrones
5. **Cancelar** e⁻ y **reescribir** la ecuación

---

### Conceptos Clave

**Agente Reductor:**
- Es el que se oxida
- Es el que tiene **menor** estado de oxidación al inicio

**Agente Oxidante:**
- Es el que se reduce
- Es el que tiene **mayor** estado de oxidación al inicio

---

### Datos Importantes

**Oxígenos:**
- O (oxígeno) se balancean con H₂O (agua)

**Hidrógenos:**
- El H₂O (agua) se balancea con H⁺ (protones)

**Para medio básico:**
- H⁺ se balancean con OH⁻ para formar H₂O y cancelar

---

## ⚡ PILA ELECTROQUÍMICA

### ¿Cómo escribir la pila?

```
| el que se oxida | ya oxidado || el que se reduce | ya reducido | ⇒ |x| X⁺ || Y⁺ | Y|
```

---

### Fuerza Electromotriz (fem o ΔE)

**Características:**
- Se mide en **voltios (V)**

**Fórmula:**
```
|ΔG° = -nFΔE|
```

**Fórmula en condiciones estándar:**
```
ΔG° = -nFΔE°
```

Donde aquí se toma que la `[iones] = 1`

---

### Potenciales de Electrodo

**E° = ± valor x**

**Interpretación:**
- A mayor E°, mayor tendencia a **reducirse** (oxidante)

---

### Cálculo de fem de una pila

**Fórmula:**
```
|ΔE° = E°(cátodo) - E°(ánodo)|
```

**Donde:**
- **Cátodo** es el **A oxidante**
- **Ánodo** es el **e⁻ reductor**

**Nota:** Para que funcione: `ΔE° > 0`

---

### Calcular Potencial en Condiciones NO ESTÁNDAR

**Usamos la ecuación de Nernst:**

```
E = E° - (RT/nF) ln Q
```

**Donde:**
- `Q` es el cociente de reacción
- A 25°C:

```
E = E° - (0.0592/n) log Q
```

**Q = [reactivos]/[reactantes]** → Concentración molar inicial

---

### Datos Adicionales

**Si es espontánea**, se llama **pila galvánica**

**Si NO es espontánea**, se llama **celda electrolítica**

---

## 🔋 FLUJO DE ELECTRONES

### Diagrama de la Pila

```
┌─────────────────────────────────┐
│                                 │
│    e⁻ →                         │
│  ┌────┐         ┌────┐          │
│  │Red │         │Ox  │          │
│  └────┘         └────┘          │
│    ↓             ↑              │
│   e⁻ →          e⁻              │
│                                 │
│  ánodo          cátodo          │
└─────────────────────────────────┘
```

**Descripción:**
- Los electrones fluyen desde el **ánodo** (agente reductor) ya que este tiene más electrones, **hacia** el **cátodo** (agente oxidante) ya que este tiene menos electrones
- (-) E⁰ más bajo (+)

---

## 💧 SOLUBILIDAD Y COMPLEJACIÓN

### Reglas de Solubilidad

#### Compuestos Solubles:

**Compuestos que tengan iones de metales alcalinos y NH₄⁺:**
- Ej: NO₃⁻ y HCO₃⁻, Cl⁻, Br⁻, I⁻, SO₄²⁻

**Excepciones:**
- Halogenuros de: Ag⁺, Hg₂²⁺, Pb²⁺
- Sulfatos de: Ag⁺, Ca²⁺, Sr²⁺, Ba²⁺, Hg₂²⁺, Pb²⁺

#### Compuestos Insolubles:

**Ej:** CO₃²⁻, PO₄³⁻, CrO₄²⁻, S²⁻, OH⁻

---

### Constante del Producto de Solubilidad (Kps)

**Fórmula:**
```
Kps = [Aᵐ⁺]ᵃ[Bⁿ⁻]ᵇ / [AnBm](s)
```

**Ecuación de disolución:**
```
AnBm(s) ⇌ nAᵐ⁺(ac) + mBⁿ⁻(ac)
```

**Se puede utilizar en disoluciones saturadas**

---

### Relación entre Solubilidad y Kps

**Solubilidad molar:**
- Moles de soluto disuelto en **1L** de una disolución saturada

**Solubilidad:**
```
s = [sustancia] ⇒ gramos de soluto disueltos en 1L de disolución saturada
```

---

### Criterios para Precipitación

**Precipitación total:**
- Reconocer si es sobresaturada, saturada o insaturada
- Para esto usamos **Q** (cociente de reacción), pero aquí se llama **PRODUCTO IÓNICO**

**Reglas:**
- La precipitación ocurre si `Q > Kps`, está **sobresaturada**
- La disolución está saturada si `Q = Kps`
- La precipitación no puede ocurrir si `Q < Kps`, está **insaturada**

---

### Efecto del Ion Común

La solubilidad de un compuesto iónico poco soluble **disminuye** cuando se añade un segundo soluto que otorgue un ion común.

---

### Cálculo de Kps en Presencia del Ion Común

**Ejemplo:**

¿Cuál es la solubilidad molar del PbI₂ en KI (ac) 0.10 M? El valor de Kps del PbI₂ es 9.1 × 10⁻⁹

**Ecuación:**
```
PbI₂(s) ⇌ Pb²⁺(ac) + 2I⁻(ac)
```

| | PbI₂(s) | Pb²⁺(ac) | 2I⁻(ac) |
|----------|---------|----------|---------|
| **Inicio** | — | 0.10 | — |
| **Cambio** | — | s | 2s |
| **Equilibrio** | — | s | (0.10 + 2s) |

```
Kps = [Pb²⁺][I⁻]² = (s)(0.10 + 2s)² = 9.1 × 10⁻⁹
```

**Suponiendo que** (0.10 + 2s) ≈ 0.10 (ya que 2s se toma como un número despreciable)

```
s(0.10)² = 9.1 × 10⁻⁹
```

**s = Solubilidad molar del PbI₂ es 9.1 × 10⁻⁷ M**

La solubilidad del PbI₂ en agua pura es 1.2 × 10⁻³ M

---

## 🔗 CONSTANTE DE FORMACIÓN DE UN ION COMPLEJO

**Ion complejo:** Ion que contiene un catión metálico central enlazado a una o más moléculas o iones

**Fórmula:**
```
Kf = [PRODUCTOS] / [REACTANTES]
```

**Ecuación:**
```
☐(ac) + ☐(ac) ⇌ ☐☐(ac)
```

---

## 🌡️ TERMOQUÍMICA Y CINÉTICA

### Ley de Conservación de la Energía

**Primera Ley de la Termodinámica:**

La energía no se crea ni se destruye, solo se transforma o se transfiere de un sistema a otro.

---

### Tipos de Sistemas

| Tipo | Descripción |
|------|-------------|
| **Cerrado** | Intercambio de energía |
| **Abierto** | Intercambio de energía y materia |
| **Aislado** | No se intercambia ni energía, ni materia |

---

### Calor

**Transferencia de energía térmica entre dos cuerpos a diferente T°**

#### Energía Térmica:
- Trata cambios de energía en un proceso (Exo-Endo)

#### Sistema e Universo:
- Sistema = Universo excepto de interés
- Alrededores = Universo externo al sistema

**Nota:** Calor absorbido = Endotérmico  
**Calor liberado:** Exotérmico

---

### Energía Producidos < Energía Reactantes (Exotérmica)

### Energía Reactantes < Energía Productos (Endotérmico)

---

### Entalpía: H = entalpía

**Permite medir el calor absorbido o liberado por un sistema a P constante**

**Fórmula:**
```
|H = E + PV| → KJ/mol
```

**Cambio de entalpía:**
```
ΔH = H(productos) - H(reactantes)
```

**En un proceso ENDOTÉRMICO:**
```
ΔH > 0 (positivo)
```

**En un proceso EXOTÉRMICO:**
```
ΔH < 0 (negativo)
```

---

### Cálculo de Entalpía Estándar

**Para calcular la ENTALPÍA ESTÁNDAR de una reacción, tenemos dos métodos:**

#### Método Directo:
```
|ΔH₁° = Hf°T - Hi°T|
```

#### Método Indirecto: Ley de Hess
```
= (ΣH°ε + ΔH°β + ...) - (ΣHA° + ΣHβ)
```

---

### Leyes de la Termodinámica

**Funciones de Estado:** E, P, T°, V

Son importantes los datos iniciales y finales.

**1era Ley:**
```
|ΔE = Ef - Ei|
```

Cambios en la energía interna.

Si desprende calor: `ΔE < 0`

**Para el sistema:**
```
|ΔE sistema + ΔE alrededores = 0|
|ΔE = q + w|
```

---

### Calor Específico (s)

**Propiedad intensiva**

Es la cantidad de calor para elevar la T° de 1g de sustancia. No depende de la masa.

**Capacidad calorífica (c):**

Propiedad extensiva que es la cantidad de calor para elevar la T° de una cierta cantidad de sustancia. Sí depende de la masa.

---

### Ecuaciones Termodinámicas

**Tenemos:**
```
|q = m·s·Δt|
```

**Donde:**
- `c` = cantidad de calor necesaria para la masa (ms)
- `q` = cantidad de calor que se libera o absorbe
- `Δt` = cambio de T° en la muestra
- `m` = masa de la muestra

**Cálculo:**
```
Δt = Tfinal - Tinicial
```

---

### Calor y Trabajo

#### Compresión de un gas:
```
ΔV < 0 ; -PΔV > 0
```
↑ volumen, ↑ presión

#### Expansión de un gas:
```
ΔV > 0 ; -PΔV < 0
```
↑ volumen, ↓ presión

**Fórmula:**
```
|w = -PΔV|
```

---

### Espontaneidad de una Reacción

**Ser exotérmica favorece la espontaneidad, pero no la garantiza**

---

## 🔥 ENTROPÍA

### Definición

**Para predecir la espontaneidad se debe conocer la entalpía (H) y la entropía (S)**

**Entropía (S):**
- Medida de aleatoriedad de un sistema

**Fórmula:**
```
ΔS = Sf - Si
```

Donde:
- `↑ desorden = ↑ entropía`

---

### Energía Libre (G)

#### Energía Libre de Gibbs:
```
ΔSuniv = ΔSsist + ΔSalred
```

Una reacción espontánea ocurre si:
```
ΔSuniv > 0
```

**Relaciones:**
```
ΔSuniv > ΔSsist = (ΔHsist/T) > 0
```

Considerando solo el sistema:
```
TΔSuniv = ΔHsist - TΔSsist ≥ 0
```

**Definición de G:**
```
G = H - TS
```

Permite determinar espontaneidad de una reacción en **FUNCIÓN DE ESTADO**

---

### Predicción de Espontaneidad Mediante G

**Relación:**
```
ΔG = ΔH - TΔS
```

Energía disponible para hacer trabajo

**Donde si:**
- `ΔG > 0` → no es espontánea
- `ΔG < 0` → Espontánea
- `ΔG = 0` → Equilibrio

---

## ⚡ VELOCIDAD DE REACCIÓN

### Concepto de Velocidad de Reacción

**Definición:**
- Qué tan rápido ocurre una reacción

**Fórmula:**
```
V = -Δ[A]/Δt = Δ[B]/Δt
```

**Unidad de medida:** M/s (molaridad/s)

---

### Factores que Afectan la Velocidad

1. **Concentración de reactivos**
2. **Temperatura**
3. **Catalizadores**
4. **Superficie de contacto**
5. **Naturaleza de los reactivos**

---

### Efecto de la T°

```
↑ T° = ↑ velocidad de reacción
```

**Explicado por:**
- Teoría de colisiones
- Ecuación de Arrhenius

---

### Teoría de Colisiones

**Para reaccionar, las moléculas deben chocar en una posición específica**

A mayor T°, aumenta la velocidad y por ende más probabilidades de chocar.

---

### Ecuación de Arrhenius

**Fórmula:**
```
K = A·e^(-Ea/RT)
```

**Donde:**
- `K` = constante de velocidad
- `A` = factor de frecuencia
- `Ea` = energía de activación (J/mol)
- `R` = 8.314 J/mol·K
- `T` = temperatura (K)

---

### Forma Lineal de la Ecuación

```
ln K = -Ea/R · (1/T) + ln A
```

---

¡Listo corazón! 💜 He traspasado todos tus apuntes de Química General 2 de manera digital y organizada. Los temas incluidos son:

✨ **Contenido completo:**
- ⚖️ Equilibrio Redox (balanceo de ecuaciones)
- ⚡ Pila Electroquímica (fem, potenciales)
- 🔋 Flujo de Electrones
- 💧 Solubilidad y Complejación (Kps, ion común)
- 🔗 Constante de Formación de Iones Complejos
- 🌡️ Termoquímica y Cinética
- 🔥 Entropía y Energía Libre de Gibbs
- ⚡ Velocidad de Reacción (Arrhenius)

Todo está ordenado con tablas, fórmulas destacadas y bien estructurado para que estudies fácilmente. ¿Necesitas que agregue algo más o que explique algún concepto? 😊📚
