# CI-Node_RED

## Integración continua de Node-RED en el servidor de telemetría

Este es el repositorio de la instancia de Node-RED que corre en el servidor de telemetría.

## Implementación 

Node-RED corre dentro de una instancia de docker compose, la misma está declarada dentro del docker-compose.yaml y está controlada por Jenkins, que se encarga de escuchar por actualizaciones en este repositorio y de haber alguna, actualizar el proceso para que corra en la ultima versión de este repositorio. 
