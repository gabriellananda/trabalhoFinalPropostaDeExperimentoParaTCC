# Plano de Experimento 

## 1. Identificação básica

### 1.1 Título do experimento
Comparação entre Protótipos Interativos e Especificações Textuais no Desenvolvimento de Interfaces Web por Estudantes de Engenharia de Software

### 1.2 ID / código
EXP-REQ-PT-ENGSW-2025

### 1.3 Versão do documento e histórico de revisão
- **Versão atual:** v1.1  
- **Histórico de revisão:**
  - v1.0 - Criação do repositório e do readme.md.
  - v1.1 – Descrição da identificação básica, contexto e problema.
  - v1.2 - Descrição do objetivo, escopo, stakeholders, impacto, riscos de alto nível, premissas e critérios de sucesso.
  - v1.3 - Descrição do modelo conceitual e hipóteses; variáveis, fatores, tratamentos e objetos de estudo; desenho experimental.

### 1.4 Datas
- **Data de criação:** 23/11/2025  
- **Última atualização:** 28/11/2025

### 1.5 Autores
- **Nome:** *Gabriella Fernanda Silva PInto*  
  - **Curso/Área:** Engenharia de Software  
  - **Contato:** *1405624@sga.pucminas.br*  

### 1.6 Responsável principal (PI / dono do experimento)
- **Responsável:** *Gabriella Fernanda Silva Pinto*  
- **Papel:** Estudante / Pesquisador principal do experimento de TCC  
- **Orientador(a):** *Danilo de Quadros Maia Filho*

### 1.7 Projeto / produto / iniciativa relacionada
- **Projeto acadêmico:** Trabalho Final: Proposta de Experimento para TCC em Engenharia de Software.  
- **Produto alvo do experimento:** A forma de representação dos requisitos (Protótipos Interativos vs. Especificações Textuais) e seus efeitos no processo de desenvolvimento de software por estudantes, como qualidade da implementação, aderência aos requisitos, tempo de desenvolvimento e experiência subjetiva.
- **Disciplina/Iniciativa relacionada:** Medição e Experimentação em Engenharia de Software.

---

## 2. Contexto e problema

### 2.1 Descrição do problema / oportunidade
Em atividades de desenvolvimento de software, especialmente na fase de levantamento e especificação de requisitos, diferentes formas de representação são utilizadas para comunicar o que deve ser implementado. Duas representações comuns são:

1. **Especificações textuais** (descrições em linguagem natural, listas de requisitos, critérios de aceitação, etc.);  
2. **Protótipos de baixa ou média fidelidade**, incluindo **protótipos interativos** em ferramentas como Figma.

Diferentes formas de apresentar requisitos, como descrições textuais e protótipos interativos, podem influenciar o modo como desenvolvedores realizam suas tarefas. Essa possível variação pode afetar fatores como:

- A **qualidade da interface desenvolvida**;
- O **tempo de desenvolvimento**;
- O **entendimento dos requisitos** pelos estudantes;
- A **satisfação dos alunos** com o processo de desenvolvimento.

O experimento busca investigar **se e como** a forma de representação dos requisitos (protótipo interativo vs. especificação textual) influencia o desenvolvimento de uma tela de cadastro de um petshop por alunos em diferentes níveis de conhecimento das tecnlogias (CSS, HTML e JavaScript) e de formação (1º, 5º e 8º períodos).

### 2.2 Contexto organizacional e técnico
A organização na qual o experimento será realizado é o Curso de Engenharia de Software da PUC Minas – Unidade Lourdes, onde os participantes são alunos matriculados em diferentes períodos da graduação e possuem diferentes níveis de conhecimento das tecnologias utilizadas. O experimento será executado no ambiente dos laboratórios de informática da universidade, utilizando computadores institucionais e ferramentas padrão de desenvolvimento web.
- **Organização:** Curso de Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais.
- **Local de execução:** Laboratórios de informática da PUC Minas – Unidade Lourdes.  
- **Participantes:** 60 estudantes do curso de Engenharia de Software, sendo:
  - 20 alunos do 1º período,
  - 20 alunos do 5º período,. 
  - 20 alunos do 8º período.
- **Conhecimento técnico:**  
  Nível heterogêneo em HTML, CSS e JavaScript, variando de iniciantes a intermediários/avançados. Esse nível será **autoavaliado em escala de 0 a 10** para cada tecnologia (HTML, CSS e JavaScript) antes do início do experimento.  
- **Ambiente técnico:**  
  - Desenvolvimento front-end em HTML, CSS e JavaScript;  
  - Ferramentas de edição de código (VS Code);  
  - Navegador web para execução e inspeção da interface (Chrome);  
  - Ferramenta de prototipação (Figma) para o grupo que receberá protótipos interativos.  
