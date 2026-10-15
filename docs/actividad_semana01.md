# Actividades resueltas - Semana 1

## 3.1 Matriz dato - información - decisión (mínimo 3 situaciones)

| Situación | Dato | Información | Decisión posible |
|---|---|---|---|
| Seguimiento académico | Asistencia = 68%; promedio = 3.1 | Bajo desempeño y asistencia insuficiente | Programar acompañamiento y revisar barreras |
| Inventario | Stock = 6 unidades; ventas diarias = 4 | El producto se agota en menos de dos días | Solicitar reposición prioritaria |
| Sostenibilidad | Residuos aprovechables = 120 kg/mes | Existe oportunidad de reutilización | Diseñar ruta de aprovechamiento o alianza circular |
| Ventas de un emprendimiento (propia) | 15 pedidos al mes; ticket promedio $20.000 | Los ingresos mensuales son cercanos a $300.000 | Revisar precios y lanzar promoción para aumentar pedidos |

## 3.2 Diagnóstico de aprendizajes previos (respuestas)

1. Un **dato** es un registro bruto que por sí solo no tiene significado (ej.: 68%). La **información** surge cuando esos datos se organizan y se contextualizan (ej.: asistencia del 68% en la ficha).
2. Ejemplos: % de asistencia diaria de aprendices; número de evidencias entregadas por ficha.
3. Un **CSV** (valores separados por comas) es un archivo de texto plano que almacena datos tabulares y se usa para intercambiar información entre aplicaciones (Excel, Python, etc.).
4. En una fila se registra un elemento u observación; en una columna se registra una variable o característica.
5. Para una nota usaría **número decimal** (permite décimas, ej.: 3.8).
6. El riesgo es vulnerar la privacidad de las personas: sanciones legales (Ley 1581 de 2012 en Colombia), pérdida de confianza y discriminación.
7. Ejemplo de pregunta: ¿qué porcentaje de aprendices aprobó la formación?
8. Herramientas: uso básico de Excel y Google Sheets para tablas y gráficos.
9. Un dato incompleto es el que tiene campos vacíos; duplicado es cuando aparece más de una vez el mismo registro. Ambos distorsionan el análisis.
10. Espero aprender a analizar datos con Python, aplicar ética y crear reportes para apoyar decisiones.

**Autoevaluación inicial (1 a 4):** Python 2, Excel/CSV 3, lectura de tablas 3, gráficos 2, ética de datos 2, organización de archivos 3.

## 3.5 Preguntas analíticas del caso integrador (mínimo 5)

1. ¿Cuántos aprendices tienen asistencia menor al 80% y promedio inferior a 3.5?
2. ¿Qué ficha concentra más aprendices con alertas de desempeño?
3. ¿Existe relación entre el porcentaje de asistencia y el promedio de actividades?
4. ¿Cuántos aprendices no han entregado todas las evidencias?
5. ¿Cuáles son las observaciones de acompañamiento más frecuentes?

## Matriz de variables del caso integrador

| Variable | Tipo esperado | Uso posible | Riesgo o cuidado |
|---|---|---|---|
| id_aprendiz | Texto/código | Identificación interna sin exponer documento real | No usar datos sensibles innecesarios |
| ficha | Texto/código | Agrupar resultados por grupo de formación | Evitar comparaciones sin contexto |
| asistencia_porcentaje | Número decimal | Detectar alertas de inasistencia | Verificar causas antes de concluir |
| promedio_actividades | Número decimal | Revisar desempeño académico | No reducir el aprendizaje a una sola nota |
| evidencias_entregadas | Número entero | Medir avance en productos | Validar calidad, no solo cantidad |
| observacion | Texto | Registrar comentario de acompañamiento | Evitar lenguaje discriminatorio o subjetivo |

## 3.8 Bitácora de cierre

- **Qué entiendo por ciencia de datos:** el proceso de convertir datos en evidencia para apoyar decisiones, con ética y rigor técnico.
- **Pregunta analítica más importante:** ¿qué aprendices requieren acompañamiento preventivo?
- **Dificultad técnica inicial:** configurar el entorno e instalar dependencias.
- **Compromiso:** proteger los datos personales, no modificar los datos originales y documentar cada decisión.

## Reflexión sobre ética, privacidad y uso responsable

Los datos personales requieren autorización, minimización (usar solo lo necesario), trazabilidad y confidencialidad. Se evitan comparaciones sin contexto, etiquetas discriminatorias y conclusiones sin validar. La IA generativa se usa como apoyo, no como sustituto del criterio técnico.
