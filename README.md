# Sistema de Controle de Versões – 09/02/2026

# O que é? 
Um sistema de controle de versões (VCS) é um software que auxilia desenvolvedores com a finalidade de salvar diferentes versões no desenvolvimento de um projeto, permitindo restaurar versões anteriores caso ocorra um erro durante uma atualização para comparação de códigos e para muitas equipes o código fonte é como uma mina de ouro caso corrompa o  sistema de controle de versões (VCS)  ajuda na recuperação de código fonte.  O sistema de controle de versões (VCS) é usado por diversos desenvolvedores e empresas pois ajuda equipes a trabalharem juntas e reduzem o tempo de desenvolvimento assim podendo focar em outras implementações bem-sucedidas. são essenciais, mas trazem desafios técnicos e de aprendizado. Os principais pontos negativos incluem uma curva de aprendizado íngreme, o risco de conflitos complexos ao mesclar códigos 

# 5 Vantagens:
•	```Controle do histórico:``` facilidade em desfazer e possibilidade de analisar o histórico do desenvolvimento, como também facilidade no resgate de versões mais antigas e estáveis. A maioria das implementações permitem analisar as alterações com detalhes, desde a primeira versão até a última.

•	```Trabalho em equipe:``` um sistema de controle de versão permite que diversas pessoas trabalhem sobre o mesmo conjunto de documentos ao mesmo tempo e minimiza o desgaste provocado por problemas com conflitos de edições. É possível que a implementação também tenha um controle sofisticado de acesso para cada usuário ou grupo de usuários.

•	```Marcação e resgate de versões estáveis:``` a maioria dos sistemas permite marcar onde é que o documento estava com uma versão estável, podendo ser facilmente resgatado no futuro.

•	```Ramificação de projeto:``` a maioria das implementações possibilita a divisão do projeto em várias linhas de desenvolvimento, que podem ser trabalhadas paralelamente, sem que uma interfira na outra.

•	```Segurança:``` Cada software de controle de versão usa mecanismos para evitar qualquer tipo de invasão de agentes infecciosos nos arquivos. Além do mais, somente usuários com permissão poderão mexer no código.

# Exemplos de Sistemas de Controles de Versões:

•	```Git:``` É um sistema de controle de versão distribuído, usado para gerenciar alterações em arquivos e códigos ao longo do tempo. Cada desenvolvedor possui uma cópia completa do repositório, incluindo todo o histórico do projeto, o que permite trabalhar offline e com mais segurança.

•	```SVN:``` É um sistema de controle de versão centralizado, onde existe um servidor único que armazena o projeto e seu histórico. Os desenvolvedores dependem desse servidor para realizar a maioria das operações, como commits e atualizações.

•	```GitLab:``` é uma plataforma de gerenciamento de projetos baseada em Git. Ele não substitui o Git, mas fornece uma interface web e ferramentas para hospedar repositórios, colaborar em equipe e automatizar processos.

# Desafio 2 - 12/02/2026

##  Oque é POO?
Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o desenvolvimento de sistemas com base no conceito de objetos, que representam entidades do mundo real dentro do software. Em vez de estruturar o programa apenas como um conjunto de funções e procedimentos, a POO combina dados e comportamentos em estruturas chamadas classes.Uma classe funciona como um modelo ou molde para criar objetos, e cada objeto possui características próprias, chamadas atributos, e ações que pode executar, chamadas métodos.A POO facilita a manutenção e a reutilização de código, pois cada parte do sistema pode ser desenvolvida de forma independente e com responsabilidades bem definidas. A POO tem 4 pilares sendo eles: Encapsulamento, Herança, Polimorfismo e Abstração. apresenta desvantagens como alta complexidade e curva de aprendizado íngreme, especialmente para iniciantes. Projetos pequenos podem se tornar excessivamente estruturado
## Abstração:
```Foca apenas nos aspectos essenciais de um objeto para o sistema, ignorando detalhes complexos e desnecessários.``` 

Exemplo:
Em um sistema de biblioteca, um livro real tem peso, cor, tipo de papel etc.
Mas no sistema usamos apenas: título, autor, ISBN e disponibilidade.
Ignoramos o resto porque não é necessário para controlar empréstimos.
Ou seja, abstração é esconder detalhes desnecessários e manter só o essencial.
## Encapsulamento:
```Oculta detalhes internos do funcionamento de um objeto, protegendo os dados e expondo apenas o necessário via interfaces.```

Exemplo:
Em uma conta bancária, o saldo não pode ser alterado diretamente.
Só é possível mudar o saldo usando métodos como depositar e sacar.
Assim, o saldo fica protegido e segue regras (ex: não sacar mais do que tem).
Encapsulamento é esconder os dados e controlar como eles são usados.

##  Herança: 
```Permite que uma classe (subclasse) herde atributos e métodos de outra (superclasse), promovendo o reaproveitamento de código.```

Exemplo:
Temos uma classe Animal com:
nome
"emitirSom"
Criamos a classe Cachorro, que herda de Animal.
O Cachorro já possui nome e emitirSom, mas pode adaptar o som para “latir”.
Herança é reaproveitar características de uma classe base e criar versões mais específicas dela.

## Polimorfismo:
```Capacidade de objetos de diferentes classes serem tratados de forma uniforme, permitindo que métodos com o mesmo nome se comportem de maneiras diferentes.```

Polimorfismo é quando diferentes classes respondem ao mesmo método de maneiras diferentes.

Exemplo:
Temos a classe Animal com o método emitirSom().
Cachorro → emitirSom() = “Latir”;
Gato → emitirSom() = “Miar”;
Mesmo método, comportamentos diferentes.
Polimorfismo é usar a mesma ação, mas com resultados diferentes dependendo do objeto.

# 5 Vantagens da POO:
• ```Reuso de código:``` classes e métodos podem ser usados em diferentes partes do programa ou em outros projetos.

• ```Organização:``` o código fica mais estruturado, com objetos representando entidades reais.

• ```Facilidade de manutenção:``` alterações em uma classe refletem em todos os lugares que a usam, tornando correções mais fáceis.

• ```Encapsulamento:``` protege dados e garante que só possam ser acessados ou modificados de forma controlada.

• ```Flexibilidade e extensibilidade:``` herança e polimorfismo permitem criar novas funcionalidades sem modificar código existente.


