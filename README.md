### README In production

#### Other microservices for this project:
##### https://github.com/luizfernandorg/usuario
##### https://github.com/luizfernandorg/notificacao
##### https://github.com/luizfernandorg/bff-agendador-tarefas (in production)

## Installation

To install this project, follow the steps below. Before starting the service, ensure that the other services are running with
their respective databases.
This service does not include a frontend page; it's a Java backend only. Therefore, using Postman is recommended for testing.
The project is also documented, accessible on [http](http://localhost:8083/swagger-ui/index.html).

```bash
  git clone https://github.com/luizfernandorg/bff-agendador-tarefas.git
  cd bff-agendador-tarefas.git
  mvn exec:java -Dexec.mainClass="com.javanauta.bffagendadortarefas.BffAgendadorTarefasApplication"
```
