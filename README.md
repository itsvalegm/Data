from pathlib import Path

# Contenido del README.md
readme_content = """
# HR Analytics

Este repositorio contiene un notebook desarrollado como parte del curso de **Data Analytics** en **WE Educación Ejecutiva**, cuyo objetivo principal es analizar patrones relacionados con las promociones internas dentro de una empresa, utilizando datos proporcionados en clase.

---

## 👥 Autores

- Jheny Jorge Zelaya  
- Sofía Solís Quevedo  
- Eduardo Alonso Mamani Hernandez  
- Gino Vasquez Delgado  
- Lizbeth Cristina Centeno Saire  
- Valeria Zared Gomez Mejía  

---

## 🧪 Dataset

El conjunto de datos fue proporcionado por la docente **Ana Lucía Palacios** y contiene información relacionada con empleados, incluyendo variables relevantes para el análisis de promociones laborales dentro de una organización.

---

## 🎯 Objetivo del análisis

El propósito de este trabajo es identificar y explorar factores que pueden influir en la promoción de los empleados dentro de una empresa. A través de un análisis descriptivo, se busca comprender mejor los perfiles y condiciones que caracterizan a los trabajadores promovidos, con el fin de generar posibles insights para la toma de decisiones en gestión del talento humano.

---

## 📎 Tecnologías utilizadas

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## 🧑‍🏫 Curso

Trabajo desarrollado para el curso de **Data Analytics** de **WE Educación Ejecutiva**.
"""

# Guardar como archivo README.md
readme_path = Path("/mnt/data/README_HR_Analytics.md")
readme_path.write_text(readme_content.strip())

readme_path.name
