
23-09-2025 12:05

Tags: [[Informática]], [[Tratamento de Dados]]
Status: #Maduro 


### Definição

RAID 0 consiste em uma arquitetação de HDs[^1] seguindo o esquema de RAID[^2]. Nesse caso, dois HDs são dispostos de forma a representarem, um único volume correspondente a soma da capacidade de armazenamento dos mesmos, com o diferencial de se ==particionar a escrita e leitura de blocos[^3] entre os dois dispositivos==.

### Relevância

Este modelo de RAID é ideal para sistemas que buscam desempenho.

Devido a sua forma de funcionamento, sistemas que possuem seu mecanismo de armazenamento em RAID 0 podem ter um ganho de até 100% de desempenho nas operações de escrita e leitura. Com a divisão dos blocos de um arquivo, parte fica armazenada em um HD e a outra no segundo. Esse diferencial faz com que estes possam ser ==escritos e lidos de forma paralela e simultânea nos dois dispositivos==, diferentemente do método sequencial tradicional de um HD.

Um ponto negativo desta estruturação de armazenamento é que, como os blocos dos arquivos estão particionados entre dois dispositivos, caso um dos volumes falhe perdem-se todos os dados armazenados em ambos os volumes. Ocorre que, já que os blocos remanescentes estariam incompletos, todos os arquivos do sistema estariam corrompidos. 


### Referências:

[^1]: [[HD (Hard Disk)]]

[^2]: [[RAID (Redundant Array of Inexpenive Disks)]]

[^3]: [[Bloco (dados)]]

[[Quebrei 3 HDs Entendendo Armazenamento]]