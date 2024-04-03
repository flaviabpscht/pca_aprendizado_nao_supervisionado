# <a>Projeto 4 - Aprendizado Não Supervisionado (PCA)</a>

## <a> Motivação </a>

PCA é uma ferramenta muito útil na vida real e bastante subutilizada! Mais que um "martelo matemático", a análise de componmentes principais tem muitas aplicações práticas que podem ser utilizadas em praticamente qualquer empresa/organização.

Uma das principais aplicações é na segmentação de clientes, usuários, fornecedores, etc. Imagine uma empresa que queira lançar um novo produto e realiza uma pesquisa para entender melhor as necessidades/desejos dos clientes a fim de direcionar as campanhas de marketing para o lançamento. A utilização do PCA permite reduzir a dimensionalidade das respostas a tais questionários melhor muito a compreensão e aplicação da análise de aglomerados (clusterização).

Esse tipo de problema claramente é aplicável em diversos segmentos da economia!

## <a> Motivation </a>
PCA is a very useful tool in real life and often underutilized! More than just a "mathematical hammer," principal component analysis has many practical applications that can be used in virtually any company/organization.

One of the main applications is in customer segmentation, user segmentation, supplier segmentation, etc. Imagine a company that wants to launch a new product and conducts a survey to better understand the needs/desires of customers in order to target marketing campaigns for the launch. The use of PCA allows for the reduction of the dimensionality of responses to such surveys greatly enhancing the understanding and application of cluster analysis.

This type of problem is clearly applicable in various sectors of the economy!

## <a> Objeto de Estudo </a>

Analisar a viabilidade de um novo conceito de carro, uma espécie de microvan (maior que SUV, mas menor que minivan), e conhecer melhor público para iniciar nossas campanhas de marketing.
O principal método para detectar tais tendências é a pesquisa primária do consumidor, geralmente começando com grupos focais direcionados e prosseguindo para pesquisas de média e, eventualmente, de grande escala. Essas pesquisas servem a pelo menos dois propósitos: 
- verificar os “desejos e necessidades” de um determinado grupo/nicho de consumidores
- junto com os dados demográficos, tentar avaliar o perfil de quem gostou do conceito de microvan da Let's Ride

As perguntas de negócio que queremos responder são:
- Qual é o segmento alvo para este carro? 
- Quais são os desejos e necessidades deste segmento?

Então, a Let's Ride realizou pesquisa de vários grupos focais entre potenciais compradores desses carros. Ainda, a equipe de marketing examinou uma longa lista de potenciais atributos que poderiam ser importantes para compradores de microvans, bem como declarações de estilo de vida, validadas por suas extensas pesquisas anteriores na indústria automobilística. Com base em notas detalhadas feitas durante a fase de grupo focal, estabeleceu-se em um conjunto de 30 atributos que pareciam capturar a natureza da discussão, bem como variáveis demográficas importantes. O objetivo é usar esses atributos para capturar as dimensões-chave que caracterizam potenciais compradores e identificar os segmentos que a Let's Ride poderia criar para suas campanhas. Por fim, foi apresentado um projeto do carro (microvan) para que os potenciais consumidores dessem uma nota de 1 a 9 se gostaram ou não.

O problema é que, se fizermos uma análise de aglomerados com 30 features, o resultado não será muito inteligível e ficaria difícil depreender os perfis dos clientes. Podemos reduzir a dimensionalidade das features para agrupar as que possuem variância similar (PCA) e então avaliar qual foi o resultado dessa redução em termos de interesses dos clientes. Para avaliar a homegeneidade dos grupos, somente com clusterização, mas já com PCA conseguimos ter a junção de features com variância semelhante, o que, para respostas de questionários, serve como um agrupamento de perfis de respostas.

Assim como nos outros projetos, bancos, telefônicas, varejo, qualquer empresa que presta algum tipo de serviços e possui informações sobre seus clientes pode se beneficiar de análise de questionários de clientes e redução em componentes principais conforme iremos construir nesse projeto.

ps: esse estudo de caso real (Grosse Pointe Associates and The “Microvan”) está disponível no excelente livro "Modern Marketing Research: Concepts, Methods, and Cases" ISBN 1133188966

Object of Study 
Analyzing the feasibility of a new car concept, a kind of microvan (larger than an SUV but smaller than a minivan), and getting to know the audience better to kickstart our marketing campaigns.

The main method to detect such trends is primary consumer research, usually starting with targeted focus groups and progressing to medium and eventually large-scale surveys. These surveys serve at least two purposes:

to verify the "wants and needs" of a particular group/niche of consumers
along with demographic data, to try to assess the profile of those who liked the Let's Ride microvan concept
The business questions we want to answer are:

What is the target segment for this car?
What are the wants and needs of this segment?
So, Let's Ride conducted several focus group surveys among potential buyers of these cars. Additionally, the marketing team examined a long list of potential attributes that could be important for microvan buyers, as well as lifestyle statements, validated by their extensive previous research in the automotive industry. Based on detailed notes made during the focus group phase, a set of 30 attributes was established that seemed to capture the nature of the discussion, as well as important demographic variables. The goal is to use these attributes to capture the key dimensions that characterize potential buyers and identify the segments that Let's Ride could create for its campaigns. Finally, a car design (microvan) was presented for potential consumers to rate from 1 to 9 whether they liked it or not.

The problem is that if we perform a cluster analysis with 30 features, the result will not be very intelligible and it would be difficult to discern customer profiles. We can reduce the dimensionality of the features to group those with similar variance (PCA) and then evaluate the result of this reduction in terms of customer interests. To assess the homogeneity of the groups, only with clustering, but already with PCA we can have the combination of features with similar variance, which, for questionnaire responses, serves as a grouping of response profiles.

Like in other projects, banks, telecommunications companies, retailers, any company that provides some kind of service and has information about its customers can benefit from customer questionnaire analysis and reduction in principal components as we will build in this project.

P.S: This real case study (Grosse Pointe Associates and The "Microvan") is available in the excellent book "Modern Marketing Research: Concepts, Methods, and Cases" ISBN 1133188966.

