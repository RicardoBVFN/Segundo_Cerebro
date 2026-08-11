
22-09-2025 20:56

Tags: [[Informática]], [[Tratamento de Dados]]
Status: #Maduro 


### Definição

RAID 1 consiste em um tipo de estruturação de HDs[^1] em RAID[^2]. Nesse caso, o sistema operacional enxerga dois HDs como dois volumes para registro, com o ==diferencial de utilizar um componente como cópia de backup do outro==. Esse processo é realizado por meio da escrita dos exatos mesmos blocos[^3] em ambos os dispositivos.

### Relevância

Esse tipo de estruturação é ideal para máquinas cujo propósito é garantia de integridade de armazenamento de dados.

HDs são componentes mecânicos que, como qualquer outro, podem e vão deteriorar com o passar do tempo e de acordo com a intensidade do uso dos mesmos. A pesar de se ter certeza quanto à falha de um componente desse tipo, a chance de ambos falharem simultaneamente é muito baixa.

Com esse pensamento em mente, já que nesse modelo de RAID o sistema possui dois HDs com os mesmos dados, quando um dos volumes apresentar um defeito de natureza qualquer (normalmente mecânica) o gestor do sistema será notificado e terá tempo de substituir apenas o componente defeituoso sem perda de dados.

Mesmo sacrificando parte do desempenho, devido ao trabalho dobrado de escrita e consulta, esta solução é uma alternativa robusta para projetos de backup de dados sensíveis.


### Referências:

[^1]: [[HD (Hard Disk)]]

[^2]: [[RAID (Redundant Array of Inexpenive Disks)]]

[^3]: [[Bloco (dados)]]

[[Quebrei 3 HDs Entendendo Armazenamento]]