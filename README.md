# config-server-stockmype

**Config Server** (modo nativo) de StockMYPE. Entrega a cada microservicio su conexión a MySQL.

- Puerto: **8888**
- Archivos de configuración: `src/main/resources/config/` (`auth-service.yml`, `producto-service.yml`)
- La contraseña de MySQL se toma de la variable `DB_PASSWORD` (por defecto `root`).

```bash
./mvnw spring-boot:run
```

Ver la configuración servida: http://localhost:8888/producto-service/default
