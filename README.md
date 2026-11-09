# Projeto-Exchange-de-Criptomoedas
Projeto desenvolvido na linguagem Java que sera um dos critérios de avaliação do 3 semestre de Ciência da Computação na FEI

## [Primeiro Desenvolvimento: Desenvolvimento de classes e funções](#primeiro)
# Projeto Criptomoedas

## 1. Descrição do projeto

O Projeto Criptomoedas consiste no desenvolvimento de uma plataforma de compra e venda de criptomoedas, permitindo que os usuários gerenciem seus saldos em reais e em diferentes moedas digitais.

O sistema foi desenvolvido em Java, utilizando interface gráfica para facilitar a interação do usuário com as funcionalidades da plataforma. As operações realizadas são armazenadas em banco de dados PostgreSQL, permitindo manter os dados da conta e o histórico das transações.

## 2. Principais funcionalidades

O sistema possui as seguintes funcionalidades:

- **Login:** acesso ao sistema por meio das informações cadastradas do investidor.
- **Consulta de saldo:** visualização dos saldos em reais, Bitcoin, Ethereum e Ripple.
- **Depósito:** adição de valores em reais à carteira.
- **Saque:** retirada de valores em reais da carteira.
- **Compra de criptomoedas:** compra de Bitcoin, Ethereum e Ripple utilizando saldo em reais, com aplicação de taxas.
- **Venda de criptomoedas:** venda das moedas digitais disponíveis na carteira, com aplicação de taxas.
- **Confirmação por senha:** validação da senha numérica antes de determinadas operações.
- **Histórico de transações:** registro das operações realizadas pelo investidor.
- **Persistência de dados:** armazenamento das informações dos usuários, saldos e transações no banco de dados.

## 3. Tecnologias utilizadas

- **Linguagem de programação:** Java.
- **Interface gráfica:** Java Swing.
- **Ambiente de desenvolvimento:** Apache NetBeans IDE.
- **Banco de dados:** PostgreSQL.
- **Conexão com o banco de dados:** JDBC.
- **Arquitetura:** Model-View-Controller (MVC).

## 4. Dependências e configurações

Para executar o projeto, são necessários:

- Java Development Kit (JDK) compatível com a versão utilizada no desenvolvimento.
- PostgreSQL instalado e configurado.
- Banco de dados `projeto_criptomoedas` criado.
- Driver JDBC do PostgreSQL.

### Configuração do banco de dados

É necessário configurar a conexão com o PostgreSQL na classe `Conexao`, informando o endereço do banco de dados, usuário e senha correspondentes ao ambiente utilizado.

### Build e execução

O projeto pode ser compilado pelo Apache NetBeans utilizando a opção **Clean and Build**.

Após a compilação, o executável `.jar` é gerado na pasta `dist`, acompanhado da pasta `lib`, que contém as bibliotecas necessárias.

Para executar, é necessário manter o arquivo `.jar` e a pasta `lib` juntos, além de possuir o banco de dados configurado.

## 5. Imagens da aplicação

### Tela de login

<img width="627" height="460" alt="image" src="https://github.com/user-attachments/assets/12458aff-743e-47fc-9a21-17b403a57884" />

### Tela principal (integrado a parte de atualização de cotação de criptomoedas)

<img width="670" height="452" alt="image" src="https://github.com/user-attachments/assets/bc629afa-8acd-4e9e-a6a1-fc4445a0a8ae" />

### Consulta de saldo

<img width="495" height="411" alt="image" src="https://github.com/user-attachments/assets/0be1b678-1491-436f-8860-f8a7e6a280ba" />

### Depósito e saque

<img width="493" height="408" alt="image" src="https://github.com/user-attachments/assets/0233b067-5f26-438d-b2db-434f1473244d" />
<img width="501" height="413" alt="image" src="https://github.com/user-attachments/assets/c7e187d6-2342-4173-b900-a1f9ceeac4a3" />


### Compra e venda de criptomoedas

<img width="501" height="412" alt="image" src="https://github.com/user-attachments/assets/b49f062b-cd28-49df-8d5d-d5ccbfe00f6a" />
<img width="498" height="411" alt="image" src="https://github.com/user-attachments/assets/e7750a5f-eedd-4e6a-b81b-6e192c98720d" />


### Histórico de transações

<img width="507" height="413" alt="image" src="https://github.com/user-attachments/assets/6d223cd1-d0fa-4cdb-92c3-c73dd13d3ccb" />

### Senha obrigatória

<img width="498" height="411" alt="image" src="https://github.com/user-attachments/assets/6102b34e-5159-4d1f-be07-6eb4f5761c72" />

