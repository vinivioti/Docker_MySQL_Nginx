# Docker_MySQL_Nginx


Terceira atividade do curso Infrastructure and Cloud Computing 

Professor: João Victorino

## Alunos:

Leonardo Ananias do Nascimento Azogue 

Vinissius Vioti dos Santos 

## ***Descrição Atividade:*** 
Subir dois contêineres, nginx e mysql, mapeando a porta 80 do nginx para acesso pelo host e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql.  
Enviar sequência de comandos na linha de comando ou o Docker-compose com os arquivos necessários para que a solução funcione.

> Passo a passo
```
Baixar o código no github https://github.com/vinivioti/Docker_MySQL_Nginx.git
abra o Visual Code na pasta do projeto
Execute o comando: docker-compose up -d
Depois de tudo ok
http://localhost:80  - (nginx)
http://localhost:8080 - (MySQL)
Para acessar o MySQL - preencha os campos conforme segue:
Servidor: mysql-server
Usuário: root
Senha: "Password1234!"
Então será apresentado a lista de database, sendo a "root" a criada nesse processo.

```
