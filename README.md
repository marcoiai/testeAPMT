###########
Teste CI e Jquery

Crie uma aplicação single page: 
	contendo uma listagem;
	Uma tela de cadastro contendo no minimo 4 campos distintos. 
	Faça a navegação entre as mesmas pelo Jquery.

Faça a modelagem de dados Orientada a Objeto para o form anterior.

###########
Teste PHP

Qual o retrono deste código?
$string = 'php';
$string++;
echo $string;


###########
Teste SQL

Identifique os erros e/ou melhore as query's SQL abaixo:
	
	Essa tabela possui os seguintes campos (id, nome, sobrenome, data_cadastro, status);
	"select 
	nome, sobrenome, CASE status = 1 then 'ATIVO' end status
	From usuario  
	Where 
	1 = 1  AND status = 1;"

	Essa tabela possui os seguintes campos (id, nome, id_uf, data_cadastro, status);
	"select	top(50) *
	From cidades  
	Where 
	1 = 1  AND status = 1;" 
	
	Essa tabela possui os seguintes campos (id, uf, data_cadastro, status);
	"select	top 50 *
	From estados  
	Where 
	1 = 1  AND status = 1;"

	Diga qual o retorno das query's abaixo;
	"select convert(datetime, '2020-03-01 00:00:00', 103);"
	"select convert(datetime, '01/03/2020 00:00:00', 103);"
	"select convert(datetime, '2020-03-01 00:00:00', 121);"
	"select convert(datetime, '01/03/2020 00:00:00', 121);"
	"select convert(datetime, '01/03/2020 00:00:00', 22);"
	"select convert(datetime, '2020-03-01 00:00:00', 22);"
	"select convert(datetime, '01/03/2020 00:00:00', 101);"

	descreva as diferenças dos JOINS;

#########