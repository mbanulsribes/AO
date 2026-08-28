# Tema 5 · Tenemos datos, pero nadie sabe qué significan

!!! info "CAOS, S.L."
    Dirección tiene miles de filas, pero no consigue respuestas útiles.

## 🚨 1. Incidencia inicial

Dirección quiere saber:

- qué producto vende más;
- qué comercial funciona mejor;
- qué clientes han dejado de comprar;
- qué meses son peores.

**Objetivo:** pasar de datos a información.

## 🎯 2. Qué aprenderás

- limpiar datos;
- ordenar y filtrar;
- validar entradas;
- realizar búsquedas;
- elegir gráficos;
- importar CSV;
- crear tablas dinámicas;
- responder preguntas a partir de un conjunto de datos.

## 🛠️ 3. Rescate guiado · Análisis comercial

### Paso 1. Limpieza

Comprueba:

- encabezados;
- filas vacías;
- tipos;
- duplicados;
- valores incoherentes.

### Paso 2. Ordenación

Ordenamos por:

- importe;
- fecha;
- comercial;
- varios criterios.

### Paso 3. Filtros

Ejemplos:

- ventas > 1000;
- ciudad = Valencia;
- fecha en trimestre 2.

### Paso 4. Validación

Creamos listas para:

- provincia;
- categoría;
- estado.

### Paso 5. Búsquedas

A partir del código de producto recuperamos su nombre o precio.

Según la aplicación se utilizará `BUSCARV`, `BUSCARX/XLOOKUP` o funciones equivalentes.

### Paso 6. Gráficos

Regla:

> primero formula la pregunta; después elige el gráfico.

- barras/columnas: comparar;
- líneas: evolución;
- sectores: proporciones simples y pocas categorías.

### Paso 7. Importación CSV

Hay que revisar:

- delimitador;
- codificación;
- encabezados;
- tipos.

### Paso 8. Tabla dinámica

Podemos resumir:

- ventas por comercial;
- ventas por mes;
- ventas por categoría.

## 📚 4. Lo que necesitas saber

### 4.1 Tabla de datos limpia

Una tabla fuente debería cumplir:

- una fila = un registro;
- una columna = una variable;
- encabezados únicos;
- sin filas vacías internas;
- sin subtotales incrustados en el listado.

### 4.2 Ordenar no es filtrar

**Ordenar** cambia el orden de los registros.

**Filtrar** oculta temporalmente los que no cumplen una condición.

### 4.3 Validación

La validación evita errores antes de que se produzcan.

Ejemplos:

- lista cerrada de provincias;
- límite de valores;
- fechas dentro de un intervalo;
- mensajes de entrada.

### 4.4 Búsquedas

Una búsqueda recupera información asociada a una clave.

Ejemplo:

```text
codigo_producto -> nombre_producto
```

Es importante que la clave sea coherente y que el rango de búsqueda esté bien definido.

### 4.5 Gestión de errores

Una hoja profesional debe distinguir:

- dato inexistente;
- error de fórmula;
- entrada no válida.

Ocultar todos los errores sin analizarlos puede ocultar problemas reales.

### 4.6 Gráficos

Un gráfico debe responder una pregunta.

Evita:

- 3D innecesario;
- leyendas redundantes;
- colores sin significado;
- exceso de categorías;
- ejes engañosos.

### 4.7 CSV

CSV es un formato de texto para datos tabulares.

Puede variar en:

- separador;
- codificación;
- representación decimal;
- formato de fecha.

Por eso hay que revisar la importación.

### 4.8 Tablas dinámicas

Una tabla dinámica resume grandes conjuntos de datos sin escribir una fórmula para cada resultado.

Conceptos:

- filas;
- columnas;
- valores;
- filtros.

## 🏋️ 5. Practica

1. Filtra ventas de Valencia superiores a 750 €.
2. Completa automáticamente el nombre de producto desde su código.
3. Crea un gráfico mensual.
4. Crea una tabla dinámica por comercial y trimestre.

## 🔥 6. Nueva incidencia

Dirección formula cinco preguntas sobre un fichero nuevo. Debes decidir qué herramienta utilizar para responder cada una.

## 🔒 7. Ticket cerrado · Evaluable

Cada alumno recibe:

- un dataset distinto;
- preguntas distintas;
- condiciones de análisis distintas.

## ✅ 8. Comprueba que sabes...

- [ ] Sé limpiar una tabla de datos.
- [ ] Distingo ordenar y filtrar.
- [ ] Sé aplicar validación.
- [ ] Sé realizar búsquedas por clave.
- [ ] Sé importar un CSV.
- [ ] Sé elegir un gráfico con criterio.
- [ ] Sé crear una tabla dinámica.
- [ ] Sé justificar cómo he obtenido una respuesta.
