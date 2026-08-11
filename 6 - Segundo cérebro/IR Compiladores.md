
21-09-2025 11:20

Tags: [[Informática]], [[Desenvolvimento]], [[Linguagens de Programação]]
Status: #Maduro 


### Definição

IR (Intermediate Language) consiste em uma linguagem intermediaria, como o próprio nome sugere, que age entre com fator comum na compilação de programas. Possui sua aplicação na fase entre a linguagem de alto nível (front-end[^1]) e a saída para linguagem de máquina (back-end[^2]) de um compilador LLVM[^3].

### Relevância

Por ser um intermediador universal entre o código escrito e a execução do programa, a IR torna muito mais prático o processo de compilação de uma linguagem.

Adaptando-se o front-end do compilador, qualquer linguagem pode ser traduzida para IR. Uma vez traduzido, o código pode ser otimizado pelo mesmo algoritmo de Optimization[^4] independentemente da linguagem que está sendo compilada, tornando este processo muito mais otimizado e modulável.

Por fim, fazendo projeções para o futuro, uma linguagem intermediaria comum poderia ser o alicerce de uma revolução no desenvolvimento de aplicações. Pro exemplo, com os front-ends de compilador corretos, seria possível, em tese, desenvolver e otimizar o client-side, interatividade e server-side de uma aplicação web com um mesmo compilador por meio da IR.


### Referências:

[^1]: [[Front-end Compiladores]]

[^2]: [[Back-end Compiladores]]

[^3]: [[LLVM (Low Level Virtual Machine)]]

[^4]: [[Optimization Compiladores]]

[[Entendendo Apple, GPL e Compiladores]]
