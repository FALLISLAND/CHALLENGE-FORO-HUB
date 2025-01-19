# Proyecto: API REST de Foro con Java, Spring Boot y MySQL

## 🚀 Descripción

Este proyecto consiste en crear una **API REST** para un foro, donde las personas usuarias puedan:

1. **Listar tópicos**: Ver todos los temas creados.
2. **Crear tópicos**: Agregar nuevos temas al foro.
3. **Eliminar tópicos**: Eliminar temas específicos.
4. **Autenticarse**: Usar JWT para garantizar que solo usuarios autenticados puedan realizar acciones como crear o eliminar tópicos.

---

## 🛠️ Tecnologías

- **Java 11+**
- **Spring Boot**
- **JWT** (autenticación)
- **Base de datos** (MySQL)
- **Insomnia/Postman** (pruebas)

---

## 🔗 Endpoints principales

- **Autenticación**:  
  `POST /auth` → Obtiene un token JWT con email y contraseña.

- **Tópicos**:  
  - `GET /topicos` → Lista todos los tópicos.  
  - `POST /topicos` → Crea un nuevo tópico (requiere token).  
  - `DELETE /topicos/{id}` → Elimina un tópico (requiere token).

---

## 📝 Recomendaciones

- Usa **Trello** para organizar tareas y gestionar el proyecto.
- Asegúrate de probar los endpoints y manejar códigos de estado HTTP correctamente (`200`, `201`, `403`, `404`).

---

**¡Listo para comenzar!** 🎉
