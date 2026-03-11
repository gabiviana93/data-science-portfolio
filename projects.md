# Projetos de Data Science

## 🏢 Modelo preditivo de churn - Telecomunicações
🔗 **Repositório:** [GitHub](https://github.com/gabiviana93/telco_churn_clients)

**Desafios:**

    - Prever a probabilidade de clientes de telecomunicações cancelarem seus serviços (churn) para permitir ações de retenção
    - Identificar a maior proporção possível de churners reais (76% de recall) com precisão aceitável (55%) para maximizar o impacto de negócio
    - Desenvolver um pipeline completo e profissional de Machine Learning, desde a análise exploratória até o deploy e monitoramento em produção
    - Gerenciar o desbalanceamento de classes inerente a problemas de churn (taxa de 26,5%)

Abordagem:

    - Análise exploratória detalhada (EDA) com Pandas, Matplotlib e Seaborn, incluindo cálculo de Information Value (IV) para seleção de features
    - Engenharia de features avançada, expandindo 19 features originais para 48 novas variáveis
    - Criação de um pipeline modular e reprodutível com separação clara de responsabilidades (src/, scripts/, notebooks/)
    - Experimentação com múltiplos algoritmos: LightGBM, XGBoost, CatBoost e métodos ensemble
    - Tratamento do desbalanceamento com técnicas híbridas como SMOTETomek (combinação de oversampling e undersampling)
    - Otimização de hiperparâmetros com Optuna, incluindo pruning bayesiano e otimização específica do threshold de decisão para maximizar F1-Score
    - Avaliação robusta com múltiplas métricas: F1-Score (0.635), ROC-AUC (0.842), AUPRC (0.654), além de Precision, Recall e Matriz de Confusão
    - Implementação de práticas de MLOps: tracking de experimentos com MLflow, containerização com Docker (multi-stage), orquestração com docker-compose, CI/CD com GitHub Actions
    - Disponibilização do modelo via API REST com FastAPI e criação de dashboard interativo com Streamlit para visualização de resultados e monitoramento de drift

---


## 🏢 Teste Técnico – Mercado Livre
🔗 **Repositório:** [GitHub](https://github.com/gabiviana93/teste_mercado_livre)

**Desafios:**
- Análises exploratórias sobre Ofertas Relâmpago
- Previsão de manutenção em equipamentos de telemetria para redução de custos

**Abordagem:**
- Análise exploratória e normalização de dados
- Modelos Baseline com testes de balanceamento (Undersampling/Oversampling)
- Avaliação com ROC-AUC, curva ROC e Matriz de Confusão

---

## 🏢 Teste Técnico – Datasprints
🔗 **Repositório:** [GitHub](https://github.com/gabiviana93/teste-datasprints)

**Desafio:**
- Análise exploratória do dataset NYC Trips para identificar perfis de passageiros, sazonalidade e padrões de viagens

**Abordagem:**
- Processamento de grandes volumes com **PySpark**
- Integração com serviços **AWS** (SageMaker e S3)

---

## 🏢 Teste Técnico – Maxmilhas
🔗 **Repositório:** [GitHub](https://github.com/gabiviana93/teste_maxmilhas)

**Desafio:**
Identificar tendências e preferências de clientes para três objetivos estratégicos:

### 📌 Tópico 1: Construir a Marca e Suportar Buscas
**Objetivo:** Traçar perfis de clientes para melhorar recomendações de passagens e promoções

**Questões investigadas:**
- Composição de viajantes (adultos, crianças, bebês)
- Relação entre duração da viagem e compras anteriores
- Preferências de companhias aéreas para voos internacionais
- Preferência por classe executiva em viagens internacionais
- Correlação entre duração e quantidade de viajantes
- Padrões de destinos recorrentes

### 📌 Tópico 2: Minimizar Riscos Competitivos
**Objetivo:** Ganhar vantagem competitiva através de análise de mercado e concorrentes

**Estratégias:**
- Identificar tendências de compra e passagens menos vendidas por região
- Monitorar portais de concorrentes via **web scraping**
- Comparar preços com o mercado para ofertas estratégicas

### 📌 Tópico 3: Fidelização e Recomendação
**Objetivo:** Prospectar novos clientes e fidelizar existentes

**Iniciativas:**
- Sugerir passagens baseadas em histórico de interesses e compras
- Identificar melhor época de compra por destino
- Recomendar períodos com melhores preços

**Abordagem técnica:**
- Processamento de grandes datasets usando **chunks**
- Tratamentos e validações em cada partição
- Análise estatística e visualizações com **Pandas, Matplotlib, Seaborn e Numpy**
- Pré-processamento com **LabelEncoding**
