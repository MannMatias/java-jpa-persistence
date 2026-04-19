# 🗄️ Persistencia con JPA & H2

Aplicación Java que implementa persistencia de datos usando **JPA (Java Persistence API)** con base de datos embebida H2. Demuestra el mapeo objeto-relacional (ORM), creación de entidades y operaciones básicas sobre la base de datos.

## 🛠️ Tecnologías

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

**Dependencias:** JPA (Hibernate), H2 Database, Gradle

## 📋 Funcionalidades

- Mapeo de entidades Java a tablas relacionales con anotaciones JPA
- Configuración de `persistence.xml` para la conexión con H2
- Creación y consulta de registros en base de datos embebida
- Verificación de datos desde la consola H2

## 🚀 Cómo ejecutar

**Requisitos:** IntelliJ IDEA, H2 Database instalado

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/MannMatias/java-jpa-persistence
   ```
2. Abrir en IntelliJ IDEA: `File > Open` → seleccionar la carpeta del proyecto
3. Iniciar el servidor H2 (`h2.bat` o `h2.sh`)
4. Conectarse a la consola H2 con:
   - **JDBC URL:** `jdbc:h2:tcp://localhost/~/test`
   - **User:** `sa` | **Password:** *(vacío)*
5. Ejecutar `Main.java` con click derecho → `Run 'Main.main()'`
6. Verificar los datos creados en la consola H2:
   ```sql
   SELECT * FROM ARTICULO;
   ```

## 📚 Contexto

Proyecto desarrollado para la materia **Desarrollo de Software** — UTN FRM.
