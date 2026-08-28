# Tema 6 · Tenemos 847 clientes y cuatro se llaman igual

!!! info "CAOS, S.L."
    La empresa usa varias hojas para clientes y pedidos y ya no puede garantizar que los datos sean coherentes.

## 🚨 1. Incidencia inicial

Problemas:

- duplicados;
- inconsistencias;
- direcciones diferentes;
- pedidos sin cliente identificable.

**Objetivo:** diseñar una base de datos relacional.

## 🎯 2. Qué aprenderás

- identificar entidades y atributos;
- diseñar tablas;
- elegir claves primarias;
- crear relaciones;
- comprender la integridad referencial;
- realizar consultas;
- crear formularios;
- generar informes;
- distinguir cuándo conviene una base de datos frente a una hoja de cálculo.

## 🛠️ 3. Rescate guiado · Clientes y pedidos

### Paso 1. Entidades

```text
CLIENTES
PRODUCTOS
PEDIDOS
LINEAS_PEDIDO
```

### Paso 2. Campos

Ejemplo CLIENTES:

| Campo | Tipo |
|---|---|
| id_cliente | texto/autonumérico |
| nombre | texto |
| email | texto |
| ciudad | texto |

### Paso 3. Clave primaria

`id_cliente` identifica de forma única.

No usamos el nombre como clave porque pueden existir personas con el mismo nombre.

### Paso 4. Relaciones

```text
CLIENTES 1 --- N PEDIDOS
PEDIDOS 1 --- N LINEAS_PEDIDO
PRODUCTOS 1 --- N LINEAS_PEDIDO
```

### Paso 5. Integridad

No debe existir una línea de pedido para un pedido inexistente.

### Paso 6. Consultas

Ejemplo:

> pedidos pendientes de clientes de Valencia.

Campos:

- cliente;
- pedido;
- fecha;
- estado.

Criterios:

```text
ciudad = "Valencia"
estado = "Pendiente"
```

### Paso 7. Formularios

Creamos formularios para facilitar el alta y consulta de datos.

### Paso 8. Informes

Generamos un informe de pedidos por cliente.

## 📚 4. Lo que necesitas saber

### 4.1 Tabla, campo y registro

- **tabla**: conjunto de registros del mismo tipo;
- **campo**: una característica de esos registros;
- **registro**: una fila concreta.

Ejemplo: en CLIENTES, `email` es un campo y cada cliente es un registro.

### 4.2 Entidades y atributos

Antes de crear tablas, identifica:

- qué cosas existen en el problema;
- qué datos describen cada cosa;
- cómo se relacionan.

### 4.3 Clave primaria

La clave primaria identifica un registro de forma única.

Una buena clave debe ser:

- única;
- estable;
- no ambigua.

### 4.4 Clave externa

Una clave externa conecta una tabla con otra.

Ejemplo:

```text
PEDIDOS.id_cliente -> CLIENTES.id_cliente
```

### 4.5 Relaciones

**1:1**  
Un registro de A se relaciona con uno de B.

**1:N**  
Un cliente puede tener muchos pedidos, pero cada pedido pertenece a un cliente.

**N:M**  
Un pedido puede contener muchos productos y un producto puede aparecer en muchos pedidos.

Se resuelve mediante una tabla intermedia, como `LINEAS_PEDIDO`.

### 4.6 Integridad referencial

La integridad evita relaciones imposibles.

Ejemplo: no podemos asignar un pedido al cliente `C999` si ese cliente no existe.

### 4.7 Base de datos frente a hoja de cálculo

Una hoja de cálculo es excelente para:

- cálculo;
- análisis;
- gráficos.

Una base de datos es preferible cuando:

- existen entidades relacionadas;
- se necesita integridad;
- hay múltiples consultas;
- debe evitarse duplicidad.

### 4.8 Consultas

Una consulta recupera información según criterios.

Puede:

- seleccionar campos;
- filtrar;
- ordenar;
- combinar tablas;
- calcular valores.

### 4.9 Formularios e informes

**Formulario:** facilita entrada y consulta.

**Informe:** presenta información preparada para lectura, impresión o distribución.

## 🏋️ 5. Practica

1. Diseña tablas para proveedores y compras.
2. Crea relaciones.
3. Consulta compras > 500 € del último mes.
4. Crea un formulario de alta de proveedor.

## 🔥 6. Nueva incidencia

> Necesito todos los pedidos pendientes de clientes de Valencia cuyo total sea superior a 300 €.

Debes responder mediante una consulta, no buscando fila por fila.

## 🔒 7. Ticket cerrado · Evaluable

Mini caso distinto por alumno.

Debe incluir:

- diseño de tablas;
- claves;
- relaciones;
- consultas;
- formulario;
- informe.

## ✅ 8. Comprueba que sabes...

- [ ] Distingo tabla, campo y registro.
- [ ] Sé identificar entidades y atributos.
- [ ] Sé elegir una clave primaria.
- [ ] Entiendo una clave externa.
- [ ] Distingo relaciones 1:1, 1:N y N:M.
- [ ] Entiendo la integridad referencial.
- [ ] Sé construir consultas.
- [ ] Sé usar formularios e informes.
