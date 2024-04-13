# ETL
Realização de ETL com MySQL, Spoon e PowerBI

Realização de ETL utilizando ferramentas e processos planejado

Primeiramente foi analisado o banco de dados relacional no qual seria analisado a tabela vendas para ter como principal medida para o novo modelo dimensional o valor de venda total

Usando  ferramneta de Administração de Banco de dados Heide Sql e acessado de forma local o banco de dados MySQL, foi realizado todo o proceso passo a passo para analisar as tabelas
![image](https://github.com/CarlosJuncher03/ETL/assets/145303814/4abeb779-37c1-44e7-8820-6268afd42a4e)

Após definir de forma pratica qual seria a médida a ser analisada completamente e as dimensões que serão os grãos de filtragem dos dados, foi realiado a modelagem do banco de dados dimensional utilizando a ferramenta BRMODELO
![Modelagem](https://github.com/CarlosJuncher03/ETL/assets/145303814/f6b0f842-6f29-47c6-97e3-d41f1ae4d3b9)

Após isso foi realizado a geração do script e criado o modelo dimensional no MySQL
![image](https://github.com/CarlosJuncher03/ETL/assets/145303814/fdb291ac-0931-46f6-8164-1e6350c2bddd)

Extração e Tranformação

Coom a criação do banco de dados realizada com sucesso, iniciou o processo de extração e tranformação dos dados na ferramenta Pentaho. Onde foi realizado o processo de seleção da tabela e criação e transformações da tabela fato, dimensão tempo, dimensão cliente, dimensão vendedor e diensão local
![image](https://github.com/CarlosJuncher03/ETL/assets/145303814/0b143506-a049-4c5c-a5fa-f7d9ca96b1c9)

Leitura

Após a inserção dos dados no relatorio dimensional, foi utlizado o PowerBi, no qual foi desenvlveido metricas com o dashbord 
![image](https://github.com/CarlosJuncher03/ETL/assets/145303814/76ffeacf-c327-4ed4-8e4b-a0b0e5ccd85d)

Finalizaçao
Todos os arquivos desse processo são encontrados nesse diretorio
