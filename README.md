# Relatório Financeiro Power BI

Desafio de relatório criativo utilizando o Power BI.

Para esse projeto foi utilizada uma base de dados sample, um relatório financeiro em .csv que segue disponível neste repositório. Foi disponibilizado também o arquivo do relatório.

- relatorio financial.pbix
- Data Base.xlsx

## Visualização

Abaixo podemos ver as páginas e os gráficos gerados nesse relatório.

### Página 1

![page1](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/page%201.png?raw=true)

### Página 2

![page2](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/page%202.png?raw=true)

### Página 3

![page3](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/page%203.png?raw=true)

O relatório é todo interativo, no qual podemos selecionar datas, selecionar produtos específicos e todos os gráficos se alteram automaticamente.

## Extensões

Para esse projeto foram utilizadas duas extensões:

- **Chiclet Slicer** - Para gerar o fatiamento dos botões de data.
- **Radar Chart** - Um gráfico em forma de radar em exibição na segunda página.
- **Map Chart** - Bolhas que mostram a distribuição de dados em diferentes locais.

## Interação

![interact](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/paseo.png?raw=true)

Veja acima como ocorre a interação. Selecionamos apenas o produto **Paseo** que é também o mais vendido. Veja como todos os gráficos e cards se alteram automaticamente para apresentar somente suas informações.

## Análise

Através da análise apresentada na **terceira página**, podemos observar que as regiões com os maiores números de vendas não foram, necessariamente, as que obtiveram o maior lucro. Essa discrepância pode ser atribuída a diversos fatores, como os custos operacionais variáveis entre as regiões, a diferença nos preços de venda e a eficiência das estratégias de marketing implementadas. Portanto, é crucial considerar não apenas o volume de vendas, mas também a margem de lucro ao avaliar o desempenho regional.

---

<br></br>
<br></br>

# Criando um Dashboard Gerencial para Tomada de Decisões Com Power BI

A partir da Sample acima vamos criar um novo relatório mais estético e com mais funcionalidades.

- Botões para navegação entre as páginas.
- Alterar o viés de gráficos.
- Melhorar a visibilidade dos relatórios.
- Utilização de proporção áureo para criação de gráficos.
- Segmentação de Dados.

## Sales

![sales](https://raw.githubusercontent.com/devcaiada/sample-powerbi-dio/main/images/1-sales.png)

A primeira página dedicamos apenas para os dados referente às vendas. Incluimos também os botões de navegação entre páginas e um botão para alterar o tipo de gráfico entre Vendas por Produto e Vendas por Segmento.

## Profit

![profit](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/2-profit.png?raw=true)

A segunda página foi dedicada aos dados de Lucro. Detalhamos o lucro por segmento, lucro por ano e trimestre e criamos um botão para voltar para a Home Page.

## Report

![report](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/3-report.png?raw=true)

A terceira página dedicamos para mostrar os dados por períodos, mostrando a evolução das vendas ao longo dos meses e anos.

---

<br></br>
<br></br>

# Relatório de Vendas e Lucros com Data Analytics e Power BI

Agora, vamos aprofundar nosso relatório de vendas utilizando a amostra financeira. Vamos incluir um relatório gerencial completo que aborde as vendas e os lucros, além de utilizar opções avançadas como Top N, Gráfico de Dispersão e Gráficos Dinâmicos, acessíveis através de botões.

Também criaremos botões para navegação entre as páginas, tornando nosso relatório mais responsivo. Por fim, faremos uma verificação de outliers e adicionaremos uma pequena animação para representar o período analisado.

## Capa

![capa](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/Capa.png?raw=true)

A capa é bem estética e possui um botão **Explorar análise** que nos leva à pagina principal do relatório.

## Principal

![principal](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/Principal.png?raw=true)

Já na pagina principal encontramos todas as informações necessárias sobre vendas. Total de vendas, vendas por segmento, por país, por período e ainda possui dois gráficos dinamicos, onde podemos mudar o seu tipo e visualizar melhor as informações conforme necessário.

## Detalhes

![detalhes](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/Detalhes.png?raw=true)

Já na página de detalhes temos gráficos mais avançados, como um Histograma das unidades vendidas, uma matriz com as vendas por trimestre e um gráfico dinâmico de venda por período, onde é possível escolher entre semestre ou mês através dos botões acima.

## TOP N e Outliers

![TOPN](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/TOPN.png?raw=true)

A terceira página apresenta dois gráficos utilizando a função P e R. No primeiro gráfico, mostramos os Top 3 produtos vendidos por país, enquanto no segundo gráfico destacamos os Top 3 produtos mais vendidos no geral.

Além disso, incluímos um gráfico de dispersão de vendas, que permite observar o comportamento das vendas de cada produto ao longo dos meses. Utilizando o Eixo de Reprodução, é possível visualizar uma animação dessa variação ao longo do período analisado.

## Parâmetros

![parameter](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/country%20parameter.png?raw=true)

Na última pagina adicionamos um gráfico de segmento e um gráfico de vendas / lucro, utilizando parâmetros como comparação. Cada botão acima apresenta um parâmetro, como vendas, produto, mês e outros.
Assim os gráficos ficam mais dinâmicos e consigo ecnomizar páginas para contrastar as informações.

![parameter2](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/images/Month%20parameters.png?raw=true)

Cada botão selecionado em parâmetro, um novo gráfico é apresentado na tela, deixando as informações muito mais dinâmicas e econômicas.

## Considerações finais

Um relatório gerencial em Power BI é uma ferramenta poderosa para a tomada de decisões estratégicas. Ele permite a visualização e análise de dados de forma interativa e dinâmica, facilitando a identificação de tendências, padrões e insights valiosos.

![icon](https://github.com/devcaiada/sample-powerbi-dio/blob/main/images/final_report/icons/sales_icon.png?raw=true)

Utilizar diferentes tipos de gráficos em um relatório gerencial no Power BI permite uma análise mais completa e detalhada dos dados de vendas. Isso não só melhora a compreensão dos dados, mas também apoia a tomada de decisões informadas e estratégicas, contribuindo para o sucesso e crescimento do negócio.

Caso tenha ficado curioso ou queira saber mais sobre esse relatório, o arquivo ficara disponível para download nesse repositório:

- [**sales_report_desafio_projeto.pbix**](https://github.com/devcaiada/sample-powerbi-dio/blob/main/sales_report_desafio_projeto.pbix)
