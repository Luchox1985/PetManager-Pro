# "PetManager Pro: Gestión Robusta de Datos"

# El Origen del Proyecto
Como dueño de tres mascotas y analista de datos, me di cuenta de que la información veterinaria suele estar dispersa. Decidí aplicar mis conocimientos de ingeniería para crear una herramienta que no solo guarde datos, sino que lo haga de forma segura y persistente.

Este es mi primer proyecto integrando los fundamentos de la **Ingeniería en Informática**, enfocado en la integridad de la información y la experiencia de usuario.

# Lo que hace especial a este software
No es solo un registro de nombres. He aplicado principios de arquitectura de software para asegurar su calidad:

* **Persistencia Real:** Los datos no se pierden al cerrar el programa gracias a un motor de persistencia basado en JSON.
* **A prueba de errores:** Implementé validaciones estrictas. El sistema guía al usuario y evita que el programa falle si se ingresan datos incorrectos (Robustez).
* **Identidad Única:** Cada mascota recibe un ID único generado por algoritmo, evitando duplicidad de registros (Integridad de Datos).
* **Arquitectura Modular:** Separé la lógica de almacenamiento de la interfaz, permitiendo que el sistema crezca fácilmente en el futuro.

## Tecnologías utilizadas
* **Python 3.x**
* **JSON** para la base de datos local.
* **Módulos Nativos:** `os`, `datetime`, `json`.

##  Cómo probarlo
1. Clona este repositorio.
2. Ejecuta `python main.py`.
3. ¡Registra a tu primera mascota y observa cómo se crea el archivo `mascotas.json` automáticamente!

---
*Proyecto desarrollado como parte de mi ruta hacia la especialización en Ciberseguridad.*

