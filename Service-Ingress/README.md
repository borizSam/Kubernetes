[minikube]
     |
 +---+------------+
 | Ingress       |   (Redirige tráfico basado en el dominio)
 +---+------------+
     |
 +---+------------+
 | Service       |   (Balancea tráfico entre Pods)
 +---+------------+
     |      |      |
  +--+--+  +--+--+  +--+--+
  | POD |  | POD |  | POD |   (3 réplicas de Nginx)
  +-----+  +-----+  +-----+
