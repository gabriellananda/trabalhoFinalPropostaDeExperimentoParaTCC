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

### 1.4 Datas
- **Data de criação:** 23/11/2025  
- **Última atualização:** 23/11/2025

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
