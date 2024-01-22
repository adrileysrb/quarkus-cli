# Repositorio com comandos Quarkus CLI

Esse repositorio contem comandos utilizados na CLI do framework Quarkus.

<details><summary><b>Comandos básicos</b></summary>

- **Comandos básicos**
    
    
    Configuração inicial:
    
    ```bash
        # Criar projeto com groupId=teste.teste1, artifactId=testando e adicionar duas dependencias e version=1.0.0-SNAPSHOT
        quarkus create app teste.teste1:testando \
        --extension=resteasy \
        --extension=smallrye-reactive-messaging
    ```

    ```bash
        # Criar projeto com groupId=teste.teste1, artifactId=testando e adicionar duas dependencias, version=1.0 e especificando qual versão do Quarkus será utilizada
        quarkus create app teste.teste2:testando222:1.0 \
        -P io.quarkus.platform:quarkus-bom:3.2.9.Final \
        --extension=resteasy \
        --extension=smallrye-reactive-messaging
    ```

</details> 
