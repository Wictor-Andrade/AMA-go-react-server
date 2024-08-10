## Como Rodar o Projeto

Siga os passos abaixo para configurar e rodar o projeto:

1. **Subir os serviços com Docker Compose**: Certifique-se de que o Docker e o Docker Compose estão instalados e configurados. Para subir os serviços, execute:

    ```bash
    docker-compose up -d
    ```

2. **Instalar o Tern**: Para gerenciar as migrações do banco de dados, você precisará do `tern`. Instale o `tern` usando Go:

    ```bash
    go install github.com/jackc/tern@latest
    ```

    Isso instalará o `tern` globalmente no seu sistema.

3. **Executar as Migrações**: Depois de instalar o `tern`, você pode rodar as migrações do banco de dados com o seguinte comando:

    ```bash
    tern migrate
    ```