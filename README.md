Imagem carregada no DOCKER ( https://hub.docker.com ):
sergiokanno/postgresql:1.0

Versão PostgreSQL:
12.18

Volume para persistir dados do PostgreSQL:
postgressql_data

Executar usando comando:
docker run -d -p 5432:5432 --name postgresql_1_0 -v postgressql_data:/var/lib/postgresql/data sergiokanno/postgresql:1.0


