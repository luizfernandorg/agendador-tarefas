### README In production

#### Other microservices for this project:
##### https://github.com/luizfernandorg/usuario
##### https://github.com/luizfernandorg/notificacao
##### https://github.com/luizfernandorg/bff-agendador-tarefas (in production)

## Installation

To install this project, follow the steps below. Before starting the service, ensure that the MongoDB document named 'tarefa' has been created. 
This service does not include a frontend page; it's a Java backend only. Therefore, using Postman is recommended for testing.

```bash
  git clone https://github.com/luizfernandorg/agendador-tarefas.git
  cd agendador-tarefas
  ./gradlew clean build; ./gradlew bootRun
```
