# Guía básica de Markdown

## 1. ¿Qué es Markdown?

Markdown es un **lenguaje de marcado ligero** que permite dar formato a
documentos de texto utilizando símbolos y caracteres sencillos.

Se utiliza mucho en documentación técnica, manuales, notas y proyectos
informáticos. Por ejemplo, GitHub utiliza Markdown para mostrar los
archivos `README.md`.

Markdown no es un lenguaje de programación y no sustituye a HTML. Es una
forma sencilla de estructurar y presentar documentos.

## 2. Títulos y subtítulos

Se utiliza el símbolo `#`. Cuantos más símbolos, menor es el nivel del
título.

```markdown
# Título principal

## Apartado

### Subapartado
```

## 3. Negrita y cursiva

```markdown
**Este texto está en negrita**

_Este texto está en cursiva_
```

También puedes combinar ambos:

```markdown
**_Negrita y cursiva_**
```

## 4. Listas

Para crear una lista sin ordenar, utiliza `-` o `*`.

```markdown
- Reparación de ordenadores
- Instalación de redes
- Mantenimiento informático
```

Para crear una lista ordenada, utiliza números:

```markdown
1. Investigar empresas
2. Analizar sus servicios
3. Comparar resultados
```

## 5. Enlaces

La sintaxis es `[texto que se muestra](dirección web)`.

```markdown
[Visita Google](https://www.google.com)
```

Se vería asi: [Visita Google](https://www.google.com)

Tambien puedes hacer un enlace a un título del mismo documento:

```markdown
[Qué es Markdown](#1-qué-es-markdown)
```

Se vería asi: [Qué es Markdown](#1-qué-es-markdown)

## 6. Imágenes

La sintaxis es `![texto alternativo](ruta de la imagen)`.

```markdown
![Logotipo de la empresa](img/logo.png)
```

La ruta indica dónde está guardada la imagen respecto al archivo
Markdown.

## 7. Tablas

Las tablas permiten organizar información en filas y columnas.

```markdown
| Servicio      | Descripción              | Precio |
| ------------- | ------------------------ | -----: |
| Reparación    | Diagnóstico y reparación |   30 € |
| Formateo      | Instalación del sistema  |   40 € |
| Mantenimiento | Revisión de equipos      |   50 € |
```

Ejemplo:
| Servicio | Descripción | Precio |
| ------------- | ------------------------ | -----: |
| Reparación | Diagnóstico y reparación | 30 € |
| Formateo | Instalación del sistema | 40 € |
| Mantenimiento | Revisión de equipos | 50 € |

## 8. Bloques de código

Se utilizan tres acentos graves (\`\`\`) antes y después del código.

Se puede indicar el lenguaje para que se resalte su sintaxis:

````markdown
```html
<h1>Hola, mundo</h1>
<p>Mi primera página web</p>
```
````

## 9. Separadores

Tres guiones crean una línea horizontal que separa secciones.

```markdown
---
```

---

# Ejemplo práctico: nuestra empresa TIC

A continuación tienes un ejemplo que combina varios elementos de
Markdown.

```markdown
# TechFix Solutions

![Logotipo](img/logo.png)

**Soluciones informáticas para tu negocio.**

## ¿Quiénes somos?

Somos una empresa especializada en ofrecer servicios informáticos
a particulares y pequeñas empresas.

## Nuestros servicios

- Reparación de ordenadores.
- Instalación y configuración de redes.
- Mantenimiento informático.

## Tarifas

| Servicio              | Precio |
| --------------------- | -----: |
| Reparación            |   30 € |
| Formateo              |   40 € |
| Mantenimiento mensual |   50 € |

## Contacto

- Correo: contacto@techfix.example
- Web: [www.techfix.example](https://example.com)

---

_TechFix Solutions - Tu tecnología, en buenas manos._
```

## 10. ¿Cómo previsualizar Markdown en Visual Studio Code?

1.  Crea un archivo con extensión `.md`, por ejemplo `README.md`.
2.  Escribe el contenido utilizando la sintaxis de Markdown.
3.  Pulsa `Ctrl + Shift + V` para abrir la previsualización.
4.  Para ver el editor y la previsualización a la vez, pulsa `Ctrl + K`
    y después `V`.

La previsualización muestra cómo quedará el documento una vez
interpretadas las marcas.
