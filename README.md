# ETL
## Realização de ETL com MySQL, Spoon e PowerBI

Este projeto envolve a realização de processos ETL utilizando ferramentas planejadas para a análise de dados.

### Análise Inicial
Inicialmente, analisamos o banco de dados relacional MySQL, focando especificamente na tabela `vendas`. O principal indicador para o novo modelo dimensional foi o `valor de venda total`.

Utilizamos a ferramenta de administração de banco de dados, HeidiSQL, para acessar o MySQL localmente e analisar as tabelas.

![Análise de Tabelas](https://github.com/CarlosJuncher03/ETL/assets/145303814/4abeb779-37c1-44e7-8820-6268afd42a4e)

### Modelagem Dimensional
Definidas as medidas e dimensões para análise, realizamos a modelagem do banco de dados dimensional usando a ferramenta BRMODELO.

![Modelagem Dimensional](https://github.com/CarlosJuncher03/ETL/assets/145303814/f6b0f842-6f29-47c6-97e3-d41f1ae4d3b9)

### Scripting e Criação do Modelo Dimensional
Após a modelagem, geramos scripts e criamos o modelo dimensional diretamente no MySQL.

![Criação do Modelo no MySQL](https://github.com/CarlosJuncher03/ETL/assets/145303814/fdb291ac-0931-46f6-8164-1e6350c2bddd)

### Extração e Transformação
Com o banco de dados preparado, iniciamos o processo de extração e transformação dos dados utilizando o Pentaho. Durante esta fase, selecionamos a tabela principal e realizamos as transformações necessárias para criar a tabela fato, bem como as dimensões de tempo, cliente, vendedor e localização.

![Extração e Transformação no Pentaho](https://github.com/CarlosJuncher03/ETL/assets/145303814/0b143506-a049-4c5c-a5fa-f7d9ca96b1c9)

### Visualização dos Dados
Os dados transformados foram então utilizados para alimentar dashboards no PowerBI, onde desenvolvemos métricas relevantes para análise.

![Dashboard no PowerBI](https://github.com/CarlosJuncher03/ETL/assets/145303814/59661a51-9217-4dbd-98e6-6fb35ef2ce4b)

### Conclusão
Todos os arquivos e scripts utilizados neste processo estão disponíveis neste diretório.
