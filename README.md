
# Auditoría PDF Clínica PRO - Enterprise

Plataforma profesional para auditoría masiva de soportes clínicos.

## Instalación

pip install -r requirements.txt

## Ejecutar Streamlit

streamlit run app_streamlit.py

## Ejecutar API

uvicorn api.main:app --reload

## Ejecutar Tests

pytest

## Estructura

engine/ → Motor determinístico  
services/ → Servicios PDF, Excel, Logging  
api/ → Microservicio FastAPI  
tests/ → Pruebas unitarias  
config/rules.json → Reglas persistentes  
logs/ → Auditoría estructurada  

Preparado para procesamiento masivo (100k PDFs).
