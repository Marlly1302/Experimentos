Gestor de Proyectos Experimentales
📋 Descripción General
Este sistema permite a los investigadores gestionar experimentos científicos en diferentes áreas como Química, Biología y Física, proporcionando una interfaz para agregar, analizar y comparar experimentos. Además, permite la generación de informes detallados que incluyen estadísticas de los resultados, como el promedio, máximo y mínimo.

🎯 Características

Gestión de Experimentos
Agregar nuevos experimentos con información detallada
Visualizar todos los experimentos en una tabla formateada
Eliminar experimentos del sistema
Análisis de Datos
Calcular estadísticas básicas (media, máximo, mínimo) de los resultados
Comparar múltiples experimentos para identificar los mejores y peores resultados
Generar informes completos en formato TXT
Validación de Datos
Validación de entrada para fechas, resultados numéricos y categorías
Manejo de errores para entradas inválidas
Restricciones de categoría para mantener la consistencia de datos
🔧 Requisitos Técnicos

Python 3.x
Bibliotecas requeridas:
datetime
statistics
prettytable
📦 Instalación

Clonar el repositorio:
bash
Copiar código
git clone https://github.com/Marlly1302/Experimentos
Instalar dependencias requeridas:
Copiar código
pip install prettytable
🚀 Uso
Ejecutar el Programa:

css
Copiar código
python main.py
Opciones del Menú Principal

Agregar experimentos
Ver todos los experimentos
===== MANEJO DE DATOS =====
Análisis de resultados
Comparar los experimentos
Generar Informes de experimentos
Borrar un experimento
== 7. Salir del programa ==
Función de las Opciones del Menú

Agregar Experimentos
Ingresar nombre del experimento
Introducir fecha (formato DD/MM/AAAA)
Seleccionar categoría (Biología, Física, Química)
Ingresar resultados numéricos (separados por comas)
Visualizar Experimentos
Muestra todos los experimentos en una tabla formateada
Presenta ID, nombre, fecha, categoría y resultados
Eliminar Experimentos
Eliminar experimentos por ID
Validación para prevenir eliminaciones inválidas
Calcular Estadísticas
Calcula valores medio, máximo y mínimo
Resultados mostrados en una tabla formateada
Comparar Experimentos
Seleccionar múltiples experimentos por ID
Comparar métricas estadísticas
Identificar mejores y peores resultados
Generar Informe
Crea informe_experimentos.txt
Incluye estadísticas completas
Documenta mejores y peores resultados
📊 Ejemplo de Uso

Agregar un Experimento
=== MENU PRINCIPAL ===

Agregar experimentos
Ingrese el nombre del experimento: Prueba de Temperatura
Ingrese la fecha: 18/11/2024
Ingrese la categoría: Física
Ingrese los resultados: 98.6, 99.1, 98.9, 99.2

Visualizar Estadísticas
Resultados experimentos:
+----------+--------------+--------------+
| Promedio | Maximo Valor | Minimo Valor |
+----------+--------------+--------------+
| 98.95 | 99.2 | 98.6 |
+----------+--------------+--------------+

📝 Estructura del Código
Componentes Principales

Clase Experimento: Estructura de datos central
Sistema de menú: Interfaz interactiva de línea de comandos
Validación de datos: Verificación de entradas y manejo de errores
Análisis estadístico: Funciones de cálculo y comparación
Generación de informes: Exportación de datos y creación de resúmenes
Funciones Principales

agregarExperimento(): Añade nuevos experimentos con validación
visualizarExperimentos(): Muestra datos formateados de experimentos
calcularEstadisticas(): Calcula estadísticas básicas
compararExperimentos(): Analiza múltiples experimentos
generaInforme(): Crea informes detallados
⚠️ Validación de Entrada
El sistema incluye validación completa de entradas:

Verificación del formato de fecha (DD/MM/AAAA)
Validación de categorías contra opciones predefinidas
Validación de datos numéricos para resultados
Verificación de rango de índices para selección de experimentos
📝 Formato del Informe
El informe generado (informe_experimentos.txt) incluye:

Información detallada de experimentos
Análisis estadístico
Comparaciones de rendimiento
Mejores y peores resultados para cada métrica
🤝 Contribuciones
¡Las contribuciones son bienvenidas! Por favor, siéntase libre de enviar pull requests.

📄 Licencia
Este proyecto es de código abierto y está disponible bajo la Licencia MIT.

👥 Autores
Marlly Lorena Plazas Quiñones
Eder Ferney Montealegre Valero

📚 Historial de Versiones
1.0.0

Lanzamiento inicial
Gestión básica de experimentos
Funciones de análisis estadístico
Generación de informes
