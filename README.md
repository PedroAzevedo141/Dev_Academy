# Dev_Academy

## Objetivos do projeto

DEV Academy é uma plataforma para ensino a distância, que tem como objetivo facilitar a implementação do ensino remoto, ela é uma plataforma web focada em cursos abertos e massivos, onde os professores poderão criar cursos e disponibilizá-los gratuitamente para seus alunos.

Os cursos serão divididos por módulos, cada módulo terá um conjunto de vídeos aulas disponibilizadas por plataformas de vídeo gratuito(youtube,vimeo) e materiais adicionais como(Códigos, pdf ’s, slides...), a plataforma terá um sistema de fórum para interação dos professores com alunos, um sistema de avisos onde os alunos poderão receber informações sobre os cursos e um sistema de contas, para que os  usuários possam se cadastrar e logar no sistema. 


## Instalando o python 3.8

```bash
sudo apt-get install software-properties-common
```
```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```
```bash
sudo apt-get update
```
```bash
sudo apt-get install python3.8
```
```bash
sudo apt install python3.8-venv
```

## Criando a Venv

```bash
python3.8 -m venv .venv
```
```bash
source .venv/bin/activate
```

## Configurando o Docker

```bash
docker build .
```
```bash
docker-compose up -d --build
```
## Ativando o container

```bash
docker-compose up --build
```