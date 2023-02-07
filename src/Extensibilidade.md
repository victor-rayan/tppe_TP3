# Característica: Extensibilidade

### Descrição: 

A extensibilidade permite que o software seja facilmente adaptado para atender a novas demandas ou mudanças futuras. Essas mudanças podem ser feitas por meio da adição de novas funcionalidades ou por meio da modificação de funcionalidades existentes

Pode-se fazer isso por meio da modularização do código, separando o código em partes menores e independentes com baixo acoplamento entre eles. Isso permite que novos recursos sejam adicionados ou modificados sem afetar o funcionamento geral do software. 

A extensibilidade melhora a clareza e a coesão do código, tornando mais fácil manter e evoluir o software, ou seja prevendo melhorias sem prejudicar o código existente.

### Relação com maus cheiros: 

A Extensibilidade contribui para evitar maus-cheiros:

* Código Duplicado: Ao separar o código em partes menores, fica mais fácil encontrar e remover códigos repetidos, tornando a reutilização mais fácil.

* Métodos Longos: Quando o código é modularizado, é mais fácil identificar trechos de código que possam ser extraídos para novos métodos, tornando-os mais claros e fáceis de entender.

* Herança negada: Quando uma classe é estendida e contém informações desnecessárias herdadas da classe principal, isso pode resultar em problemas que serão propagados.

* Classes Grandes: Ao modularizar o código, é possível separar responsabilidades em classes menores e mais claras, evitando classes gigantes e difíceis de entender.

### Operação de refatoração:

Exemplos de operações de refatoração que podem ser usadas para melhorar a extensibilidade do código são:

* Extrair método: Ao extrair código repetido em um método separado, é possível aumentar a clareza e a reutilização do código.

* Extrair classe: Colocar partes do código em uma nova classe para deixar o código mais organizado e fácil de entender."

* Introduzir interface: Define uma interface para uma classe para tornar o acoplamento mais fraco e o código mais flexível.

* Herança negada: 
    *  Mover métodos e campos que não são usados para outra classe relacionada.
    *  Usar delegação em vez de herança: Quando uma classe filha não precisa herdar a forma como a classe mãe implementa uma interface."

