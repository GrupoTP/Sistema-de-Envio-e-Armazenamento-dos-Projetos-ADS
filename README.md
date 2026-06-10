<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Senac_logo.svg.png" width="140" alt="Logo Senac" />

# 🎓 Observatório de Projetos Integradores

**Faculdade Senac Recife · Curso de Análise e Desenvolvimento de Sistemas**

*Janeiro a Junho de 2026*

![Status](https://img.shields.io/badge/Status-Finalizado-brightgreen?style=for-the-badge)
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
- [Especificações Técnicas e Regras de Negócio](#-especificações-técnicas-e-regras-de-negócio)
  - [Contexto do Sistema](#contexto-do-sistema)
  - [Tela de Login](#tela-de-login)
  - [Regras de Cadastro de Usuários](#regras-de-cadastro-de-usuários)
  - [Campos Obrigatórios no Cadastro](#campos-obrigatórios-no-cadastro)
  - [Campos Não Obrigatórios no Cadastro](#campos-não-obrigatórios-no-cadastro)
  - [Regras de E-mail](#regras-de-e-mail)
  - [Tela de Configurações do Perfil](#tela-de-configurações-do-perfil)
  - [Tela de Criação de Currículo/Portfólio](#tela-de-criação-de-currículoportfólio)
- [Sistema de Notas](#-sistema-de-notas)
- [Impacto ESG](#-impacto-esg)
- [Mercado](#-mercado)
- [Benchmark](#-benchmark)
- [Modelo de Negócio](#-modelo-de-negócio)
- [Público-Alvo](#-público-alvo)
- [Legislação e Conformidade](#-legislação-e-conformidade)
- [Tecnologias](#-tecnologias)
- [Protótipo e Equipe](#-protótipo-e-equipe)
- [Credenciais Padrão de Demonstração](#-credenciais-padrão-de-demonstração)
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
- **Tela de seleção de perfil** — usuários que acumulam múltiplos papéis (Aluno, Professor, Administrador, Coordenador) escolhem com qual perfil desejam acessar a cada sessão
- **Alternância de perfil** — disponível apenas para usuários que possuam mais de um perfil cadastrado

### 🛡️ Regras de Administração
- **Mínimo obrigatório de 2 ADMs/Coordenadores** — o sistema bloqueia ações que reduzam os administradores/coordenadores ativos abaixo de 2, prevenindo travamento total
- **Recuperação de ADM** — mecanismo especial de restauração de acesso caso todas as contas administrativas sejam perdidas
- **Tela de cadastro exclusiva do ADM** — somente o Administrador pode criar novos usuários no sistema; o Professor **não tem acesso** à tela de cadastro de usuários
- **Ativar / Desativar perfis** — o ADM pode suspender um perfil sem excluí-lo, preservando todo o histórico e dados vinculados

### ⚙️ Configurações e Personalização
- **Nome Social** — cadastrável e modificável nas configurações, reutilizado em todo o sistema automaticamente
- **Dois telefones cadastráveis** — o usuário pode registrar até 2 números de contato nas configurações, ambos com opção de sinalizar que é WhatsApp
- **Registro de utilização da plataforma** — data de criação da conta e data do último login exibidos automaticamente na tela de configurações

### 🧭 Navegação e Interface
- **Ícone de voltar universal** — presente em todas as páginas de todos os perfis, retornando sempre à página Início do perfil atual
- **Menu volante em todas as páginas** — acessível em qualquer tela, exibindo cabeçalho com o ícone do Senac e o nome do Painel em uso

### 📝 Formulários e Validação
- **Sinalização visual de campos obrigatórios** — todo campo obrigatório possui marcação visual clara e imediata, visível para o usuário, evitando erros de submissão

### 🎓 Currículo e Portfólio
- **Tela dedicada de Currículo/Portfólio** para Professores e Alunos
- **Preview em tempo real** do currículo/portfólio, atualizado conforme o usuário preenche os campos
- **Opção de visibilidade por campo** — cada informação do currículo pode ser configurada para aparecer ou não para contratantes
- **Opção "Autorizo empresas parceiras do SENAC a entrarem em contato comigo"** no currículo
- **Competências em formato de tags escaneáveis por IA** — palavras-chave claramente destacadas para identificação automática de habilidades

### 📊 Avaliações
- **Opção de avaliação por grupo ou individual**
- **Opção de adicionar mais critérios de avaliação e avaliações**
- **Notas com cores diferentes** por faixa de desempenho
- **Filtro de notas** — do melhor para o pior desempenho, com legenda de menções coloridas

### 🤝 Projetos e Parcerias
- **Opção "Autorizar empresas parceiras a visualizar este projeto"** na tela de submissão de projeto

---

## 📐 Especificações Técnicas e Regras de Negócio

### Contexto do Sistema

- Somente o **Administrador** pode criar novos perfis de usuários para Professores e Alunos.
- O **Professor não pode cadastrar novos usuários** no sistema e, consequentemente, **não deve ter acesso à tela de cadastro de usuários**.
- **Todo campo obrigatório deve ter sinalização visual visível para o usuário**, indicando que o preenchimento é necessário.

---

### Tela de Login

A tela de login deve conter:

**Campos obrigatórios:**
- E-mail
- Senha

**Recursos de usabilidade:**
- Opção de **mostrar/ocultar senha** (ícone de olho)
- **Seleção de perfil** para usuários com múltiplos papéis:
  - Aluno
  - Professor
  - Administrador
  - Coordenador
- A **alternância de perfil só é exibida** para usuários que possuam mais de um perfil cadastrado

**Mensagens de erro:**
- Credenciais inválidas
- Campos obrigatórios vazios

---

### Regras de Cadastro de Usuários

- O cadastro de usuários é feito **somente pelo Administrador**.
- O Administrador pode criar perfis para: **Aluno**, **Professor**, **Administrador** e **Coordenador**.
- O Professor **não pode criar** novos usuários e não deve ter acesso à tela de cadastro de usuários.
- **Deve existir no mínimo 2 Administradores/Coordenadores** cadastrados e ativos no sistema a qualquer momento.

**Permissões por perfil:**

| Perfil | Permissões |
|---|---|
| **Administrador / Coordenador** | Acesso total ao sistema |
| **Professor** | Acesso restrito — sem permissão para cadastrar usuários |
| **Aluno** | Acesso somente às funções permitidas ao seu perfil |

---

### Campos Obrigatórios no Cadastro

Campos exigidos no momento em que o Administrador cadastra um usuário:

| Campo | Observação |
|---|---|
| **Cargo** | Aluno / Professor / Administrador / Coordenador |
| **CPF** | — |
| **Nome** | — |
| **Sobrenome** | — |
| **Nome Social** | Não obrigatório, mas pode ser preenchido e reutilizado em todo o sistema |
| **E-mail institucional / E-mail primário** | — |
| **Matrícula** | Obrigatória apenas para Aluno |
| **Status do Perfil** | Ativo / Inativo |

---

### Campos Não Obrigatórios no Cadastro

Os campos abaixo podem ser preenchidos/modificados posteriormente nas configurações do perfil:

- Identidade
- Data de nascimento
- Telefone / celular (2 opções)
- CEP
- Endereço completo (rua, número, complemento)
- Bairro
- Cidade e estado
- País
- Foto de perfil

---

### Regras de E-mail

| Regra | Detalhe |
|---|---|
| O **e-mail primário** é o e-mail institucional do usuário | — |
| O **e-mail primário não pode ser alterado** pelo próprio usuário | Somente o Administrador pode alterá-lo |
| O **e-mail secundário não é obrigatório** no cadastro | — |
| O **e-mail secundário pode ser alterado** pelo próprio usuário | Via tela de Configurações do perfil |

---

### Tela de Configurações do Perfil

A área de **Configurações do Perfil** deve permitir:

- Edição e visualização de todos os **campos não obrigatórios** do cadastro
- Visualização de todos os **campos obrigatórios** do cadastro
- Envio e modificação da **foto de perfil** (mesma usada no currículo)
- Edição do **e-mail secundário** pelo próprio usuário
- Edição de dados pessoais (**exceto e-mail primário**, que só o Administrador altera)
- Exibição dos dados principais do perfil:
  - Cargo
  - Nome e Nome Social
  - CPF e Identidade
  - E-mails (primário e secundário)
  - **Data de criação** e **último login** (gerados automaticamente, somente visualização)

---

### Tela de Criação de Currículo/Portfólio

Disponível para **Professores** e **Alunos**. O usuário pode editar todas as informações relevantes e visualizar em tempo real como o currículo/portfólio será exibido para um possível contratante.

> As **palavras-chave de competências** devem ser claramente destacadas (tags, chips ou blocos), de forma que uma IA consiga identificar imediatamente as habilidades do candidato.

---

#### 👤 Dados Pessoais e Contato

| Campo | Obrigatório | Compartilhado com toda a conta |
|---|:---:|:---:|
| Nome completo | ✅ | ✅ |
| Nome Social | — | ✅ |
| Telefone principal (celular) + campo WhatsApp (sim/não) | ✅ | ✅ |
| Gênero | ✅ | ✅ |
| Telefone secundário + campo WhatsApp (sim/não) | — | ✅ |
| E-mail principal | ✅ | Exclusivo desta tela |
| E-mail secundário | — | Exclusivo desta tela |
| Cidade / Estado onde mora | — | — |
| LinkedIn ou outro perfil profissional | — | Com opção de visibilidade no currículo |
| Site | — | Com opção de visibilidade no currículo |
| GitHub (link) | — | Com opção de visibilidade no currículo |
| Portfólio (links) | — | Com opção de visibilidade no currículo |
| Foto de perfil | — | Com opção de visibilidade no currículo |
| Permissão para empresas entrarem em contato | — | Autorização explícita: Sim / Não |
| País e Nacionalidade | ✅ | — |

---

#### 🕐 Horários e Disponibilidade de Contato

- Melhor horário para contato: até **4 faixas de horário por dia** (7 dias da semana), com seleção de dias e opção de repetir o bloco para combinações diferentes
- Disponibilidade de mudança (Sim/Não)
- Disponibilidade de viagem (Sim/Não)

---

#### 🌈 Diversidade

Campo de múltipla escolha com opção individual de visibilidade no currículo:

- LGBTQIA+
- Mulher
- PCD – Pessoas com Deficiência
- Negro
- Pardo
- Indígena

---

#### 💼 Tipo de Trabalho Buscado

**Regime (múltipla escolha):** Jovem Aprendiz · Estágio · Trainee · CLT · PJ · Freelancer · Projeto · Temporário

**Modalidade (múltipla escolha):** Presencial · Híbrido · 100% Remoto

**Horários disponíveis para trabalho (múltipla escolha):**
- Diurno
- Noturno
- Final de semana
- Segunda a sexta
- De ___ a ___ de ___ a ___ *(campo livre: dia da semana + hora)*

**Período de disponibilidade:** campo de escrita livre (ex.: *"a partir de julho de 2026"*)

**Pretensão salarial** (opcional, múltipla escolha — cada opção com visibilidade configurável):
- Bolsa para cobrir deslocamento e alimentação
- A considerar a partir de _____
- Faixa salarial desejada: _____ a _____
- Quero adquirir experiência prática na área

---

#### 📝 Sobre (Resumo do Currículo)

Campo de texto livre com **até 2.600 caracteres**, com:
- Contador de caracteres visível (usados / total)
- Placeholder: *"Resuma sua experiência descrevendo e destacando o que é importante no seu currículo e sobre você, com foco profissional e objetivos. Lembre-se, esse é um campo de destaque para recrutadores lerem e você tem 2.600 caracteres"* — desaparece ao clicar para escrever

---

#### 1. Nível de Ensino e Formação Acadêmica

| Campo | Observação |
|---|---|
| Nível de ensino | Ensino Médio, Técnico, Graduação, Bacharel, Tecnólogo, Pós-Graduação, Pós-Graduação lato/stricto sensu, Mestrado, Doutorado, MBA, Especialização, EJA, Educação Especial, Educação Profissional Técnica |
| Curso | Escrita livre (ex.: "Técnico em Informática", "Engenharia de Software") |
| Instituição de ensino | — |
| Período atual ou "formado em ___" | — |
| Situação | Cursando / Concluído / Trancado / Em Transferência |
| Previsão de conclusão | Mês/Ano |
| Aparecer no currículo | Sim / Não — por registro |

---

#### 2. Experiência Profissional e Estágios

| Campo | Observação |
|---|---|
| Empresa ou projeto | — |
| Cargo / função | — |
| Período de início e fim | — |
| Tipo | Estágio / Estágio não obrigatório / Voluntariado / Projeto de extensão / Freelancer / CLT |
| Descrição breve das atividades e resultados | — |
| Aparecer no currículo | Sim / Não — por registro |

---

#### 3. Licenças e Certificados

| Campo | Observação |
|---|---|
| Nome do certificado/licença | — |
| Instituição / plataforma | — |
| Data de obtenção | — |
| Válida até | Se aplicável |
| Aparecer no currículo | Sim / Não — por registro |

---

#### 4. Projetos

| Campo | Observação |
|---|---|
| Nome do projeto | — |
| Descrição do projeto | — |
| Responsabilidades / função | — |
| Tecnologias / ferramentas usadas | — |
| Resultado / impacto | — |
| Link para o projeto | GitHub, site, vídeo, apresentação, etc. |
| Aparecer no currículo | Sim / Não — por registro |

---

#### 5. Outros Cursos

| Campo | Observação |
|---|---|
| Nome do curso | — |
| Instituição / plataforma | ex.: Alura, Udemy, FIAP |
| Data de conclusão | — |
| Aparecer no currículo | Sim / Não — por registro |

---

#### 6. Habilidades

- **Hard Skills / Habilidades técnicas:** campos de escrita livre com seleção de nível (básico, intermediário, avançado, fluente); inclui campo específico "Linguagens / ferramentas" (ex.: Python, Excel, Figma, JavaScript)
- **Soft Skills / Habilidades comportamentais:** campos de escrita livre (ex.: liderança, comunicação, trabalho em equipe)
- Cada habilidade deve ser exibida em **formato de tag/chip**, facilmente escaneável por IA

---

#### 7. Idiomas

| Campo | Opções |
|---|---|
| Idioma | Escrita livre |
| Nível | Iniciante · Básico · Intermediário · Avançado · Fluente · Nativo |

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
- Visualiza feedback e nota final do professor (com codificação por cores e filtro de ordenação)
- Monta e compartilha seu currículo/portfólio profissional com preview em tempo real
- Uso semestral, concentrado nos períodos de entrega

</details>

<details>
<summary><strong>👩‍🏫 Professor</strong></summary>

- Faixa etária: 25 a 65 anos
- Acessa lista de projetos aprovados pelo Coordenador/Administrador
- Avalia por rubrica: Funcionalidade, Documentação e Criatividade (0 a 10)
- Fornece comentários de feedback detalhados
- Acesso ao repositório histórico para referência acadêmica
- **Não possui acesso à tela de cadastro de usuários**
- Uso semestral, no período de avaliação

</details>

<details>
<summary><strong>🏛️ Coordenador / Administrador</strong></summary>

- Faixa etária: 30 a 60 anos
- Valida submissões: aprova ou reprova projetos para avaliação
- Cadastra, edita e gerencia perfis de alunos e professores
- Ativa e desativa perfis sem excluí-los permanentemente
- Único com permissão para alterar o e-mail primário de um usuário
- Garante que sempre haja no mínimo 2 Administradores/Coordenadores ativos
- Uso contínuo, com maior intensidade nos períodos de entrega

</details>

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

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Encerramento%20.png" width="100%" alt="Slide: Encerramento — Stack Tecnológica" />

</div>

A plataforma centraliza submissão, validação e avaliação de Projetos Integradores, desenvolvida com conformidade total à LGPD e utilizando as seguintes tecnologias:

<div align="center">

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![YouTrack](https://img.shields.io/badge/YouTrack-000000?style=for-the-badge&logo=youtrack&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

| Camada | Tecnologia |
|---|---|
| **Backend** | PHP |
| **Frontend** | HTML + Bootstrap |
| **Banco de Dados** | MySQL |
| **Gerenciamento de Projeto** | [YouTrack](https://grupotp.youtrack.cloud/projects) |
| **Design / Prototipação** | [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) |
| **Versionamento** | Git / GitHub |
| **Segurança** | HTTPS, autenticação por perfil, conformidade LGPD |

---

## 🖥️ Protótipo e Equipe

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/EquipeProtótipo.png" width="100%" alt="Slide: Equipe e Protótipo" />

</div>

O protótipo de alta fidelidade foi desenvolvido no **FigmaMaker**, contemplando todos os fluxos principais de cada perfil de usuário.

<div align="center">

[![Ver Protótipo no Figma](https://img.shields.io/badge/Ver%20Prot%C3%B3tipo%20no%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10)

[![Ver Repositório no GitHub](https://img.shields.io/badge/Ver%20Reposit%C3%B3rio%20no%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 🔑 Credenciais Padrão de Demonstração

Credenciais válidas para o [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) e para o Aplicativo Observatório de Projetos Integradores — Senac Recife · 2026

> 🌐 Aplicativo programado: [https://grupotp.polyclub.com.br/](https://grupotp.polyclub.com.br/)

| Perfil | E-mail | Senha |
|---|---|---|
| Aluno | aluno@aluno | senac123 |
| Parceiro | parceiro@parceiro | senac123 |
| Aluno 2 | aluno2@aluno | senac123 |
| Professor | professor@professor | senac123 |
| Administrador | admin@admin | senac123 |

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
Quer saber mais sobre o projeto ou entrar em contato? 🤝

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

📧 **Email:** [thaynabdstec@gmail.com](mailto:thaynabdstec@gmail.com) ✉️

📱 **Telefone:** +55 (81) 97912-6121 📞

---

<div align="center">

### 👤 Thayná Batista da Silva
**Scrum Master • Product Designer • Requirements Analyst** 💼

Senac Recife-PE Faculty | Systems Analysis and Development 🎓

![TEC Card Thayná](https://github.com/thaynabds/AppMedSmart/blob/main/CapaCartão%20ThaynáBDSTEC.png)

</div>

</div>

---

## 📄 Licença

<div align="center">

**Copyright © 2026, Polyana Fontes; Thayná Batista da Silva — Observatório de Projetos Integradores. Todos os direitos reservados.**

Feito com 💜 por **Thayná Batista da Silva** e **Polyana Fontes**
durante o curso de **Análise e Desenvolvimento de Sistemas**
**Faculdade Senac Recife · 2026**

*Componente Curricular: Engenharia de Requisitos · Docente: Sonia Gomes de Oliveira*

</div>

&nbsp;

&nbsp;

&nbsp;

---
---
---

&nbsp;

&nbsp;

&nbsp;

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Senac_logo.svg.png" width="140" alt="Senac Logo" />

# 🎓 Integrative Projects Observatory

**Senac Recife College · Systems Analysis and Development Program**

*January to June 2026*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![College](https://img.shields.io/badge/College-Senac%20Recife-red?style=for-the-badge)
![Program](https://img.shields.io/badge/Program-ADS-blue?style=for-the-badge)
![Year](https://img.shields.io/badge/2026-Jan%20–%20Jun-purple?style=for-the-badge)

</div>

---

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Capa.png?raw=true" width="100%" alt="Project Cover — Integrative Projects Observatory" />

</div>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [The Problem](#-the-problem)
- [The Solution — Features](#-the-solution--features)
- [System Differentials](#-system-differentials)
- [Technical Specifications and Business Rules](#-technical-specifications-and-business-rules)
  - [System Context](#system-context)
  - [Login Screen](#login-screen)
  - [User Registration Rules](#user-registration-rules)
  - [Required Registration Fields](#required-registration-fields)
  - [Optional Registration Fields](#optional-registration-fields)
  - [Email Rules](#email-rules)
  - [Profile Settings Screen](#profile-settings-screen)
  - [Resume/Portfolio Creation Screen](#resumeportfolio-creation-screen)
- [Grading System](#-grading-system)
- [ESG Impact](#-esg-impact)
- [Market](#-market)
- [Benchmark](#-benchmark)
- [Business Model](#-business-model)
- [Target Audience](#-target-audience)
- [Legislation and Compliance](#-legislation-and-compliance)
- [Technologies](#-technologies)
- [Prototype and Team](#-prototype-and-team)
- [Default Demo Credentials](#-default-demo-credentials)
- [Team](#-team)
- [Contact](#-contact)

---

## 📖 About the Project

The **Integrative Projects Observatory** is a web platform developed for **Senac Recife College**, aimed at centralizing and organizing the submission, validation, and evaluation of Integrative Projects from the **Systems Analysis and Development** program.

The system addresses the need to replace manual and decentralized processes, providing a historical project repository accessible to students — for building professional portfolios — and to professors — for structured academic evaluation.

> _"Centralized platform for submission, deadline tracking, rubric-based feedback, and portfolio generation with achievement badges."_

The platform features specific profiles for **Students**, **Professors**, and **Coordinators/Administrators**, ensuring a structured workflow from project conception to final grade, with full submission traceability.

---

## 🚨 The Problem

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Problema.png" width="100%" alt="Slide: The Problem — 4 critical bottlenecks in the current process" />

</div>

The current process for delivering and evaluating Integrative Projects presents **4 critical bottlenecks**:

| # | Bottleneck | Impact |
|:---:|---|---|
| 1 | **Fragmentation** | Information scattered across multiple channels and tools |
| 2 | **Invisibility** | Projects with no institutional visibility or organized portfolio |
| 3 | **Rework** | Processes repeated manually every semester |
| 4 | **Lack of Governance** | Absence of control, traceability, and LGPD compliance |

> _"These bottlenecks cost time, visibility, and institutional credibility."_

---

## ✨ The Solution — Features

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades.png" width="100%" alt="Slide: System Features" />

</div>

We addressed the bottlenecks with a complete system organized in modules:

| Module | What it delivers |
|---|---|
| 🖥️ **Dashboard** | Overview of submissions, deadlines, and real-time status |
| 📁 **Projects** | File submission (PDF/ZIP), demo video, and description |
| 👤 **Profiles** | Management of Students, Professors, and Admins with distinct permissions |
| 🔐 **Authentication** | Single login per profile, primary and secondary email |
| 📊 **Reports** | Export of deliveries and evaluation history |
| 🌐 **Public Observatory** | Showcase of approved projects accessible institutionally |

---

## 🚀 System Differentials

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades%20Diferenciais.png" width="100%" alt="Slide: Differential Features of the Observatory" />

</div>

The Observatory was built with original features that make it unique within the academic context of Senac Recife College:

### 🔐 Authentication and Access
- **Multiple login authentication** — institutional email (primary) **or** student-chosen email (secondary), both functional for login
- **Profile selection screen** — users who hold multiple roles (Student, Professor, Administrator, Coordinator) choose which profile to use each session
- **Profile switching** — available only for users who have more than one registered profile

### 🛡️ Administration Rules
- **Mandatory minimum of 2 Admins/Coordinators** — the system blocks actions that would reduce active administrators/coordinators below 2, preventing a total lockout
- **Admin recovery** — special mechanism to restore access if all administrative accounts are lost
- **Admin-exclusive registration screen** — only the Administrator can create new users; Professors **do not have access** to the user registration screen
- **Activate / Deactivate profiles** — the Admin can suspend a profile without deleting it, preserving all linked history and data

### ⚙️ Settings and Personalization
- **Social Name** — can be registered and modified in settings, automatically reused throughout the system
- **Two registerable phone numbers** — users can register up to 2 contact numbers in settings, each with an option to flag as WhatsApp
- **Platform usage log** — account creation date and last login date displayed automatically on the settings screen

### 🧭 Navigation and Interface
- **Universal back icon** — present on all pages of all profiles, always returning to the Home page of the current profile
- **Floating menu on all pages** — accessible on any screen, displaying a header with the Senac icon and the name of the current Panel

### 📝 Forms and Validation
- **Visual indication of required fields** — every required field has a clear, immediate visual marker visible to the user, preventing submission errors

### 🎓 Resume and Portfolio
- **Dedicated Resume/Portfolio screen** for Professors and Students
- **Real-time preview** of the resume/portfolio, updated as the user fills in the fields
- **Per-field visibility option** — each piece of resume information can be configured to appear or not to recruiters
- **Option "I authorize SENAC partner companies to contact me"** on the resume
- **Skills in AI-scannable tag format** — keywords clearly highlighted for automatic skill identification

### 📊 Evaluations
- **Option for group or individual assessment**
- **Option to add more evaluation criteria and assessments**
- **Color-coded grades** by performance range
- **Grade filter** — from best to worst performance, with color-coded mention legend

### 🤝 Projects and Partnerships
- **Option "Authorize partner companies to view this project"** on the project submission screen

---

## 📐 Technical Specifications and Business Rules

### System Context

- Only the **Administrator** can create new user profiles for Professors and Students.
- **Professors cannot register new users** in the system and, consequently, **must not have access to the user registration screen**.
- **Every required field must have a visual indicator visible to the user**, indicating that it must be filled in.

---

### Login Screen

The login screen must contain:

**Required fields:**
- Email
- Password

**Usability features:**
- Option to **show/hide password** (eye icon)
- **Profile selection** for users with multiple roles:
  - Student
  - Professor
  - Administrator
  - Coordinator
- **Profile switching is only displayed** for users who have more than one registered profile

**Error messages:**
- Invalid credentials
- Empty required fields

---

### User Registration Rules

- User registration is done **only by the Administrator**.
- The Administrator can create profiles for: **Student**, **Professor**, **Administrator**, and **Coordinator**.
- Professors **cannot create** new users and must not have access to the user registration screen.
- **There must be at least 2 Administrators/Coordinators** registered and active in the system at all times.

**Permissions by profile:**

| Profile | Permissions |
|---|---|
| **Administrator / Coordinator** | Full system access |
| **Professor** | Restricted access — no permission to register users |
| **Student** | Access only to functions permitted for their profile |

---

### Required Registration Fields

Fields required when the Administrator registers a user:

| Field | Note |
|---|---|
| **Role** | Student / Professor / Administrator / Coordinator |
| **CPF (Tax ID)** | — |
| **First Name** | — |
| **Last Name** | — |
| **Social Name** | Not required, but can be filled in and reused throughout the system |
| **Institutional Email / Primary Email** | — |
| **Student ID** | Required for Students only |
| **Profile Status** | Active / Inactive |

---

### Optional Registration Fields

The fields below can be filled in or modified later in the profile settings:

- Identity document
- Date of birth
- Phone / mobile (2 options)
- ZIP code
- Full address (street, number, complement)
- Neighborhood
- City and state
- Country
- Profile photo

---

### Email Rules

| Rule | Detail |
|---|---|
| The **primary email** is the user's institutional email | — |
| The **primary email cannot be changed** by the user themselves | Only the Administrator can change it |
| The **secondary email is not required** at registration | — |
| The **secondary email can be changed** by the user themselves | Via the profile Settings screen |

---

### Profile Settings Screen

The **Profile Settings** area must allow:

- Editing and viewing all **optional** registration fields
- Viewing all **required** registration fields
- Uploading and modifying the **profile photo** (same one used in the resume)
- Editing the **secondary email** by the user themselves
- Editing personal data (**except primary email**, which only the Administrator can change)
- Display of the main profile data:
  - Role
  - Name and Social Name
  - CPF and Identity document
  - Emails (primary and secondary)
  - **Account creation date** and **last login** (auto-generated, view only)

---

### Resume/Portfolio Creation Screen

Available for **Professors** and **Students**. The user can edit all relevant information and see in real time how the resume/portfolio will appear to a potential employer.

> **Skill keywords** must be clearly highlighted (tags, chips, or blocks), so that an AI can immediately identify the candidate's abilities.

---

#### 👤 Personal Data and Contact

| Field | Required | Shared across the account |
|---|:---:|:---:|
| Full name | ✅ | ✅ |
| Social Name | — | ✅ |
| Primary phone (mobile) + WhatsApp field (yes/no) | ✅ | ✅ |
| Gender | ✅ | ✅ |
| Secondary phone + WhatsApp field (yes/no) | — | ✅ |
| Primary email | ✅ | Exclusive to this screen |
| Secondary email | — | Exclusive to this screen |
| City / State of residence | — | — |
| LinkedIn or other professional profile | — | With visibility option on resume |
| Website | — | With visibility option on resume |
| GitHub (link) | — | With visibility option on resume |
| Portfolio (links) | — | With visibility option on resume |
| Profile photo | — | With visibility option on resume |
| Permission for companies to contact | — | Explicit authorization: Yes / No |
| Country and Nationality | ✅ | — |

---

#### 🕐 Contact Hours and Availability

- Best time to be contacted: up to **4 time slots per day** (7 days a week), with day selection and option to repeat the block for different combinations
- Willingness to relocate (Yes/No)
- Willingness to travel (Yes/No)

---

#### 🌈 Diversity

Multiple choice field with individual visibility option per item on the resume:

- LGBTQIA+
- Woman
- PwD – Person with Disability
- Black
- Mixed-race (Pardo)
- Indigenous

---

#### 💼 Type of Work Sought

**Employment type (multiple choice):** Young Apprentice · Internship · Trainee · Full-time (CLT) · Contractor (PJ) · Freelancer · Project-based · Temporary

**Work mode (multiple choice):** On-site · Hybrid · 100% Remote

**Available working hours (multiple choice):**
- Daytime
- Nighttime
- Weekends
- Monday to Friday
- From ___ to ___ from ___ to ___ *(free field: weekday + time)*

**Availability period:** free text field (e.g.: *"starting July 2026"*)

**Salary expectation** (optional, multiple choice — each option with configurable visibility):
- Stipend to cover transportation and meals
- Open to offers starting from _____
- Desired salary range: _____ to _____
- I want to gain practical experience in the field

---

#### 📝 About (Resume Summary)

Free text field with **up to 2,600 characters**, including:
- Visible character counter (used / total)
- Placeholder: *"Summarize your experience by describing and highlighting what is important in your resume and about you, with a professional focus and goals. Remember, this is a highlight field for recruiters to read and you have 2,600 characters"* — disappears when clicked to write

---

#### 1. Education Level and Academic Background

| Field | Note |
|---|---|
| Education level | High School, Technical, Undergraduate, Bachelor's, Technologist, Graduate, Post-Graduate lato/stricto sensu, Master's, Doctorate, MBA, Specialization, Adult Education (EJA), Special Education, Technical Professional Education |
| Course | Free text (e.g.: "IT Technician", "Software Engineering") |
| Educational institution | — |
| Current period or "graduated in ___" | — |
| Status | Enrolled / Completed / On Hold / Transferring |
| Expected graduation | Month/Year |
| Show on resume | Yes / No — per entry |

---

#### 2. Professional Experience and Internships

| Field | Note |
|---|---|
| Company or project | — |
| Position / role | — |
| Start and end period | — |
| Type | Internship / Non-mandatory internship / Volunteering / Extension project / Freelancer / Full-time (CLT) |
| Brief description of activities and results | — |
| Show on resume | Yes / No — per entry |

---

#### 3. Licenses and Certificates

| Field | Note |
|---|---|
| Certificate/license name | — |
| Institution / platform | — |
| Date obtained | — |
| Valid until | If applicable |
| Show on resume | Yes / No — per entry |

---

#### 4. Projects

| Field | Note |
|---|---|
| Project name | — |
| Project description | — |
| Responsibilities / role | — |
| Technologies / tools used | — |
| Result / impact | — |
| Project link | GitHub, website, video, presentation, etc. |
| Show on resume | Yes / No — per entry |

---

#### 5. Other Courses

| Field | Note |
|---|---|
| Course name | — |
| Institution / platform | e.g.: Alura, Udemy, FIAP |
| Completion date | — |
| Show on resume | Yes / No — per entry |

---

#### 6. Skills

- **Hard Skills / Technical skills:** free text fields with level selection (basic, intermediate, advanced, fluent); includes a specific "Languages / tools" field (e.g.: Python, Excel, Figma, JavaScript)
- **Soft Skills / Behavioral skills:** free text fields (e.g.: leadership, communication, teamwork)
- Each skill must be displayed in **tag/chip format**, easily scannable by AI

---

#### 7. Languages

| Field | Options |
|---|---|
| Language | Free text |
| Level | Beginner · Basic · Intermediate · Advanced · Fluent · Native |

---

## 🎨 Grading System

Grades displayed to students use **color-coded visual encoding** and a **sort filter from best to worst**, making results more intuitive and accessible to read.

| Code | Description | Range | Color |
|:---:|---|:---:|:---:|
| **AE** | Attended with Excellence | 9.5 — 10 | 🟢 GREEN |
| **O** | Outstanding | 8.0 — 9.4 | 🔵 BLUE |
| **B** | Good | 6.5 — 7.9 | 🟡 YELLOW |
| **ANS** | Not Yet Sufficient | 4.0 — 6.4 | 🟠 ORANGE |
| **I** | Insufficient | 0.0 — 3.9 | 🔴 RED |

---

## 🌱 ESG Impact

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/ESG.png" width="100%" alt="Slide: ESG Impact of the Project" />

</div>

The Integrative Projects Observatory was conceived with responsibility across three dimensions:

| Dimension | Action |
|---|---|
| 🌿 **Environmental (E)** | Eliminates physical printouts and redundant emails; fully digitalizes the academic workflow |
| 🤝 **Social (S)** | Generates an official digital portfolio for students, expanding professional opportunities |
| 🏛️ **Governance (G)** | LGPD compliance, profile-based access control, and integrated audit logs |

---

## 📈 Market

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Mercado.png" width="100%" alt="Slide: Market Analysis" />

</div>

- 💰 By 2025, the market invested **US$ 340 million** in the educational technology sector
- 🌎 Brazil holds a prominent position in the **World Digital Education Ranking**
- 🏫 Senac has more than **500 units** in Brazil — making the Observatory a **highly replicable solution** at a national scale

---

## 🔍 Benchmark

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Benchmark.png" width="100%" alt="Slide: Benchmark — Why the Observatory?" />

</div>

### Why build the Observatory instead of using existing tools?

| Criterion | Google Classroom | Moodle | GitHub + Drive | ✅ **Observatory** |
|---|:---:|:---:|:---:|:---:|
| Focus on integrative projects | ❌ | ❌ | ❌ | ✅ |
| Public portfolio | ❌ | ❌ | Partial | ✅ |
| Multiple profiles with permissions | Partial | Partial | ❌ | ✅ |
| Native LGPD compliance | ❌ | ❌ | ❌ | ✅ |
| Integrated management (submission + validation + evaluation) | ❌ | Partial | ❌ | ✅ |

> _The Observatory surpasses generic tools in institutional focus, governance, and portfolio._

---

## 💼 Business Model

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Modelo%20de%20Neg%C3%B3cio.png" width="100%" alt="Slide: Business Model" />

</div>

**Value delivered to Senac:**
- Significant reduction in semester rework during evaluation processes
- Expansion potential as a **replicable product** for other units (SaaS model)

**Value delivered to Students:**
- Official and traceable portfolio linked to the institution
- Visibility to **partner companies** through the public Observatory

---

## 🎯 Target Audience

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/P%C3%BAblico%20Alvo.png" width="100%" alt="Slide: Target Audience" />

</div>

> _"Transforming academic management into institutional intelligence."_

The Integrative Projects Observatory was designed for three complementary profiles within Senac Recife College:

<details>
<summary><strong>🎓 Student</strong></summary>

- Age range: 18 to 45 years
- Uploads files, adds a video link and project description
- Tracks submission approval status in real time
- Views professor feedback and final grade (with color coding and sort filter)
- Builds and shares a professional resume/portfolio with real-time preview
- Semester-based use, concentrated during submission periods

</details>

<details>
<summary><strong>👩‍🏫 Professor</strong></summary>

- Age range: 25 to 65 years
- Accesses the list of projects approved by the Coordinator/Administrator
- Evaluates by rubric: Functionality, Documentation, and Creativity (0 to 10)
- Provides detailed feedback comments
- Access to historical repository for academic reference
- **Does not have access to the user registration screen**
- Semester-based use, during the evaluation period

</details>

<details>
<summary><strong>🏛️ Coordinator / Administrator</strong></summary>

- Age range: 30 to 60 years
- Validates submissions: approves or rejects projects for evaluation
- Registers, edits, and manages student and professor profiles
- Activates and deactivates profiles without permanently deleting them
- Only one with permission to change a user's primary email
- Ensures there are always at least 2 active Administrators/Coordinators
- Continuous use, with greater intensity during submission periods

</details>

---

## ⚖️ Legislation and Compliance

The system was developed in full compliance with current Brazilian legislation:

- 🔒 **LGPD — Law No. 13.709/2018** · Protection of personal data for students and professors, with audit logs, access control, and consent for sensitive data
- 🌐 **Marco Civil da Internet — Law No. 12.965/2014** · Storage of access records and user privacy
- 🎓 **LDB — Law No. 9.394/1996** · Educational guidelines and confidentiality of academic data
- ✍️ **Copyright Law — Law No. 9.610/1998** · Protection of authorship of projects submitted by students
- 🏫 **Internal Policies of Senac Recife College** · Academic regulations and institutional IT policies

---

## 🛠️ Technologies

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Encerramento%20.png" width="100%" alt="Slide: Closing — Tech Stack" />

</div>

The platform centralizes submission, validation, and evaluation of Integrative Projects, developed with full LGPD compliance using the following technologies:

<div align="center">

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![YouTrack](https://img.shields.io/badge/YouTrack-000000?style=for-the-badge&logo=youtrack&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

| Layer | Technology |
|---|---|
| **Backend** | PHP |
| **Frontend** | HTML + Bootstrap |
| **Database** | MySQL |
| **Project Management** | [YouTrack](https://grupotp.youtrack.cloud/projects) |
| **Design / Prototyping** | [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) |
| **Version Control** | Git / GitHub |
| **Security** | HTTPS, profile-based authentication, LGPD compliance |

---

## 🖥️ Prototype and Team

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/EquipeProtótipo.png" width="100%" alt="Slide: Team and Prototype" />

</div>

The high-fidelity prototype was developed in **FigmaMaker**, covering all main flows for each user profile.

<div align="center">

[![View Prototype on Figma](https://img.shields.io/badge/View%20Prototype%20on%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10)

[![View Repository on GitHub](https://img.shields.io/badge/View%20Repository%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 🔑 Default Demo Credentials

Credentials valid for [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) and for the Integrative Projects Observatory Application — Senac Recife · 2026

> 🌐 Scheduled application: [https://grupotp.polyclub.com.br/](https://grupotp.polyclub.com.br/)

| Profile | Email | Password |
|---|---|---|
| Student | aluno@aluno | senac123 |
| Partner | parceiro@parceiro | senac123 |
| Student 2 | aluno2@aluno | senac123 |
| Professor | professor@professor | senac123 |
| Administrator | admin@admin | senac123 |

---

## 👩‍💻 Team

<div align="center">

### Polyana Fontes
**Full Stack Developer · Database Modeling · Technical Documentation**

Student of Systems Analysis and Development
Senac Recife-PE College

---

### Thayná Batista da Silva
**Project Manager / Requirements Analyst · Scrum Master**
**Product Designer · High-Fidelity Prototyping (Figma)**

Student of Systems Analysis and Development
Senac Recife-PE College · Class of 2025 · Expected graduation: 2027

</div>

---

## 📬 Contact
Want to learn more about the project or get in touch? 🤝

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

📧 **Email:** [thaynabdstec@gmail.com](mailto:thaynabdstec@gmail.com) ✉️

📱 **Phone:** +55 (81) 97912-6121 📞

---

<div align="center">

### 👤 Thayná Batista da Silva
**Scrum Master • Product Designer • Requirements Analyst** 💼

Senac Recife-PE Faculty | Systems Analysis and Development 🎓

![TEC Card Thayná](https://github.com/thaynabds/AppMedSmart/blob/main/CapaCartão%20ThaynáBDSTEC.png)

</div>

</div>

---

## 📄 License

<div align="center">

**Copyright © 2026, Polyana Fontes; Thayná Batista da Silva — Integrative Projects Observatory. All rights reserved.**

Made with 💜 by **Thayná Batista da Silva** and **Polyana Fontes**
during the **Systems Analysis and Development** program
**Senac Recife College · 2026**

*Curricular Component: Requirements Engineering · Instructor: Sonia Gomes de Oliveira*

</div>