- **Processo experimental (visão geral):**
  - Antes de iniciar a tarefa de desenvolvimento, cada estudante responderá a um **formulário de autoavaliação**, classificando seu nível de conhecimento em HTML, CSS e JavaScript em uma escala de **0 a 10** para cada tecnologia.
  - Essa autoavaliação será utilizada para **distribuir de forma mais uniforme possível** os diferentes tipos de requisitos entre os participantes, de acordo com o período e o nível de conhecimento.
  -  Em cada período (1º, 5º e 8º), pretende-se identificar:
    - 10 alunos com **nível de conhecimento abaixo ou igual a 5**, e  
    - 10 alunos com **nível de conhecimento acima de 5** (considerando a média das notas de HTML, CSS e JavaScript ou regra definida no protocolo).
  - Dentro de cada um desses subgrupos (abaixo de 5 e acima de 5), os alunos serão divididos da seguinte forma:
    - 5 alunos receberão os requisitos na forma de **protótipo interativo** (Figma);  
    - 5 alunos receberão os requisitos na forma de **especificação textual** (PDF).
  - Cada estudante desenvolverá, individualmente, uma tela de cadastro para um petshop, com campos para:
    - Dados pessoais do cliente (nome, telefone, e-mail, endereço etc.);
    - Dados do animal (nome, espécie, raça, idade, necessidades especiais etc.).
  - O experimento será realizado **nos laboratórios da PUC Minas Lourdes**, em ambiente controlado, e os alunos terão **50 minutos (equivalente a uma aula)** para desenvolver a tela front-end com base nos requisitos recebidos.
  - Ao final da atividade, serão coletados:
    - o código desenvolvido;  
    - o tempo efetivamente utilizado (dentro do limite de 50 minutos);  
    - e respostas a um questionário pós-tarefa sobre clareza, facilidade e satisfação.

### 2.3 Trabalhos e evidências prévias (internos e externos)
- Estudos em Engenharia de Software Experimental apontam que diferentes representações de requisitos podem influenciar:
  - Entendimento de requisitos;
  - Taxa de erros de implementação;
  - Tempo de desenvolvimento.
- Trabalhos em IHC (Interação Humano-Computador) e Design de Interfaces sugerem que **protótipos visuais** facilitam a comunicação entre stakeholders, mas há menos evidência quantitativa sobre o impacto em **estudantes** com diferentes níveis de experiência.
- Internamente, na disciplina de Desenvolvimento de Interfaces Web, já foram realizadas atividades práticas utilizando tanto casos de uso textuais quanto protótipos de tela, mas sem controle experimental formal.

### 2.4 Referencial teórico e empírico essencial
- **Engenharia de Requisitos:** importância da clareza e da não ambiguidade na especificação de requisitos.  
- **Interação Humano-Computador (IHC):** princípios de usabilidade e design centrado no usuário.  
- **Representações de requisitos:**
  - Textuais (histórias de usuário, requisitos funcionais em linguagem natural);
  - Visuais (protótipos de baixa/média fidelidade, mockups, wireframes).
- **Medição e Experimentação em Engenharia de Software:**
  - Conceitos de experimento controlado;
  - Hipóteses nula e alternativa;
  - Validade interna e externa.

---

## 3. Objetivos e questões (Goal / Question / Metric – GQM)

### 3.1 Objetivo geral (Goal template)
**Analisar** o impacto do uso de protótipos interativos, em comparação com especificações textuais, **no desenvolvimento de interfaces web para um sistema de cadastro de petshop**, **com o propósito de** avaliar a qualidade do software produzido e a eficiência do desenvolvimento, **sob a perspectiva** de estudantes e docentes de Engenharia de Software, **no contexto** de um experimento controlado com 60 alunos de 1º, 5º e 8º períodos, de variados níveis de conhecimento em HTML, CSS e JavaScript, realizado em laboratório (PUC Minas Lourdes) e com tempo de implementação limitado a 50 minutos.

### 3.2 Objetivos específicos

- **O1 – Qualidade da implementação:**  
  Avaliar se o uso de protótipos interativos influencia a **qualidade funcional e de usabilidade** da tela implementada em comparação com especificações textuais.

- **O2 – Eficiência temporal:**  
  Comparar o **tempo de desenvolvimento**, dentro do limite de 50 minutos, da tela de cadastro entre alunos que utilizam protótipos interativos e aqueles que utilizam especificações textuais.

- **O3 – Entendimento e aderência aos requisitos:**  
  Investigar se a forma de representação dos requisitos impacta a **compreensão dos requisitos** e o nível de **aderência da implementação** em relação ao que foi solicitado.

