# Tema 4 · `#¡VALOR!`: las cuentas no cuadran

!!! info "CAOS, S.L." 
    Formas parte del equipo de rescate digital de una empresa cuya gestión ofimática es un desastre.  
    Todo lo que arregles en este tema quedará incorporado a la empresa y podrá volver a utilizarse en temas posteriores.

## Estructura del tema

1. 🚨 **Incidencia inicial** — qué problema tiene hoy CAOS, S.L.
2. 🛠️ **Rescate guiado** — resolvemos un caso completo mientras aprendemos.
3. 📚 **Lo que necesitas saber** — teoría y procedimientos de consulta.
4. 🏋️ **Ahora tú** — ejercicio individual de consolidación.
5. 🔥 **Nueva incidencia** — reto menos guiado.
6. 🔒 **Ticket cerrado** — caso evaluable individual.

!!! warning "Importante" 
    En los casos evaluables los datos, archivos o condiciones pueden cambiar entre alumnos. No se evalúa reproducir unos pasos de memoria, sino resolver correctamente la incidencia y poder explicar las decisiones tomadas.
    
## Objetivos del rescate

Construir hojas de cálculo fiables utilizando tipos de datos, fórmulas, referencias y funciones básicas, de texto, lógicas, estadísticas y de fecha/hora.

## 🚨 Incidencia inicial · «El beneficio cambia cada vez que alguien copia una fórmula»

Contabilidad dispone de un libro con ventas, descuentos e IVA.

Problemas detectados:

- algunos números están guardados como texto;
- varias fórmulas se han sobrescrito;
- el porcentaje de IVA cambia al copiar;
- aparecen errores;
- nadie sabe de dónde salen los totales.

**Misión:** reconstruir el cálculo y hacerlo verificable.

## 🛠️ Rescate guiado · Rehacemos la hoja de ventas

### 1. Elementos de una hoja de cálculo

- libro;
- hoja;
- fila;
- columna;
- celda;
- rango.

### 2. Tipos de datos

- texto;
- número;
- fecha/hora;
- porcentaje;
- moneda;
- valores lógicos.

### 3. Fórmulas

Una fórmula comienza normalmente por `=`.

Ejemplo:

```text
=B2*C2
```

### 4. Operadores

- aritméticos: `+ - * / ^`;
- comparación: `= > < >= <= <>`;
- concatenación, según la aplicación.

### 5. Referencias relativas

```text
=B2*C2
```

Al copiar la fórmula, las referencias cambian de forma relativa.

### 6. Referencias absolutas

```text
=B2*$H$1
```

`$H$1` permanece fija al copiar.

### 7. Referencias mixtas

Ejemplos:

```text
$A2
B$1
```

Permiten fijar solo fila o columna.

### 8. Formato condicional

Permite destacar celdas según reglas:

- ventas bajas;
- importes negativos;
- fechas vencidas;
- valores duplicados.

### 9. Funciones básicas

Ejemplos conceptuales:

```text
SUMA
PROMEDIO
MIN
MAX
CONTAR
```

### 10. Funciones estadísticas

Usaremos funciones adecuadas para:

- contar;
- obtener medias;
- identificar extremos;
- resumir información.

### 11. Funciones de texto

Utilidades:

- unir;
- extraer;
- cambiar mayúsculas/minúsculas;
- calcular longitud;
- limpiar datos.

### 12. Funciones lógicas

La función condicional permite obtener un resultado u otro según una condición.

Ejemplo conceptual:

```text
SI(condición; valor_si_verdadero; valor_si_falso)
```

También combinaremos condiciones con funciones equivalentes a Y/O.

### 13. Fecha y hora

Las fechas son valores que pueden utilizarse en operaciones.

Practicaremos:

- fecha actual;
- diferencia entre fechas;
- extracción de partes;
- vencimientos.

### 14. Errores

Aprenderemos a interpretar errores frecuentes y, sobre todo, a localizar su causa.

## 📚 Lo que necesitas saber

### Una hoja debe poder auditarse

Evita:

- números escritos directamente dentro de fórmulas cuando deberían estar en celdas;
- fórmulas diferentes sin motivo dentro de la misma columna;
- celdas mezclando texto y números;
- colores usados como único significado.

### Copiar no es entender

Antes de arrastrar una fórmula debes saber qué referencias deben cambiar y cuáles deben mantenerse.

## 🏋️ Ahora tú · «Comisiones comerciales»

Construye una hoja que calcule importes, descuentos, impuestos y comisiones a partir de un conjunto de ventas.

## 🔥 Nueva incidencia · «Hay resultados imposibles»

Recibirás una hoja ya calculada con varios resultados incorrectos.  
Debes localizar los errores sin rehacer todo desde cero.

## 🔒 Ticket cerrado · Evaluable

Cada alumno recibirá un conjunto diferente de ventas, porcentajes y reglas.

Se evaluará:

- estructura;
- fórmulas;
- referencias;
- funciones;
- formato;
- detección de errores;
- capacidad para explicar una fórmula seleccionada.

## ✅ Checklist

- [ ] Distingo tipos de datos.
- [ ] Sé escribir fórmulas.
- [ ] Domino referencias relativas, absolutas y mixtas.
- [ ] Sé usar funciones básicas y estadísticas.
- [ ] Sé utilizar funciones de texto.
- [ ] Sé construir condiciones lógicas.
- [ ] Sé trabajar con fechas.
- [ ] Sé investigar un error de cálculo.
