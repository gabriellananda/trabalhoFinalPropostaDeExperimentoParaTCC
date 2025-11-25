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

### 1.4 Datas
- **Data de criação:** 23/11/2025  
- **Última atualização:** 24/11/2025

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
