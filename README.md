# SBS-Financial-WebScraper

## Descripción
**SBS-Financial-WebScraper** es un proyecto que realiza **web scraping** de los estados financieros de bancos registrados en la **Superintendencia de Banca, Seguros y AFP (SBS) de Perú**. Extrae información de los **balances generales** y **estados de ganancias y pérdidas** desde enero de 2002 hasta diciembre de 2024. Luego, los datos se **normalizan y transforman de formato wide a long** utilizando `pandas`, facilitando su análisis y uso en modelos de datos.

## Características principales
✅ **Web Scraping** automatizado desde la web de la SBS.

✅ **Normalización** de datos para estandarizar nombres de columnas y valores.

✅ **Transformación de datos** de formato wide a long para facilitar análisis.

✅ **Exportación** en formatos **CSV y Parquet** para mayor compatibilidad.

✅ **Código abierto**, con restricciones para uso comercial sin autorización.

## Requisitos
### 🔹 Dependencias
Este proyecto utiliza las siguientes librerías de Python:
- `requests`
- `BeautifulSoup`
- `pandas`
- `numpy`
- `selenium`

Puedes instalarlas con:
```sh
pip install requests beautifulsoup4 pandas numpy selenium
```

### 🔹 Requisitos adicionales
- **Python 3.8+**
- **Acceso a internet** para descargar los datos de la SBS.

## Instalación y Uso
### 1️⃣ Clonar el repositorio
```sh
git clone https://github.com/brando-rojas/SBS-Financial-WebScraper.git
cd SBS-Financial-WebScraper
```

### 2️⃣ Ejecutar el notebook
Dado que el código está contenido en un **Jupyter Notebook**, puedes ejecutarlo con:
```sh
jupyter notebook SBS_Balance_General_con_Web_Scraping.ipynb
```
Esto abrirá el entorno de Jupyter donde podrás correr cada celda paso a paso.

### 3️⃣ Ver los datos procesados
Los datos limpios estarán en la carpeta `Output_Files/` en formato CSV y Parquet.

## Licencia
Este proyecto está licenciado bajo la **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

📌 **Esto significa que:**
- ✅ Puedes copiar, modificar y distribuir el código **mencionando al autor**.
- ❌ **No puedes usarlo con fines comerciales** sin permiso explícito.

Para más detalles, revisa el archivo `LICENSE` en este repositorio.

## Contribuciones
Si deseas contribuir, ¡eres bienvenido! Puedes hacerlo mediante _pull requests_ o reportando problemas en la sección de **Issues** del repositorio.

---
💻 **Autor:** [Brando Rojas](https://github.com/brando-rojas)  
📅 **Última actualización:** 2025

