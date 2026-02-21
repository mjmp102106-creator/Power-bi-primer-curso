# 📊 Análisis de Patentes en México  
### Organización por Zona Geográfica y Clasificación Tecnológica

## 📌 Descripción del Proyecto

Este proyecto presenta un análisis de patentes registradas en México, organizadas por:

- 🗺️ Zona geográfica  
- 🏷️ Clasificación tecnológica  
- 📈 Tendencias y distribución  

El objetivo es identificar patrones de innovación, concentración regional y áreas tecnológicas con mayor actividad.

Los datos analizados provienen del Instituto Mexicano de la Propiedad Industrial (IMPI), organismo responsable del registro y administración de la propiedad industrial en México.

---

## 🎯 Objetivos

- Analizar la distribución de patentes por región en México.
- Clasificar las patentes según su sector tecnológico.
- Identificar zonas con mayor concentración de innovación.
- Detectar tendencias relevantes en el desarrollo tecnológico.

---

## 🗂️ Estructura del Proyecto

```
📦 analisis-patentes-mexico
 ┣ 📂 data
 ┃ ┣ raw/              # Datos originales
 ┃ ┗ processed/        # Datos limpios y transformados
 ┣ 📂 notebooks        # Análisis exploratorio
 ┣ 📂 src              # Scripts de procesamiento y análisis
 ┣ 📂 visualizations   # Gráficas y resultados
 ┣ README.md
 ┗ requirements.txt
```

---

## 📊 Metodología

1. **Obtención de datos**  
   Descarga de registros de patentes desde fuentes oficiales.

2. **Limpieza y transformación**
   - Normalización de nombres de zonas.
   - Estandarización de clasificaciones tecnológicas.
   - Eliminación de datos incompletos.

3. **Análisis exploratorio**
   - Distribución por estado o región.
   - Clasificación por sector tecnológico.
   - Comparativas y tendencias temporales.

4. **Visualización**
   - Gráficas de barras.
   - Mapas por zona.
   - Series temporales.

---

## 🗺️ Organización por Zonas

Las patentes se agrupan por:

- Norte  
- Centro  
- Bajío  
- Occidente  
- Sur-Sureste  

*(La división puede ajustarse según la metodología definida en el análisis.)*

---

## 🏷️ Clasificación Tecnológica

Se utiliza la Clasificación Internacional de Patentes (IPC), agrupando en categorías como:

- Ingeniería Mecánica  
- Electrónica y Telecomunicaciones  
- Química y Farmacéutica  
- Tecnologías de la Información  
- Energía  
- Biotecnología  

---

## 🛠️ Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/analisis-patentes-mexico.git
cd analisis-patentes-mexico
```

2. Crear entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
source venv/bin/activate  # En Mac/Linux
venv\Scripts\activate     # En Windows
```

3. Instalar dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecutar los notebooks o scripts en la carpeta correspondiente.

---

## 📈 Resultados Esperados

- Identificación de regiones con mayor actividad en innovación.
- Sectores tecnológicos predominantes en cada zona.
- Insights útiles para análisis académico, económico o estratégico.

---

## 📚 Posibles Aplicaciones

- Estudios de innovación regional.
- Análisis de competitividad tecnológica.
- Planeación estratégica empresarial.
- Investigación académica.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas.

1. Haz un fork del proyecto.
2. Crea una nueva rama.
3. Envía un pull request.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.  
Consulta el archivo `LICENSE` para más información.
