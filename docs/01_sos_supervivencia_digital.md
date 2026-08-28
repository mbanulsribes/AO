# Tema 1 · SOS: supervivencia en el caos digital

!!! info "CAOS, S.L."
    Formas parte del equipo de rescate digital de una empresa cuya gestión ofimática es un desastre.

    Todo lo que arregles en este tema quedará incorporado a la empresa y podrá volver a utilizarse en temas posteriores.

## 🚨 1. Incidencia inicial

Primer día en **CAOS, S.L.**.

La carpeta compartida contiene archivos con nombres como:

```text
factura.docx
factura_nueva.docx
factura_final.docx
factura_final2.docx
factura_FINAL_BUENA_ahora_si.docx
captura1.png
captura2.png
presupuesto_cliente23_FINAL.xlsx
entrega.zip
```

Además:

- algunos empleados no saben qué formato deben enviar;
- hay archivos que no se abren;
- los correos llegan sin asunto;
- las capturas no muestran el error;
- nadie sabe qué versión es la correcta.

**Objetivo del tema:** crear un protocolo mínimo de trabajo para que la empresa pueda empezar a funcionar.

## 🎯 2. Qué aprenderás

Al terminar el tema deberás ser capaz de:

- reconocer las principales aplicaciones ofimáticas;
- organizar archivos y carpetas de forma profesional;
- elegir nombres y versiones coherentes;
- distinguir formatos habituales;
- decidir cuándo conviene PDF, formato editable o CSV;
- preparar capturas útiles;
- redactar un correo profesional básico;
- registrar una incidencia con información suficiente;
- revisar requisitos y licencias antes de instalar software.

## 🛠️ 3. Rescate guiado · La carpeta compartida

### Paso 1. Identificamos las herramientas

La **ofimática** reúne herramientas para crear, tratar, almacenar, organizar y comunicar información habitual en una organización.

Durante el curso utilizaremos:

- procesadores de texto;
- hojas de cálculo;
- bases de datos;
- presentaciones;
- gestores de correo y agenda;
- editores de imagen;
- editores de vídeo.

Una **suite ofimática** agrupa varias de estas aplicaciones. Ejemplos habituales:

- Microsoft 365;
- LibreOffice;
- Google Workspace.

### Paso 2. Creamos una estructura lógica

Una posible estructura sería:

```text
CAOS_SL/
├── 01_Administracion/
├── 02_Clientes/
├── 03_Ventas/
├── 04_Marketing/
├── 05_Soporte/
└── 99_Temporal/
```

No existe una única estructura correcta. Debe ser:

- coherente;
- comprensible;
- estable;
- compartida por todo el equipo.

### Paso 3. Renombramos los archivos

Evita nombres como:

```text
factura_final2_buena.docx
```

Es preferible usar nombres descriptivos y, cuando proceda, fecha, cliente o versión:

```text
2026-09_factura_C023.docx
2026-09_factura_C023_v01.docx
2026-09_factura_C023_v02.docx
```

### Paso 4. Reconocemos extensiones

| Extensión | Uso habitual |
|---|---|
| `.docx`, `.odt` | documentos editables |
| `.pdf` | distribución y lectura |
| `.xlsx`, `.ods` | hojas de cálculo |
| `.csv` | intercambio de datos tabulares |
| `.jpg`, `.png`, `.svg` | imagen |
| `.mp4`, `.webm` | vídeo |
| `.zip`, `.7z` | archivos comprimidos |

!!! warning "Importante"
    Cambiar `.odt` por `.docx` en el nombre **no convierte realmente el archivo**.

### Paso 5. Elegimos formato según la finalidad

Si Administración debe enviar una circular que el receptor solo tiene que leer, la mejor salida suele ser **PDF**.

Si el receptor tiene que modificar el contenido, será necesario enviar además un formato editable compatible.

Si otra aplicación debe importar una tabla, un **CSV** suele ser adecuado porque contiene datos tabulares en texto plano.

### Paso 6. Preparamos una captura útil

Una captura de soporte debe:

- mostrar el error;
- mostrar suficiente contexto;
- ser legible;
- evitar información privada no necesaria;
- llevar un nombre descriptivo.

Ejemplo:

```text
error_apertura_archivo_2026-09-15.png
```

### Paso 7. Redactamos un correo profesional

**Asunto:** Incidencia al abrir listado de clientes

> Buenos días:  
> Al intentar abrir `listado_clientes.ods` aparece el mensaje «formato no compatible».  
> He probado a abrirlo con la aplicación instalada en el equipo y he adjuntado una captura del error.  
> Necesito consultar el listado, pero no modificarlo.  
> Gracias.

### Paso 8. Registramos el ticket

Campos mínimos:

- usuario;
- fecha/hora;
- aplicación o archivo afectado;
- descripción;
- mensaje de error;
- pasos realizados;
- evidencias;
- estado.

## 📚 4. Lo que necesitas saber

### 4.1 Software libre, propietario, freeware y shareware

**Software libre** no significa necesariamente gratuito. Significa que la licencia concede libertades como usar, estudiar, modificar y redistribuir el programa bajo determinadas condiciones.

