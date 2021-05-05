# docker-nginx-mysql

Esse repositório sobe dois contêineres, nginx e mysql, mapeando a porta 80 do nginx para acesso pelo host e permitindo que o contêiner do nginx tenha comunicação de rede no contêiner mysql. 

Alunas: Amanda Botelho de Moraes e Bruna Vieira Teixeira

## Execução

* docker-compose up

## Teste de comunicação

* docker exec -it container_nginx /bin/bash
* apt-get update
* apt-get install iputils-ping
* ping container_mysql