- **O4 – Experiência subjetiva do desenvolvedor:**  
  Avaliar a **percepção dos estudantes** quanto à clareza dos requisitos, facilidade de desenvolvimento e satisfação com o processo, em cada tipo de representação.

### 3.3 Questões de pesquisa / de negócio

(**O1 – Qualidade da implementação**)
- **Q1.1:** A quantidade de defeitos funcionais na interface implementada difere entre o uso de protótipos interativos e de especificações textuais?  
- **Q1.2:** A quantidade de problemas de usabilidade identificados na interface difere entre as duas representações de requisitos?  
- **Q1.3:** Há diferença na nota global de qualidade da interface (avaliada por um checklist ou rubrica) entre os dois grupos?

(**O2 – Eficiência temporal**)
- **Q2.1:** O tempo total de desenvolvimento da tela, dentro do limite de 50 minutos, é menor quando os alunos utilizam protótipos interativos em vez de especificações textuais?  
- **Q2.2:** O tempo de retrabalho (correções após revisão) difere entre os dois grupos?  
- **Q2.3:** A variação do tempo de desenvolvimento é influenciada pelo período do aluno (1º, 5º, 8º) e/ou pelo nível de experiência em conjunto com o tipo de representação?

(**O3 – Entendimento e aderência aos requisitos**)
- **Q3.1:** A porcentagem de requisitos corretamente implementados é maior em algum dos grupos (protótipo vs. texto)?  
- **Q3.2:** A quantidade de requisitos interpretados incorretamente (implementação divergente) difere entre os grupos?  
- **Q3.3:** O nível de experiência em HTML/CSS/JS (autoavaliação 0–10) modera a relação entre tipo de representação e aderência aos requisitos?

(**O4 – Experiência subjetiva do desenvolvedor**)
- **Q4.1:** A percepção de clareza dos requisitos, segundo os estudantes, difere entre protótipos interativos e especificações textuais?  
- **Q4.2:** A percepção de facilidade de desenvolvimento da interface difere entre os grupos?  
- **Q4.3:** O nível de satisfação geral com o processo de desenvolvimento é maior em algum dos grupos?

### 3.4 Métricas associadas (GQM)

#### Tabela GQM – Relação Objetivo / Perguntas / Métricas

| Objetivo | Pergunta | Métricas associadas |
|---------|----------|---------------------|
| O1 | Q1.1 – Diferença em defeitos funcionais? | M1 – Nº de defeitos funcionais; M10 – Período do aluno |
| O1 | Q1.2 – Diferença em problemas de usabilidade? | M2 – Nº de problemas de usabilidade; M3 – Nota de usabilidade (rubrica) |
| O1 | Q1.3 – Diferença na nota global de qualidade? | M3 – Nota de usabilidade; M4 – Nota global de qualidade da interface |
| O2 | Q2.1 – Diferença no tempo total de desenvolvimento? | M5 – Tempo total de desenvolvimento (min); M10 – Período do aluno |
| O2 | Q2.2 – Diferença no tempo de retrabalho? | M6 – Tempo de retrabalho (min); M1 – Nº de defeitos funcionais |
| O2 | Q2.3 – Interação tipo de representação x período/experiência no tempo? | M5 – Tempo total de desenvolvimento; M10 – Período do aluno |
| O3 | Q3.1 – Diferença na porcentagem de requisitos implementados corretamente? | M7 – Cobertura de requisitos (%); M8 – Nº de requisitos faltantes |
| O3 | Q3.2 – Diferença em requisitos mal interpretados? | M9 – Nº de requisitos implementados de forma incorreta; M7 – Cobertura de requisitos (%) |
| O3 | Q3.3 – Experiência técnica modera o efeito? | M11 – Nível de experiência autoavaliado em HTML/CSS/JS; M7 – Cobertura de requisitos (%) |
| O4 | Q4.1 – Diferença na clareza percebida? | M12 – Escore de clareza percebida (Likert); M11 – Experiência técnica |
| O4 | Q4.2 – Diferença na facilidade percebida? | M13 – Escore de facilidade de desenvolvimento (Likert); M5 – Tempo total de desenvolvimento |
| O4 | Q4.3 – Diferença na satisfação geral? | M14 – Escore de satisfação geral (Likert); M12 – Escore de clareza percebida |

#### Tabela de métricas (descrição e unidade)

