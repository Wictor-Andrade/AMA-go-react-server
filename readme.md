## Como Rodar o Projeto

Siga os passos abaixo para configurar e rodar o projeto:

1. **Subir os serviços com Docker Compose**: 
    ```bash
    docker-compose up -d
    ```

2. **Instalar o Tern**: 
    ```bash
    go install github.com/jackc/tern@latest
    ```

3. **Executar as Migrações**:
    ```bash
    go run .\cmd\tools\terndotenv\main.go  
    ```

4. **Instalar SQLC**:
    ```bash
    go install github.com/sqlc-dev/sqlc/cmd/sqlc@latest
    ```