# Segmentação de Clientes

****

## 🔍 Sobre o projeto

Neste projeto, vamos fazer um trabalho de segmentação de clientes. O intuito é poder fazer campanhas mais direcionadas a um determinado público que tem uma maior propensão ao consumo de um produto, tipo de oferta etc.. Com isso, reduzimos o custo por aquisição de clientes (CPA) devido ao aumento da probabilidade de compra. 

Para começarmos, vou falar sobre o framework STP. Ele é um conceito que se baseia na Segmentação, Targeting e Posicionamento. 

<ol>
    <li> <strong>Segmentação</strong>: é o processo de separar os nossos clientes em grupos que compartilham características comportamentais semelhantes. Se fizermos observações dentro de um mesmo grupo, iremos observar comportamentos de compra e reações a ofertas de forma bem similar.
    <li> <strong>Targeting</strong>: é o processo de mensurar o lucro potencial de cada grupo e decidir em qual deles focar. Um dos critérios a serem analisados é o seu tamanho atual, potencial de crescimento e as ofertas dos concorrentes. Além disso, aqui é onde você irá selecionar os meios de veiculação do anúncio (TV, online, outdoor etc.).
    <li> <strong>Posicionamento</strong>: aqui é onde você vai pensar em qual é(são) o(s) produto(s) que se enquadra(m) mais com as características e necessidades do seu segmento. Mostra como o produto deve ser apresentado ao cliente e através de qual meio. 
</ol>

<br>
Agora, vamos falar sobre Marketing Mix. Basicamente, Marketing Mix é você desenvolver o melhor produto para o seu segmento com o preço certo e apresentá-lo através dos canais certos.

Neste projeto de análise de clientes, vamos focar em responder 3 perguntas:

<ol>
    <li> O cliente irá comprar um produto de uma determinada categoria quando ele entrar na loja?
    <li> Qual marca ele irá escolher?
    <li> Quantas unidades do produto ele irá comprar?
</ol>


Essas 3 perguntas se baseiam no comportamento do cliente quando ele entra em uma loja. Primeiramente, ele se pergunta se vai ou não comprar um determinado produto (probabilidade de compra). Depois, caso ele decida que irá comprar, ele pensa de qual marca será. Após decidir a marca, ele pensa em quantos produtos irá levar daquela marca.  


Esses questionamentos fazem parte do que chamamos de os 4P's do Marketing: Produto, Preço, Promoção e Posicionamento. 

Agora, vamos fazer a apresentação do dataset que iremos utilizar:

<ul>
    <li> ID - Identificador do cliente
    <li> Sex - Gênero (0 -> Homem, 1 -> Mulher)
    <li> Marital status - Estado civil (0 -> Solteiro, 1 -> Não solteiro)
    <li> Age - Idade
    <li> Education - Nível de educação (0 -> Outro/Desconhecido, 1 -> Ensino Médio, 2 -> Ensino Superior, 3 -> Pós-graduação)
    <li> Income - Salário anual declarado em dólares americanos
    <li> Occupation - Categoria do emprego (0 -> Desempregado, 1 -> Funcionário qualificado, 2 -> Funcionário altamente qualificado ou empreendedor)
    <li> Settlement size - Tamanho da cidade que o consumidor vive (0 -> Pequena, 1 -> Médio porte, 2 -> Cidade grande)
</ul>

## 🗃️ Tópicos do projeto

O projeto é dividido nos seguintes tópicos:
<ol>
  <li> Decrição do Banco de Dados
  <li> Cluster Hierárquico
  <li> Cluster com o algoritmo K-Means
  <li> Análise dos Componentes Principais (PCA)
  <li> Aplicando K-Means com PCA
  <li> Exportação de dados com Pickle
</ol>
