

07-08-2026 16:55

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

Uma requisição[^1] que usa o verbo HTTP[^2] HEAD utiliza a exata mesma estrutura de uma requisição do tipo GET[^3], entretanto, a response[^4] gerada ==não pode retornar uma entidade (objeto/conteúdo) em seu body==[^5]. Este tipo de requisição pode obter ==apenas os headers[^6] referentes ao alvo da requisição==.

### Relevância

Embora pareça redundante, por não retornar uma entidade em seu body, uma transação gerada por um HEAD ==consome menos largura de banda==[^7]. Dessa forma, ==a informação é trocada rapidamente e com um custo computacional menor quando comparado com o GET==. Ideal quando o objetivo do cliente é obter ==meta dados de determinado recurso== sem ter que lidar com uma representação do mesmo.

### Considerações importantes

Como uma requisição HEAD não deveria possuir body[^8], ela não possui uma semântica definida para o mesmo. Seria relevante ==realizar implantações de mecanismos de defesa no resvidor alvo da requisição para rejeitar e cancelar a conexão caso esta tenha um body== a fim de evitar ataques como request smuggling[^9]. 


### Referências:

[^1]: [[Requests]]

[^2]: [[Verbos HTTP]]

[^3]: [[GET (Verbo HTTP)]]

[^4]: [[Responses]]

[^5]: [[Response Message Body]]

[^6]: [[Response headers]]

[^7]: [[Throughput]]

[^8]: [[Request Message Body]]

[^9]: [[Request Smuggling Atack]]

[[IETF HEAD (Verbo HTTP)]]

[[0209 Os Verbos HTTP menos conhecidos]]
