# Exercícios 

### Exercício 1
Crie um diagrama de classes partindo da classe Funcionário. Crie ao menos 3 cargos específicos utilizando o conceito de herança e polimorfismo. O seu diagrama deve seguir as seguintes regras: 
- A classe Funcionário, deve ter um atributo salário, que deve ser protegido. 
- As classes que herdam de Funcionário devem ter o método “calcularSalario” que receba as horas trabalhadas e o valor cobrado por hora e retorne o seu salário se baseando nos 2 parâmetros. 
- As classes devem ter ao menos 1 método e 1 atributo que a diferencie das outras classes. 


### Exercício 2
Crie um diagrama de classes mostrando a relação entre um cachorro e seu dono. 


### Exercício 3
Crie um diagrama de classes usando herança e polimorfismo, tendo como tema a classe pai: Mamífero. 
Crie pelo menos 3 classes filhas, cada uma com pelo menos uma característica específica. 


### Exercício  4
O Banco solicita a modelagem de um novo sistema. Esse sistema será usado para registrar as contas e os clientes do banco. 
- Clientes: os clientes serão identificados por um número de cliente, um sobrenome, um número de RG e um CPF. 
- Contas: as contas do banco permitem fazer depósitos, sacar dinheiro e consultar o saldo. Cada conta está associada a um cliente. 
Extensão ex 4: 
- Conta poupança: além do saldo, as contas poupança têm uma taxa de juros. Neste tipo de conta, é possível realizar três operações: 
  - Depositar dinheiro: o cliente pode depositar a quantia de dinheiro que quiser. 
  - Sacar dinheiro: o cliente pode sacar dinheiro desde que não supere seu saldo
  - Recolher juros: o cliente pode recolher os juros mensais aplicados pela sua conta poupança.
- Conta corrente: além do saldo, as contas correntes têm um limite autorizado de cheque especial. Neste tipo de conta, é possível realizar três operações: 
   - Depositar dinheiro: o cliente pode depositar a quantia de dinheiro que quiser
   - Depositar cheques: o cliente pode depositar cheques. Um cheque tem um valor, um banco emissor e uma data de pagamento. 
   - Sacar dinheiro: o cliente pode sacar dinheiro e, caso não tenha saldo suficiente, usar seu cheque especial. 
Implemente as classes e aplique os conceitos de Herança e de classe abstrata para a resolução do sistema. 


### Exercício 5
Modelar um sistema de impressão, em que uma impressora tem uma fila de arquivos para imprimir. A qualquer momento, é possível pedir que a impressora imprima todos os arquivos da fila. Considerar que essa impressora pode imprimir fotos, documentos de Word e PDF. 


### Exercício 6
Uma rede de fast food solicita o desenvolvimento de um “carrinho” para seu serviço de comércio eletrônico. É necessário modelar um carrinho que permita que os usuários adicionem os produtos que querem comprar (diferentes sanduíches e acompanhamentos como batatas fritas, saladas e refrigerantes).

Além disso, deve ser possível adicionar menus especiais (combos) ao carrinho, que já estão montados com uma seleção de diferentes produtos a um preço promocional (com desconto). 

Também deve ser possível adicionar combos familiares ao carrinho, que são formados por vários combos individuais (p. ex., 2 combos médios e 2 combos pequenos). Esses combos também terão um preço promocional. 

OBS: O carrinho deve informar o valor total da compra. 


### Exercício 7
Modelar o funcionamento interno de um forno: 

Temos um termostato, que pode ser usado para regular a temperatura selecionado pelo usuário; 

Também temos um termômetro de mercúrio, que informa a temperatura atual;

Por último, temos um queimador, que modifica a temperatura de acordo com a intensidade da chama. 

### Exercício 8
Desenvolva um diagrama de classes que represente um sistema de animais. Nesse sistema deverá conter:
- Uma classe Animal que será modelo para outras classes. A classe animal deverá conter espécie e a ação de comer que deverão ser obrigatoriamente implementados por outras classes. 
- Deverá conter também as classes **GatoEstimacao** e **CachorroEstimacao** que deverão conter alguma característica específica e contendo a ação de comer, além disso implementar a interface **Brincável** com a ação de brincar. 
- E uma classe chamada **AnimalSelvagem** que deverá conter uma característica específica e as ações de caçar e comer.
