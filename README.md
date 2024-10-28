# Desafio DIO - Sistema Bancário em POO com Python

Este projeto implementa um sistema bancário simples em Python, aplicando conceitos de Programação Orientada a Objetos (POO). Ele faz parte de um desafio da Digital Innovation One (DIO) e visa simular funcionalidades bancárias básicas, como criação de contas, depósitos, saques, e consulta de extratos.

## Funcionalidades

- **Criar Cliente**: Cadastro de novos clientes com informações básicas.
- **Criar Conta**: Criação de contas associadas aos clientes.
- **Depositar**: Realiza depósitos em uma conta existente.
- **Sacar**: Realiza saques com controle de limite e saldo.
- **Extrato**: Exibe o histórico de transações de uma conta.
- **Listar Contas**: Mostra as contas criadas e suas informações básicas.

## Estrutura do Projeto

- **Classes**:
  - `Cliente` e `PessoaFisica`: Representam os clientes do banco.
  - `Conta` e `ContaCorrente`: Modelam contas bancárias com métodos de transação.
  - `Historico`: Registra o histórico de transações da conta.
  - `Transacao`, `Saque`, `Deposito`: Representam operações bancárias específicas.

## Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/desafio-dio-modelando-o-sistema-bancario-em-poo-com-python.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd desafio-dio-modelando-o-sistema-bancario-em-poo-com-python
   ```

3. Execute o script:

   ```bash
   python nome_do_arquivo.py
   ```

## Exemplo de Uso

Após iniciar o programa, um menu de opções será exibido para que o usuário possa escolher a operação desejada. Basta seguir as instruções para realizar operações como criar uma conta, fazer um depósito, sacar ou visualizar o extrato.

## Requisitos

- Python 3.6 ou superior

## Licença

Este projeto é para fins educacionais.
