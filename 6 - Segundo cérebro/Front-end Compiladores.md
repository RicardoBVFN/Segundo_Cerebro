
03-09-2025 11:24

Tags: [[Informática]], [[Desenvolvimento]], [[Linguagens de Programação]]
Status: #jovial 


### Definição

Particionamento do processo de compilação de software implementado pela primeira vez na LLVM[^1]. Responsável por interpretar o código escrito em linguagem de programação e transcreve-lo para IL[^2].

### Relevância

Por ser apenas responsável pela transcrição do código escrito, sua modularidade permite que os demais componentes das etapas de Optimization[^3] e Back-end[^4] possam ser reaproveitadas para qualquer linguagem de programação compilada, desde que esta possua um Front-end compatível.

Já que esta etapa é responsável pela análise ortográfica do código, em fronts mais desenvolvidos é possível integrar APISs de suporte ortográfico, sintático e semântico para feedback em tempo real.


### Referências:

[^1]: [[LLVM (Low Level Virtual Machine)]]

[^2]: [[IR Compiladores]]

[^3]: [[Optimization Compiladores]]

[^4]: [[Back-end Compiladores]]
