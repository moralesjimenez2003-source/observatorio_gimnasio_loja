# Observatorio de gimnasios del centro de Loja

Análisis de precios y promociones de membresías mensuales de gimnasios ubicados en el centro de Loja, Ecuador. Proyecto integrador de Programación Aplicada a la Inteligencia de Mercados (UIDE Loja).

## Pregunta de negocio

¿Cómo se compara el precio de la membresía mensual estándar de nuestro gimnasio con el de cuatro gimnasios competidores del centro de Loja y qué promociones ofrece cada uno durante cada mes?

## Quién decide y qué decisión apoya

- **Quién decide:** el gerente comercial del gimnasio.
- **Decisión:** decidir si se mantiene o ajusta el precio de la membresía mensual y si se implementan promociones para atraer nuevos clientes y mejorar la competitividad del gimnasio.

### Importancia para el decisor

Conocer la posición de precio frente a la competencia permite al gerente evitar cobrar de más (y perder clientes) o de menos (y perder ingresos), y detectar qué promociones usan los competidores en cada mes para reaccionar a tiempo.

## Alcance

- Se compara únicamente la **membresía mensual estándar**: acceso general a las instalaciones, sin servicios personalizados.
- Se excluyen planes trimestrales, semestrales o anuales, y servicios adicionales como entrenador personal, nutricionista o clases privadas.
- Se analizan cuatro gimnasios competidores ubicados en el centro de Loja.

## Indicadores

- Precio promedio mensual de las membresías estándar de los cuatro gimnasios competidores.
- Diferencia porcentual entre el precio de nuestra membresía y el precio promedio de la competencia.
- Número de promociones de inscripción y membresías publicadas por los competidores cada mes.

## Fuentes previstas

- Páginas oficiales de Facebook e Instagram de los gimnasios competidores.
- Sitios web oficiales y perfiles de Google Maps de los gimnasios.
- Consultas directas a los establecimientos para verificar precios y promociones.

Se usan únicamente datos públicos o proporcionados por los propios establecimientos al ser consultados; no se recopilan datos personales.

## Supuestos

1. **Validación del precio.** Cuando un gimnasio no publica sus tarifas en redes sociales ni en la web, se asumirá como precio válido el valor obtenido mediante contacto directo (llamada o mensaje) o visita presencial al establecimiento.
2. **Comparabilidad de planes.** Se consideran planes estándar de membresía mensual, sin incluir servicios personalizados (como entrenador personal o nutricionista), para asegurar una comparación real entre gimnasios.

## Limitaciones

- Los precios y promociones pueden cambiar sin aviso entre la fecha de recolección y la de análisis.
- **Tratamiento de datos faltantes o desactualizados.** Si de un competidor no se logra obtener un dato vigente del mes (precio sin confirmar o información desactualizada), ese competidor se **omitirá del cálculo del promedio de ese mes**; no se mantendrá su último precio registrado. En el reporte se indicará cuántos gimnasios entraron en cada promedio y cuáles quedaron como "sin dato".
- Al trabajar con cuatro competidores, omitir uno reduce de forma notable la muestra, por lo que los promedios deben leerse con cautela.

## Estructura del proyecto

- `data/raw/`: datos originales (no se modifican)
- `data/processed/`: datos limpios
- `notebooks/`: cuadernos de análisis
- `src/`: funciones reutilizables
- `reports/`: resultados para quien decide
- `pyproject.toml`: dependencias del proyecto

## Cómo ejecutar

Abrir el cuaderno en Google Colab y usar **Entorno de ejecución > Reiniciar sesión y ejecutar todo**.

## Declaración de uso de IA
Utilicé ChatGPT como herramienta de IA generativa para organizar la pregunta de negocio, proponer indicadores y redactar el README. Verificaré los precios y las promociones mediante las fuentes originales antes de utilizarlos en el análisis.

