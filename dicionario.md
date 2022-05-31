#### Dicionário de dados para a Árvore de Decisão
Para melhorar o desenvolvimento estou mudando alguns informações escritas por 0 ou 1. Como por exemplo na coluna do CHURN temos NO para clientes que não cancelaram o contrato e YES para clientes que cancelaram o contrato.

`0 = False / 1 = True`

* `customerID`: número de identificação único de cada cliente
* `Churn`: se o cliente deixou ou não a empresa `(0 = Clientes / 1 = Contrato Cancelado)`
* `Genero`: gênero `(0 = Masculino / 1= Feminino)` 
* `MelhorIdade`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos `(0 = Menor que 65 anos / 1 = Maior ou igual a 65 anos)` 
* `Conjuge`:  se o cliente possui ou não um parceiro ou parceira `(0 = Não tem / 1 = Tem parceirx)`
* `Dependentes`: se o cliente possui ou não dependentes `(0 = Não tem / 1 = Tem dependentes)`
* `MesesContrato`:  meses de contrato do cliente
* `ServicoTelefonico`: assinatura de serviço telefônico `(0 = Não tem / 1 = Tem)`
* `MultiplosTelefones`: assisnatura de mais de uma linha de telefone `(0.0 = Não tem / 1.0 = Tem)`
* `ServicoInternet`: tipo de assinatura de um provedor internet 
* `SergurancaOnline`: assinatura adicional de segurança online 
* `BackupOnline`: assinatura adicional de backup online 
* `ProtecaoDevice`: assinatura adicional de proteção no dispositivo 
* `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera `(0.0 = Não tem / 1.0 = Tem)`
* `StreamingTV`: assinatura de TV a cabo `(0.0 = Não tem / 1.0 = Tem)`
* `StreamingMovies`: assinatura de streaming de filmes `(0.0 = Não tem / 1.0 = Tem)`
* `TipoContrato`: tipo de contrato
* `TipoDaFatura`: se o cliente prefere receber online a fatura `(0 = Não / 1 = Sim)`
* `FormaDePagamento`: forma de pagamento
* `Cobranca.Mes`: total de todos os serviços do cliente por mês
* `Cobranca.Total`: total gasto pelo cliente
* `GastoDiario30Dias`: média do total gasto pelo clientes em 30 dias
* `GastoDiario365Dias`: média do total gasto pelo clientes em 365 dias
