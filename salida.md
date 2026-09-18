Basado en el modelo canónico proporcionado, aquí tienes una tabla con tres de las entidades principales, sus rutas en la estructura de archivos y sus descripciones:

| Entidad | Carpeta en el modelo | Descripción |
| :--- | :--- | :--- |
| **Customer (Cliente)** | `customers/` | Representa a los clientes (usuarios del servicio) que consumen la infraestructura y los servicios gestionados. El modelo MVP define 3 clientes sintéticos. |
| **Workload (Carga de trabajo)** | `workloads/` | Son las aplicaciones, sistemas o tareas específicas que ejecuta un cliente. En este modelo, cada cliente tiene asignadas exactamente 2 cargas de trabajo (6 en total). |
| **Environment (Entorno)** | `environments/` | Define los entornos específicos de cada cliente (como producción, desarrollo, pruebas, etc.) donde se despliegan y ejecutan las instancias de los servicios. |