| Código | Nome da métrica | Descrição | Unidade |
|--------|-----------------|-----------|---------|
| M1 | Nº de defeitos funcionais | Quantidade de erros funcionais identificados na interface (campos que não funcionam, validações ausentes, botões que não executam ações esperadas etc.) | Contagem (n) |
| M2 | Nº de problemas de usabilidade | Número de problemas de usabilidade identificados com base em um checklist (por exemplo, consistência, feedback, alinhamento, legibilidade) | Contagem (n) |
| M3 | Nota de usabilidade | Nota atribuída à interface com base em rubrica de usabilidade (por ex. escala de 0 a 10) | Escala numérica (0–10) |
| M4 | Nota global de qualidade da interface | Nota geral considerando aspectos funcionais, de layout e de usabilidade, atribuída por avaliadores | Escala numérica (0–10) |
| M5 | Tempo total de desenvolvimento | Tempo desde o início da tarefa até a primeira versão finalizada da tela (sem correções) | Minutos |
| M6 | Tempo de retrabalho | Tempo adicional gasto em correções após a primeira avaliação (se houver) | Minutos |
| M7 | Cobertura de requisitos | Percentual de requisitos especificados que foram corretamente implementados na interface | Percentual (%) |
| M8 | Nº de requisitos faltantes | Quantidade de requisitos previstos que não foram implementados | Contagem (n) |
| M9 | Nº de requisitos implementados incorretamente | Número de requisitos cuja implementação diverge do esperado (implementação errada ou incompleta) | Contagem (n) |
| M10 | Período do aluno | Período em que o aluno está: 1, 5 ou 8 (usado como variável de contexto/fator) | Categórica (1º, 5º, 8º) |
| M11 | Experiência técnica em HTML/CSS/JS | Autoavaliação do aluno sobre seu nível de experiência em desenvolvimento web | Escala Likert (1–5) |
| M12 | Escore de clareza percebida dos requisitos | Percepção do aluno sobre o quão claros estavam os requisitos fornecidos (texto ou protótipo) | Escala Likert (1–5) |
| M13 | Escore de facilidade de desenvolvimento | Percepção de quão fácil foi implementar a tela com base na representação recebida | Escala Likert (1–5) |
| M14 | Escore de satisfação geral | Grau de satisfação geral do aluno com a atividade de desenvolvimento | Escala Likert (1–5) |

---

## 4. Escopo e contexto do experimento

### 4.1 Escopo funcional / de processo (incluído e excluído)

**Template de escopo (Incluído / Excluído):**

| Dimensão | Incluído no escopo | Fora do escopo |
|---------|---------------------|----------------|
| Funcionalidades | Tela de cadastro de cliente e animal para um sistema de petshop (front-end) | Desenvolvimento de back-end, banco de dados e lógica de negócio completa do sistema |
| Artefatos de requisitos | Especificações textuais; Protótipos interativos (Figma) | Outros tipos de artefatos (diagramas UML, user stories, casos de uso formais, etc.) |
| Participantes | Estudantes de 1º, 5º e 8º períodos de Engenharia de Software | Profissionais de mercado, alunos de outros cursos |
| Linguagens e tecnologias | HTML, CSS e JavaScript para implementação da interface | Frameworks avançados (React, Angular, Vue), bibliotecas de UI complexas |
| Processo de avaliação | Coleta de tempo de desenvolvimento, inspeção da interface, aplicação de questionários pós-tarefa | Avaliação longitudinal (uso em produção, avaliação com usuários finais) |
| Análises | Comparação estatística entre grupos (protótipo vs. texto; estratificação por período) | Modelos preditivos complexos, generalização para todos os contextos industriais |

### 4.2 Contexto do estudo
- **Tipo de organização:** Instituição de ensino superior.  
- **Tamanho do “projeto”:** Pequeno, focado em uma única tela de sistema.  
- **Criticidade:** Baixa (projeto acadêmico, sem impacto direto em sistemas de produção).
- **Local e formato:** Execução em **laboratórios da PUC Minas Lourdes**, em sessão única de **50 minutos** de desenvolvimento, com todos os participantes em ambiente controlado. 
- **Perfil dos participantes:**
  - Estudantes em diferentes fases da graduação;
  - Experiência prática limitada ou intermediária em desenvolvimento web;
  - Familiaridade variada com prototipação (alguns já utilizaram Figma, outros não).

### 4.3 Premissas
- Todos os 60 estudantes estarão presentes e disponíveis no momento da execução do experimento.  
- Os ambientes de desenvolvimento (IDE, navegador, acesso à internet) estarão funcionais nos laboratórios da PUC Minas Lourdes.
- Os alunos não terão acesso ao material de outro grupo (para evitar contaminação entre tratamentos).  
- O tempo de atividade de **50 minutos** será suficiente para que todos concluam a tarefa ou atinjam um ponto comparável de desenvolvimento. 
- As instruções fornecidas serão compreendidas de maneira geral pelos participantes.
- Os estudantes responderão ao formulário de autoavaliação (0–10 em HTML, CSS e JavaScript) de forma honesta, de modo que a distribuição de tratamentos por nível técnico seja significativa.

