# Ciencia de Datos con Python - Semana 1

Proyecto del Aprendiz para la guía **GFPI-F-135 - Semana 1: Ciencia de Datos con Python (SENA, actualización 2026)**.

## Propósito

Preparar un ambiente de trabajo reproducible y comprender el valor de los datos
para apoyar decisiones: del dato a la información, del análisis a la acción y
de la ética a la evidencia.

## ¿Qué contiene este proyecto?

| Archivo / carpeta | Descripción |
|---|---|
| `data/raw/` | Datos originales (no se modifican) |
| `data/processed/` | Datos procesados y limpios |
| `notebooks/semana_01_contexto_ambiente.ipynb` | Notebook de verificación del ambiente |
| `outputs/verificacion_ambiente_salida.txt` | Salida del script de verificación |
| `docs/actividad_semana01.md` | Actividades resueltas: diagnóstico, matriz dato-información-decisión, preguntas analíticas, bitácora y matriz de variables |
| `scripts/verificacion_ambiente.py` | Primer script de verificación |
| `requirements.txt` | Dependencias instaladas (pandas, numpy, jupyter, openpyxl, faker) |
| `README.md` | Este documento |

## Estructura del proyecto

```
ciencia de datos python/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── semana_01_contexto_ambiente.ipynb
├── outputs/
│   └── verificacion_ambiente_salida.txt
├── docs/
│   └── actividad_semana01.md
├── scripts/
│   └── verificacion_ambiente.py
├── README.md
└── requirements.txt
```

## Cómo ejecutar la verificación del ambiente

Desde la carpeta `scripts`:

```powershell
python verificacion_ambiente.py
```

Salida esperada (real, guardada en `outputs/`):

```
Ambiente listo para iniciar Ciencia de Datos con Python
Python: 3.14.7
Pandas: 3.0.6
NumPy: 2.5.3
Verificada: .../data/raw
...
```

> Nota: el ambiente quedó configurado de forma permanente:
> - `python` → `C:\Python314\python.exe` (Python 3.14.7)
> - Librerías en `C:\Users\Sena\AppData\Local\Programs\Python\Python314`
> - `PYTHONHOME` y PATH se configuraron con `setx`: abre una terminal nueva y funcionará.
> - En VS Code: cierra y vuelve a abrir la terminal para que tome la configuración.
> Si tuviera problemas, reinstala dependencias con: `pip install -r requirements.txt`.

## Actividades de la guía (resueltas en `docs/actividad_semana01.md`)

1. **3.1 Reflexión del dato a la decisión:** matriz con mínimo 4 situaciones.
2. **3.2 Diagnóstico de saberes previos:** cuestionario respondido + autoevaluación.
3. **3.3 Contexto actual:** síntesis empleada en la bitácora y en la matriz de conceptos.
4. **3.4 Ciclo de vida del dato:** fases pregunta → fuente → exploración → calidad → análisis → comunicación → acción.
5. **3.5 Caso integrador:** matriz de variables y 5 preguntas analíticas.
6. **3.6 Ambiente reproducible:** esta carpeta, con estructura, `requirements.txt` y README.
7. **3.7 Script de verificación:** implementado en `scripts/` y en el notebook.
8. **3.8 Cierre y socialización:** bitácora incluida en el documento de actividades.

## Conceptos clave vistos en la Semana 1

- **Dato:** registro bruto (ej.: 68%).
- **Información:** dato organizado y contextualizado.
- **Conocimiento:** interpretación que permite comprender.
- **Decisión:** acción basada en evidencia.
- **Reproducibilidad:** repetir el análisis con instrucciones, datos y dependencias documentadas.
- **Ética de datos:** privacidad, contexto, transparencia y no discriminación.

## Buenas prácticas

1. No modificar directamente los datos originales (`data/raw`).
2. Documentar cada decisión relevante.
3. Proteger datos personales: no usar documentos reales ni datos sensibles.
4. Usar rutas relativas.
5. Mantener el notebook ordenado y comentado.
6. Nombrar archivos con claridad: `semana_01_diagnostico.ipynb`, no `prueba2_ultima_ahora_si.ipynb`.
7. Usar la IA generativa como apoyo, nunca como sustituto del criterio técnico.

## Criterios de evaluación atendidos

- **Conocimiento:** diagnóstico diligenciado y autoevaluación.
- **Desempeño:** participación y formulación de preguntas analíticas.
- **Producto:** estructura del proyecto, README, ambiente configurado y matriz de variables.
- **Rúbrica:** comprensión del valor del dato, ética y privacidad, ambiente reproducible y comunicación.

## Referentes

- SENA. Normograma: Acuerdo 9 de 2024.
- Python Software Foundation. Python Documentation.
- Pandas Development Team. Pandas Documentation.
- Project Jupyter. Jupyter Documentation.
- World Economic Forum. The Future of Jobs Report 2025.
- Ministerio TIC Colombia. Datos abiertos y CONPES 4144.
