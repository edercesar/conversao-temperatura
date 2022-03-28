## Criar a Imagem

1- acesse cd /conversao-temperatura/src <br/>
2- execute o comando para criar a sua imagem "Docker build -t namespace/nomedorepo:TAG ." <br/>

## Execução do container

1 - execute Docker run -dti -p 8080:8080 namespace/nomedorepo:TAG <br/>
2 - para acessar a aplicação no navegador digite http://localhost:8080/ <br/>