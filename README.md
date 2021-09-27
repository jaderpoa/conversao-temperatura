# conversao-temperatura

Para efetuar o deploy desta aplicação, proceder os seguintes procedimentos:

- git clone https://github.com/jaderpoa/conversao-temperatura.git
- cd conversao-temperatura/
- docker image build -t "conversao-temperatura:v1".
- docker container run -d --name conversao-temperatura --restart=always -p 8080:8080 conversao-temperatura:v1
