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

## Supuestos y limitaciones
- Supuesto 1 es que los cuatro gimnasios competidores del centro de Loja mantienen información sobre sus precios y promociones en redes sociales, sitios web u otros canales de comunicación, permitiendo recopilar y actualizar estos datos mensualmente.
- Supuesto 2 es que que las membresías mensuales de los gimnasios seleccionados ofrecen servicios y condiciones relativamente similares, facilitando la comparación de precios y la identificación de diferencias competitivas.
- Limitación es la información de algunos gimnasios puede ser incompleta o estar desactualizada, debido a que no todos publican sus precios y promociones en medios digitales o actualizan oportunamente sus canales de comunicación.
¿Por qué importa para el decisor?
Esta información es importante para el gerente comercial porque le permitirá evaluar la competitividad de los precios de su gimnasio y establecer promociones adecuadas para atraer nuevos clientes. No obstante, deberá verificar los datos recopilados antes de modificar sus precios o implementar estrategias comerciales, evitando tomar decisiones basadas en información incompleta o desactualizada.
