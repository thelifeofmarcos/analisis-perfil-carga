# Análisis de perfil de carga - planta industrial
Análisis de 8760 registros horarios de demanda eléctrica de una planta industrial, con Python y pandas.
## Hallazgos
- Demanda máxima: 666 kW (1 de septiembre, 15:00)
- Consumo anual: 2607.87 MWh
- Factor de carga: 0.447

Descomposición de la carga: 
- Carga base (24/7): 124 kW
- Producción (dos turnos, lunes a sábado): 230 kW
- Climatización (verano, mediodía): 106 kW

## Conclusión

El pico anual coincide con el día laboral, hora de turno y temporada cálida.
La componente de climatización coincide  con las horas de mayor generación solar, lo que favorece un sistema fotovoltaico de autoconsumo.

## Herramientas

Python, pandas, matplotlib, Google Colab
Los datos son un perfil sintético de 8760 registros horarios, generado para simular una planta industrial de dos turnos.
