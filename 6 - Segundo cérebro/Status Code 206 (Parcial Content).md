

27-01-2026 18:49

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 206[^2] indica que o servidor ==processou de forma satisfatória a requisição[^3] mas decidiu enviar apenas parte do conteúdo requisitado==, por qualquer motivo que seja. Mesmo não contendo todas as informações requisitadas, ==a response[^4] recebida de ser suficiente para satisfazer a demanda do cliente==.

### Relevância

Esse status é importante para reconhecer o motivo de não se ter retornado todos os dados. ==Normalmente o servidor envia esse status quando uma ação de otimização foi tomada, a fim de aliviar a carga no tráfego da informação==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 2xx]]

[^3]: [[Requests]]

[^4]: [[Responses]]

[[RFC Status Code 206]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]