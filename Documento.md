# Revisão da Literatura Científica Experimental com Aprendizado de Máquina

## Tema
**Detecção de spam ou phishing em e-mails com técnicas de aprendizado de máquina**

## Integrantes
- Nome do integrante 1
- Nome do integrante 2
- Nome do integrante 3
- Nome do integrante 4

---

# 1. Introdução

A comunicação por e-mail continua sendo uma das formas mais utilizadas para troca de informações em ambientes pessoais, acadêmicos e corporativos. No entanto, esse meio também é amplamente explorado por agentes maliciosos para o envio de mensagens de spam e ataques de phishing, que podem comprometer dados pessoais, credenciais de acesso e informações sensíveis dos usuários.

O spam consiste no envio de mensagens indesejadas, geralmente em grande volume, enquanto o phishing busca enganar o destinatário por meio de links, anexos ou conteúdos falsos, simulando fontes confiáveis com o objetivo de roubar informações. Diante do crescimento desses ataques, torna-se necessário o desenvolvimento de mecanismos automáticos capazes de identificar e filtrar essas ameaças com maior precisão.

Nesse contexto, o aprendizado de máquina tem se destacado como uma abordagem eficiente para a detecção de spam e phishing em e-mails, pois permite identificar padrões presentes no conteúdo das mensagens, em seus metadados e em outros atributos relevantes. Assim, este trabalho tem como objetivo realizar uma revisão da literatura científica experimental sobre a aplicação de técnicas de aprendizado de máquina nesse problema, analisando os principais métodos utilizados, as bases de dados adotadas e os resultados encontrados.

---

# 2. Questões de pesquisa geradas

As questões de pesquisa definidas para esta revisão foram:

1. **Como o aprendizado de máquina tem sido aplicado na detecção de spam ou phishing em e-mails?**
2. **Quais algoritmos são mais utilizados para classificar e-mails legítimos, spam ou phishing?**
3. **Quais atributos ou características dos e-mails são mais empregados nos estudos analisados?**
4. **Quais métricas de avaliação são mais utilizadas para medir o desempenho dos modelos?**
5. **Quais são os principais resultados, desafios e limitações encontrados na literatura científica experimental?**

---

# 3. Strings de busca utilizadas pela ferramenta

As strings de busca utilizadas foram:

```text
("machine learning" OR "aprendizado de máquina") AND ("email spam detection" OR "detecção de spam em e-mails")
("machine learning" OR "aprendizado de máquina") AND ("phishing email detection" OR "detecção de phishing em e-mails")
("classification") AND ("spam email")
("classification") AND ("phishing email")
("artificial intelligence" OR "inteligência artificial") AND ("email security")
("spam filtering") AND ("machine learning")
("phishing detection") AND ("email") AND ("machine learning")
("email spam" OR "email phishing") AND ("experimental study" OR "estudo experimental")
("detecção de spam") AND ("aprendizado de máquina")
("detecção de phishing") AND ("e-mails")
```

---

# 4. Critérios de seleção dos artigos

## 4.1 Critérios de inclusão

Foram incluídos artigos que:

- abordam a detecção de spam ou phishing em e-mails;
- utilizam técnicas de aprendizado de máquina;
- apresentam análise ou validação experimental;
- descrevem algoritmos, dados e métricas de avaliação;
- contribuem para responder às questões de pesquisa propostas.

## 4.2 Critérios de exclusão

Foram excluídos artigos que:

- não tratam diretamente de spam ou phishing em e-mails;
- não utilizam aprendizado de máquina;
- não apresentam resultados experimentais;
- são duplicados;
- possuem pouca relação com o tema central da revisão.

---

# 5. Lista dos 8 artigos escolhidos

> Substituir os campos abaixo pelos 8 artigos reais selecionados pelo grupo.

## Artigo 1
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 2
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 3
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 4
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 5
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 6
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 7
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

## Artigo 8
**Título:** [Inserir título do artigo]  
**Autores:** [Inserir autores]  
**Ano:** [Inserir ano]  
**Fonte:** [Inserir periódico ou evento]  
**Link:** [Inserir link]

---

# 6. Texto de revisão da literatura gerado pela ferramenta

A literatura científica experimental sobre detecção de spam e phishing em e-mails demonstra que o aprendizado de máquina tem sido amplamente utilizado como estratégia para aumentar a segurança digital e reduzir os riscos associados a mensagens maliciosas. Isso ocorre porque técnicas tradicionais baseadas apenas em regras fixas ou listas de bloqueio nem sempre conseguem acompanhar a constante evolução dos padrões utilizados por atacantes.

