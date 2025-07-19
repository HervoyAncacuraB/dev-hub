---
layout: default
title: Lista de Componentes
has_children: true
nav_order: 3
---

### Lista de Componentes

* DNS
* ELB NUBE
  * AWS ALB: Es la primera línea de defensa y el punto de entrada público. Distribuye el tráfico entrante a las instancias de tu API Gateway. También maneja la terminación SSL/TLS.
  
* ApiGateway Spring Cloud Gateway -> apigateway-ms
  * Autenticación y Autorizacion
  * Limitación de Tasas (Rate Limiting)
  * Seguridad (CORS, CSRF, etc.)
  * Transformación de Solicitudes/Respuestas
  * Caching
  * Logging de Acceso
* EurekaServer(Service Registry)  -> eureka-server-ms
