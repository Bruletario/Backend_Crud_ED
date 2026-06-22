API REST desenvolvida em Java com Spring Boot para o trabalho prático de Engenharia de Dados.

## Pré-requisitos
- Java 26 (ou compatível)
- Maven 3.x
- Acesso à rede (para conectar ao banco PostgreSQL na AWS RDS)

## Configuração
1. O projeto já está configurado para conectar ao banco de dados em `src/main/resources/application.properties`.
2. Certifique-se de que seu IP está liberado no Security Group da AWS, caso necessário.

## Como rodar
1. No terminal, dentro da pasta do projeto, execute:
   ```bash
   mvn clean install
   mvn spring-boot:run
