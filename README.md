# ProjetoCreditoSql

Contrução de Projeto em SQL   

Realizando a execução no AWS  S3 e ATHENA 

************************************************************************************
# TerceiraQuery

idade               	int                 	                    
sexo                	string              	                    
dependentes         	int                 	                    
escolaridade        	string              	                    
estado_civil        	string              	                    
salario_anual       	string              	                    
tipo_cartao         	string              	                    
qtd_produtos        	bigint              	                    
iteracoes_12m       	int                 	                    
meses_inativo_12m   	int                 	                    
limite_credito      	float               	                    
valor_transacoes_12m	float               	                    
qtd_transacoes_12m  	int   


# QuartaQuery

#	escolaridade
1	"sem educacao formal"
2	"na"

4	na
5	mestrado
6	graduacao
7	doutorado
8	"escolaridade"
9	"ensino medio"
10	"mestrado"
11	ensino medio
12	sem educacao formal

# QuintaQuery
#	_col0	salario_anual
1	451	$60K - $80K
2	467	$40K - $60K
3	222	$120K +
4	63	
5	4	"$60K - $80K"
6	2	"menos que $40K"
7	1	"$120K +"
8	701	menos que $40K
9	235	na
10	1	"salario_anual"
11	2	"$80K - $120K"
12	1	"$40K - $60K"
13	488	$80K - $120K

# Sexta Query 


#	_col0	sexo
1	1	"salario_anual"
2	1	"$40K - $60K"
3	1	"$80K - $120K"
4	2	"F"
5	1001	F
6	8	"M"
7	1	"""$120K +"""
8	69	
9	1	"$120K +"
10	1	"""$60K - $80K"""
11	1	"menos que $40K"
12	1	"na"
13	1	"""$80K - $120K"""
14	1	"""$40K - $60K"""
15	1	"sexo"
16	1	"$60K - $80K"
17	1	"""menos que $40K"""
18	1	"""salario_anual"""
19	1	
20	1563	M

# Setima Query 

#	limite_credito	escolaridade	tipo_cartao	sexo
1	34516.99	sem educacao formal	blue	M
2	34516.98	mestrado	gold	M
3	34516.97	mestrado	blue	M
4	34516.96	doutorado	platinum	F
5	34516.96	sem educacao formal	silver	M
6	34516.95	ensino medio	gold	M
7	34516.94	graduacao	gold	M
8	34516.94	graduacao	gold	F
9	34516.89	graduacao	silver	M
10	34516.74	ensino medio	blue	M

# OitavaQuery 

#	maior_valor_gasto	media_valor_gasto
1		
2		
3		
4		
5		
6		
7		
8		
9		
10	4686.93	1807.968
11		
12		
13		
14		
15		
16		
17		
18		
19		
20		
21		
22		
23		
24		
25		
26		
27		
28		
29		
30		
31	4776.58	1839.6226
32		
33		
34		
35		
36		
37		


# NonaQuery 

#	qts_produtos	media_valor_transacoes	media_limite	sexo	salario_anual
1	4.394230769230769	1963.6719	3452.4036	M	menos que $40K
2	4.291970802919708	1878.2974	5753.31	M	$40K - $60K
3	4.408710217755444	1845.1332	4212.1987	F	menos que $40K
4	4.352549889135255	1818.6364	9096.028	M	$60K - $80K
5	4.4404145077720205	1781.4299	4773.4463	F	$40K - $60K
6	4.329918032786885	1755.2499	14886.556	M	$80K - $120K
7	4.328828828828829	1701.4652	17801.488	M	$120K +
8				"M"	"$40K - $60K"
9				"sexo"	"salario_anual"
10				"M"	"$60K - $80K"
11				"F"	"menos que $40K"
12				"M"	"$80K - $120K"
13				"M"	"$120K +"
