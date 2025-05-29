# Autores

David Styvenn Barcos Jurado
Jarrinson Osnaider Perea Perea
Kevin Yersey Vaquiro Castiblanco

# Sistema de Control de Reciclaje por Familias

Este proyecto simula un sistema de control y registro de materiales reciclados por familias en zonas como Ciudad Bolívar, donde se promueve el reciclaje como alternativa de ingreso y mejora ambiental.

## 🧩 Contexto

En muchas comunidades, el reciclaje no solo es una necesidad ambiental, sino también una forma de sustento para muchas familias. Sin embargo, no existen herramientas digitales que permitan registrar, incentivar y monitorear la participación activa de los ciudadanos en estas prácticas. Este proyecto nace como una solución básica y funcional a este problema, permitiendo llevar un registro detallado de los materiales reciclados por cada familia.

## 🎯 Objetivo

Simular un sistema que permita:
- Registrar familias recicladoras con sus respectivos datos.
- Registrar materiales reciclados indicando tipo, peso y fecha.
- Calcular puntos o beneficios por tipo de material.
- Generar reportes resumidos de materiales reciclados por cada familia.

## ⚙️ Estructura del Proyecto

- `codigo_base.py`: contiene las clases principales del sistema (`Familia`, `MaterialReciclado`, `SistemaReciclaje`) y su lógica de funcionamiento.
- `main.py`: script principal que ejecuta un menú interactivo para la gestión del sistema.
- `README.md`: documentación completa del proyecto, requisitos y guía de uso.

## 📦 Cómo ejecutar

1. Asegúrate de tener Python 3 instalado en tu sistema.
2. Descarga los archivos `codigo_base.py`, `main.py` y `README.md`.
3. Colócalos en la misma carpeta o directorio.
4. Abre una terminal en esa carpeta y ejecuta el sistema con:

## 📋 Funcionalidades del sistema

- **Registrar familias:** Se almacenan nombre, número de integrantes y dirección.
- **Registrar materiales reciclados:** Cada familia puede registrar múltiples materiales con tipo, peso (en kg) y fecha.
- **Cálculo de puntos:** Cada tipo de material otorga una cantidad de puntos específica.
- **Visualización de resumen:** Por cada familia se puede visualizar un resumen de materiales registrados y sus puntos acumulados.

## 🛠️ Requisitos no funcionales

- Programación orientada a objetos, con uso de herencia y polimorfismo (estructurado para futuras extensiones).
- Interacción por consola con menú simple y amigable.
- Comentarios claros en el código para facilitar su lectura y mantenimiento.

## 💡 Ideas para mejorar

- Agregar una interfaz gráfica con Tkinter o una web app con Flask/Django.
- Guardar datos en archivos `.csv` o una base de datos SQLite.
- Incluir autenticación y estadísticas globales de reciclaje.

---

Desarrollado con fines académicos y educativos. ¡Reciclar es una forma de cuidar el planeta y apoyar a quienes más lo necesitan! 🌱
