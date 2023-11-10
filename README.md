# Configuração do Ambiente do Projeto de Ciência de Dados

## Pré-requisitos

Certifique-se de ter o Python versão 3.6 ou superior instalado no seu sistema executando:

```
 python3 --version
```

## Configuração do Ambiente de Desenvolvimento

Siga estas instruções para configurar seu ambiente de desenvolvimento.

### Clonar o Repositório

Primeiro, clone o repositório do projeto para sua máquina local usando Git

```
    git https://github.com/coutinhonobre/Introducao-data-mining
    cd Introducao-data-mining
```

### Criar um Ambiente Virtual

Dentro do diretório do projeto, crie um ambiente virtual:

```
    python3 -m venv .env
```

### Ativar o Ambiente Virtual

Ative o ambiente virtual criado:

```
source .env/bin/activate
```

### Instalar Dependências

Com o ambiente virtual ativado, instale as dependências do projeto usando `pip`:

```
pip install -r requirements.txt
```

### Iniciar o Jupyter Lab

Para começar a trabalhar com o Jupyter Lab:

```
    jupyter lab
```

## Trabalhando no Projeto

Sempre que iniciar uma nova sessão, certifique-se de ativar o ambiente virtual:

```
   source .env/bin/activate
```

## Desativando o Ambiente Virtual

Para sair do ambiente virtual quando terminar de trabalhar:

```
deactivate
```
