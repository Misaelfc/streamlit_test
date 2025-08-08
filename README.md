# 🪙 Lanzar una Moneda - Simulación con Streamlit

Este proyecto es una aplicación interactiva creada con **Python** y **Streamlit** que simula el lanzamiento de una moneda varias veces y muestra cómo evoluciona la media de resultados en tiempo real.

## 🚀 Características

- Simulación de lanzamientos de moneda usando la distribución Bernoulli (`scipy.stats`).
- Visualización dinámica de la media acumulada en un gráfico de líneas.
- Registro de resultados de múltiples experimentos usando `pandas` y el estado de sesión de Streamlit.
- Control de número de intentos mediante un *slider*.
- Historial de experimentos anteriores.

## 🛠️ Tecnologías utilizadas

- [Python 3.12+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://scipy.org/)

## 📦 Instalación

1. **Clonar este repositorio**
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   cd tu-repo

2.	Crear un entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate  # En macOS/Linux
venv\Scripts\activate     # En Windows

3.	Instalar dependencias
pip install -r requirements.txt
Si no tienes el archivo requirements.txt, puedes instalar manualmente:
pip install streamlit pandas scipy watchdog

▶️ Ejecución

Ejecuta la aplicación con:
streamlit run app.py

Por defecto, se abrirá en tu navegador en la dirección:
http://localhost:8501

📂 Estructura del proyecto
.
├── app.py              # Código principal de la aplicación
├── requirements.txt    # Dependencias del proyecto
└── README.md           # Documentación

📸 Ejemplo de uso
	1.	Selecciona el número de lanzamientos en el slider.
	2.	Presiona el botón Ejecutar.
	3.	Observa cómo la media acumulada se acerca a 0.5 con más intentos.
	4.	Repite y compara resultados en la tabla de historial.

📚 Próximos pasos y mejoras
	•	Botón para reiniciar el historial.
	•	Exportar resultados a CSV.
	•	Añadir un histograma de distribución de medias.
	•	Personalizar estilos y colores del gráfico.