Nos estudos analisados, observa-se predominância do uso de técnicas de classificação, uma vez que o problema geralmente envolve categorizar e-mails como legítimos, spam ou phishing. Entre os algoritmos mais recorrentes na literatura estão Naive Bayes, Support Vector Machine, Random Forest, Decision Tree, K-Nearest Neighbors e Redes Neurais. Esses métodos permitem identificar padrões em textos, links, remetentes, cabeçalhos e outros atributos extraídos das mensagens.

Outro aspecto importante encontrado na literatura é a variedade de características utilizadas para treinar os modelos. Muitos estudos empregam atributos textuais, frequência de palavras, presença de URLs suspeitas, endereços de remetentes, estruturas do cabeçalho, anexos e indicadores semânticos. Em alguns casos, também são utilizadas técnicas de processamento de linguagem natural para melhorar a representação do conteúdo das mensagens.

As métricas de avaliação mais comuns nos trabalhos são acurácia, precisão, recall, F1-score e matriz de confusão. Em geral, os resultados mostram desempenho satisfatório dos algoritmos, especialmente quando há bom pré-processamento dos dados e seleção adequada de atributos. No entanto, a literatura também aponta desafios como desbalanceamento de classes, mudanças constantes nas estratégias de ataque, dificuldade de generalização dos modelos e necessidade de atualização contínua.

Por fim, a revisão indica que o aprendizado de máquina possui papel fundamental na detecção automatizada de spam e phishing em e-mails, contribuindo para a proteção dos usuários e para o fortalecimento da segurança da informação. Ainda assim, os estudos mostram que o problema permanece dinâmico, exigindo soluções cada vez mais robustas, interpretáveis e adaptáveis a novos tipos de ameaça.

---

# 7. Resumo estruturado da literatura

## 7.1 Objetivo da revisão

Investigar como técnicas de aprendizado de máquina vêm sendo aplicadas na detecção de spam ou phishing em e-mails, considerando algoritmos, atributos, métricas e principais resultados experimentais encontrados na literatura.

## 7.2 Método

Foi realizada uma busca bibliográfica com strings relacionadas à detecção de spam, phishing e aprendizado de máquina. Após a aplicação dos critérios de inclusão e exclusão, foram selecionados 8 artigos para análise comparativa.

## 7.3 Principais técnicas encontradas

- Naive Bayes
- Support Vector Machine
- Random Forest
- Árvore de Decisão
- K-Nearest Neighbors
- Redes Neurais

## 7.4 Principais métricas utilizadas

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

## 7.5 Principais achados

- O aprendizado de máquina tem sido amplamente utilizado na filtragem de spam e na detecção de phishing.
- Técnicas de classificação são predominantes nesse tipo de problema.
- Atributos textuais e estruturais dos e-mails são frequentemente utilizados.
- O desempenho dos modelos depende da qualidade dos dados e do pré-processamento.
- O problema é dinâmico e exige atualização contínua dos modelos.

## 7.6 Lacunas identificadas

- Dificuldade de generalização para diferentes bases de e-mails.
- Mudanças frequentes nas estratégias de spam e phishing.
- Necessidade de modelos mais interpretáveis.
- Desbalanceamento entre classes legítimas e maliciosas em alguns conjuntos de dados.

---

# 8. Tabela comparativa dos artigos analisados

| Nº | Artigo | Objetivo | Técnica de ML | Base de Dados | Métricas | Principais Resultados |
|----|--------|----------|---------------|---------------|----------|------------------------|
| 1 |  | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 2 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 3 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 4 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 5 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 6 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 7 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |
| 8 | [Título resumido] | Detectar spam/phishing | [Técnica] | [Base] | [Métricas] | [Resultado] |

---

# 9. Considerações finais

Com base na literatura analisada, observa-se que o uso de aprendizado de máquina na detecção de spam ou phishing em e-mails constitui uma abordagem relevante para o fortalecimento da segurança digital. Os estudos mostram que diferentes algoritmos podem ser aplicados para identificar mensagens maliciosas com bom desempenho, especialmente quando há seleção adequada de atributos e tratamento apropriado dos dados. Além disso, a revisão permitiu identificar métodos recorrentes, métricas amplamente utilizadas e desafios ainda presentes, evidenciando que o tema possui grande importância acadêmica e prática.

---

# 10. Referências

> Inserir aqui as referências completas dos 8 artigos selecionados.

### Modelo de referência

SOBRENOME, Nome. Título do artigo. **Nome do periódico ou evento**, ano. Disponível em: <link>. Acesso em: dia mês ano.
