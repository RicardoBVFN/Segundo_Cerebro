
15-10-2025 21:49

Tags: [[Desenvolvimento]], [[Linguagens de Programação]], [[Tratamento de Dados]]
Status: #Maduro  


### Definição

Métodos[^1] da classe[^2] String em Java[^3] para manipular os valores do tipo String[^4] em objetos dessa classe.

### Tamanho fonte

- `.toLowerCase()`: passa todos os caracteres da string para o minúsculo (caso possível).

```
String teste = "TESTE";
teste = teste.toLowerCase;

// o valor de teste agora é "teste"
```

- `.toUpperCase()`: passa todos os caracteres da string para o maiúsculo (caso possível).

```
String teste = "teste";
teste = teste.toUpperCase();

// o valor de teste agora é "TESTE"
```

### Formatação

- `.trim()`: remove todos os espaços em branco das extremidades da string.

```
String teste = "     teste          ";
teste = teste.trim();

// o valor de teste agora é "teste"
```

- `.concat(String x)`: concatena uma string com outra passando a segunda como parâmetro do método.

```
String x = "hello";
String y = " world";
String z = x.concat(y);

// o valor de z é "hello world"
```

### Varreduras e verificações

- `.startsWith(String prefix)`: realiza uma varredura a partir do início da string. Caso o valor passado como parâmetro possa se onvertido para Char, verifica-se se o primeiro caractere da string corresponde a esse char. Caso o valor passado seja uma string, verifica-se se a primeira sequência de caracteres de tamanho correspondente a string passada como parâmetro corresponde a string passada como parâmetro. Retorna um valor booleano.

```
String x = "hello world";

System.out.println(x.startsWith("h")); //true
System.out.println(x.startsWith("e")); //false
System.out.println(x.startsWith("hello")); //true
System.out.println(x.startsWith("world")); //false
System.out.println(x.startsWith("hell")); //true
```

- `.length()`: retorna um valor inteiro coorespondente ao tamanho da string.

```
String teste = "isso é um teste";
System.out.println(x.length()); // 15
```

- `.equals()`: método padrão de igualdade entre objetos. Nesse caso, verifica se duas strings são exatamente iguais retornando um valor booleano.

```
String teste = "teste";
System.out.println(x.equals("teste")); // true
System.out.println(x.equals("Teste)); // false
```

- `.equalsIgnoreCase()`: verifica se a string avaliada é igual à string passada como parâmetro independentemente da formatação de seus caracteres (maiúculo e minúsculo), retornando um valor booleano.

```
String teste = "teste";

System.out.println(teste.equals("TESTE")); // flase
System.out.println(teste.equalsIgnoreCase("TESTE")); // true
```

- `.charAt(int index)`: seleciona o caractere no índice passado como parâmetro, caso este seja um índice válido para a string em questão.

```
String teste = "teste";

System.out.println(teste.charAt(2)); // "s"
System.out.println(teste.charAt(5)); // Index out of range
```

- `.substring(int index) / .substring(int beginIndex, int endIndex)`: seleciona um trecho da string analisada a partir dos índices passados como parâmetro, caso esses sejam índices válidos. Se for passado apenas um índice como parâmetro, a substring selecionada será o trecho começando a partir do índice informado e indo até o fim da string. Caso dois índices sejam passados como parâmetro, o trecho selecionado começará no índice informado no primeiro parâmetro e seguirá até o índice correspondente ao valor passado no segundo parâmetro, não incluindo o caractere neste índice.

```
String teste = "isso é um teste";

System.out.println(teste.substring(10)); // "teste"
System.out.println(teste.substring(0, 4));
```



### Referências:

[^1]: [[Método (POO)]]

[^2]: [[Classe (POO)]]

[^3]: [[Java]]

[^4]: [[String]]
