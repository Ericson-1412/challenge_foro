# 📣 ForoHub 🌐 Challenge

**ForoHub** es una aplicación de foro en línea desarrollada con **Spring Boot**, como parte del Challenge de **Alura Latam**.  
Permite gestionar usuarios, cursos y tópicos, con autenticación y seguridad integrada.

### 🕹️ **Controller**  
Contiene los controladores que gestionan las solicitudes HTTP y devuelven las respuestas adecuadas:  
- **AutenticacionController** → Maneja la autenticación de usuarios.  
- **CursoController** → Gestiona las operaciones sobre cursos.  
- **TopicoController** → Administra las operaciones sobre tópicos.  
- **UsuarioController** → Gestiona las operaciones sobre usuarios.  

### 💼 **Dominio**  
Contiene las clases de dominio que representan los datos y la lógica de negocio de la aplicación:  
- **curso** → Clases relacionadas con cursos.  
- **topico** → Clases relacionadas con tópicos (entidad, repositorio y DTOs).  
- **usuario** → Clases relacionadas con usuarios (entidad, repositorio y DTOs).  
- **ValidacionExcepcion** → Clase para manejo de excepciones de validación.

