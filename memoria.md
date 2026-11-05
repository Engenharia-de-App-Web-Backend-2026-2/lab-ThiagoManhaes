# O que foi feito na aula de hoje?
## Implementação de um servidor Nginx usando o Docker compose
* nginx -> servidor e balanceador de carga (load balance)
* docker compose up -d -> sobe o servidor de acordo com o docker-compose.yml
* docker compose down -> derruba o servidor
* O container deve ser reiniciado toda vez que uma modificação por feita no servidor. 
## Implementação do algoritmo round-robin com pesos
* basta adicionar o atributo weight no grupo de sevidores no nginx.conf -> em cada servidor individualment 
## Implementação do algoritmo de ip hash
* basta adicionar o atributo ip_hash no servidor no nginx.conf 
## Implementação do algoritmo least connected 
* basta adicionar o atributo least_conn no servidor no nginx.conf 