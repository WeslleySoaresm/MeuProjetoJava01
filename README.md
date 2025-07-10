

# 📚 Guia de Estudo de Fundamentos Java

Este repositório serve como um compêndio dos meus estudos em Java, abordando desde estruturas de dados básicas como **Arrays** até conceitos de **Programação Orientada a Objetos (POO)** e técnicas de tratamento de erros. Cada seção contém exemplos de código que ilustram os conceitos abordados.

---

## 🔢 Arrays

Arrays são estruturas de dados fundamentais em Java, usadas para armazenar uma coleção de elementos do mesmo tipo em uma sequência fixa. Este módulo explora diferentes aspectos e usos de arrays.

| Arquivo                  | Descrição                                                          |
| :----------------------- | :----------------------------------------------------------------- |
| `CarrinhoDeAeroporto.java` | Exemplo de uso de array para simular um carrinho em aeroporto.     |
| `SqrTable.java`          | Demonstra a criação e preenchimento de uma tabela de quadrados.    |
| `exmplosArraysList.java` | Ilustra o uso de `ArrayList`, uma alternativa dinâmica aos arrays. |
| `Exemplos.java`          | Contém exemplos gerais de manipulação de arrays.                   |
| `MaxMin.java`            | Encontra o valor máximo e mínimo em um array.                      |
| `TwoD.java`              | Demonstra a criação e manipulação de arrays bidimensionais.        |
| `ola2`                   | Um exemplo simples, possivelmente relacionado a arrays básicos.    |
| `sampleDemo.java`        | Outro exemplo para demonstração de conceitos de array.              |

---

## 📁 Manipulando Arquivos (File I/O)

Esta seção foca na leitura e escrita de dados em arquivos, essencial para persistência de informações em aplicações Java.

| Arquivo           | Descrição                                                          |
| :---------------- | :----------------------------------------------------------------- |
| `ArquivosExemplo.java` | Exemplos básicos de operações com arquivos (criação, leitura).     |
| `MenuIOExemplo.java` | Um menu interativo para praticar operações de I/O de arquivos.      |

---

## 🚦 Estruturas Condicionais

As estruturas condicionais permitem que o fluxo do programa mude com base em certas condições, possibilitando a tomada de decisões.

| Arquivo                 | Descrição                                                         |
| :---------------------- | :---------------------------------------------------------------- |
| `ExemploTernario.java`  | Demonstra o uso do operador ternário para decisões concisas.      |
| `MenuBancario.java`     | Um menu interativo com lógica condicional para operações bancárias.|
| `classificaçãoDaConta.java` | Classifica tipos de conta com base em condições específicas.       |
| `verificaçãoSaldo.java` | Verifica o saldo da conta usando estruturas condicionais.          |

---

## 🔐 Controle de Acesso

Este módulo explora conceitos de controle de acesso, como classes com array interno com falha suave para garantir resiliência.

| Arquivo          | Descrição                                                              |
| :--------------- | :--------------------------------------------------------------------- |
| `FailSoftArray.java` | Uma implementação de array com comportamento de "falha suave".        |
| `FsDemo.java`    | Demonstra o uso e o comportamento do `FailSoftArray`.                  |

---

## 🅿️ Estacionamento

Um exemplo prático de modelagem de entidades e suas interações, como veículos em um estacionamento.

| Arquivo             | Descrição                                        |
| :------------------ | :----------------------------------------------- |
| `Estacionamento.java` | Lógica principal para gerenciar o estacionamento.|
| `Veiculo.java`      | Representa o objeto Veículo com suas propriedades.|

---

## 🧬 Herança

Herança é um pilar da Programação Orientada a Objetos, permitindo que classes herdem propriedades e métodos de outras classes, promovendo reuso de código.

| Arquivo                   | Descrição                                                           |
| :------------------------ | :------------------------------------------------------------------ |
| `AuditoriaBancaria.java`  | Exemplo de como a auditoria pode ser implementada.                  |
| `AuditoriaContaCorrente.java` | Uma extensão da auditoria específica para contas correntes.         |
| `BancoDemo.java`          | Demonstra o uso das classes de conta e auditoria bancária.          |
| `ContaBancaria.java`      | Classe base para diferentes tipos de contas bancárias.              |
| `ContaCorrente.java`      | Herda de `ContaBancaria`, representando uma conta corrente.         |
| `ContaCorrenteEspecial.java` | Herda de `ContaCorrente` com funcionalidades especiais.             |
| `ContaPoupanca.java`      | Herda de `ContaBancaria`, representando uma conta poupança.         |
| `OperaacaoBancaria.java`  | Define operações bancárias abstratas ou concretas.                  |

---

## 🤝 Interfaces

Interfaces em Java definem um contrato, especificando um conjunto de métodos que uma classe deve implementar. Promovem polimorfismo e design modular.

