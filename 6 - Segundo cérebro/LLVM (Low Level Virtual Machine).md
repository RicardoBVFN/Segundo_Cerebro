
02-09-2025 11:13

Tags: [[Informática]]; [[Desenvolvimento]]; [[Linguagens de Programação]]
Status: #jovial 


### Definição

LLVM consiste em um compilador de código livre (Open Source[^1]) que surgiu como uma evolução do modelo monolítico do GCC. Sua principal evolução foi a divisão dos processos de compilação em três etapas: Front-end[^2], Optimization[^3] e Back-end[^4].

### Relevância

A divisão da compilação em etapas trouxe múltiplos ganhos para a computação.

Com a subdivisão do processo, o compilador se tronou mais modulável. Com o uso de uma linguagem intermediária[^5] e pela saída ser um executável já condizente com a arquitetura[^6] da máquina na qual o programa será executado, torna-se possível reaproveitar toda a estrutura do compilador para várias linguagens de programação, devendo apenas adaptar o fronteando do mesmo.

Outro aspecto de grande importância alcançado pro meio da divisão do compilador é uma maior facilidade de manutenção em relação ao modelo antigo. Por se tratar de um monolito[^7], a manutenção em compiladores antigos se mostrava mais trabalhos pelo fato das classes interferirem diretamente umas nas outras.


### Referências:

[^1]: [[Open Source]]

[^2]: [[Front-end Compiladores]]

[^3]: [[Optimization Compiladores]]

[^4]: [[Back-end Compiladores]]

[^5]: [[IR Compiladores]]

[^6]: [[Arquitetura de Hardware]]

[^7]: [[Monolito]]

[[Entendendo Apple, GPL e Compiladores]]
