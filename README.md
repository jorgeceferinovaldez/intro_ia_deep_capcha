# Especialización en Inteligencia Artificial

# Asignatura: Introduccióna la Inteligencia Artificial
# Trabajo grupal

Josselyn Ordoñez - Tatiana Arenas - Javier Cambiasso - Jorge Valdez

# Deep-CAPTCHA
El paper presenta Deep-CAPTCHA, un sistema basado en deep learning para resolver CAPTCHAs automáticamente. Los CAPTCHAs son pruebas utilizadas en sitios web para determinar si el usuario es humano o un bot. 

Deep-CAPTCHA utiliza redes neuronales convolucionales para analizar y resolver imágenes CAPTCHA. El sistema fue entrenado con un gran conjunto de datos de imágenes CAPTCHA sintéticas generadas automáticamente. 

En las pruebas, Deep-CAPTCHA logró una tasa de éxito de 85% resolviendo CAPTCHAs de texto y 70% resolviendo CAPTCHAs de imágenes. Esto demuestra que los CAPTCHAs existentes pueden ser vulnerables a ataques automatizados con deep learning.

Los autores proponen que los resultados exponen una debilidad en la seguridad de los CAPTCHAs actuales. Sugieren que nuevos CAPTCHAs más robustos deben ser desarrollados, posiblemente incorporando otros problemas AI-hard además del reconocimiento de imágenes.

En resumen, el paper presenta un nuevo enfoque con deep learning para resolver CAPTCHAs automáticamente, demostrando vulnerabilidades en los CAPTCHAs existentes. Los autores recomiendan mejoras en el diseño de CAPTCHAs para prevenir futuros ataques.

## ¿Como ejecutarlo?
Las siguientes librerías son necesarias para la ejecución del código:
- captcha 
- opencv-python
- opencv-python-headless
- opencv-contrib-python-headless
- keras

## Paper original
- Basado en el paper [Deep-CAPTCHA: a deep learning based CAPTCHA solver for vulnerability assessment](https://arxiv.org/abs/2006.08296)
