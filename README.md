# 🦠 Dengue-4: Análisis Filogenético del Virus DENV-4

¡Bienvenido a **Dengue-4**! 🧬 Este proyecto se centra en la reconstrucción filogenética del serotipo 4 del virus del dengue (**DENV-4**), con un enfoque en el **dominio III** de la proteína de envoltura, una región clave para la interacción del virus con las células huésped.

## 📝 ¿Qué hemos hecho?

Este trabajo recrea el análisis presentado en el artículo **"Análisis filogenético del dominio III de la proteína de envoltura del virus dengue 4"** de **Mota et al. (2002)**. Utilizando herramientas bioinformáticas modernas, hemos:

- 🔍 **Analizado secuencias genéticas** de variantes de DENV-4 de distintas regiones del mundo.
- 🌍 **Comparado** las secuencias con otros serotipos de dengue (DENV-1, DENV-2 y DENV-3) para entender su evolución.
- 🌿 **Construido árboles filogenéticos**, demostrando la existencia de dos genotipos principales.
- 🛠️ **Usado herramientas como BioPython y AlphaFold2** para recrear estructuras tridimensionales del virus y validar su evolución.

## 📂 Contenido del repositorio

- `data/` → Secuencias genéticas utilizadas en el análisis (en formato FASTA).
- `scripts/` → Códigos en Python para la alineación de secuencias y construcción de árboles filogenéticos.
- `results/` → Árboles filogenéticos generados y visualizaciones de estructuras proteicas.
- `report/` → Informe detallado con la metodología y hallazgos clave.

## 🚀 Cómo usar este repositorio

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/deepamino/dengue-4.git
   cd dengue-4
   ```

2. **Instala las dependencias necesarias** (ver `requirements.txt`):

   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecuta los scripts de análisis**:

   ```bash
   python scripts/phylogenetic_analysis.py
   ```

4. **Explora los resultados** en la carpeta `results/`.

## 📊 Resultados principales

- Se confirmó la existencia de **dos genotipos principales** en DENV-4.
- La diferenciación entre serotipos es clara, validando el **dominio III** como un marcador filogenético robusto.
- La estructura de la proteína de envoltura varía según la región geográfica, lo que podría estar vinculado a la virulencia.

## 🤝 Contribuciones

¡Toda ayuda es bienvenida! Si deseas contribuir:

1. Haz un fork del repositorio.
2. Crea una nueva rama con tus mejoras.
3. Envía un Pull Request detallado.

## 📄 Licencia

Este proyecto está bajo la licencia MIT, lo que permite su libre uso y modificación.
