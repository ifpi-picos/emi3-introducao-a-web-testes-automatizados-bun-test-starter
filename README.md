# Projeto Conta Bancária

### Requisitos da Classe `ContaBancaria`

#### Atributos:

1. **numeroConta**: Representa o número da conta bancária.
2. **agencia**: Representa o número da agência bancária.
3. **saldo**: Armazena o saldo atual da conta.
4. **extrato**: Armazena o histórico de operações realizadas na conta (depósitos, saques, transferências).

#### Métodos:

1. **depositar(valor: number)**: Permite realizar um depósito na conta, aumentando o saldo.
2. **sacar(valor: number)**: Permite realizar um saque, diminuindo o saldo, desde que o valor seja válido e não exceda o saldo disponível.
3. **transferir(valor: number, contaDestino: ContaBancaria)**: Realiza a transferência de um valor para outra conta bancária, diminuindo o saldo da conta origem e aumentando o saldo da conta destino.
4. **consultarSaldo()**: Retorna o saldo atual da conta.
5. **exibirExtrato()**: Exibe o histórico de transações (extrato) realizadas na conta.
6. **registrarOperacao(descricao: string)**: Método privado para registrar cada operação no extrato da conta, incluindo a data e a descrição da transação.


Para executar os testes:

```sh
bun test
```
