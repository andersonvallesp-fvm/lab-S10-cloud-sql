# Caso 1: Interacción entre Base de Datos Cloud SQL (SQL Server) y Entorno Local

## 📌 Descripción del Trabajo
Este proyecto demuestra la configuración, gestión e interacción entre una base de datos hospedada en la nube mediante **Google Cloud Platform (Cloud SQL)** y la herramienta de administración local **SQL Server Management Studio (SSMS)**.

## 🛠️ Especificaciones Técnicas
* **Plataforma Cloud:** Google Cloud Platform (GCP)
* **Servicio:** Cloud SQL
* **Motor BD:** Microsoft SQL Server
* **Nombre de Instancia:** `bd_ventas_cloud`
* **Base de Datos Inicial:** `ventas_online`

---

## 🚀 Pasos Desarrollados

### 1. Despliegue de Instancia en la Nube
1. Se ingresó a la consola de GCP y se seleccionó el servicio **Cloud SQL**.
2. Se configuró la instancia para SQL Server denominada `bd_ventas_cloud`.
3. Se creó la base de datos `ventas_online`.

### 2. Conexión Remota y Scripting SQL
A través de la dirección IP pública asignada a la instancia, se estableció conexión segura desde **SSMS** para ejecutar la creación de tablas, vistas, procedimientos almacenados e inserciones locales.
