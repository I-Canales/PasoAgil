# Plan de Pruebas ISO/IEC 25000 - SICOFRON

## Criterios de Calidad Seleccionados
* **Eficiencia:** Capacidad para procesar 50 registros de formularios por minuto en horas punta sin degradación de la infraestructura local.
* **Fiabilidad:** Tolerancia a fallos en alta montaña. Almacenamiento asíncrono en colas locales ante caídas de la red de fibra óptica.
* **Mantenibilidad:** Separación modular de la lógica legal (plazos de 180 y 90 días) mediante microservicios independientes.
* **Portabilidad:** Compatibilidad adaptativa del frontend (Web App para smartphones de usuarios y versión Desktop para funcionarios).

## Métricas y Umbrales de Aceptación
* **Tiempo de Respuesta:** Menor a 2 segundos en el 95% de las búsquedas de patentes.
* **Pérdida de Datos:** 0% de transacciones perdidas en colas de contingencia offline.
* **Tolerancia:** Tiempo de recuperación total (RTO) inferior a 15 minutos ante incidentes leves.