# SH_UTILS_C42
# Bienvenido al Repositorio de Utilidades en Bash para Archivos en C de 42

¿Eres estudiante de 42 y buscas herramientas para facilitar tu trabajo con archivos en C? ¡Estás en el lugar correcto! Nuestro repositorio ofrece scripts en Bash diseñados para ayudarte a mejorar y simplificar tu proceso de desarrollo.

## ¿Qué Ofrecemos?

### 1. Script para Quitar el Heading
Este script elimina automáticamente el heading de tus archivos en C, ayudándote a mantener tu código limpio y estandarizado sin esfuerzo.

### 2. Script para Buscar y Remplazar palabras
¿Necesitas cambiar una palabras en tus ficheros? Nuestro script automatiza este proceso, asegurando que puedas realizar cambios rápidamente sin errores manuales.

### 3. Script para generar .h
¿Cansado de escribir el fichero .h? Nosotros lo hacemos por ti!
> Nota : El NORMINETTE no te lo hace!

### 4. Script para eliminar los comentarios de tus ficheros
Comenta tu codigo dónde quieras que nuestro script te los eliminara de tu fichero y creara un fichero adicional donde se habran guardado dichos comentarios.
> Nota: Solo funciona con los comentarios de una línea

## ¿Por Qué Usar Estas Herramientas?

- **Ahorro de Tiempo**: Olvídate de las tediosas tareas manuales. Nuestros scripts te permiten enfocarte en el desarrollo de tu proyecto.
- **Facilidad de Uso**: Diseñados pensando en los estudiantes de 42, nuestros scripts son intuitivos y fáciles de integrar en tu flujo de trabajo.
- **Mejora de la Calidad**: Automatiza tareas repetitivas y minimiza errores humanos, haciendo que tu código sea más robusto y limpio.

## ¿Cómo Empezar?

1. **Clona el Repositorio**:
    ```bash
    git clone https://github.com/ahernE2/sh_utils_C42.git
    ```
2. **Navega al Directorio del Repositorio**:
    ```bash
    cd sh_utils_C42
    ```
3. **Dar permisos de ejecucion a los Scripts**
    ```bash
    chmod +x *.sh
    ```
4. **Ejecuta los Scripts**:
     - Para quitar el heading:
        ```bash
		./remove_heading.sh <ruta_archivo.c>
        ```
     - Para hacer un buscar y remplazar de una palabra de tu archivo:
        ```bash
		./search_and_replace.sh <ruta_archivo.c> <search> <replace>
        ```
     - Para la generación del archivo .h y añadir los includes a tus ficheros .c:
        ```bash
		./generate_includers.sh <directorio_archivo_h> <nombre_del_archivo_h_a_generar> <directorio_srcs>
        ```
     - Para descomentar tus ficheros .c:
        ```bash
		./uncoment_file.sh <ruta_archivo.c>
        ```

## Contribuye y Mejora

Este es solo el comienzo. Estamos continuamente mejorando y agregando nuevas utilidades. ¡Nos encantaría contar con tu colaboración! Si tienes ideas o mejoras, siéntete libre de contribuir.

---

Empieza a usar nuestros scripts y transforma tu flujo de trabajo. ¡Haz que tu tiempo en 42 sea aún más productivo y eficiente con nuestras herramientas en Bash!
