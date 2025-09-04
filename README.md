# Calculo-de-Suma-Fija-NR

Script para Cálculo de Asignación Fija No Remunerativa
Este repositorio contiene un script de Google Colab diseñado para automatizar el cálculo de la asignación fija no remunerativa, basándose en la nómina de empleados. El script procesa un archivo Excel de entrada y genera un archivo de resultados con los valores proporcionales que deben liquidarse.

📋 Características principales
Cálculo proporcional: Determina el valor de la asignación fija para personal con jornadas parciales.

Gestión de reglas: Aplica reglas de cálculo específicas para los convenios de Sanidad (108/75) y personal fuera de convenio.

Filtrado inteligente: Solo incluye en el resultado final los casos que requieren un cálculo proporcional (valores menores a $60,000), excluyendo automáticamente a los empleados que cobran el monto completo.

🚀 ¿Cómo usar el script?
Abre el archivo Calculo_Suma_Fija_NR.ipynb directamente en Google Colab.

Ejecuta la primera celda para iniciar el proceso.

Sube tu archivo de nómina en formato Excel cuando el script lo solicite.

El script procesará los datos y, al finalizar, te proporcionará un archivo de resultados para descargar.
