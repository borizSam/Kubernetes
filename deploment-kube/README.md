```
[minikube]
     |
 +---+---+
 |Deployment|
 +---+---+
     |
 +---+---+---+
 | POD | POD | POD |   (3 réplicas de nginx)
 +---+---+---+
 ```
Deployment: Controla los Pods y garantiza que siempre haya la cantidad deseada.
PODs: Múltiples réplicas de Nginx corriendo en el clúster.