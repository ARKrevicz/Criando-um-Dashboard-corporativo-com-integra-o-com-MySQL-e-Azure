# Criando-um-Dashboard-corporativo-com-integra-o-com-MySQL-e-Azure
Bootcamp Python Data Analysis - Projeto Final - Relatório de ETL
1 - Cabeçalho de dados estão preenchidos de maneira correta, sem falta de dados ou redundâncias, mas os nomes foram alterados para melhor identificação do conteúdo.
2 - Transformação dos Dados de Salário para Decimal Fixo
3 - Há uma informação NULL na coluna Super Ssn, tabela employees, mas não será excluída, pois aquela pessoa é um gerente.
4 - Verificação que James Borg Ssn 888665555 é supervisor de Duas pessoas (Franklin Wong - Ssn 333445555; Jennifer Wallace - Ssn 987654321)
5 - Não há departamentos sem gerentes
6 - Não há departamento sem gerentes
7 - Tempo dos Projetos
Projeto_nome	Projeto_tempo
1		52.5
2		37.5
3		50
10		55
20		25
30		55

8 - Tratado o endereço 975-Fire-Oak-Humble-TX por 975-Fire_Oak-Humble-TXmpara possibilitar a divisão da coluna complexa de endereço em número, cidade e estado, através do delimitador "-".
9 - Realizada a mescla das consultas employee e departament gerando assim a tabela "Employee_Departament_Gerente".
10 - Foram eliminadas as colunas desnecessários e acrescentadas colunas que são interessantes para a análise naquela tabela.
11 - Foi acrescentada a coluna nome dos gerentes associados aos colaboradores, utilizando com o base o departamento ao qual eles pertencem.
12 - Foi realizada a junção/mescla da coluna nome e sobrenome dos colaboradores através do comando intercalar colunas.
13 - Foi realizada a junção/mescla da coluna departamentos com o local de cada um, fazendo com que a combinação departamento-local seja único, através do comando intercalar colunas.
14 - No caso anterior deve-se utilizar o intercalar/mesclar consulta pois este comando permite combinar tabelas com base em colunas chave, adicionando colunas adicionais de uma tabela à outra, situação que não é possível para o comando acrescentar consulta.
15 - 	James Borg: Possui 2 colaboradores
	Franklin Wong: Possui 3 colaboradores
	Jennifer Wallace: Possui 2 colaboradores
16 - Após a criação do relatório, foram eliminadas as colunas desnecessárias
