
📌 **Ventajas**
- Se ve bonito en GitHub
- Es profesional
- Muy usado en proyectos reales
- No necesitas imágenes

---

## ✅ OPCIÓN 2: Diagrama ASCII (simple y compatible)

Si prefieres **texto plano**, usa esta versión (más corta y estable):


## 🧩 Arquitectura del Sistema

Frontend (Angular)
        |
        v
API Gateway (Spring Boot)
        |
        v
Eureka Server
        |
        +-------------------------------+
        |              |                |
  Huéspedes      Habitaciones        Reservas
        |
        v
    Oracle DB

Authorization Server:
- Maneja autenticación y JWT
- Funciona de manera independiente
