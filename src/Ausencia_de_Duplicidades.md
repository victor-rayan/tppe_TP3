# Característica: Ausência de Duplicidades

### Descrição: 

A ausência de duplicidades em software garante que o código é escrito de uma forma que não existem trechos de código repetidos ou parecidos em diferentes partes do sistema.

Os principais efeitos no código em termo de coesão é manter o código mais coerente,pois todas as tarefas são realizadas por funções únicas e não há várias implementações parecidas no código.

Também, se precisar dar manutenção em alguma parte do código, não é necessário procurar em várias partes do sistema, o que evita erros e torna o processo de manutenção mais rápido.

Por fim, a estrutura é clara, o código é mais fácil de ler e entender, pois não há trechos repetidos que possam causar confusão. Dessa forma, como o código é mais estruturado, há menos dependências entre as partes do sistema, tornando-o mais fácil de mudar ou manter (Menor Acoplamento).

### Relação com maus cheiros: 

A ausência de duplicidade contribui para evitar maus-cheiros:

- Duplicação de código: Quando o código é repetido em várias partes do sistema, isso torna o código mais complexo, mais difícil de dar manutenção e mais propenso a erros.

- Espaguetificação: quando o código é repetido em vários lugares, ele pode ficar muito longo e difícil de entender. Além disso, mudanças no código duplicado precisam ser feitas em vários lugares, o que torna o processo de manutenção mais demorado.

- Acoplamento ruim: a duplicação pode tornar o acoplamento entre as partes do sistema mais forte, o que pode tornar o sistema mais propenso a erros.

### Operação de refatoração:

- Extrair método: Ao extrair código repetido em um método separado, é possível aumentar a clareza e a reutilização do código.

- Extrair classe: Remover trechos de código repetidos e colocando eles em uma classe separada, ajuda a evitar a duplicação de código, aumenta a clareza e a coesão do código.