### 4.4 Restrições
- Tempo **estritamente limitado a 50 minutos** (equivalente a uma aula) para execução da atividade de desenvolvimento. 
- Quantidade fixa de participantes (60 alunos), determinada pelas turmas disponíveis.  
- Recursos de laboratório (computadores, internet, acesso ao Figma) compartilhados e sujeitos a falhas.  
- Ferramenta de prototipação já definida (Figma), sem tempo para treinar extensivamente os alunos.  
- A avaliação da qualidade da interface dependerá de avaliadores (professor/monitores), o que pode introduzir subjetividade.

### 4.5 Limitações previstas
- Participantes são estudantes, não profissionais de mercado, o que limita a **generalização** dos resultados para contextos industriais.  
- A tarefa é relativamente simples (uma tela de cadastro), podendo não capturar toda a complexidade de projetos reais.  
- O conhecimento prévio em HTML/CSS/JS é heterogêneo e baseado em **autoavaliação**, o que pode introduzir variabilidade adicional difícil de controlar completamente.  
- O experimento ocorre em um contexto acadêmico controlado, que não representa o ambiente de pressão e prazos de empresas.

---

## 5. Stakeholders e impacto esperado

### 5.1 Stakeholders principais
- **Estudantes participantes** (1º, 5º e 8º períodos).  
- **Docente responsável pela disciplina**.  
- **Orientador(a) do TCC**.  
- **Coordenação do curso de Engenharia de Software**.  
- **Futuros professores da área de Engenharia de Software** (interessados em métodos de ensino).  

### 5.2 Interesses e expectativas dos stakeholders
- **Estudantes:**  
  - Vivenciar um experimento de Engenharia de Software;  
  - Aprender sobre diferentes formas de especificação de requisitos;  
  - Receber feedback sobre seu desenvolvimento de interface.
- **Docente/Orientador:**  
  - Obter evidências quantitativas e qualitativas sobre o impacto de diferentes representações de requisitos;  
  - Utilizar os resultados para aprimorar as práticas de ensino na disciplina.
- **Coordenação do curso:**  
  - Verificar se atividades de experimentação podem melhorar a formação prática dos alunos;  
  - Avaliar possíveis ajustes curriculares (incluindo prototipação e IHC).  

### 5.3 Impactos potenciais no processo / produto
- **Durante o experimento:**  
  - Aulas serão parcialmente dedicadas à coleta de dados, reduzindo tempo para outros conteúdos naquele dia.  
  - Os alunos podem sentir aumento de carga cognitiva por estarem sendo avaliados experimentalmente.
- **Após o experimento:**  
  - Possíveis mudanças nas práticas de especificação de requisitos em disciplinas futuras (mais uso de protótipos, por exemplo).  
  - Produção de um estudo empírico que pode servir como base para publicações acadêmicas ou melhoria da matriz curricular.

---

## 6. Riscos de alto nível, premissas e critérios de sucesso

### 6.1 Riscos de alto nível
- **Risco R1 – Ausência de participantes:** número significativo de faltas no dia do experimento reduzindo o tamanho da amostra.  
- **Risco R2 – Problemas técnicos:** falhas em laboratório, internet, Figma ou IDE atrapalhando o experimento.  
- **Risco R3 – Contaminação entre grupos:** estudantes compartilhando materiais (protótipo/texto) durante a execução.  
- **Risco R4 – Viés de avaliação:** subjetividade na avaliação de qualidade da interface por parte do professor/avaliadores.  
- **Risco R5 – Autoavaliação imprecisa:** estudantes podem subestimar ou superestimar seu nível de conhecimento, prejudicando o balanceamento dos grupos.

### 6.2 Critérios de sucesso globais (go / no-go)
O experimento será considerado **útil e viável** se:

- Pelo menos **80% dos 60 estudantes** participarem integralmente do experimento.  
- For possível coletar, sem grandes falhas, os dados principais de:
  - Tempo de desenvolvimento (M5),  
  - Qualidade funcional e de usabilidade (M1, M2, M3, M4),  
  - Aderência aos requisitos (M7, M8, M9),  
  - Experiência subjetiva (M12, M13, M14).
- Os dados permitirem realizar um **teste de hipóteses** sobre, pelo menos, um dos objetivos principais (por exemplo, diferença no tempo de desenvolvimento ou na qualidade entre protótipo vs. texto).  
- Os resultados gerarem **insights claros** que possam ser comunicados na disciplina e no TCC.

