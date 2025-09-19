# lab-speech-language-azure
Este projeto demonstra um pipeline de Inteligência Artificial de ponta a ponta, utilizando os Serviços Cognitivos do Azure para realizar duas tarefas cruciais: a **análise de conteúdo** com o **Language Studio** e a **apresentação de resultados** com avatares de IA do **Speech Studio**.

A demonstração utiliza um único texto-base, simulando um cenário de negócios real onde primeiro se extraem insights de um relatório e, em seguida, se apresenta esse mesmo relatório de forma automatizada e visual.

---

## 🚀 O Cenário de Teste: Relatório de Solução Tecnológica

O texto a seguir foi o coração do projeto, servindo como entrada para ambas as ferramentas. Ele descreve a arquitetura de uma solução de atendimento ao cliente:

> "Para desenvolver nossa solução de atendimento ao cliente, utilizamos os Serviços Cognitivos do Azure. O processo iniciou com a implementação do Speech Studio para a transcrição de áudio em tempo real, convertendo as chamadas de voz em texto. Em seguida, o Language Studio foi aplicado para realizar a análise de sentimento e o reconhecimento de entidades nomeadas, como produtos e datas. A integração foi realizada via API REST, garantindo uma arquitetura escalável e segura para o processamento dos dados."

---

## 🏗️ Arquitetura da Solução Demonstrada

O fluxo de trabalho seguiu uma arquitetura lógica de dois estágios:

**Passo 1: Análise e Extração de Insights (Language Studio):** O texto foi processado para entender seu sentimento e identificar opiniões específicas sobre os componentes da solução.

**Passo 2: Apresentação e Comunicação (Speech Studio):** O mesmo texto foi usado para gerar um vídeo com um porta-voz virtual, comunicando o relatório de forma clara e acessível.

---

### Etapa 1: Análise de Conteúdo com o Language Studio

Na primeira fase, utilizei o Language Studio para realizar uma análise profunda do texto.

-   **Análise de Sentimento:** A ferramenta avaliou o sentimento geral do documento como **majoritariamente positivo**. Além disso, analisou o sentimento de cada sentença individualmente.
-   **Mineração de Opinião (Opinion Mining):** Esta funcionalidade avançada permitiu identificar opiniões detalhadas. Por exemplo, no trecho "...garantindo uma **arquitetura escalável** e **segura**...", o modelo corretamente identificou:
    -   **Alvo:** `arquitetura`
    -   **Opiniões (Avaliações):** `escalável` (positiva) e `segura` (positiva).

Isso demonstra a capacidade de extrair insights granulares que seriam úteis para a tomada de decisão.

### Etapa 2: Apresentação com Avatar de IA (Speech Studio)

Na segunda fase, o mesmo texto foi inserido no Speech Studio para gerar uma apresentação em vídeo.

-   **Geração de Vídeo com Avatar:** Utilizando um avatar e uma voz neural, a plataforma converteu o relatório em um vídeo com um porta-voz fotorrealista.
-   **Sincronização e Realismo:** O resultado foi um vídeo com excelente sincronização labial e movimentos naturais, demonstrando como relatórios técnicos podem ser transformados em comunicações de vídeo engajadoras.

---

## 🧠 Conclusão e Principais Aprendizados

-   **Sinergia das Ferramentas:** A verdadeira força dos Serviços Cognitivos do Azure está na sua integração. Demonstrei como o Language Studio pode "entender" o conteúdo e o Speech Studio pode "apresentá-lo", criando um fluxo de trabalho poderoso.
-   **De Dados a Decisões:** A análise de sentimento e a mineração de opinião são ferramentas fantásticas para transformar texto não estruturado (como e-mails, relatórios ou transcrições) em dados acionáveis.
-   **O Futuro da Comunicação:** Avatares de IA representam o futuro da criação de conteúdo para treinamento, suporte ao cliente e comunicação corporativa, tornando-a mais escalável e acessível.

---

## 🎬 Demonstrações Visuais

Veja abaixo os GIFs que capturam os momentos-chave de cada etapa do pipeline.

### Análise no Language Studio (Passo a Passo)

**1. Configurando o idioma e o texto para análise:**
![Configurando a análise](images/Analyze%20sentiment%20and%20opinions%20PT.1.gif)

**2. Executando o processo de análise:**
![Executando a análise](images/Analyze%20sentiment%20and%20opinions%20PT.2.gif)

**3. Visualizando os resultados detalhados, incluindo a Mineração de Opinião:**
![Visualizando os resultados](images/Analyze%20sentiment%20and%20opinions%20PT.3.gif)

### Geração do Avatar no Speech Studio

**Gerando o vídeo a partir do texto e das configurações de voz e avatar:**
![Demonstração do Avatar em Ação](images/Playground%20de%20Fala.gif)

---

## 💻 Tecnologias Utilizadas
-   Microsoft Azure AI
-   Azure Language Studio (Análise de Sentimento, Mineração de Opinião)
-   Azure Speech Studio (Avatar de Conversão de Texto em Fala)
-   Markdown
