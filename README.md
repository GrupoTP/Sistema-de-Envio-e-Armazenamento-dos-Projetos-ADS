<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Senac_logo.svg.png" width="140" alt="Logo Senac" />

# 🎓 Observatório de Projetos Integradores

**Faculdade Senac Recife · Curso de Análise e Desenvolvimento de Sistemas**

*Janeiro a Junho de 2026*

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Faculdade](https://img.shields.io/badge/Faculdade-Senac%20Recife-red?style=for-the-badge)
![Curso](https://img.shields.io/badge/Curso-ADS-blue?style=for-the-badge)
![Ano](https://img.shields.io/badge/2026-Jan%20–%20Jun-purple?style=for-the-badge)

</div>

---

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Capa.png?raw=true" width="100%" alt="Capa do Projeto — Observatório de Projetos Integradores" />

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [O Problema](#-o-problema)
- [A Solução — Funcionalidades](#-a-solução--funcionalidades)
- [Diferenciais do Sistema](#-diferenciais-do-sistema)
- [Impacto ESG](#-impacto-esg)
- [Mercado](#-mercado)
- [Benchmark](#-benchmark)
- [Modelo de Negócio](#-modelo-de-negócio)
- [Público-Alvo](#-público-alvo)
- [Perfis de Usuário](#-perfis-de-usuário)
- [Sistema de Notas](#-sistema-de-notas)
- [Legislação e Conformidade](#-legislação-e-conformidade)
- [Tecnologias](#-tecnologias)
- [Protótipo e Equipe](#-protótipo-e-equipe)
- [Equipe](#-equipe)
- [Contato](#-contato)

---

## 📖 Sobre o Projeto

O **Observatório de Projetos Integradores** é uma plataforma web desenvolvida para a **Faculdade Senac Recife**, com o objetivo de centralizar e organizar a submissão, validação e avaliação dos Projetos Integradores do curso de **Análise e Desenvolvimento de Sistemas**.

O sistema nasce da necessidade de substituir processos manuais e descentralizados, oferecendo um repositório histórico de projetos acessível a alunos — para composição de portfólio profissional — e a professores — para avaliação acadêmica estruturada.

> _"Plataforma centralizada para submissão, acompanhamento de prazos, feedback por rubricas e geração de portfólio com selos de conquista."_

A plataforma conta com perfis específicos para **Alunos**, **Professores** e **Coordenadores/Administradores**, garantindo um fluxo de trabalho estruturado desde a concepção do projeto até a nota final, com rastreabilidade completa das submissões.

---

## 🚨 O Problema

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Problema.png" width="100%" alt="Slide: O Problema — 4 gargalos críticos do processo atual" />

</div>

O processo atual de entrega e avaliação de Projetos Integradores apresenta **4 gargalos críticos**:

| # | Gargalo | Impacto |
|:---:|---|---|
| 1 | **Fragmentação** | Informações dispersas em múltiplos canais e ferramentas |
| 2 | **Invisibilidade** | Projetos sem visibilidade institucional ou portfólio organizado |
| 3 | **Retrabalho** | Processos repetidos manualmente a cada semestre |
| 4 | **Falta de Governança** | Ausência de controle, rastreabilidade e conformidade LGPD |

> _"Esses gargalos custam tempo, visibilidade e credibilidade institucional."_

---

## ✨ A Solução — Funcionalidades

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades.png" width="100%" alt="Slide: Funcionalidades do Sistema" />

</div>

Solucionamos os gargalos com um sistema completo organizado em módulos:

| Módulo | O que entrega |
|---|---|
| 🖥️ **Dashboard** | Visão geral de submissões, prazos e status em tempo real |
| 📁 **Projetos** | Submissão de arquivos (PDF/ZIP), vídeo demonstrativo e descrição |
| 👤 **Perfis** | Gestão de Alunos, Professores e Administradores com permissões distintas |
| 🔐 **Autenticação** | Login único por perfil, e-mail primário e secundário |
| 📊 **Relatórios** | Exportação de entregas e histórico de avaliações |
| 🌐 **Observatório Público** | Vitrine de projetos aprovados acessível institucionalmente |

---

## 🚀 Diferenciais do Sistema

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades%20Diferenciais.png" width="100%" alt="Slide: Funcionalidades Diferenciais do Observatório" />

</div>

O Observatório foi desenvolvido com funcionalidades originais que o tornam único no contexto acadêmico da Faculdade Senac Recife:

### 🔐 Autenticação e Acesso
- **Autenticação múltipla de login** — e-mail institucional (primário) **ou** e-mail escolhido pelo próprio aluno (secundário), ambos funcionais para login
- **Tela de seleção de perfil** — usuários que acumulam múltiplos papéis (Aluno, Professor, Administrador) escolhem com qual perfil desejam acessar a cada sessão

### 🛡️ Regras de Administração
- **Mínimo obrigatório de 2 ADMs** — o sistema bloqueia ações que reduzam os administradores ativos abaixo de 2, prevenindo travamento total
- **Recuperação de ADM** — mecanismo especial de restauração de acesso caso todas as contas administrativas sejam perdidas
- **Tela de cadastro exclusiva do ADM** — somente o Administrador pode criar novos usuários no sistema
- **Ativar / Desativar perfis** — o ADM pode suspender um perfil sem excluí-lo, preservando todo o histórico e dados vinculados

### ⚙️ Configurações e Personalização
- **Nome Social** — cadastrável e modificável nas configurações, reutilizado em todo o sistema automaticamente
- **Dois telefones cadastráveis** — o usuário pode registrar até 2 números de contato nas configurações
- **Registro de utilização da plataforma** — data de criação da conta e data do último login exibidos automaticamente na tela de configurações

### 🧭 Navegação e Interface
- **Ícone de voltar universal** — presente em todas as páginas de todos os perfis, retornando sempre à página Início do perfil atual
- **Menu volante em todas as páginas** — acessível em qualquer tela, exibindo cabeçalho com o ícone do Senac e o nome do Painel em uso

### 📝 Formulários e Validação
- **Sinalização visual de campos obrigatórios** — marcação visual clara e imediata em todos os campos obrigatórios, evitando erros de submissão

### 🎓 Currículo e Portfólio
- **Tela dedicada de Currículo/Portfólio** — preview em tempo real para Professores e Alunos, com competências em formato de tags escaneáveis por IA

---

## 🌱 Impacto ESG

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/ESG.png" width="100%" alt="Slide: Impacto ESG do Projeto" />

</div>

O Observatório de Projetos Integradores foi concebido com responsabilidade em três dimensões:

| Dimensão | Ação |
|---|---|
| 🌿 **Ambiental (E)** | Elimina impressões físicas e e-mails redundantes; digitaliza completamente o fluxo acadêmico |
| 🤝 **Social (S)** | Gera portfólio digital oficial para alunos, ampliando oportunidades profissionais |
| 🏛️ **Governança (G)** | Conformidade LGPD, controle de acesso por perfil e logs de auditoria integrados |

---

## 📈 Mercado

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Mercado.png" width="100%" alt="Slide: Análise de Mercado" />

</div>

- 💰 Até 2025, o mercado investiu **US$ 340 milhões** no setor de tecnologia educacional
- 🌎 O Brasil ocupa posição de destaque no **Ranking Mundial de Educação Digital**
- 🏫 O Senac possui mais de **500 unidades** no Brasil — tornando o Observatório uma **solução altamente replicável** em escala nacional

---

## 🔍 Benchmark

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Benchmark.png" width="100%" alt="Slide: Benchmark — Por que o Observatório?" />

</div>

### Por que criar o Observatório em vez de usar ferramentas existentes?

| Critério | Google Classroom | Moodle | GitHub + Drive | ✅ **Observatório** |
|---|:---:|:---:|:---:|:---:|
| Foco em projetos integradores | ❌ | ❌ | ❌ | ✅ |
| Portfólio público | ❌ | ❌ | Parcial | ✅ |
| Múltiplos perfis com permissões | Parcial | Parcial | ❌ | ✅ |
| Conformidade LGPD nativa | ❌ | ❌ | ❌ | ✅ |
| Gestão integrada (submissão + validação + avaliação) | ❌ | Parcial | ❌ | ✅ |

> _O Observatório supera as ferramentas genéricas em foco institucional, governança e portfólio._

---

## 💼 Modelo de Negócio

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Modelo%20de%20Neg%C3%B3cio.png" width="100%" alt="Slide: Modelo de Negócio" />

</div>

**Valor entregue ao Senac:**
- Redução significativa de retrabalho semestral nos processos de avaliação
- Potencial de expansão como **produto replicável** para outras unidades (modelo SaaS)

**Valor entregue aos Alunos:**
- Portfólio oficial e rastreável vinculado à instituição
- Visibilidade para **empresas parceiras** por meio do Observatório público

---

## 🎯 Público-Alvo

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/P%C3%BAblico%20Alvo.png" width="100%" alt="Slide: Público-Alvo" />

</div>

> _"Transformando gestão acadêmica em inteligência institucional."_

O Observatório de Projetos Integradores foi projetado para três perfis complementares dentro da Faculdade Senac Recife:

<details>
<summary><strong>🎓 Aluno</strong></summary>

- Faixa etária: 18 a 45 anos
- Realiza upload de arquivos, adiciona link de vídeo e descrição do projeto
- Acompanha o status de aprovação da submissão em tempo real
- Visualiza feedback e nota final do professor
- Monta e compartilha seu currículo/portfólio profissional
- Uso semestral, concentrado nos períodos de entrega

</details>

<details>
<summary><strong>👩‍🏫 Professor</strong></summary>

- Faixa etária: 25 a 65 anos
- Acessa lista de projetos aprovados pelo Coordenador/Administrador
- Avalia por rubrica: Funcionalidade, Documentação e Criatividade (0 a 10)
- Fornece comentários de feedback detalhados
- Acesso ao repositório histórico para referência acadêmica
- Uso semestral, no período de avaliação

</details>

<details>
<summary><strong>🏛️ Coordenador / Administrador</strong></summary>

- Faixa etária: 30 a 60 anos
- Valida submissões: aprova ou reprova projetos para avaliação
- Cadastra, edita e gerencia perfis de alunos e professores
- Ativa e desativa perfis sem excluí-los permanentemente
- Único com permissão para alterar o e-mail primário de um usuário
- Uso contínuo, com maior intensidade nos períodos de entrega

</details>

---

## 🎨 Sistema de Notas

As notas exibidas ao aluno possuem **codificação visual por cores** e **filtro de ordenação do melhor para o pior**, tornando a leitura dos resultados mais intuitiva e acessível.

| Sigla | Descrição | Faixa | Cor |
|:---:|---|:---:|:---:|
| **AE** | Atendido com Excelência | 9,5 — 10 | 🟢 VERDE |
| **O** | Ótimo | 8,0 — 9,4 | 🔵 AZUL |
| **B** | Bom | 6,5 — 7,9 | 🟡 AMARELO |
| **ANS** | Ainda Não Suficiente | 4,0 — 6,4 | 🟠 LARANJA |
| **I** | Insuficiente | 0,0 — 3,9 | 🔴 VERMELHO |

---

## ⚖️ Legislação e Conformidade

O sistema foi desenvolvido em plena conformidade com a legislação brasileira vigente:

- 🔒 **LGPD — Lei nº 13.709/2018** · Proteção de dados pessoais de alunos e professores, com logs de auditoria, controle de acesso e consentimento para dados sensíveis
- 🌐 **Marco Civil da Internet — Lei nº 12.965/2014** · Guarda de registros de acesso e privacidade dos usuários
- 🎓 **LDB — Lei nº 9.394/1996** · Diretrizes educacionais e sigilo dos dados acadêmicos
- ✍️ **Lei de Direitos Autorais — Lei nº 9.610/1998** · Proteção da autoria dos projetos submetidos pelos alunos
- 🏫 **Normas Internas da Faculdade Senac Recife** · Regulamento acadêmico e políticas de TI institucionais

---

## 🛠️ Tecnologias

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Encerramento.png" width="100%" alt="Slide: Encerramento — Stack Tecnológica" />

</div>

A plataforma centraliza submissão, validação e avaliação de Projetos Integradores, desenvolvida com conformidade total à LGPD e utilizando as seguintes tecnologias:

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-0095D5?style=for-the-badge&logo=ktor&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![YouTrack](https://img.shields.io/badge/YouTrack-000000?style=for-the-badge&logo=youtrack&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

| Camada | Tecnologia |
|---|---|
| **Backend** | Kotlin + Ktor |
| **Banco de Dados** | SQL (modelagem relacional) |
| **Gerenciamento de Projeto** | YouTrack |
| **Design / Prototipação** | Figma / FigmaMaker |
| **Versionamento** | Git / GitHub |
| **Segurança** | HTTPS, autenticação por perfil, conformidade LGPD |

---

## 🖥️ Protótipo e Equipe

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Equipe_Prot%C3%B3tipo.png" width="100%" alt="Slide: Equipe e Protótipo" />

</div>

O protótipo de alta fidelidade foi desenvolvido no **FigmaMaker**, contemplando todos os fluxos principais de cada perfil de usuário.

<div align="center">

[![Ver Protótipo no Figma](https://img.shields.io/badge/Ver%20Prot%C3%B3tipo%20no%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/6PLVp9KMc4E00q1DhgzxM0/OBSERVATORIO-DE-PROJETOS-INTEGRADORES-FACULDADE-SENAC?fullscreen=1&t=EgHVDl4rL7Kb4xUX-1&preview-route=%2Flogin)

[![Ver Repositório no GitHub](https://img.shields.io/badge/Ver%20Reposit%C3%B3rio%20no%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 👩‍💻 Equipe

<div align="center">

### Polyana Fontes
**Desenvolvedora Full Stack · Modelagem de Banco de Dados · Documentação Técnica**

Aluna de Análise e Desenvolvimento de Sistemas
Faculdade Senac Recife-PE

---

### Thayná Batista da Silva
**Gerente / Analista de Requisitos · Scrum Master**
**Product Designer · Prototipação de Alta Fidelidade (Figma)**

Aluna de Análise e Desenvolvimento de Sistemas
Faculdade Senac Recife-PE · Turma 2025 · Formação prevista: 2027

</div>

---

## 📬 Contato

<div align="center">

### Polyana Fontes

<a href="https://github.com/Polyana-Fontes" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

---

### Thayná Batista da Silva

<a href="https://br.linkedin.com/in/thaynabds" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://www.instagram.com/thaynabdstec/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>
<a href="mailto:thaynabdstec@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

📧 [thaynabdstec@gmail.com](mailto:thaynabdstec@gmail.com) · 📱 +55 (81) 97912-6121

<img src="https://raw.githubusercontent.com/thaynabds/AppMedSmart/refs/heads/main/Cart%C3%A3o%20TEC%20Thayn%C3%A1%20Batista%20da%20Silva.png" width="340" alt="Cartão TEC Thayná Batista da Silva" />

</div>

---

<div align="center">

**Copyright © 2026, Polyana Fontes; Thayná Batista da Silva — Observatório de Projetos Integradores. Todos os direitos reservados.**

Feito com 💜 por **Thayná Batista da Silva** e **Polyana Fontes**
durante o curso de **Análise e Desenvolvimento de Sistemas**
**Faculdade Senac Recife · 2026**

*Componente Curricular: Engenharia de Requisitos · Docente: Sonia Gomes de Oliveira*

</div>

---

</div>

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Senac_logo.svg.png" width="140" alt="Senac Logo" />

# 🎓 Integrative Projects Observatory

**Faculdade Senac Recife · Systems Analysis and Development Course**

*January – June 2026*

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Institution](https://img.shields.io/badge/Faculdade-Senac%20Recife-red?style=for-the-badge)
![Course](https://img.shields.io/badge/Course-ADS-blue?style=for-the-badge)
![Year](https://img.shields.io/badge/2026-Jan%20–%20Jun-purple?style=for-the-badge)

</div>

---

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Capa.png?raw=true" width="100%" alt="Project Cover — Integrative Projects Observatory" />

</div>

---

## 📋 Index

- [About the Project](#-about-the-project)
- [The Problem](#-the-problem)
- [The Solution — Features](#-the-solution--features)
- [System Differentiators](#-system-differentiators)
- [ESG Impact](#-esg-impact)
- [Market](#-market)
- [Benchmark](#-benchmark)
- [Business Model](#-business-model)
- [Target Audience](#-target-audience)
- [User Profiles](#-user-profiles)
- [Grading System](#-grading-system)
- [Legislation and Compliance](#-legislation-and-compliance)
- [Technologies](#-technologies)
- [Prototype and Team](#-prototype-and-team)
- [Team](#-team)
- [Contact](#-contact)

---

## 📖 About the Project

The **Integrative Projects Observatory** is a web platform developed for **Faculdade Senac Recife**, designed to centralize and streamline the submission, validation, and evaluation of **Integrative Projects** for the **Systems Analysis and Development** course.

The system replaces scattered, manual workflows with a unified repository of projects, accessible to:
- **Students** — to build an official professional portfolio.
- **Teachers and Coordinators** — to conduct structured academic evaluation.

> _"A centralized platform for project submission, deadline tracking, rubric‑based feedback, and portfolio generation with achievement badges."_

The platform offers tailored profiles for **Students**, **Teachers**, and **Administrators**, ensuring a structured workflow from project conception to final grade, with full traceability of all submissions.

---

## 🚨 The Problem

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Problema.png" width="100%" alt="Slide: The Problem — 4 critical bottlenecks of the current process" />

</div>

The current process for submitting and evaluating Integrative Projects faces **4 critical bottlenecks**:

| # | Bottleneck | Impact |
|:---:|---|---|
| 1 | **Fragmentation** | Information scattered across multiple channels and tools |
| 2 | **Invisibility** | Projects lack institutional visibility and an organized portfolio |
| 3 | **Rework** | Manual processes repeated every semester |
| 4 | **Lack of Governance** | No control, traceability, or LGPD compliance |

> _"These bottlenecks waste time, visibility, and institutional credibility."_

---

## ✨ The Solution — Features

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades.png" width="100%" alt="Slide: System Features" />

</div>

The Observatory addresses these bottlenecks with a complete, modular system:

| Module | What it delivers |
|---|---|
| 🖥️ **Dashboard** | Real‑time overview of submissions, deadlines, and status |
| 📁 **Projects** | Upload of files (PDF/ZIP), demo video link, and project description |
| 👤 **Profiles** | Management of Students, Teachers, and Administrators with distinct permissions |
| 🔐 **Authentication** | Single‑sign‑on per profile, with primary and secondary email support |
| 📊 **Reports** | Export of deliveries and evaluation history |
| 🌐 **Public Observatory** | Institutional showcase of approved projects |

---

## 🚀 System Differentiators

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades%20Diferenciais.png" width="100%" alt="Slide: Unique Features of the Observatory" />

</div>

The Observatory includes original features that make it stand out in the academic context of **Faculdade Senac Recife**:

### 🔐 Authentication and Access
- **Multiple login emails** — institutional email (primary) or student‑chosen email (secondary), both valid for login.
- **Profile selection screen** — users with multiple roles (Student, Teacher, Administrator) choose which profile to use per session.

### 🛡️ Administration Rules
- **Minimum of 2 Admins** — actions that reduce active admins below 2 are blocked, preventing total lockout.
- **Admin recovery** — dedicated recovery mechanism if all admin accounts are lost.
- **Admin‑only registration** — only Administrators can create new users.
- **Activate / Deactivate profiles** — suspend a profile without deleting it, preserving all history and data.

### ⚙️ Settings and Personalization
- **Social Name** — registered and editable in settings, automatically reused across the system.
- **Two phone numbers** — up to 2 contact numbers can be stored in user settings.
- **Usage records** — account creation date and last login displayed automatically on the settings screen.

### 🧭 Navigation and Interface
- **Universal back icon** — present on every page for every profile, returning to the current profile’s Home page.
- **Floating menu** — available on all pages, with a header containing the Senac logo and the current panel name.

### 📝 Forms and Validation
- **Visual required‑field indicators** — clear visual cues on all mandatory fields, reducing submission errors.

### 🎓 CV and Portfolio
- **Dedicated CV/Portfolio screen** — real‑time preview for Students and Teachers, with competencies shown as AI‑scannable tags.

---

## 🌱 ESG Impact

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/ESG.png" width="100%" alt="Slide: ESG Impact of the Project" />

</div>

The Integrative Projects Observatory was designed with responsibility across three dimensions:

| Dimension | Action |
|---|---|
| 🌿 **Environmental (E)** | Eliminates physical printing and redundant emails; fully digitizes the academic workflow |
| 🤝 **Social (S)** | Provides an official digital portfolio for students, boosting professional opportunities |
| 🏛️ **Governance (G)** | LGPD‑compliant access control, audit logs, and structured data governance |

---

## 📈 Market

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Mercado.png" width="100%" alt="Slide: Market Analysis" />

</div>

- 💰 By 2025, the edtech market invested **US$ 340 million** in Brazil.  
- 🌎 Brazil ranks among the top countries in the **Global Digital Education Ranking**.  
- 🏫 Senac has over **500 units** nationwide — making the Observatory a **highly scalable, replicable solution**.

---

## 🔍 Benchmark

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Benchmark.png" width="100%" alt="Slide: Why the Observatory?" />

</div>

### Why build the Observatory instead of using existing tools?

| Criterion | Google Classroom | Moodle | GitHub + Drive | ✅ **Observatory** |
|---|:---:|:---:|:---:|:---:|
| Focused on integrative projects | ❌ | ❌ | ❌ | ✅ |
| Public portfolio | ❌ | ❌ | Partial | ✅ |
| Multiple profiles with permissions | Partial | Partial | ❌ | ✅ |
| Native LGPD compliance | ❌ | ❌ | ❌ | ✅ |
| Integrated management (submission + validation + evaluation) | ❌ | Partial | ❌ | ✅ |

> _The Observatory outperforms generic tools in institutional focus, governance, and portfolio‑oriented flows._

---

## 💼 Business Model

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Modelo%20de%20Neg%C3%B3cio.png" width="100%" alt="Slide: Business Model" />

</div>

**Value delivered to Senac:**
- Drastically reduced rework in semester‑based evaluation cycles.
- A scalable product that can be replicated across other Senac units (SaaS‑like model).

**Value delivered to Students:**
- Official, traceable portfolio linked to the institution.
- Visibility to **partner companies** through the public Observatory.

---

## 🎯 Target Audience

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/P%C3%BAblico%20Alvo.png" width="100%" alt="Slide: Target Audience" />

</div>

> _"Transforming academic management into institutional intelligence."_

The Integrative Projects Observatory targets three complementary profiles at **Faculdade Senac Recife**:

<details>
<summary><strong>🎓 Student</strong></summary>

- Age range: 18–45 years.
- Uploads project files, demo video link, and description.
- Tracks submission approval status in real time.
- Views feedback and final grades from professors.
- Builds and shares a professional CV/portfolio.
- Uses the platform mainly during submission periods each semester.

</details>

<details>
<summary><strong>👩‍🏫 Teacher</strong></summary>

- Age range: 25–65 years.
- Accesses a list of projects approved by Coordinators/Administrators.
- Grades via rubric (Functionality, Documentation, Creativity; 0–10).
- Leaves detailed feedback comments.
- Can consult the historical repository for academic reference.
- Uses the platform mainly during evaluation periods.

</details>

<details>
<summary><strong>🏛️ Coordinator / Administrator</strong></summary>

- Age range: 30–60 years.
- Validates submissions: approves or rejects projects for evaluation.
- Registers, edits, and manages student and teacher profiles.
- Activates and deactivates profiles without permanent deletion.
- Only user allowed to change a user’s primary email.
- Uses the platform continuously, with higher activity during submission seasons.

</details>

---

## 🎨 Grading System

Grades shown to students are **color‑coded** and support **sorting from best to worst**, making results more intuitive and accessible.

| Abbreviation | Description | Range | Color |
|:---:|---|:---:|:---:|
| **AE** | Met with Excellence | 9.5 — 10 | 🟢 GREEN |
| **O**  | Great | 8.0 — 9.4 | 🔵 BLUE |
| **B**  | Good | 6.5 — 7.9 | 🟡 YELLOW |
| **ANS** | Not Yet Sufficient | 4.0 — 6.4 | 🟠 ORANGE |
| **I**  | Insufficient | 0.0 — 3.9 | 🔴 RED |

---

## ⚖️ Legislation and Compliance

The system was developed in full compliance with current Brazilian legislation:

- 🔒 **LGPD — Law No. 13.709/2018** · Protects personal data of students and teachers, with audit logs, access control, and consent management for sensitive data.  
- 🌐 **Marco Civil da Internet — Law No. 12.965/2014** · Ensures retention of access records and user privacy.  
- 🎓 **LDB — Law No. 9.394/1996** · Follows national educational guidelines and academic confidentiality standards.  
- ✍️ **Copyright Law — Law No. 9.610/1998** · Guarantees authorship rights for all student‑submitted projects.  
- 🏫 **Senac Recife internal regulations** · Adheres to academic rules and institutional IT policies.

---

## 🛠️ Technologies

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Encerramento.png" width="100%" alt="Slide: Closing — Tech Stack" />

</div>

The platform centralizes submission, validation, and evaluation of Integrative Projects, built with full LGPD compliance and the following technologies:

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-0095D5?style=for-the-badge&logo=ktor&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![YouTrack](https://img.shields.io/badge/YouTrack-000000?style=for-the-badge&logo=youtrack&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

| Layer | Technology |
|---|---|
| **Backend** | Kotlin + Ktor |
| **Database** | SQL (relational modeling) |
| **Project Management** | YouTrack |
| **Design / Prototyping** | Figma / FigmaMaker |
| **Versioning** | Git / GitHub |
| **Security** | HTTPS, profile‑based authentication, LGPD compliance |

---

## 🖥️ Prototype and Team

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Equipe_Prot%C3%B3tipo.png" width="100%" alt="Slide: Team and Prototype" />

</div>

The high‑fidelity prototype was developed in **FigmaMaker**, covering all main user flows for each profile.

<div align="center">

[![View Prototype on Figma](https://img.shields.io/badge/View%20Prototype%20on%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/6PLVp9KMc4E00q1DhgzxM0/OBSERVATORIO-DE-PROJETOS-INTEGRADORES-FACULDADE-SENAC?fullscreen=1&t=EgHVDl4rL7Kb4xUX-1&preview-route=%2Flogin)

[![View Repository on GitHub](https://img.shields.io/badge/View%20Repository%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 👩‍💻 Team

<div align="center">

### Polyana Fontes  
**Full Stack Developer · Database Modeling · Technical Documentation**

Student of Systems Analysis and Development  
Faculdade Senac Recife-PE  

---

### Thayná Batista da Silva  
**Manager / Requirements Analyst · Scrum Master**  
**Product Designer · High‑fidelity Prototyping (Figma)**

Student of Systems Analysis and Development  
Faculdade Senac Recife‑PE · Class 2025 · Expected graduation: 2027  

</div>

---

## 📬 Contact

<div align="center">

### Polyana Fontes

<a href="https://github.com/Polyana-Fontes" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

---

### Thayná Batista da Silva

<a href="https://br.linkedin.com/in/thaynabds" target="_blank">
  <img src="https://github.com/thaynabds/AppMedSmart/blob/main/CapaCartão%20ThaynáBDSTEC.png" />
</a>
<a href="https://www.instagram.com/thaynabdstec/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>
<a href="mailto:thaynabdstec@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

📧 [thaynabdstec@gmail.com](mailto:thaynabdstec@gmail.com) · 📱 +55 (81) 97912-6121

<img src="https://raw.githubusercontent.com/thaynabds/AppMedSmart/refs/heads/main/Cart%C3%A3o%20TEC%20Thayn%C3%A1%20Batista%20da%20Silva.png" width="340" alt="Cartão TEC Thayná Batista da Silva" />


</div>

---

<div align="center">

**Copyright © 2026, Polyana Fontes; Thayná Batista da Silva — Integrative Projects Observatory. All rights reserved.**

Made with 💜 by **Thayná Batista da Silva** and **Polyana Fontes**  
during the **Systems Analysis and Development** course  
**Faculdade Senac Recife · 2026**

*Course Component: Requirements Engineering · Instructor: Sonia Gomes de Oliveira*

</div>
