# 📣 ForoHub 🌐 Challenge

**ForoHub** es una aplicación de foro en línea desarrollada con **Spring Boot**, como parte del Challenge de **Alura Latam**.  
Permite gestionar usuarios, cursos y tópicos, con autenticación y seguridad integrada.

## 💼 Dominio  
El paquete **Dominio** contiene las **entidades principales**, sus **repositorios** y **objetos de transferencia de datos (DTOs)** que representan y manipulan la información clave del foro: **cursos**, **tópicos** y **usuarios**.  
Aquí se encuentra la **lógica de negocio** que conecta la base de datos con el resto de la aplicación, garantizando que las **reglas** y **validaciones** se apliquen antes de procesar o devolver datos.

---

## 📖 Descripción del Proyecto  
**ForoHub** es una **API REST** desarrollada con **Spring Boot** que permite gestionar **cursos**, **usuarios** y **tópicos** en un foro en línea.  
Incluye:
- 🔐 **Autenticación** con JWT y control de accesos con Spring Security.  
- ⚠️ **Manejo centralizado de errores** para respuestas consistentes.  
- 📄 **Documentación automática** de la API con Springdoc OpenAPI.  

Su arquitectura está organizada en capas para:
- 📦 **Separar responsabilidades**.  
- 🔧 **Facilitar el mantenimiento**.  
- 📈 **Permitir escalabilidad**.  