| Arquivo                     | Descrição                                                          |
| :-------------------------- | :----------------------------------------------------------------- |
| `ContaTest.java`            | Possivelmente testa a implementação de interfaces em classes de conta.|
| `GerenciadorDeContas.java`  | Gerencia diferentes tipos de contas através de uma interface.       |
| `RegistroAuditoria.java`    | Interface para definição de registro de auditoria.                  |
| `RegistroAuditoriaCompleta.java` | Implementação completa da interface de registro de auditoria.     |
| `RegistroAuditoriaSimples.java` | Implementação simplificada da interface de registro de auditoria. |

---

## 📦 Objetos

Este módulo aborda a criação e manipulação de objetos, a base da Programação Orientada a Objetos.

| Arquivo         | Descrição                                             |
| :-------------- | :---------------------------------------------------- |
| `TesteCarro.java` | Testa a criação e comportamento de objetos `Carro`.   |
| `TesteHasSet.java`| Demonstra o uso de `HashSet` para coleções de objetos.|
| `carro.java`    | Define a classe `Carro` com suas propriedades.        |

---

## 🧠 Paradigma

Uma visão geral sobre o conceito de paradigma de programação.

| Arquivo   | Descrição                       |
| :-------- | :------------------------------ |
| `Estrutural`| Conteúdo sobre o paradigma estrutural (diretório). |

---

## 🖥️ Programação Orientada a Objetos (POO)

A essência da POO, com exemplos de classes, objetos, e conceitos como passagem de valor e referência.

| Arquivo                       | Descrição                                                         |
| :---------------------------- | :---------------------------------------------------------------- |
| `Carro.java`                  | Outro exemplo de classe `Carro` (pode ter diferenças do anterior). |
| `NomeDaClasse.java`           | Um template ou exemplo genérico de definição de classe.           |
| `TestePAssagemValor.java`     | Demonstra como valores são passados em métodos Java.              |
| `TestePassagemPorReferencia.java` | Demonstra a passagem por referência em Java (para objetos).       |
| `TesteVeiculo.java`           | Testa a classe `Veiculo`.                                         |
| `veiculo.java`                | Define a classe `Veiculo`.                                        |

---

## 🔄 Repetição (Loops)

Estruturas de repetição para executar blocos de código múltiplas vezes, como `for`, `while`, `do-while`, e comandos de controle de fluxo.

| Arquivo                     | Descrição                                                            |
| :-------------------------- | :------------------------------------------------------------------- |
| `DowhileBrackAndContinue.java`| Demonstra `do-while` com `break` e `continue`.                     |
| `ForeackContinue.java`      | Uso do `for-each` com `continue`.                                   |
| `LoopEntradaUsuario.java`   | Exemplo de loop que interage com entrada do usuário.                |
| `LoopExemplos.java`         | Exemplos variados de diferentes tipos de loops.                     |
| `LoopsAninhados.java`       | Demonstra loops dentro de outros loops.                             |
| `braekExmplo.java`          | Uso do comando `break` para sair de um loop.                        |
| `continueExemplo.java`      | Uso do comando `continue` para pular a iteração atual do loop.      |
| `loopInfinito.java`         | Exemplo e cuidado com loops infinitos.                             |

---

## 📏 Sobrecarga (Overloading)

Sobrecarga de métodos permite definir múltiplos métodos com o mesmo nome, mas com diferentes listas de parâmetros.

| Arquivo            | Descrição                                                             |
| :----------------- | :-------------------------------------------------------------------- |
| `AutoConvertOverload.java`| Demonstra sobrecarga com autoconversão de tipos.                    |
| `AutoConvertTest.java` | Testa o comportamento da sobrecarga com autoconversão.               |
| `OverloadDemo.java`| Um exemplo básico de método sobrecarregado.                         |
| `OverloadTest.java`| Testa os métodos sobrecarregados em `OverloadDemo`.                  |

---

## ⚠️ Tratamento de Exceções (`try-catch`)

Tratamento de exceções é fundamental para criar aplicações robustas, permitindo lidar com erros e situações inesperadas de forma controlada.

| Arquivo           | Descrição                                                              |
| :---------------- | :--------------------------------------------------------------------- |
| `ExemploTry1.java`| Primeiro exemplo de uso de `try-catch`.                               |
| `ExemplosTry.java`| Exemplos mais complexos ou variados de blocos `try-catch`.            |
| `BlocoDePergunta.java`| Provável exemplo de como manipular entrada de usuário com `try-catch`.|
| `BooleanDemo.java`| Demonstra o tipo `boolean`.                                           |
| `EntradaDados.java`| Manipulação de entrada de dados do usuário (possivelmente com tratamento de erro).|
| `ErroComumm.java` | Ilustra um erro comum e como ele pode ser tratado.                   |
| `ExemploEscopo.java`| Demonstra o escopo de variáveis.                                      |
| `Main.java`       | Arquivo principal de algum projeto ou um ponto de entrada.             |
| `StringDemo.java` | Exemplos de manipulação de strings.                                   |
| `TempoDeVida.java`| Conceito de tempo de vida de variáveis e objetos.                      |

---

