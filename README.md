# fullcycle-ddd
DDD: Modelagem Tática e Patterns

1) Nesse desafio você deverá fazer com que a classe OrderRepository implemente totalmente os métodos definidos pelo OrderRepositoryInterface.
Toda essa implementação deverá ser reproduzida através de testes.

Após realizar tal implementação submeta seu projeto, nesse ponto todos os testes devem estar passando.

Boa sorte.

* A linguagem de programação para este desafio é TypeScript


Implemente Domain Events de Customer

Agora que você já possui a base sobre Domain Events, implemente dois Eventos de Domínio para o agregado de Customer.

O primeiro evento deverá acontecer quando um novo Customer é criado. Nesse ponto, crie 2 handlers exibindo um "console.log". 

Handler1: EnviaConsoleLog1Handler. Mensagem: "Esse é o primeiro console.log do evento: CustomerCreated".
Handler2: EnviaConsoleLog2Handler. Mensagem: "Esse é o segundo console.log do evento: CustomerCreated". 
O segundo evento deverá ser disparado quando o endereço do Customer é trocado (método changeAddress()). Nesse caso, o ID, Nome, bem como os dados do endereço devem ser passados ao evento.

Handler: EnviaConsoleLogHandler. Mensagem: "Endereço do cliente: {id}, {nome} alterado para: {endereco}".
Todos os testes devem ser realizados para garantir o bom funcionamento dos eventos.

Boa sorte.

* A linguagem de programação para este desafio é TypeScript

Como Usar o projeto?

1) digite npm i , no prompt de comando.
2) digite o Test, npm test,
A saida na imagem abaixo:

![image](https://github.com/user-attachments/assets/185d659b-bfa2-460b-bdfb-9d24d9072905)




