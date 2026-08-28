# Tema 4 · `#¡VALOR!`: las cuentas no cuadran

!!! info "CAOS, S.L."
    Contabilidad tiene fórmulas que cambian al copiarse, números almacenados como texto y resultados imposibles.

## 🚨 1. Incidencia inicial

**Objetivo:** construir cálculos fiables, comprensibles y auditables.

## 🎯 2. Qué aprenderás

- distinguir tipos de datos;
- crear fórmulas;
- usar referencias relativas, absolutas y mixtas;
- emplear funciones básicas;
- trabajar con texto, lógica y fechas;
- aplicar formato condicional;
- interpretar errores;
- diseñar hojas que puedan revisarse.

## 🛠️ 3. Rescate guiado · Ventas de septiembre

Partimos de una tabla como esta:

| Producto | Cantidad | Precio | %Desc. | Subtotal | Descuento | Base | %IVA | IVA | Total |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Monitor | 2 | 129,90 | 0,10 |  |  |  | 0,21 |  |  |

### Paso 1. Subtotal

En `E2`:

```text
=B2*C2
```

### Paso 2. Descuento

En `F2`:

```text
=E2*D2
```

### Paso 3. Base imponible

En `G2`:

```text
=E2-F2
```

### Paso 4. IVA

Si cada fila contiene su porcentaje de IVA:

```text
=G2*H2
```

Si el IVA general está almacenado en una celda común, por ejemplo `H1`, se usaría una referencia absoluta:

```text
=G2*$H$1
```

### Paso 5. Total

```text
=G2+I2
```

### Paso 6. Referencias mixtas

Ejemplos:

```text
$A2
B$1
```

Se usan cuando queremos fijar solo columna o fila.

### Paso 7. Funciones básicas

```text
=SUMA(J2:J20)
=PROMEDIO(J2:J20)
=MIN(J2:J20)
=MAX(J2:J20)
=CONTAR(J2:J20)
```

### Paso 8. Funciones lógicas

```text
=SI(J2>=1000;"Objetivo";"Pendiente")
```

Con varias condiciones:

```text
=SI(Y(J2>=1000;K2="Valencia");"Bonus";"Sin bonus")
```

### Paso 9. Fecha y hora

Trabajaremos con:

- fecha actual;
- diferencias;
- vencimientos;
- año, mes y día.

### Paso 10. Formato condicional

Ejemplos:

- importes negativos;
- objetivos alcanzados;
- vencimientos;
- duplicados.

## 📚 4. Lo que necesitas saber

### 4.1 Fórmula, función y operador

Una **fórmula** es una expresión de cálculo, por ejemplo:

```text
=B2*C2
```

Una **función** es una operación predefinida, por ejemplo:

```text
=SUMA(B2:B20)
```

Los operadores indican la operación:

- `+`, `-`, `*`, `/`, `^`;
- `=`, `>`, `<`, `>=`, `<=`, `<>`.

### 4.2 Referencias

- relativa: `A1`;
- absoluta: `$A$1`;
- mixta: `$A1` o `A$1`.

La diferencia se aprecia al copiar una fórmula.

### 4.3 Números como texto

Un valor puede parecer un número y estar almacenado como texto.

Esto puede provocar:

- sumas incorrectas;
- ordenaciones extrañas;
- funciones que ignoran valores.

### 4.4 Funciones de texto

Se usan para limpiar y transformar información.

Ejemplos habituales:

- unir;
- extraer izquierda/derecha;
- calcular longitud;
- convertir mayúsculas/minúsculas.

### 4.5 Funciones lógicas

Una función condicional devuelve un resultado u otro según se cumpla una condición.

```text
SI(condición; valor_si_verdadero; valor_si_falso)
```

Las funciones equivalentes a `Y` y `O` permiten combinar criterios.

### 4.6 Fechas

Las fechas se almacenan internamente como valores y pueden usarse en operaciones.

Por ejemplo, si `B2` contiene una fecha de vencimiento:

```text
=B2-HOY()
```

puede indicar cuántos días quedan.

### 4.7 Errores

No memorices solo el nombre del error. Investiga:

- referencia;
- tipo de dato;
- operador;
- función;
- rango.

### 4.8 Buen diseño

Una hoja profesional:

- coloca parámetros en celdas;
- usa encabezados claros;
- mantiene fórmulas coherentes;
- evita mezclar unidades;
- evita números «mágicos» dentro de fórmulas;
- permite seguir de dónde sale cada resultado.

## 🏋️ 5. Practica

### Ejercicio 1 · IVA

Calcula:

- subtotal;
- descuento;
- base;
- IVA;
- total.

### Ejercicio 2 · Comisión

Reglas:

- ventas < 500 € → 0 %;
- 500–999,99 € → 3 %;
- 1000 € o más → 6 %.

### Ejercicio 3 · Texto

A partir de nombre y apellidos, genera un identificador.

### Ejercicio 4 · Fechas

Calcula días hasta vencimiento.

## 🔥 6. Nueva incidencia

Recibes una hoja con cinco resultados imposibles. Debes localizar las fórmulas incorrectas y explicar la causa.

## 🔒 7. Ticket cerrado · Evaluable

Datos distintos por alumno.

Se evalúan:

- fórmulas;
- referencias;
- funciones;
- lógica;
- formato condicional;
- interpretación.

## ✅ 8. Comprueba que sabes...

- [ ] Distingo fórmula y función.
- [ ] Uso referencias relativas, absolutas y mixtas.
- [ ] Sé detectar números almacenados como texto.
- [ ] Sé utilizar funciones básicas y lógicas.
- [ ] Sé trabajar con fechas.
- [ ] Sé aplicar formato condicional.
- [ ] Sé investigar la causa de un error.
- [ ] Sé diseñar una hoja verificable.