### 6.3 Critérios de parada antecipada (pré-execução)
O experimento deverá ser **adiado ou cancelado** se:

- Menos de 50% dos participantes esperados puderem comparecer no dia da coleta.  
- Houver **falha crítica** no ambiente (laboratório indisponível, falta de energia ou internet) que inviabilize a execução.  
- Houver reprovação ética ou administrativa da proposta pela coordenação ou pelo professor responsável (por exemplo, problemas com consentimento dos alunos ou uso de dados).

---

## 7. Modelo conceitual e hipóteses

### 7.1 Modelo conceitual do experimento

O modelo conceitual deste experimento parte da ideia de que a **forma de representação dos requisitos** (Protótipos Interativos em Figma vs. Especificações Textuais em PDF) pode influenciar o **desempenho dos estudantes** no desenvolvimento de uma tela de cadastro de petshop em HTML, CSS e JavaScript.

O experimento assume que:

- O **tipo de requisito** (protótipo vs. texto) é o **fator experimental principal**;
- O **período do aluno** (1º, 5º, 8º) e o **nível de conhecimento autoavaliado** em HTML/CSS/JS atuam como **variáveis de bloqueio/moderação**, pois podem alterar a forma como o aluno interpreta e usa os requisitos;
- As **respostas** (variáveis dependentes) são medidas em termos de:
  - Qualidade funcional e de usabilidade da interface;
  - Aderência aos requisitos;
  - Tempo de desenvolvimento;
  - Experiência subjetiva (clareza, facilidade, satisfação).

De forma integrada, o modelo conceitual entende que:

- O tipo de representação dos requisitos influencia o desempenho no desenvolvimento, e esse efeito pode variar de acordo com o período do aluno e seu nível de conhecimento técnico.

### 7.2 Hipóteses formais (H₀, H₁)

**Hipótese geral**

- **H₀ (Hipótese nula geral):**  
  O tipo de representação dos requisitos (protótipo interativo vs. especificação textual) **não produz diferença estatisticamente significativa** no desempenho dos estudantes no desenvolvimento da tela de cadastro.

- **H₁ (Hipótese alternativa geral):**  
  O tipo de representação dos requisitos (protótipo interativo vs. especificação textual) **produz diferença estatisticamente significativa** em pelo menos uma dimensão de desempenho dos estudantes (qualidade, aderência, tempo de desenvolvimento, usabilidade, clareza percebida, facilidade ou satisfação).

**Hipóteses específicas por dimensão**

- **Qualidade da implementação**
  - **H₀₁:** Não há diferença significativa na qualidade funcional e de usabilidade entre interfaces desenvolvidas com requisitos em protótipo e com requisitos em texto.  
  - **H₁₁:** Existe diferença significativa na qualidade funcional e/ou de usabilidade entre interfaces desenvolvidas com requisitos em protótipo e com requisitos em texto.

- **Eficiência temporal**
  - **H₀₂:** O tempo total de desenvolvimento (dentro dos 50 minutos) não difere significativamente entre os grupos (protótipo vs. texto).  
  - **H₁₂:** O tempo total de desenvolvimento (dentro dos 50 minutos) difere significativamente entre os grupos (protótipo vs. texto).

- **Aderência aos requisitos**
  - **H₀₃:** A aderência aos requisitos (requisitos corretamente implementados, faltantes e incorretos) não difere significativamente entre os grupos.  
  - **H₁₃:** A aderência aos requisitos difere significativamente entre os grupos.

- **Experiência subjetiva do desenvolvedor**
  - **H₀₄:** Não há diferença significativa entre os grupos quanto à clareza percebida dos requisitos, facilidade de desenvolvimento e satisfação geral.  
  - **H₁₄:** Há diferença significativa entre os grupos quanto à clareza percebida dos requisitos, facilidade de desenvolvimento e/ou satisfação geral.

### 7.3 Nível de significância e considerações de poder

- **Nível de significância (α):**  
  Será adotado **α = 0,05**, valor usual em experimentos de Engenharia de Software.

- **Poder estatístico e tamanho da amostra:**  
  O experimento utilizará **60 estudantes** (30 no tratamento com protótipo, 30 no tratamento com texto), distribuídos de forma balanceada entre:
  - Períodos (1º, 5º e 8º);  
  - Níveis de conhecimento (abaixo/igual a 5 e acima de 5 na autoavaliação).

  Trata-se de um experimento de **escala acadêmica** (disciplina), em que o tamanho da amostra é determinado pela quantidade de alunos disponíveis. Não há cálculo formal de poder estatístico, mas o tamanho da amostra é considerado razoável para observar tendências e realizar testes básicos (como t-teste, ANOVA ou testes não paramétricos equivalentes), desde que os resultados sejam interpretados com cautela e explicitando as limitações.

