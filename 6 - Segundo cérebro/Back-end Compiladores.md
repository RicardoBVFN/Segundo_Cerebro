
22-09-2025 11:05

Tags: [[Informática]], [[Desenvolvimento]], [[Linguagens de Programação]]
Status: #Maduro 


### Definição

Módulo do processo de compilação em um compilador LLVM[^1]. É responsável por interpretar o código em IR[^2] otimizado na etapa de Optimization[^3] e gerar os arquivos executáveis para a arquitetura[^4] e sistema operacional da máquina na qual será rodado o programa compilado.

### Relevância

A modularização da geração de executáveis compilados é vital para a proposta de funcionamento de um compilador LLVM.

Ao se modular esta etapa, além de facilitar a manutenção do código, torna-se possível reaproveitar toda a estrutura aplicada nas etapas anteriores (front-end[^5] e Optimization), adaptando apenas a saída para as especificações da máquina.

Por fim, projetando-se para o futuro, a modularização do back-end do compilador abre a possibilidade para existir uma linguagem universal para determinados tipos de sistema. Tendo como exemplo um sistema web, ao se escrever o código para um sistema web completo (estrutura da página, interatividade e processamento de dados) em uma linguagem única e compilando este código em um LLVM, por meio da estruturação do back-end, é possível este gerar os executáveis específicos para estruturar o site e configurar iteratividade e processamento de dados a partir de uma única linguagem.


### Referências:

[^1]: [[LLVM (Low Level Virtual Machine)]]

[^2]: [[IR Compiladores]]

[^3]: [[Optimization Compiladores]]

[^4]: [[Arquitetura de Hardware]]

[^5]: [[Front-end Compiladores]]

[[Entendendo Apple, GPL e Compiladores]]

[^5]: 
