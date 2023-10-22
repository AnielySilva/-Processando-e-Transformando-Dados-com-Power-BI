#	Desafio: Processando e Transformando Dados com Power BI - (DIO)

## Desafio proposto no bootcamp Santander 2023 - Ciência de dados com Python

1. Configurando o ambiente > Criando uma instância com Azure para MySQL
	- Ao acessar a conta no site da Azure pesquise por MySQL, vá em criar > Servidor flexível e faça a criação.
2. Criando o banco de dados com base no script disponivel no github
	- Conectando ao banco de dados pelo terminal da Azure
	- No terminal digite:
		- `mysql -h desafio-projeto-bi-dio.mysql.database.azure.com -u  powerbidio -p`
		- Digite a senha:
	- Insira o script azure_company

                                                                                              | Legendas:     |
                                                                                              |---------------|
                                                                                              | -h: Host      |
                                                                                              | -u: User      |
                                                                                              | -p: Password  |

3. Criando regra de firewall na Azure para acessar o banco de dados 
	- No menu do site Azure, vá em rede e em regras de firewall adiciona para que qualquer IP possa ter acesso

4. Criando uma conexão com o banco de dados
	- Seguindo o tutorial da Azure em: Menu > Conectar > MySQL Workbench
	
5. Abrindo o power BI 
	- Obter dados, selecione o banco de dados
