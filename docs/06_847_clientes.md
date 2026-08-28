# Tema 6 · Tenemos 847 clientes y cuatro se llaman igual

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

Diseñar y utilizar una base de datos ofimática con tablas, claves, relaciones, consultas, formularios e informes.

## 🚨 Incidencia inicial · «¿Cuál de los cuatro Carlos García es este?»

CAOS, S.L. mantiene clientes en varias hojas de cálculo.

Se detecta:

- información duplicada;
- direcciones diferentes para el mismo cliente;
- nombres escritos de varias formas;
- pedidos sin cliente claro;
- teléfonos dentro de la columna de observaciones.

**Misión:** dejar de tratar la información relacionada como simples listas independientes.

## 🛠️ Rescate guiado · Creamos la base de datos de clientes y pedidos

### 1. Cuándo necesitamos una base de datos

Una hoja de cálculo funciona muy bien para cálculo y análisis.

Una base de datos resulta especialmente útil cuando debemos gestionar muchas entidades relacionadas y mantener coherencia entre ellas.

### 2. Conceptos

- base de datos;
- tabla;
- campo;
- registro;
- clave primaria.

### 3. Tipos de datos

Elegiremos el tipo adecuado para cada campo.

Ejemplos:

- texto;
- número;
- fecha;
- moneda;
- sí/no.

### 4. Diseño de tablas

Separaremos entidades:

```text
CLIENTES
PRODUCTOS
PEDIDOS
LINEAS_PEDIDO
```

### 5. Claves

Una clave primaria identifica cada registro de forma única.

No utilizaremos el nombre de una persona como identificador único.

### 6. Relaciones

Estudiaremos relaciones entre tablas y el significado de:

- uno a uno;
- uno a muchos;
- muchos a muchos mediante tabla intermedia.

### 7. Integridad

El objetivo es evitar situaciones incoherentes, por ejemplo un pedido asociado a un cliente inexistente.

### 8. Importación de datos

Partiremos de información procedente de temas anteriores y prepararemos su incorporación.

### 9. Consultas

Una consulta permite recuperar información según criterios.

Practicaremos:

- selección de campos;
- criterios;
- ordenación;
- varias tablas;
- cálculos sencillos.

### 10. Formularios

Los formularios facilitan la introducción y consulta de datos.

### 11. Informes

Los informes permiten presentar información de forma organizada para imprimir o distribuir.

### 12. Exportación

Extraeremos resultados hacia formatos adecuados para utilizarlos en otros programas.

## 📚 Lo que necesitas saber

### Diseñar antes de crear

No empezamos pulsando «Nueva tabla».  
Primero identificamos:

- qué entidades existen;
- qué atributos tiene cada una;
- cómo se relacionan.

### No dupliques información innecesariamente

Si la dirección de un cliente aparece en 25 pedidos, actualizarla manualmente 25 veces es una señal de mal diseño.

## 🏋️ Ahora tú · «Proveedores y compras»

Diseña una pequeña base de datos relacionada a partir de unas necesidades descritas.

## 🔥 Nueva incidencia · «Necesito todos los pedidos pendientes de clientes de Valencia»

Debes responder mediante una consulta, no buscando manualmente fila por fila.

## 🔒 Ticket cerrado · Evaluable

Cada alumno recibirá un pequeño caso de negocio distinto.

Deberá:

1. diseñar tablas;
2. definir claves;
3. crear relaciones;
4. importar o introducir datos;
5. construir consultas;
6. crear un formulario;
7. generar un informe.

## ✅ Checklist

- [ ] Distingo tabla, campo y registro.
- [ ] Sé elegir una clave primaria.
- [ ] Sé separar entidades.
- [ ] Sé crear relaciones.
- [ ] Sé construir consultas.
- [ ] Sé usar formularios.
- [ ] Sé generar informes.
- [ ] Sé importar/exportar información.
