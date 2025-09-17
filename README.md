# 🔵 Dashboard OMOP Framework IDARA

## 📊 Descripción

Dashboard interactivo para visualizar la transformación de datos Synthea a formato OMOP CDM v6.0, desarrollado específicamente para datos de gastroenterología de Galicia.

## ✨ Características

- **🏠 Resumen Ejecutivo**: Métricas principales y estado del sistema
- **🔗 Comparación Detallada**: Transformación Synthea → OMOP lado a lado
- **🗂️ Mapeo de Conceptos**: Análisis de cobertura de vocabularios OMOP
- **🔍 Análisis de Mapeo Detallado**: Identificación de conceptos faltantes y estrategias de mejora

## 🚀 Demo en Vivo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://tu-dashboard.streamlit.app)

## 📁 Estructura del Proyecto

```
Framework_OMOP_IDARA/
├── omop_framework/
│   ├── dashboard_simple/
│   │   ├── dashboard_simple.py    # Dashboard principal
│   │   └── ejecutar_dashboard.py  # Script de ejecución
│   ├── test_data/                 # Datos de prueba Synthea
│   └── output/                    # Resultados OMOP
├── requirements.txt               # Dependencias
└── README.md                     # Este archivo
```

## 🛠️ Instalación Local

### Prerrequisitos
- Python 3.8+
- pip

### Pasos

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/Framework_OMOP_IDARA.git
cd Framework_OMOP_IDARA
```

2. **Instalar dependencias**
```bash
pip install -r requirements.txt
```

3. **Ejecutar el dashboard**
```bash
streamlit run omop_framework/dashboard_simple/dashboard_simple.py
```

4. **Abrir en el navegador**
```
http://localhost:8501
```

## 📊 Datos de Ejemplo

El dashboard incluye datos de ejemplo de:
- **30 pacientes** gallegos sintéticos
- **Especialidad**: Gastroenterología
- **Formato origen**: Synthea CSV
- **Formato destino**: OMOP CDM v6.0

## 🎯 Métricas Principales

- ✅ **Tasa de éxito**: >90%
- 🫃 **Mapeo gastroenterológico**: 46.7% (en mejora)
- 💊 **Medicamentos**: 88% mapeados
- ⚕️ **Procedimientos**: 92% mapeados

## 🔧 Tecnologías

- **Frontend**: Streamlit
- **Visualización**: Plotly
- **Datos**: Pandas, NumPy
- **Formato**: OMOP CDM v6.0

## 👥 Equipo

Desarrollado por el equipo de IDARA para la transformación de datos médicos gallegos.

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver `LICENSE` para más detalles.

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📞 Contacto

- **Proyecto**: Framework OMOP IDARA
- **Región**: Galicia, España
- **Especialidad**: Gastroenterología
