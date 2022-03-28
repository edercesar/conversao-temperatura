##Criar a Imagem

1- acesse cd /conversao-temperatura/src
2- execute o comando para criar a sua imagem "Docker build -t namespace/nomedorepo:TAG ."

##execução do container

1 - execute Docker run -dti -p 8080:8080 namespace/nomedorepo:TAG
2 - para acessar a aplicação no navegador digite http://localhost:8080/