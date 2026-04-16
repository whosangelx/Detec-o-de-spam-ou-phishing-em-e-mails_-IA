# Revisão da Literatura Científica Experimental com Aprendizado de Máquina

## Tema
**Detecção de spam ou phishing em e-mails com técnicas de aprendizado de máquina**

## Integrantes
- Nome Chyntia freitas prestes
- Nome do João Vitor Oliveira
---

# 2. Questões de pesquisa geradas

As questões de pesquisa definidas para esta revisão foram:

1. Quais são os métodos de aprendizado de máquina para detecção de spam e phishing por e-mail, incluindo classificação e agrupamento? 
2. Quais são os principais desafios no uso de aprendizado de máquina para detecção de phishing por e-mail? 
3. Como as tarefas de classificação e regressão se desempenham na detecção de e-mails de spam?
4. Quais são os métodos de aprendizado de máquina para detecção de spam e phishing por e-mail, incluindo classificação e agrupamento?
5. Quais são os principais desafios no uso de aprendizado de máquina para detecção de phishing por e-mail?
6. Como as tarefas de classificação e regressão se desempenham na detecção de e-mails de spam?




---

# 3. Strings de busca utilizadas pela ferramenta

As strings de busca utilizadas foram:

```text
("spam detection" OR "phishing detection") AND "email" AND ("machine learning" OR "classification" OR "clustering" OR "regression")
"email security" AND "machine learning" AND ("spam" OR "phishing") AND "challenges"
("machine learning" OR "deep learning") AND "phishing email detection" AND "comparative study"
ti:"spam detection" AND abs:"machine learning"
ti:"phishing detection" AND abs:"email"
Spam and phishing detection in emails using machine learning (classification, regression, clustering), including problem description, application, and challenges.
---

# 4. Seleção dos artigos
- A Review On Machine Learning Algorithms In Enhancing Email Security
- Enhancing email security: A hybrid machine learning approach for spam and malware detection
- Deciphering Spam Through AI: From Traditional Methods to Deep Learning Advancements in Email Security
- Email Spam Detection by Machine Learning Approaches: A Review
- A Systematic Review on Deep-Learning-Based Phishing Email Detection
- Enhancing Email Security with AI: A Review of Machine Learning, Deep Learning and Fuzzy Logic Approaches
- Hybrid machine learning approach for phishing email detection using NLP and ensemble models
- Revolutionizing Email Security with Machine Learning and NLP for Spam Detection


---

# 6. Texto de revisão da literatura gerado pela ferramenta

Revisão da Literatura: Detecção de Spam e Phishing com Aprendizado de Máquina
A detecção de spam e phishing em e-mails é um dos pilares da segurança cibernética moderna. Com base na análise de 239 artigos científicos recentes, consolidei as informações solicitadas sobre o problema, suas aplicações, métodos de solução e os desafios persistentes na literatura acadêmica.

1. Descrição Clara do Problema
O problema consiste na identificação automatizada de mensagens de e-mail indesejadas (spam) ou maliciosas (phishing).

Spam: Geralmente refere-se a mensagens em massa não solicitadas, muitas vezes de cunho publicitário, que consomem largura de banda e produtividade.
Phishing: É uma forma mais perigosa que utiliza engenharia social para enganar o usuário, visando roubar credenciais de acesso, informações financeiras ou instalar malware. O objetivo das soluções de Aprendizado de Máquina (ML) é filtrar essas mensagens antes que cheguem à caixa de entrada do usuário, minimizando o risco de comprometimento de dados [1][2].
2. Áreas de Aplicação
A detecção de ameaças via e-mail é aplicada em diversos contextos críticos:

Segurança Corporativa: Implementação em servidores de e-mail empresariais para proteger ativos e dados confidenciais de organizações [2].
Proteção do Usuário Final: Plugins de navegador, extensões e filtros nativos em provedores de e-mail (como Gmail ou Outlook) que inspecionam URLs e anexos em tempo real [4].
Plataformas de Big Data: Uso de arquiteturas escaláveis (como a Arquitetura Lambda) para processar volumes massivos de dados de e-mail em grandes infraestruturas [3].
Sistemas de Resposta a Incidentes: Integração com Centros de Operações de Segurança (SOC) para monitorar e bloquear campanhas de ataque coordenadas [2].
3. Tipos de Tarefas de Aprendizado de Máquina
As abordagens na literatura dividem-se principalmente em três categorias de tarefas:

Classificação (Tarefa Principal): É a mais comum. O modelo é treinado para rotular um e-mail como "Ham" (legítimo), "Spam" ou "Phishing".
Exemplos: Random Forest (RF), Support Vector Machines (SVM), Naive Bayes, e modelos de Deep Learning como BERT e LSTMs [1][5].
Regressão: Utilizada para prever a probabilidade ou o "score de risco" de uma mensagem. Em vez de um rótulo binário, o sistema atribui um valor contínuo que pode ser usado para decisões de filtragem mais granulares.
Exemplos: Regressão Logística (frequentemente usada como classificador probabilístico) e árvores de regressão (CART/BART) para análise de impacto [5].
Agrupamento (Clustering): Tarefa não supervisionada usada para identificar novos padrões de ataque ou descobrir "campanhas" de spam similares sem a necessidade de rótulos prévios.
Exemplos: K-Means e algoritmos de detecção de anomalia para identificar mensagens atípicas que divergem do comportamento padrão do usuário [3].
4. Principais Desafios Encontrados na Literatura
Apesar do alto desempenho dos modelos (muitos atingindo mais de 98% de precisão), a literatura aponta desafios significativos:

Ataques Adversários: Atacantes modificam sutilmente o conteúdo do e-mail (ex: trocando caracteres ou adicionando termos "invisíveis") para enganar os modelos de ML [4].
Evolução das Táticas: O uso de IA generativa (LLMs) por atacantes para criar e-mails de phishing mais convincentes exige que os sistemas de defesa também evoluam constantemente [1][2].
Escalabilidade e Tempo Real: O processamento de milhões de e-mails por segundo exige modelos que sejam não apenas precisos, mas extremamente eficientes em termos de CPU e memória [5].
Explicabilidade: Profissionais de segurança precisam entender por que um e-mail foi bloqueado para validar falsos positivos, o que é difícil em modelos de "caixa preta" como redes neurais profundas [4].
Referências
[1] AI Sentries: Evaluating Machine Learning Models for Superior Phishing Email Detection. S Sahit et al. (2024).
[2] Enhancing Phishing Detection with AI: A Novel Dataset and Comprehensive Analysis. Robin Chataut et al. (2024).
[3] Lambda Architecture-Based Big Data System for Large-Scale Targeted Social Engineering Email Detection. Mustafa Umut Demirezen et al. (2023).
[4] Deciphering Spam Through AI: From Traditional Methods to Deep Learning Advancements. scitepress.org (2024).
[5] A Comparative Study of Machine Learning and Neural Network Models for Phishing Detection. Springer (2024).

---

# 7. Resumo estruturado da literatura
Técnicas de Aprendizado de Máquina Mais Utilizadas A literatura demonstra uma evolução de algoritmos tradicionais para modelos baseados em aprendizado profundo (Deep Learning) e transformadores. Entre as técnicas clássicas, Random Forest (RF), Support Vector Machines (SVM), Naive Bayes e Regressão Logística são amplamente citadas por sua eficiência computacional e bons resultados iniciais. Atualmente, o foco reside em redes neurais como CNN, RNN (especialmente LSTM e GRU) e arquiteturas baseadas em Transformers, como BERT e RoBERTa, que apresentam as maiores taxas de acurácia, superando 98% em muitos cenários.
Atributos (Features) Recorrentes Os atributos são geralmente divididos em categorias:
Baseados em conteúdo: Palavras-chave de urgência (ex: "urgente", "agora"), termos financeiros ("banco", "pagamento"), e similaridade de conteúdo.
Baseados em links (URL): Contagem de links, obfuscação de URLs e número de pontos no domínio.
Metadados e Cabeçalho: Reputação do remetente, inconsistência no endereço de e-mail e informações de fuso horário.
Comportamentais e Estruturais: Frequência de envios, desvio de avaliação (em spam de opinião) e presença de tags HTML/JavaScript.
Nível de Caractere: Padrões de pontuação, erros ortográficos e uso excessivo de letras maiúsculas.
Principais Desafios O desafio central é a escassez de dados rotulados (labeled data) e o alto custo para obtê-los, dificultando o treinamento de modelos complexos. Além disso, os atacantes são adaptativos, mudando suas estratégias conforme as políticas de detecção evoluem. Outros obstáculos incluem o desbalanceamento de classes (muito mais e-mails legítimos do que spam), a necessidade de interpretabilidade dos modelos ("caixa-preta") e a alta demanda por recursos computacionais para processamento em larga escala.
Técnicas de Pré-processamento As etapas comuns envolvem a limpeza dos dados (remoção de nulos e duplicatas), eliminação de tags HTML/JavaScript, tokenização, stemming, e a remoção de stop words. Para representação numérica, utiliza-se frequentemente TF-IDF, One-hot encoding e Word Embeddings (como Word2Vec ou embeddings derivados do BERT). Em dados estruturados em grafos, técnicas de "esparsificação" são aplicadas para otimizar o processamento.
Métricas de Avaliação Comuns As métricas fundamentais são Acurácia, Precisão, Recall (Sensibilidade) e F1-Score. Em problemas de classificação binária desbalanceada, o Coeficiente de Correlação de Matthews (MCC) é recomendado. Outras métricas incluem a Área sob a Curva (AUC/ROC), Precisão@k e métricas de tempo de inferência e uso de CPU/RAM para aplicações em tempo real.


---

# 8. Tabela comparativa dos artigos analisados

## 2. Tabela Comparativa dos Artigos

| Referência | Técnica(s) Utilizada(s) | Atributos Utilizados | Tipo de Tarefa | Pré-processamento | Métricas de Avaliação | Principais Contribuições |
|---|---|---|---|---|---|---|
| Danilchenko et al. (2022) | Random Forest, Clique Reviewer Spammer Detection (CRSDnet), Belief Propagation | Comportamento do revisor, metadados de revisões e estrutura de grafos (cliques) | Classificação | Esparsificação de grafos, extração de metadados | AUC, AP, Precision@k, NDCG | Integra ML com modelos de grafos para lidar com poucos dados rotulados (Active Learning). |
