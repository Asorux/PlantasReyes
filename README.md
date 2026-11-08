# Plantas Reyes

Sitio web de e-commerce de plantas (catalogo, carrito, login/registro, pagos) hecho como **Proyecto Modular UDG CUCEI 2024B**, en equipo.

- **Stack:** PHP, PostgreSQL, JavaScript, Bootstrap
- **Extra:** modulo de recomendaciones con machine learning (ALS) en `machine_learning_ALS/`

## Equipo
Proyecto grupal. El historial de commits conserva la autoria de cada integrante (MaxCesni7, Omar, eliso10, Martinete2710, anafergal, Ingrid Bergman, juliorecillas, Asorux).
Repositorio original del equipo: https://github.com/CopyDawg/Proyecto-Modular-2024B

## Como correrlo
1. Crear una base PostgreSQL llamada `Plantas.Reyes.M`.
2. En `conexion.php` y `pages/usuarios.php` poner tu usuario y password de PostgreSQL (`TU_PASSWORD_AQUI`).
3. Servir la carpeta con PHP (`php -S localhost:8000`) y abrir `index.php`.
