# Actividad 1. Investigación y comparación de empresas TIC

**Proyecto Intermodular · 1.º SMR**

**Formato:** documentos Markdown (`.md`) en un repositorio de GitHub del grupo.

## ¿Qué vais a hacer?

Vais a investigar empresas reales del sector de las Tecnologías de la Información y la Comunicación (TIC) para conocer qué hacen, qué productos y servicios ofrecen, a quién se dirigen y cómo se organizan.

**Cada integrante investigará una empresa diferente y el grupo elaborará una comparación conjunta.**

Si hay 4 alumnos, 4 empresas. **1 empresa por alumno**

En esta actividad describiréis la organización general de las empresas. Las funciones detalladas de los departamentos se trabajarán en la actividad 2.

## Paso 1: preparar el repositorio

Una persona crea el repositorio del grupo con un `README.md` e invita al resto como colaboradores. Todos deben aceptar la invitación y trabajar con su propia cuenta.

Organizad los archivos así:

```text
README.md
empresas/
  nombre-empresa-a.md
  nombre-empresa-b.md
  nombre-empresa-c.md
  nombre-empresa-d.md
docs/
  01-comparativa.md
```

Usad nombres de archivo en minúsculas, sin espacios ni tildes, separados por guiones.

## Paso 2: elegir las empresas y repartir el trabajo

1. Elegid un ámbito TIC que os interese: desarrollo de videojuegos, soporte informático, redes, desarrollo de software, ciberseguridad, servicios en la nube, etc.
2. Seleccionad una empresa diferente por persona. Pueden ser locales, nacionales o internacionales, y tener tamaños distintos.
3. Comprobad que ofrecen algún producto o servicio comparable y que existe información pública suficiente para investigarlas.

## Paso 3: investigar y completar la ficha individual

Cada integrante copiará la siguiente plantilla en su archivo `empresas/nombre-empresa.md` y sustituirá los textos entre corchetes.

**Extensión orientativa:** entre 400 y 600 palabras por ficha, sin contar tablas y fuentes. Se valora la información útil, explicada con vuestras palabras y respaldada por fuentes.

**Fuentes:** utilizad páginas o documentos relevantes por empresa; al menos uno debe ser una fuente oficial. Pueden ser páginas de productos, servicios, información corporativa o informes. Citad las fuentes junto a los datos que respaldan y recogedlas al final de la ficha.

Utilizad la siguiente [plantilla](../plantillas/plantilla-empresa.md)

## 5. Paso 4: elaborar la comparación del grupo

Leed las fichas de los compañeros y completad juntos el archivo `docs/01-comparativa.md` con la siguiente plantilla. Añadid una fila por empresa y enlazad su ficha.

Utilizad la [plantilla de comparativa](../plantillas/plantilla-comparativa.md).

Cada integrante aportará la fila de su empresa. Las conclusiones se discutirán entre todos; repartid su redacción y revisión para que todos participen también en esta parte.

**Extensión orientativa de las conclusiones:** entre 300 y 500 palabras por grupo, con independencia del número de integrantes.

## 6. Cómo trabajar en GitHub

Es recomendable que uséis Visual Studio Code ya que podeis editar el archivo a la vez que veis el resultado. Para ello podéis hacer click derecho en el .md que estáis editando y seleccionar "Open Preview". Esa pestaña podéis arrastrarla a la derecha. Tambien podéis seleccionar la opción "Open to the side" y luego "Open Preview". Según modifiqueis el archivo, vereis los cambios reflejados en tiempo real.

Tambien se puede hacer toda la actividad desde el navegador, editando los archivos y guardando los cambios directamente en `main`.

### ¿Qué pasa si dos personas editan el mismo archivo?

GitHub no funciona como un documento compartido que muestra en directo lo que escriben los demás. Si dos personas cambian la misma parte de un archivo desde versiones distintas, puede aparecer un [**conflicto**](https://docs.github.com/en/pull-requests/reference/merge-conflicts): los cambios no se pueden combinar automáticamente y hay que decidir cómo quedará el texto final.

Por ejemplo, Pepito y Pablito abren la comparativa. Pepito modifica una frase y guarda. Pablito cambia esa misma frase en la versión que ya tenía abierta; al intentar guardar, puede aparecer un aviso porque el archivo ha cambiado.

Si os ocurre al editar desde el navegador:

1. **Copiad vuestro texto en un bloc de notas antes de recargar**, para conservar el trabajo pendiente.
2. Abrid de nuevo el archivo para consultar la última versión guardada.
3. Hablad con el compañero y acordad cómo combinar las aportaciones.
4. Editad esa versión actualizada y añadid solo los cambios necesarios, conservando las aportaciones de los demás.
5. Guardad el resultado con un nuevo commit.

Para reducir estos problemas, acordad turnos y haced click en fetch (si usáis GitHub desktop) o actulizar la página (desde el navegador) antes de empezar a editar.

Recursos de apoyo:

- [Cómo editar archivos en GitHub](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).
- [Sintaxis básica de Markdown en GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## 7. Qué debéis entregar

Entregad el enlace al repositorio por el medio indicado en clase. La versión final debe estar en `main` y contener:

- Un `README.md` con integrantes, reparto, justificación de la selección e índice con enlaces.
- Una ficha completa **POR** **INTEGRANTE** dentro de `empresas/`.
- El documento común `docs/01-comparativa.md` con la tabla, las conclusiones y el registro de participación.

## 8. Qué se valorará

- La selección de empresas y la calidad de la información investigada.
- La explicación de productos, servicios, clientes y organización general.
- La comparación razonada y el uso de ejemplos para justificar las conclusiones.
- La fiabilidad de las fuentes y la claridad de la redacción y del formato Markdown.
- La aportación individual y el uso de commits con mensajes descriptivos.