---

## 8. Variáveis, fatores, tratamentos e objetos de estudo

### 8.1 Objetos de estudo

Os **objetos de estudo principais** são:

- O **tipo de representação dos requisitos** (protótipo interativo vs. especificação textual), que é o fator experimental principal;
- As **implementações da tela de cadastro de petshop** produzidas pelos estudantes, que serão utilizadas para medir as variáveis dependentes (qualidade, aderência, usabilidade, etc.).

### 8.2 Sujeitos / participantes (visão geral)

Os sujeitos do experimento são:

- **60 estudantes** do curso de Engenharia de Software da PUC Minas – Unidade Lourdes, sendo:
  - 20 alunos do 1º período;
  - 20 alunos do 5º período;
  - 20 alunos do 8º período.

Eles possuem **níveis variados de conhecimento** em HTML, CSS e JavaScript, medidos por autoavaliação em escala de 0 a 10 para cada tecnologia.

### 8.3 Variáveis independentes (fatores) e seus níveis

A tabela abaixo resume as variáveis independentes (fatores experimentais e de bloqueio) e seus níveis.

#### Tabela 1 – Variáveis (independente, dependentes, moderadoras) e descrições

| Tipo de variável | Nome | Descrição | Métricas associadas |
|------------------|------|-----------|----------------------|
| Independente (fator principal) | Tipo de requisito | Forma de representação dos requisitos fornecidos ao aluno: Protótipo Interativo (Figma) ou Especificação Textual (PDF). | Tratamentos T1 (Protótipo) / T2 (Texto) |
| Dependente | Qualidade funcional | Grau em que as funcionalidades esperadas (campos, botões, validações básicas) funcionam corretamente. | M1, M4 |
| Dependente | Usabilidade | Qualidade de uso percebida e analisada, incluindo problemas de layout, legibilidade, navegação e feedback. | M2, M3, M4 |
| Dependente | Tempo de desenvolvimento | Tempo total gasto pelo aluno para desenvolver a interface (até o limite de 50 minutos). | M5 |
| Dependente | Tempo de retrabalho | Tempo adicional gasto em correções, se houver, após a primeira avaliação. | M6 |
| Dependente | Aderência aos requisitos | Grau em que os requisitos especificados foram corretamente implementados (corretos, faltantes, incorretos). | M7, M8, M9 |
| Dependente | Clareza percebida | Percepção do aluno sobre o quão claros estavam os requisitos recebidos (texto ou protótipo). | M12 |
| Dependente | Facilidade percebida | Percepção sobre o quão fácil foi desenvolver a tela com base na representação fornecida. | M13 |
| Dependente | Satisfação geral | Grau de satisfação do aluno com a atividade como um todo. | M14 |
| Moderadora / Bloqueio | Período do aluno | Momento da formação em que o aluno se encontra (1º, 5º ou 8º período). | M10 |
| Moderadora / Bloqueio | Nível de conhecimento em HTML/CSS/JS | Autoavaliação do aluno (0–10 para cada tecnologia) utilizada para estratificar em grupos “abaixo/igual a 5” e “acima de 5”. | (Formulário de autoavaliação) |
| Controle | Ambiente e ferramentas | Laboratório, VS Code, Chrome, Figma, tempo de 50 minutos, mesma tarefa de desenvolvimento. | (Parâmetros constantes) |

### 8.4 Tratamentos (condições experimentais)

Serão definidos dois tratamentos principais:

- **T1 – Protótipo Interativo (Figma):**  
  Os alunos recebem um protótipo interativo da tela de cadastro (cliente + animal) no Figma, representando campos, layout e fluxo de interação.

- **T2 – Especificação Textual (PDF):**  
  Os alunos recebem uma especificação textual em PDF, descrevendo os requisitos da mesma tela, com campos obrigatórios, opcionais e regras básicas.

### 8.5 Variáveis dependentes (respostas)

As principais variáveis dependentes (já alinhadas com as métricas M1–M14) são:

- **Qualidade funcional:** Nº de defeitos funcionais (M1) e nota global (M4);
- **Usabilidade:** Nº de problemas de usabilidade (M2) e nota de usabilidade (M3);
- **Tempo:** Tempo total de desenvolvimento (M5) e eventual tempo de retrabalho (M6);
- **Aderência:** Cobertura de requisitos (M7), requisitos faltantes (M8) e incorretos (M9);
- **Experiência subjetiva:** Clareza percebida (M12), facilidade (M13) e satisfação (M14).

