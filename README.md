# Backend Lab

Aplicación interactiva en español para organizar y practicar entrevistas de backend y arquitectura.

## Ejecutar

No requiere compilación ni dependencias. Desde esta carpeta:

```bash
python3 -m http.server 8080
```

Abre http://localhost:8080 en el navegador.

## Contenido

- Panel de dominio autoevaluado por Java, Spring Boot, microservicios, AWS, Docker, Kubernetes, Kafka, CI/CD, GitOps, React, Python, Go, Linux y arquitectura de sistemas.
- Tarjetas y ejercicios editables, filtros por tecnología, nivel y estado.
- Simulaciones escritas con rúbrica de claridad e historial.
- Registro de experiencias reales: proyectos, migraciones, rendimiento, escalabilidad y validación.
- Procesos de entrevista duplicables que reutilizan el contenido.
- Respaldo JSON mediante exportación e importación.

## Persistencia y límites

El progreso se guarda en localStorage de cada navegador y dominio. No hay sincronización en nube. Exporta un respaldo antes de cambiar de dispositivo o alojamiento, e impórtalo en el nuevo navegador.

La retroalimentación usa reglas locales de longitud, estructura y señales textuales. No usa un modelo de IA ni verifica exactitud técnica. Los ejercicios incluyen soluciones de referencia y no ejecutan código. El dominio es autoevaluado.

## Publicar

Puede servirse en cualquier alojamiento estático. Para GitHub Pages, configura Settings → Pages → Deploy from a branch → main → / (root). La disponibilidad en repositorios privados depende del plan. Revisa la visibilidad del sitio antes de publicarlo; no contiene autenticación propia.

## Estructura

- index.html: estructura de la aplicación.
- style.css: diseño responsive.
- app.js: contenido inicial, lógica y persistencia.

No incluye credenciales, respuestas personales de práctica ni archivos internos de Sites.
