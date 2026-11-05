# Observatorio de gimnasios del centro de Loja

Análisis de precios y promociones de membresías mensuales de gimnasios ubicados en el centro de Loja, Ecuador. Proyecto integrador de Programación Aplicada a la Inteligencia de Mercados (UIDE Loja).

## Pregunta de negocio
¿Cómo se compara el precio de la membresía mensual de nuestro gimnasio con el de cuatro gimnasios competidores del centro de Loja y qué promociones ofrece cada uno durante cada mes?

## Quién decide y qué decisión apoya
- **Quién decide:** El gerente comercial del gimnasio.
- **Decisión:** Decidir si se mantiene o ajusta el precio de la membresía mensual y si se implementan promociones para atraer nuevos clientes y mejorar la competitividad del gimnasio.

## Indicadores
- Precio promedio mensual de las membresías de los cuatro gimnasios competidores.
- Diferencia porcentual entre el precio de nuestra membresía y el precio promedio de la competencia.
- Número de promociones de inscripción y membresías publicadas por los competidores cada mes.

## Fuentes previstas
- Páginas oficiales de Facebook e Instagram de los gimnasios competidores.
- Sitios web oficiales y perfiles de Google Maps de los gimnasios.
- Consultas directas a los establecimientos para verificar precios y promociones.

## Estructura del proyecto
- `data/raw/`: datos originales (no se modifican)
- `data/processed/`: datos limpios
- `notebooks/`: cuadernos de análisis
- `src/`: funciones reutilizables
- `reports/`: resultados para quien decide
- `pyproject.toml`: dependencias del proyecto

## Cómo ejecutar
Abrir el cuaderno en Google Colab y usar *Entorno de ejecución > Reiniciar sesión y ejecutar todo*.

## Declaración de uso de IA
Utilicé ChatGPT como herramienta de IA generativa para organizar la pregunta de negocio, proponer indicadores y redactar el README. Verificaré los precios y las promociones mediante las fuentes originales antes de utilizarlos en el análisis.
