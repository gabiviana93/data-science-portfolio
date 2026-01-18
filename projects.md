# Projetos de Data Science

## 🏢 Teste Técnico – Mercado Livre
🔗 Repositório: https://github.com/gabiviana93/teste_mercado_livre

**Problema**
- Realizar análises exploratórias sobre Ofertas Relâmpago
- Prevenção de Falhas - Determinar a condição de aparelhos de Telemetria em serviço para prever quando a manutenção deve ser realizada, com foco naredução de custos do processo

**Abordagem**
- Análise exploratória
- Normalização dos dados
- Testes de predição com modelos Baseline
- Testes de balanceamento das classes (Undersampling e Oversampling)
- Comparação dos resultados com curva ROC e Matriz de Confusão

**Destaques técnicos**
- ROC-AUC como métrica principal
- Testes com balanceamento e vários modelos preditivos

---

## 🏢 Teste Técnico – Datasprints
🔗 Repositório: https://github.com/gabiviana93/teste-datasprints

**Problema**
- Realizar análises exploratórias sobre o dataset NYC Trips para identificar perfis de passageiros, sazonalidade e padrões de viagens

**Abordagem**
- Análise exploratória
- Utilização de serviços AWS como Sagemaker e S3 
- Uso de Pyspark

**Destaques técnicos**
- Pyspark utilizado para processar grande volumetria de dados
- Uso de serviços AWS

---

## 🏢 Teste Técnico – Maxmilhas
🔗 Repositório: https://github.com/gabiviana93/teste_maxmilhas

**Problema**
- Identificar tendências e preferências dos clientes com base em análises realizadas para responder aos seguintes questionamentos: 
    Tópico 1: Análise para Construir a Marca e Suportar as Buscas
        **Hipóteses:**
        * Adultos levam mais crianças ou bebês para viagens?
        * Qual a relação entre a duração da viagem (intervalo entre a ida e a volta do cliente) e a aquisição prévia de passagens aéreas?
        * Há a preferência de alguma empresa aérea pelo cliente para a realização de viagens internacionais? 
        * O cliente prioriza ou pelo menos considera a escolha de uma classe de viagem Executiva ao realizar uma viagem internacional?
        * Qual a relação entre a duração da viagem e a quantidade de viajantes (adultos, crianças e bebês)? 
        * O cliente costuma viajar a um mesmo local específico ou em locais próximos anualmente?

        **Motivação da Análise:**
        Traçar perfis de buscas dos clientes de modo a conhecer seus destinos de interesses e preferências para viagens e melhorar as recomendações de passagens e promoções de forma a impulsionar vendas e gerar fidelizações.

        **Execução da Análise:** 
        Realizar análises nos dados, utilizando a técnica de leitura de dados em partes (chunks), efetuando os tratamentos e validações necessárias a cada uma dessas partes dos dados e trabalhando com uma amostra de dados que represente bem cada uma das partes da fonte original dos dados. Através dessa amostra, pode-se correlacionar as informações e representá-las graficamente para visualizar as respectivas influências de cada uma dessas informações.

    Tópico 2: Minimizar Riscos de mercado e concorrência com as companhias aéreas e outros portais
        **Hipóteses:**
        * Adultos levam mais crianças ou bebês para viagens?
        * Qual a relação entre a duração da viagem (intervalo entre a ida e a volta do cliente) e a aquisição prévia de passagens aéreas?
        * Há a preferência de alguma empresa aérea pelo cliente para a realização de viagens internacionais? 
        * O cliente prioriza ou pelo menos considera a escolha de uma classe de viagem Executiva ao realizar uma viagem internacional?
        * Qual a relação entre a duração da viagem e a quantidade de viajantes (adultos, crianças e bebês)? 
        * O cliente costuma viajar a um mesmo local específico ou em locais próximos anualmente?

        **Motivação da Análise:**
        Conhecimento maior dos concorrentes para obter vantagens competitivas, atrair mais clientes através de ofertas e descontos de forma a consolidar-se mais no mercado

        **Execução da Análise:**
        Realizar análises nos dados para identificar tendências de compras e passagens menos vendidas em uma determinada região para realizar promoções, monitorar ferramentas e portais de concorrentes através de técnicas de webscrapping para verificar se os preços aplicados estão abaixo ou acima dos praticados por eles.

    Tópico 3: Construir a Marca

        **Hipóteses:**
        * Sugerir passagens a clientes baseado em indicadores de interesses e compras realizadas anteriormente: 
        * Sugerir a melhor época para a compra de uma passagem para um determinado estado baseado nos interesses do cliente 
        * Sugerir passagens a clientes através de indicadores de locais de interesse e os melhores períodos nos quais o cliente encontrará os melhores preços para realizar viagens que possui interesse.

        **Motivação da Análise:**
        Prospecção de novos clientes, construção da marca, e fidelização de antigos clientes.

        **Execução da Análise:**
        Realizar estudos através de análises nos dados para identificar tendências de compras dos clientes e sugerir através desses estudos as passagens e as melhores épocas de compras para uma determinada região.

**Abordagem**
- Análise exploratória
- Utilização de Pandas, Matplotlib, Seaborn e Numpy
- Pré-processamento de dados

**Destaques técnicos**
- Pré-processamento de dados com LabelEncoding
- Leitura e processamento de dados usando chunks (base com grande volumetria de dados)

---