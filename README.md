## Baoba-Hackers

## Integrantes:
- <a href="https://www.linkedin.com/in/erik-batista-da-silva-455612215/">Erik Batista da Silva</a>
- <a href="https://www.linkedin.com/in/nicollas-isaac/">Nicollas Isaac</a>
- <a href="https://www.linkedin.com/in/rafaella-bianca-cavalcante/">Rafaella Bianca Cavalcante</a>
- <a href="https://www.linkedin.com/in/yan-m-coutinho/">Yan Mendonça Coutinho</a>
  
## Descrição
Nosso projeto propõe uma solução inovadora para melhorar a rastreabilidade na cadeia produtiva da indústria da moda, utilizando tecnologias de blockchain. Esse sistema avançado permite a criação de um histórico detalhado dentro de toda a cadeia de produção de um produto, proporcionando um acompanhamento completo desde a produção da matéria-prima até a confecção final do SKU.

  
## Configuração para desenvolvimento e execução do código
### Pré-requisitos

&emsp;&emsp; Para utilizar deste projeto, por favor, siga a seguinte lista de pré-requisitos:

- Yarn (v1 or v2+)

### Instalação
1. **Clonar o repositório**: Primeiramente, você precisará clonar o repositório do projeto para sua máquina local. Abra o terminal e digite o seguinte comando:
   ```
   git clone [https://github.com/3R11K/Baoba-Hackers]
   ```



2. **Instalar as dependências**: Navegue até a pasta do projeto clonado e instale as dependências necessárias executando:
   ```
   cd scaffold-eth-2
   yarn install
   ```
   Esse comando irá instalar todas as dapendências necessárias.

### Execução

Após ter feito o processo de instalação, para executar o projeto, siga o seguinte passo a passo:

1. **Inicializar uma rede blockchain**: Acesse a pasta do projeto e inicie uma rede Ethereum local.
   ```
   cd y-human
   yarn chain
   ```

2. **Deploy do contrato**: Em um segundo terminal, mas ainda na mesma pasta, dê o deploy do contrato do projeto em sua rede Ethereum local.
   ```
   yarn deploy
   ```

3. **Inicie o servidor**: Por ultimo, em um terceiro terminal, ainda na mesma pasta, inicie o servidor da aplicação.
   ```
   yarn start
   ```
Pronto, agora basta acessar http://localhost:3000, onde você poderá interagir com a aplicação.

## Histórico de lançamentos
* 0.0.1 - 29/05/2024
  
## Tecnologias Utilizadas
- Scaffold-ETH 2
- Hardhat
- PostgreSQL
- Near
- NextJs
- Ethereum
- Solidity