**Software propietario** está controlado por su titular y su uso depende de la licencia concedida.

Otros conceptos:

- **freeware**: gratuito, pero no necesariamente libre;
- **shareware**: versión limitada en tiempo o funciones;
- **copyright**: conjunto de derechos del autor o titular;
- **copyleft**: mecanismo que permite reutilización y redistribución manteniendo determinadas libertades.

### 4.2 Instalación y requisitos

Antes de instalar una aplicación:

1. comprueba el sistema operativo compatible;
2. revisa memoria y espacio disponible;
3. verifica dependencias;
4. descarga desde una fuente fiable;
5. instala;
6. prueba que funciona;
7. documenta incidencias.

Una instalación correcta no termina cuando el asistente muestra «Finalizar»: hay que comprobar que la aplicación arranca y que puede realizar la tarea prevista.

### 4.3 PDF frente a archivo editable

El PDF es apropiado cuando queremos conservar el aspecto de un documento y facilitar su lectura en distintos equipos.

No sustituye al archivo editable original. Por eso, en un entorno profesional puede ser necesario conservar:

- el archivo fuente;
- el PDF final distribuido.

### 4.4 Compresión

Un ZIP permite:

- agrupar archivos;
- reducir tamaño en muchos casos;
- conservar una estructura de carpetas;
- enviar varios archivos como una sola unidad.

Antes de enviarlo revisa:

- temporales;
- duplicados;
- nombres;
- carpetas vacías;
- contenido innecesario.

### 4.5 Imagen básica

Conceptos:

- **dimensiones**: ancho × alto en píxeles;
- **formato**: JPG, PNG, SVG, etc.;
- **peso**: espacio ocupado por el archivo;
- **resolución**: nivel de detalle o densidad según el contexto.

La edición avanzada se trabajará en el Tema 7.

### 4.6 Correo profesional básico

Un mensaje de trabajo debe permitir que el receptor entienda rápidamente:

- quién escribe;
- para qué;
- qué necesita;
- qué adjunta;
- si debe realizar alguna acción.

Un asunto como `Hola` o `Mira esto` obliga al receptor a abrir el mensaje para saber de qué trata.

### 4.7 Qué convierte una captura en evidencia

Una captura no es una prueba útil si el error aparece diminuto o fuera de contexto.

Debe ayudar a otra persona a reproducir o comprender el problema.

### 4.8 Error frecuente: «No funciona»

«No funciona» no es un diagnóstico. Antes de pedir ayuda hay que concretar:

- qué intentabas hacer;
- qué esperabas que ocurriera;
- qué ocurrió realmente;
- qué mensaje apareció;
- qué has probado.

## 🏋️ 5. Practica

### Ejercicio 1 · Clasifica

Indica qué aplicación utilizarías principalmente para:

1. redactar un informe;
2. calcular un presupuesto;
3. almacenar clientes y pedidos relacionados;
4. preparar una exposición;
5. editar un logotipo;
6. montar un videotutorial;
7. enviar una convocatoria.

### Ejercicio 2 · Renombrado profesional

Propón nombres adecuados para:

```text
factura buena.docx
clientes NUEVO.xlsx
captura.png
presentacion final final.pptx
```

### Ejercicio 3 · Elige el formato

Decide qué formato entregarías en cada caso:

1. documento que solo debe leerse;
2. tabla que otro departamento debe seguir editando;
3. datos tabulares que deben importarse en otra aplicación;
4. logotipo con transparencia;
5. fotografía para una publicación.

### Ejercicio 4 · Ticket

Redacta un ticket a partir de:

> «No me va el Word. Le doy y no abre.»

Indica qué información falta y cómo la pedirías.

## 🔥 6. Nueva incidencia · «No puedo abrir esto»

Un cliente recibe `listado_clientes.ods` pero solo necesita **consultar** la información.

Resuelve la incidencia y justifica el formato de salida.

## 🔒 7. Ticket cerrado · Evaluable

Cada alumno recibe una carpeta distinta con:

- archivos mal nombrados;
- duplicados;
- un archivo incompatible;
- un ZIP desordenado;
- una captura deficiente;
- un correo mal redactado.

Entregables:

1. estructura organizada;
2. archivos renombrados;
3. conversión solicitada;
4. ZIP limpio;
5. captura útil;
6. ticket;
7. correo de respuesta.

!!! warning "Importante"
    Los datos, archivos o condiciones pueden cambiar entre alumnos. No se evalúa repetir pasos de memoria, sino resolver correctamente la incidencia y justificar las decisiones.

## ✅ 8. Comprueba que sabes...

- [ ] Distingo las principales aplicaciones ofimáticas.
- [ ] Sé organizar carpetas y archivos.
- [ ] Sé nombrar y versionar archivos con criterio.
- [ ] Distingo formato editable, PDF y CSV.
- [ ] Sé preparar una captura útil.
- [ ] Sé redactar un correo profesional básico.
- [ ] Sé registrar una incidencia con datos suficientes.
- [ ] Sé comprobar requisitos y licencias antes de instalar software.
