<div align="center">

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Senac_logo.svg.png?token=GHSAT0AAAAAAD55KXJI7BFQOJUXUQFVFTOY2QQ5U7A" width="140" alt="Logo Senac" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Problema.png?token=GHSAT0AAAAAAD55KXJJ3EUDJQBI2HFN23W42QQ5NMA" width="100%" alt="Slide: O Problema — 4 gargalos críticos do processo atual" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Funcionalidades.png?token=GHSAT0AAAAAAD55KXJJ37VPZUJK6ZPDL4KA2QQ5PDA" width="100%" alt="Slide: Funcionalidades do Sistema" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Funcionalidades%20Diferenciais.png?token=GHSAT0AAAAAAD55KXJIUQDLHWHYG4W4RAOE2QQ5N4Q" width="100%" alt="Slide: Funcionalidades Diferenciais do Observatório" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/ESG.png?token=GHSAT0AAAAAAD55KXJJALQZ4MPZ5DTQZKAA2QQ5QEA" width="100%" alt="Slide: Impacto ESG do Projeto" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Mercado.png?token=GHSAT0AAAAAAD55KXJIROJ7OQXVSHNUWX2C2QQ5QVQ" width="100%" alt="Slide: Análise de Mercado" />

</div>

- 💰 Até 2025, o mercado investiu **US$ 340 milhões** no setor de tecnologia educacional
- 🌎 O Brasil ocupa posição de destaque no **Ranking Mundial de Educação Digital**
- 🏫 O Senac possui mais de **500 unidades** no Brasil — tornando o Observatório uma **solução altamente replicável** em escala nacional

---

## 🔍 Benchmark

<div align="center">

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Benchmark.png?token=GHSAT0AAAAAAD55KXJJ2NKI7FV4PCZVRKCE2QQ5RFA" width="100%" alt="Slide: Benchmark — Por que o Observatório?" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Modelo%20de%20Neg%C3%B3cio.png?token=GHSAT0AAAAAAD55KXJJEEPBTQCYVKMXQSLK2QQ5SCQ" width="100%" alt="Slide: Modelo de Negócio" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/P%C3%BAblico%20Alvo.png?token=GHSAT0AAAAAAD55KXJIGG25GKBMHXAUNTHA2QQ5S5Q" width="100%" alt="Slide: Público-Alvo" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Encerramento.png?token=GHSAT0AAAAAAD55KXJJYB5L637VB7VYHBSM2QQ5TXA" width="100%" alt="Slide: Encerramento — Stack Tecnológica" />

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

<img src="https://raw.githubusercontent.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/refs/heads/main/Equipe_Prot%C3%B3tipo.png?token=GHSAT0AAAAAAD55KXJJ4UBTMMA5FZCNWUOY2QQ5UNA" width="100%" alt="Slide: Equipe e Protótipo" />

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
