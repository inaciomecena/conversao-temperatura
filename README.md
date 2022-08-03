# conversao-temperatura

### Executar o comandinho maroto pra buildar tudo e fazer um pacotinho dentro do container!
docker build -t conversao_temperatura:v1 .

### Agora vamos rodar o nosso container
docker run -d -p 8080:8080 conversao_temperatura:v1