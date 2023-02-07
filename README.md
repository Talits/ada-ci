# Projeto final - CI/CD

> *Curso*: DevOps
> *Módulo*: Pipelines de CI e CD
> *Professora*: Talita

## Enunciado

* Construir uma imagem Docker dentro de um processo de CI/CD, utilizando Jenkins em 2 branches (development e main). 
* Realizar o versionamento do código e das imagens Docker, utilizando GitHub como repositório.
* Usar o Dockerfile no repositório: https://github.com/Talits/ada-ci 
* Exemplo Jenkinsfile: https://github.com/Talits/Jenkinsfile-projetoFinal/blob/main/Jenkinsfile

## Passos para execução

- [X] ter o java na máquina
- [X] subir o agent atraves da configuração de node
- [X] criar novo nó
    - [X] agent permamente
    - [X] diretorio de raiz remoto .
    - [X] criar agent
- [X] Jenkinsfile -> nome do nó configurado
- [X] configurar plugin docker e credenciais dockerhub