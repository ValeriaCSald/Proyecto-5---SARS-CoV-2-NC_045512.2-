# Proyecto-5---SARS-CoV-2-NC_045512.2-
Análisis bioinformático del genoma completo del SARS-CoV-2 utilizando Python y Biopython. Automatiza la descarga de datos desde NCBI (GenBank) y procesa la secuencia de nucleótidos para su estudio

Este proyecto realiza un análisis bioinformático automatizado del genoma completo del virus SARS-CoV-2 utilizando herramientas de Python. El flujo de trabajo incluye la consulta a bases de datos biológicas públicas, la descarga del genoma y el procesamiento inicial de su secuencia de nucleótidos.

## Características
* **Descarga Automatizada:** Conexión con la base de datos NCBI (Entrez) para obtener el registro oficial en formato GenBank (Accession: `NC_045512.2`).
* **Procesamiento de Secuencias:** Lectura y manipulación de archivos biológicos mediante la librería `Biopython`.
* **Análisis de Nucleótidos:** Conversión de la secuencia a texto, normalización de caracteres (cambio de ARN/Uracilo a ADN/Timina según estándares de análisis) y cálculo de la longitud genómica.

## Tecnologías utilizadas
* **Lenguaje:** Python 3.13
* **Entorno:** Jupyter Notebook / Anaconda
* **Librerías Principales:** `Biopython` (`Bio.SeqIO`, `Bio.Entrez`)

## Requisitos e Instalación
Para ejecutar este notebook, necesitas tener instalado Anaconda o un entorno de Python con Biopython:

```bash
pip install biopython
