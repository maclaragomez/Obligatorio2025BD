# Sistema de Gestión de Reservas de Salas de Estudio - UCU

## Descripción
Sistema completo para la gestión de reservas de salas de estudio en la Universidad Católica del Uruguay. Desarrollado como trabajo obligatorio para la materia Base de Datos 1.

## Características
- Gestión de participantes, salas y reservas
- Sistema de sanciones por inasistencia  
- Reportes avanzados para análisis
- Interfaz web con Streamlit

## Instalación
```bash
pip install -r requirements.txt
streamlit run app/main.py

app/
├── main.py
├── database/queries.py
├── services/base_service.py
└── utils/validators.py
