# SGP - Banco de Dados

Esse serviço faz parte do projeto de gestão de pagamentos para a empresa Farmácioa Nossa Senhora da Conceição. O objetivo é facilitar a organização, gerenciamento e visibilidade dos pagamentos efetuados.
- Iniciativa Impacta - Projeto de Conclusão de Curso

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

O projeto está estruturado em três serviços:
- SGP - [front-end](https://github.com/sgieandimpacta/mfe.git)
- SGP - [back-end](https://github.com/sgieandimpacta/api.git)
- SGP - [Banco de Dados](https://github.com/sgieandimpacta/db.git)

O README de cada um deles contém o passo a passo para que você consiga rodar o projeto por completo em sua máquina. Este traz as instruções para subida do serviço de Banco de Dados.

### 📋 Pré-requisitos

De que coisas você precisa para instalar o software e como instalá-lo?
- Você precisará do docker em sua máquina, siga o passo a passo direto do guia de instalação contido neste [link](https://docs.docker.com/engine/install/ubuntu/)
- Após a instalação do docker, tudo que precisa fazer é seguir os passos na etapa abaixo

### 🔧 Instalação


Caso ainda não tenha feito o clone do projeto, pode fazê-lo rodando o comando abaixo na pasta onde queira o projeto

```
git clone https://github.com/sgieandimpacta/db.git

```

Caso não tenha mudado o nome do projeto durante o clone, poderá entrar na pasta usando o comando:

```
cd db

```

Para realizar a subida basta rodar o comando docker compose que realizará o build e o up dos serviços:

```
docker-compose up -d --build

```

Para confirmar se os serviços estão de pé, rode o comando:

```
docker-compose ps -a

```

Uma lista de containers como a abaixo será exibida:

![containers de banco mysql e admin de pé no docker](https://i.postimg.cc/m24Ch0G5/Captura-de-tela-2023-03-30-225925.png)

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [docker](https://www.docker.com/) - Develop faster. Run anywhere.
* [mysql](https://www.mysql.com/) - Save time and money powering their high-volume Web sites, business-critical systems and packaged software.
* [adminer](https://www.adminer.org/) - A full-featured database management tool written in PHP

## ✒️ Autores

* **Gieandes Silva** - [likedin](https://www.linkedin.com/in/gieandessilva)