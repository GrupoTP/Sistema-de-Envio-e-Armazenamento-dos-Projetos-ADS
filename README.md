# Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS
Sistema de envio e armazenamento de projetos do curso de Análise e Desenvolvimento de Sistemas — Faculdade Senac Recife (jan–jun/2026). Plataforma centralizada para submissão, acompanhamento de prazos, feedback por rubricas e geração de portfólio com selos de conquista.

<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Senac_logo.svg/320px-Senac_logo.svg.png" width="120" alt="Logo Senac" />

# 🎓 Observatório de Projetos Integradores

**Faculdade Senac Recife · Curso de Análise e Desenvolvimento de Sistemas**

*Janeiro a Junho de 2026*

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Faculdade](https://img.shields.io/badge/Faculdade-Senac%20Recife-red?style=for-the-badge)
![Curso](https://img.shields.io/badge/Curso-ADS-blue?style=for-the-badge)
![Ano](https://img.shields.io/badge/2026-Jan%20–%20Jun-purple?style=for-the-badge)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Diferenciais do Sistema](#-diferenciais-do-sistema)
- [Perfis de Usuário](#-perfis-de-usuário)
- [Sistema de Notas](#-sistema-de-notas)
- [Legislação e Conformidade](#-legislação-e-conformidade)
- [Tecnologias](#-tecnologias)
- [Protótipo](#-protótipo)
- [Equipe](#-equipe)
- [Contato](#-contato)

---

## 📖 Sobre o Projeto

O **Observatório de Projetos Integradores** é uma plataforma web desenvolvida para a **Faculdade Senac Recife**, com o objetivo de centralizar e organizar a submissão, validação e avaliação dos Projetos Integradores do curso de **Análise e Desenvolvimento de Sistemas**.

O sistema nasce da necessidade de substituir processos manuais e descentralizados, oferecendo um repositório histórico de projetos acessível a alunos — para composição de portfólio profissional — e a professores — para avaliação acadêmica estruturada.

> _"Sistema de envio e armazenamento de projetos do curso de Análise e Desenvolvimento de Sistemas — Faculdade Senac Recife (jan–jun/2026). Plataforma centralizada para submissão, acompanhamento de prazos, feedback por rubricas e geração de portfólio com selos de conquista."_

A plataforma conta com perfis específicos para **Alunos**, **Professores** e **Coordenadores/Administradores**, garantindo um fluxo de trabalho estruturado desde a concepção do projeto até a nota final, com rastreabilidade completa das submissões.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 🔐 **Login com E-mail Secundário** | Acesso por e-mail institucional ou e-mail alternativo cadastrado |
| 👤 **Seleção de Perfil** | Tela de seleção para usuários com múltiplos perfis |
| 🔑 **Recuperação de Senha** | Redefinição de senha via e-mail cadastrado |
| 📁 **Submissão de Projetos** | Upload de arquivos (PDF/ZIP), link de vídeo e descrição |
| ✅ **Validação de Submissão** | Aprovação ou reprovação pelo Administrador/Coordenador |
| 🔔 **Notificação de Status** | Notificação automática do aluno sobre o status da submissão |
| 📊 **Avaliação por Rubrica** | Notas de 0 a 10 em Funcionalidade, Documentação e Criatividade |
| 💬 **Visualização de Feedback** | Nota final e comentários do professor disponíveis ao aluno |
| 👥 **Gerenciamento de Usuários** | Cadastro, edição e desativação de perfis pelo Administrador |
| 🗂️ **Repositório de Projetos** | Histórico de projetos aprovados para portfólio e referência |
| ⚙️ **Configurações de Perfil** | Edição de dados pessoais, e-mail secundário e foto de perfil |
| 📄 **Currículo / Portfólio** | Criação e edição com preview em tempo real |
| 🎨 **Notas com Cores e Filtro** | Sistema visual de menções com filtro do melhor para o pior |

---

## 🚀 Diferenciais do Sistema

O Observatório de Projetos Integradores foi desenvolvido com funcionalidades originais que o tornam único no contexto acadêmico da Faculdade Senac Recife.

### 🔐 Autenticação e Acesso
- **E-mail secundário para login** — o usuário pode cadastrar um e-mail alternativo nas configurações, utilizável também para autenticação
- **Tela de seleção de perfil** — usuários com múltiplos perfis (Professor, Aluno, Administrador/Coordenador) escolhem com qual perfil desejam acessar

### 🛡️ Regras de Administração
- **Mínimo de 2 Administradores** — o sistema impede que o número de ADMs ativos caia abaixo de 2, prevenindo bloqueio total
- **Recuperação de ADM** — mecanismo especial para restaurar acesso administrativo em caso de perda de todas as contas
- **Tela de cadastro exclusiva do ADM** — somente o Administrador pode criar novos usuários no sistema
- **Ativar/Desativar perfis** — o ADM pode desativar um perfil sem excluí-lo, preservando histórico e dados

### ⚙️ Configurações e Personalização
- **Nome Social** — cadastrável e modificável nas configurações, reutilizado em todo o sistema
- **Dois telefones cadastráveis** — o usuário pode registrar até 2 números de contato
- **Data de criação e último login** — exibidos automaticamente na tela de configurações

### 🧭 Navegação e Interface
- **Ícone de voltar universal** — presente em todas as páginas de todos os perfis, retornando sempre ao Início do perfil atual
- **Menu volante em todas as páginas** — acessível em qualquer tela, exibindo cabeçalho com o ícone do Senac e o nome do Painel em uso

### 📝 Formulários e Validação
- **Sinalização visual de campos obrigatórios** — todos os campos obrigatórios possuem marcação visual clara e imediata

### 📄 Currículo e Portfólio
- **Tela dedicada de Currículo/Portfólio** — com preview em tempo real para Professores e Alunos, incluindo competências em formato de tags escaneáveis por IA

---

## 👤 Perfis de Usuário

<details>
<summary><strong>🎓 Aluno</strong></summary>

- Faixa etária: 18 a 45 anos
- Realiza upload de arquivos, adiciona link de vídeo e descrição do projeto
- Acompanha o status de aprovação da submissão
- Visualiza feedback e nota final do professor
- Acessa e monta seu currículo/portfólio profissional
- Uso semestral, concentrado nos períodos de entrega

</details>

<details>
<summary><strong>👩‍🏫 Professor</strong></summary>

- Faixa etária: 25 a 65 anos
- Acessa lista de projetos aprovados pelo Coordenador/Administrador
- Avalia por rubrica (Funcionalidade, Documentação e Criatividade)
- Atribui notas e fornece comentários de feedback
- Acesso ao repositório histórico de projetos
- Uso semestral, no período de avaliação

</details>

<details>
<summary><strong>🏛️ Coordenador / Administrador</strong></summary>

- Faixa etária: 30 a 60 anos
- Valida submissões: aprova ou reprova projetos enviados pelos alunos
- Cadastra, edita e gerencia perfis de alunos e professores
- Ativa e desativa perfis sem excluí-los
- É o único que pode alterar o e-mail primário de um usuário
- Uso contínuo, com maior intensidade nos períodos de entrega

</details>

---

## 🎨 Sistema de Notas

As notas exibidas ao aluno possuem **codificação visual por cores** e **filtro de ordenação do melhor para o pior**, tornando a leitura dos resultados mais intuitiva.

| Sigla | Descrição | Faixa | Cor |
|:---:|---|:---:|:---:|
| **AE** | Atendido com Excelência | 9,5 — 10 | 🟢 VERDE |
| **O** | Ótimo | 8,0 — 9,4 | 🔵 AZUL |
| **B** | Bom | 6,5 — 7,9 | 🟡 AMARELO |
| **ANS** | Ainda Não Suficiente | 4,0 — 6,4 | 🟠 LARANJA |
| **I** | Insuficiente | 0,0 — 3,9 | 🔴 VERMELHO |

---

## ⚖️ Legislação e Conformidade

O sistema foi desenvolvido em conformidade com a legislação brasileira vigente:

- **LGPD — Lei nº 13.709/2018** · Proteção de dados pessoais de alunos e professores
- **Marco Civil da Internet — Lei nº 12.965/2014** · Guarda de registros e privacidade dos usuários
- **LDB — Lei nº 9.394/1996** · Diretrizes educacionais e sigilo dos dados acadêmicos
- **Lei de Direitos Autorais — Lei nº 9.610/1998** · Proteção da autoria dos projetos submetidos
- **Normas Internas da Faculdade Senac Recife** · Regulamento acadêmico e políticas de TI institucionais

---

## 🛠️ Tecnologias

> As tecnologias definitivas serão confirmadas conforme o avanço do desenvolvimento, respeitando os servidores e a infraestrutura da instituição.

- **Frontend:** Linguagens web modernas (HTML, CSS, JavaScript)
- **Backend:** Compatível com os servidores da Faculdade Senac Recife
- **Banco de Dados:** Modelagem relacional — Polyana Fontes
- **Design / Prototipação:** Figma / FigmaMaker — Thayná Batista da Silva
- **Versionamento:** Git / GitHub
- **Segurança:** HTTPS, autenticação por perfil, conformidade LGPD

---

## 🖥️ Protótipo

O protótipo de alta fidelidade foi desenvolvido no **FigmaMaker**, contemplando todos os fluxos principais:

<div align="center">

[![Figma](https://img.shields.io/badge/Ver%20Prot%C3%B3tipo%20no%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/6PLVp9KMc4E00q1DhgzxM0/OBSERVATORIO-DE-PROJETOS-INTEGRADORES-FACULDADE-SENAC?fullscreen=1&t=EgHVDl4rL7Kb4xUX-1&preview-route=%2Flogin)

[![GitHub](https://img.shields.io/badge/Ver%20Reposit%C3%B3rio%20no%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 👩‍💻 Equipe

<div align="center">

### Thayná Batista da Silva
**Gerente / Analista de Requisitos · Scrum Master**
**Product Designer · Prototipação de Alta Fidelidade (Figma)**

Aluna de Análise e Desenvolvimento de Sistemas
Faculdade Senac Recife-PE · Turma 2025 · Formação prevista: 2027

---

### Polyana Fontes
**Desenvolvedora Full Stack · Modelagem de Banco de Dados**
**Documentação Técnica**

Aluna de Análise e Desenvolvimento de Sistemas
Faculdade Senac Recife-PE

</div>

---

## 📬 Contato

<div align="center">

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

---

### Polyana Fontes

<a href="https://github.com/Polyana-Fontes" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

<div align="center">

Feito com 💜 por **Thayná Batista da Silva** e **Polyana Fontes**
durante o curso de **Análise e Desenvolvimento de Sistemas**
**Faculdade Senac Recife · 2026**

*Componente Curricular: Engenharia de Requisitos · Docente: Sonia Gomes de Oliveira*

</div>
