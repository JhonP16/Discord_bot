# Bot de Bienvenida y Comandos para Discord

Un bot automatizado para servidores de Discord que gestiona la bienvenida de nuevos miembros y responde a comandos básicos predefinidos.

## 📋 Descripción

Este proyecto automatiza dos tareas fundamentales en la gestión de servidores de Discord:
- **Bienvenida automática**: Envía mensajes personalizados cuando un nuevo miembro se une al servidor
- **Comandos básicos**: Responde automáticamente a comandos predefinidos como reglas, información del servidor, etc.

El objetivo es ahorrar tiempo a los administradores y moderadores, eliminando tareas repetitivas y mejorando la experiencia de los nuevos usuarios desde el primer momento.

## 🎯 Problemática

En muchos servidores de Discord, los moderadores constantemente realizan las mismas tareas manuales:
- Dar la bienvenida a cada nuevo miembro
- Responder preguntas repetidas ("¿cuáles son las reglas?", "¿dónde está la información?")
- Proporcionar información básica del servidor

Este bot automatiza estas interacciones, haciendo el proceso más eficiente y consistente.

## ✨ Funcionalidades

- ✅ Conexión segura y autenticación con la API de Discord
- ✅ Mensaje de bienvenida automático para nuevos miembros
- ✅ Respuesta a comandos básicos (`!hola`, `!info`, `!reglas`)
- ✅ Gestión segura del token mediante variables de entorno
- ✅ Sistema de logging para monitorear la actividad del bot
- ✅ Configuración personalizable de mensajes y comandos

## 🚀 Tecnologías Utilizadas

### Lenguaje
- Python 3.8+

### Librerías Principales

- **discord.py**: Librería esencial para interactuar con la API de Discord. Permite conectar el bot, escuchar eventos y gestionar mensajes.
- **python-dotenv**: Gestión segura de credenciales mediante archivos `.env`, evitando exponer el token del bot en el código.

## 🎓 Conceptos de Python Aplicados

- **Variables y tipos de datos**: Almacenamiento de tokens, IDs de canales y mensajes
- **Estructuras de control**: Validación de comandos y gestión de eventos
- **Funciones**: Modularización del código en funciones reutilizables
- **Manejo de archivos**: Lectura de configuración desde `.env`
- **Manejo de errores**: Try/except para gestionar errores de conexión y API
- **Programación asíncrona**: Uso de async/await para eventos de Discord

## 🚧 Limitaciones

**El proyecto NO incluye:**
- ❌ Funciones de moderación avanzada (baneos, kicks, mutes)
- ❌ Integración con otras APIs externas
- ❌ Interfaz gráfica o web
- ❌ Sistema de base de datos

Estas limitaciones están definidas intencionalmente para mantener el proyecto enfocado en el aprendizaje fundamental de APIs y automatización.

## 👥 Autores

- **Andrés Felipe Eusse**
- **Jhon Jairo Pulgarín**

## 📚 Proyecto Académico

Este proyecto fue desarrollado como parte del curso **Python de 0 a 100**.

**Fecha de inicio:** 21 de octubre de 2025

**Categoría:** Automatización

## 📝 Licencia

Este proyecto es de código abierto y está disponible para fines educativos.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request


⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub!
