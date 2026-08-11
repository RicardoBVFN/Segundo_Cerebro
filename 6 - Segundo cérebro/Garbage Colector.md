
28-10-2025 10:58

Tags: [[Informática]], [[Linguagens de Programação]], [[Desenvolvimento]] 
Status: #Maduro 


### Definição

O garbage colector faz parte do pacote de tecnologias presente na linguagem Java[^1], sendo responsável por realizar o ==gerenciamento da alocação de memória dos programas de forma automática.== 

O algoritmo realiza um mapeamento de todos os objetos[^2], de seus ponteiros[^3] os seus respectivos espaços de memória. A verificação fundamental consiste em ==checar se a memória alocada ainda é referenciada por um objeto no código==. Esse processo de perda de referência pode acontecer de algumas maneiras:

Ex1: quando uma variável sai do escopo de execução do programa

```
public class teste{
	public static void main(String[] args){
		mensagemTeste(); //	B						
		System.out.println("\nfim do teste"); // C
	}
	
	public void mensagemTeste(){
		Mensagem msg = new Mensagem(); // A										
		msg.setMensagem("isso é um teste");
		System.out.println(msg.getMensagem());
	}
}
```

No ponto **A** o objeto msg é criado e recebe um espaço a memória para realizar suas operações, assim como um ponteiro para o mesmo (considerando que a classe[^5] Mensagem já exista e que seu método construtor[^6] segue o padrão usado no exemplo). No ponto **B** o método é chamado e o objeto msg é instanciado.

Já no ponto **C** o objeto passa a estar fora do escopo de execução do programa, portanto, deixa de existir. como o espaço de memória anteriormente alocado não mais é referenciado por um objeto, este será liberado pelo garbage colector.

Esse modus operandi é o motivo ==declarar variáveis (instanciar objetos) no menor escopo possível ser uma boa prática no desenvolvimento de código em Java==. Quando estruturado dessa forma, a memória é utilizada somente quando necessário, otimizando o funcionamento e a performasse do programa.

Ex2: quando o objeto perde a referência (ponteiro) ao espaço de memória para ele alocado

```
public class teste{
	public static void main(String[] args){
		mensagemTeste(); //	C						
		System.out.println("\nfim do teste");
	}
	
	public void mensagemTeste(){
		Mensagem msg = new Mensagem(); // A										
		msg.setMensagem("isso é um teste");
		System.out.println(msg.getMensagem());
		msg = Null; // B
	}
}
```

Adaptando o exemplo anterior, no ponto **A** o objeto é instanciado e um espaço na memória é alocado para o mesmo.

Em Java, um objeto armazena apenas os métodos de sua classe e o ponteiro para o seu espaço de memória. Quando se atribui um valor `Null` para um objeto, como visto no ponto **B**, o que ocorre na verdade é a atribuição deste valor nulo como ponteiro do objeto. Isso leva à perda de referência deste objeto ao espaço de memória anteriormente referenciado, tornando o mesmo em "lixo de memória".

Obs: esse mesmo efeito ocorreria caso o objeto recebesse um pontiro para outro endereço de memória e não houvesse um outro objeto apontando para o primeiro espaço de memória.

```
Mensagem msg = new Mensagem();
msg.setMensagem("isso é um teste");

msg = new Mensagem(); // o objeto recebe um novo ponteiro para um novo endereço de
						memória enquanto o original é perdido, tornando este um
						lixo de memória
```

Dessa forma, ainda no ponto **C**, mesmo estando dentro do escopo de execução do programa, o garbage colector irá agir sobre o espaço de memória anteriormente alocado para o objeto `msg`, liberando o mesmo.

### Relevância

A pesar de ser visto por muitos usuários como um recurso pesado e desnecessário, o garbage colector foi um dos elementos precursores do paradigma moderno de programação.

Em seus precursores, como C[^7] e C++, o gerenciamento de memória é completamente manual. Esse aspecto é interessante pois permite que o programador tenha total controle do uso de memória por parte de seu programa, permitindo o desenvolvimento voltado para alto desempenho e para projetos com recursos computacionais limitados. Entretanto, o fato de o programador ser responsável por configurar cada variável individualmente por vezes levava a vazamentos de memória e aumentava consideravelmente a complexidade do projeto.

Com a chegada do garbage colector, essa complexidade pode ser solucionada. Com o gerenciamento de memória sendo realizado automaticamente, a complexidade do programa pode ser reduzida drasticamente. Além disso, permitiu-se que o desenvolvedor pudesse direcionar sua mais sua atenção ao algoritmo e manutenção de regras de negócio e menos aos pormenores da linguagem.

Dessa forma, com foco maior em organização e clareza de código, o Java, ainda em 1996, já se alinhava com o padrão de desenvolvimento predominante no mercado de tecnologia nos dias de hoje.

### Referências:

[^1]: [[Java]]

[^2]: [[Objeto]]

[^3]: [[Ponteiros]]

[^4]: [[Escopo (Linguagens de Programação)]]

[^5]: [[Classe (POO)]]

[^6]: [[Método Construtor]]

[^7]: [[Linguagem C]]

[[Java's Garbage Collection Explained - How It Saves your Lazy Programmer Butt]]