# Projeto Web Ecovales

Esse projeto será provisionado na AWS com EC2 conforme documentado em: [Node EC2](https://www.clickittech.com/devops/deploy-nodejs-app-to-aws/). Antes de executar o projeto vamos criar um VPC pública e uma VPC privada.

## Criação de VPC

Teremos duas VPC, uma pública que permitira acesso ao a instância de Node. Outra VPC será privada com instância RDS. As duas VPC serão criadas conforme os documentos [Vídeo VPC](https://www.youtube.com/watch?v=3okhljXN9aA)



## Componentes do Projeto

| Componente          |  Objetivo                                    |
| ------------------- | -------------------------------------------  |
|  Amplify.           |  Estrutura de backend para smartphone.       |
|  DynamoDB.          |  Estrutura de banco de dados para smartphone.|
|  Athena.            |  Consulas no S3  para consolidar dados.      |  
|  S3.                |  Armazenar os dados do datalake.             |
|  Amazon RDS.        |  Postgres para RDS.                          |
|  EC2.               |  Máquina virtual que executa o WebSite       |  
