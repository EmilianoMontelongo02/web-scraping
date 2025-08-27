# Ejemplo Práctico con Selenium

Este es un ejemplo práctico donde aprendo a usar **Selenium** para realizar web scraping en Python.  
El proyecto también utiliza **Pandas** para manejar los datos obtenidos y **Jupyter Notebook** para la ejecución interactiva.

---

## Tecnologías Utilizadas
- **Python** como lenguaje principal.
- **Selenium** para el scraping.
- **Pandas** para manipulación y exportación de datos.
- **Jupyter Notebook** para entorno interactivo.

---

## Descripción
Si bien no es la implementación más optimizada, cumple con la funcionalidad requerida.

El flujo principal incluye:
1. Ingreso de un usuario de prueba mediante la interfaz de la página.
2. Iteración sobre cada ítem listado para obtener:
   - Título del producto.
   - URL de la imagen.
   - Costo.

Posteriormente, los datos se guardan en un archivo **CSV** utilizando Pandas, lo que permite organizar la información de manera ordenada y reutilizable.

---

## Sitio Web de Prueba
[https://www.saucedemo.com/](https://www.saucedemo.com/)

---

## Instalación
Clona el repositorio e instala las dependencias necesarias:

```bash
git clone https://github.com/usuario/repositorio.git
cd repositorio
pip install selenium pandas jupyter
---

## Ejecución