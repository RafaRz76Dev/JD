***

# ✨ PROJETO AGENDA-PESQUISA SATISFAÇÂO

## Na continuação do curso para  aperfeiçoar meus conhecimentos em mais um desafio da ```integração Back-End + Front-End```!!!

 ### Requisitos necessários:

🎯 Banco de Dados <img src="https://media.giphy.com/media/fXQqNrqKATCNwq6zin/giphy.gif" align="center" height="25" width="25"> ```postgreSql``` 

🎯 Front-End <img src="https://media.giphy.com/media/fXQqNrqKATCNwq6zin/giphy.gif" align="center" height="25" width="25"> ```JavaScript``` 

🎯 Back-End <img src="https://media.giphy.com/media/fXQqNrqKATCNwq6zin/giphy.gif" align="center" height="25" width="25"> ```Java```

🎯 IDE <img src="https://media.giphy.com/media/fXQqNrqKATCNwq6zin/giphy.gif" align="center" height="25" width="25"> ```Eclipse```

🎯 APIs <img src="https://media.giphy.com/media/fXQqNrqKATCNwq6zin/giphy.gif" align="center" height="25" width="25"> ```Postman``` & ```Ajax```

# <div align="center">
# <img src="https://media.giphy.com/media/9TFBxN300KpCUI6sBD/giphy.gif" align="center" height="55" width="55"> 

<img src="images/AGENDA-CLIENTES.png" align="center" height="500em" width="100%" href="https://rafarz76dev-pesquisa-satisfacao.up.railway.app/agenda_contatos/">

<br>

***
<div align="left">
  
# Passo a Passo do Projeto (Back-End):
### Este projeto usa:
- `Maven` como ferramenta de construção;
- `Java` na versão 11;
- `Tomcat` na versão 10.0;
- `PostgreSql` na versão 9.5;
- `Spring Boot`como framework.


---
### Executando o aplicativo:
#### Na IDE `Eclipse`vai rodar <img src="https://media.giphy.com/media/XwcRflO9HD0Sk6RaRM/giphy.gif" align="center" height="25" width="25"> Na porta => `http://localhost:8081/`
---
### Building for Production:
#### Este aplicativo usa `JAR` como tipo de embalagem. Isso significa que você pode executar o seguinte comando no terminal para criar algo pronto para ser usado na produção.

```bash
mvn clean package
```
---
### Execução do Projeto  Spring com o  comando java -jar ::
- Vai no caminho da pasta que foi criada e dentro vai copiar a pasta `target`, então no comando do terminal cola o `caminho` da pasta,
- logo após dentro da pasta `target` vai copiar o arquivo em `jar` e cola no comando do terminal da seguinte forma:

```bash
$ java -jar springboot-rest-api-sample-1.0.0-SNAPSHOT.jar  
```

### No Postman para execução dos testes (APIs):
#### <img src="https://media.giphy.com/media/XwcRflO9HD0Sk6RaRM/giphy.gif" align="center" height="25" width="25"> Vai executar na porta => http://localhost:8081/`agenda_contatos+nomedasAPIs`

***
# Passo a Passo do Projeto (Front-End): 

### Este projeto usa:
- `[Bootstrap CSS]` (https://getbootstrap.com/docs/4.0/components/forms/) para o formulário de pesquisa;
- `[JQuery]` (https://code.jquery.com/jquery-3.6.0.min.js) como framework;
- `Ajax`para consumo das APIs.

### Executando projeto no `servidor localhost` em Front-End:

#### <img src="https://media.giphy.com/media/XwcRflO9HD0Sk6RaRM/giphy.gif" align="center" height="25" width="25"> Vai no navegador e digita: http://localhost:8081/agenda_contatos

---
# Implantação de serviço para futuro deploy:
### Este projeto pode usar:
- `Railway.app`.

#### Criando um banco de dados `PostgreSQL`,copiando as variáveis ​​de ambiente do banco, criou- se o projeto do `git repositório` com base nessas variáveis, assim colando no editor RAW:

```properties
export spring_profiles_active=prod
export PG_HOST=postgres.railway.internal
export PG_PORT=5432
export PG_DATABASE=railway
export PG_USER=postgres
export PG_PASSWORD=NUHlXJgazzTabgctkEWkwrivxcVKbKWm
```

<br>
  
---
### Gostou, então já clica na 🌟


  


