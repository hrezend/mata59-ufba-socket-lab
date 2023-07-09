### Trabalho de Redes de Computadores (2023.1)

#### Grupo: Djair Maykon, Hérson Rezende, João Victor Florêncio, Kennedy Anderson

---

- Como executar este projeto?
  - Antes de tudo, é necessário que você possua o ambiente de desenvolvimento configurado para trabalhar com [python3](https://www.python.org/downloads/).
    1. Inicialize um terminal e execute o comando `python proxy.py` para executar o proxy da aplicação. Atente-se ao terminal, pois lá estará em log a porta em que a aplicação estará "ouvindo" requisições e você precisará dessa informação para quando rodar a aplicação do cliente. 
    2. Inicialize outro terminal e execute o comando `python client.py` para rodar o client da aplicação. Em seguida, responda aos inputs solicitados pelo programa (endereço e porta de conexão com o proxy).

- Pontos de atenção:
  - Os arquivos a serem armazenados pela aplicação precisam estar na pasta raiz do projeto.
  - As pastas referentes aos servidores, também serão criadas na pasta raiz do projeto, ou podem ainda serem criadas na pasta raiz do computador, caso você execute a aplicação em modo debug. 
  - Não é necessário executar o server.py em um servidor, já que a aplicação faz isso de forma dinâmica e "por baixo dos panos".