### 8.6 Variáveis de controle / bloqueio

- **Período do aluno (M10):** 1º, 5º e 8º período;
- **Nível de conhecimento (autoavaliação em 0–10):** usado para formar subgrupos:
  - Abaixo ou igual a 5;
  - Acima de 5.
- **Ambiente de execução:** Laboratórios da PUC Minas Lourdes, mesmos recursos (VS Code, Chrome, Figma quando aplicável), mesma tarefa, mesmo tempo (50 minutos).

### 8.7 Possíveis variáveis de confusão conhecidas

- Diferenças reais de experiência prática não capturadas completamente pela autoavaliação;
- Familiaridade prévia com Figma ou com leitura de especificações textuais;
- Motivação individual e interesse do aluno na atividade;
- Nível de cansaço ou carga de outras disciplinas no dia da coleta.

Essas variáveis não serão controladas totalmente, mas serão consideradas na discussão sobre ameaças à validade.

### 8.8 Tabela de fatores, tratamentos e combinações

Para cumprir o requisito da disciplina, segue uma tabela com os fatores, tratamentos e combinação planejada entre eles.

#### Tabela 2 – Fatores, tratamentos e combinações

| Fator | Níveis | Tipo |
|-------|--------|------|
| Tipo de requisito | Protótipo (T1); Texto (T2) | Fator experimental principal |
| Período do aluno | 1º; 5º; 8º | Fator de bloqueio / moderador |
| Nível de conhecimento | ≤ 5; > 5 | Fator de bloqueio / moderador |

**Combinações planejadas (por período e nível):**

| Período | Nível de conhecimento (autoavaliação) | T1 – Protótipo | T2 – Texto | Total de alunos |
|---------|----------------------------------------|----------------|------------|------------------|
| 1º      | ≤ 5                                    | 5              | 5          | 10               |
| 1º      | > 5                                    | 5              | 5          | 10               |
| 5º      | ≤ 5                                    | 5              | 5          | 10               |
| 5º      | > 5                                    | 5              | 5          | 10               |
| 8º      | ≤ 5                                    | 5              | 5          | 10               |
| 8º      | > 5                                    | 5              | 5          | 10               |
| **Total** | —                                     | **30**         | **30**     | **60**           |

---

## 9. Desenho experimental

### 9.1 Tipo de desenho

O experimento será conduzido como um:

- **Desenho com grupos paralelos**, com dois tratamentos (Protótipo vs. Texto);
- **Balanceado** em relação ao número de participantes por tratamento (30 em cada);
- Com **bloqueio** por:
  - Período (1º, 5º, 8º);
  - Nível de conhecimento (abaixo/igual a 5, acima de 5).

Na prática, trata-se de um desenho que se aproxima de um **fatorial 2 × 3**, com estratificação adicional pelo nível de conhecimento.

### 9.2 Randomização e alocação

- A alocação em T1 (Protótipo) ou T2 (Texto) será feita:
  - Separadamente **dentro de cada período** (1º, 5º, 8º);
  - E **dentro de cada faixa de conhecimento** (≤5 e >5).
- Após coletar as autoavaliações, os alunos de cada período serão ordenados (por nota ou aleatoriamente) e então divididos em:
  - 10 com conhecimento ≤5;
  - 10 com conhecimento >5.
- Em cada subgrupo de 10, a alocação será aleatória:
  - 5 sorteados para Protótipo (T1);
  - 5 sorteados para Texto (T2).

Essa randomização pode ser feita com uma planilha simples, função de sorteio ou ferramenta online.

### 9.3 Balanceamento e contrabalanço

- **Balanceamento:**  
  A tabela de combinações (Seção 8.8) garante que, idealmente, haja o mesmo número de alunos em cada combinação de período × nível de conhecimento × tipo de requisito.
- **Contrabalanço:**  
  Como cada aluno participa apenas de um tratamento e realiza apenas uma tarefa, não há efeitos de ordem ou aprendizagem entre tratamentos. Portanto, não é necessário contrabalanço de ordem de execução.

### 9.4 Número de grupos e sessões

- **Grupos:** Dois grupos principais, um por tratamento:
  - Grupo T1: recebe os requisitos no formato **protótipo interativo**;
  - Grupo T2: recebe os requisitos no formato **especificação textual**.
- **Sessões:**  
  O experimento será conduzido em **uma sessão principal de 50 minutos** por turma/período (ou turmas agrupadas), com:
  - Preenchimento do formulário de autoavaliação;
  - Distribuição dos tratamentos;
  - Execução da tarefa de desenvolvimento;
  - Aplicação do questionário pós-tarefa.
