# FlashMarket

Proyecto desarrollado como Trabajo de Fin de Grado en grupo, que conservo como parte de mi portfolio por ser **mi primer proyecto completo** y por las tecnologías que aprendí y apliqué durante su desarrollo.

Yo me hice cargo de la recolección y gestión de productos de supermercados online, utilizando técnicas de web scraping para obtener información y almacenarla en una base de datos mySQL.

Mi objetivo fue:
- Extraer información dinámica de páginas reales.
- Normalizar datos.
- Persistirlos en una base de datos mySQL.

## ⚙️ Qué hace el código

El código realiza las siguientes tareas:

- Automatiza un navegador usando Puppeteer con configuración stealth para evitar bloqueos.
- Navega por distintas categorías de productos de supermercados online.
- Accede a la página individual de cada producto para obtener su descripción.
- Extrae y estructura los datos de cada producto de la siguiente manera:
  - Título
  - Descripción
  - Precio
  - Imagen
  - Categoría
  - Supermercado
- Inserta los productos en nuestra base de datos.
- Actualiza el precio si el producto ya existe en la base de datos.

## 🛠️ Tecnologías utilizadas
- Node.js
- Puppeteer + puppeteer-extra-plugin-stealth
- Cheerio
- JavaScript
- MySQL

## 💡 Nota personal

Este proyecto tiene un valor especial para mí porque fue mi primer proyecto completo, donde aprendí conceptos clave de desarrollo backend, scraping y bases de datos y sobre todo el trabajo en equipo con mis compañeros.
