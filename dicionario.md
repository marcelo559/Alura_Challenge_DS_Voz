#### Dicionário de dados para a Árvore de Decisão
Para melhorar o desenvolvimento estou mudando alguns informações escritas por 0 ou 1. Como por exemplo na coluna do CHURN temos NO para clientes que não cancelaram o contrato e YES para clientes que cancelaram o contrato.

`0 = False / 1 = True`

* `customerID`: número de identificação único de cada cliente
* `Churn`: se o cliente deixou ou não a empresa `(0 = Clientes / 1 = Contrato Cancelado)`
* `gender`: gênero `(0 = Masculino / 1= Feminino)` 
* `SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos `(0 = Menor que 65 anos / 1 = Maior ou igual a 65 anos)` 
* `Partner`:  se o cliente possui ou não um parceiro ou parceira `(0 = Não tem / 1 = Tem parceirx)`
* `Dependents`: se o cliente possui ou não dependentes
* `tenure`:  meses de contrato do cliente
* `PhoneService`: assinatura de serviço telefônico 
* `MultipleLines`: assisnatura de mais de uma linha de telefone 
* `InternetService`: assinatura de um provedor internet 
* `OnlineSecurity`: assinatura adicional de segurança online 
* `OnlineBackup`: assinatura adicional de backup online 
* `DeviceProtection`: assinatura adicional de proteção no dispositivo 
* `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera
* `StreamingTV`: assinatura de TV a cabo 
* `StreamingMovies`: assinatura de streaming de filmes 
* `Contract`: tipo de contrato
* `PaperlessBilling`: se o cliente prefere receber online a fatura
* `PaymentMethod`: forma de pagamento
* `Charges.Monthly`: total de todos os serviços do cliente por mês
* `Charges.Total`: total gasto pelo cliente
