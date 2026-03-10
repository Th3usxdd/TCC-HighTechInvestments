<!--
README.md (Markdown) para seu TCC
Cole este conteúdo no arquivo README.md do seu repositório.
-->
<!-- O bloco acima é só um aviso para você. O conteúdo real do README está abaixo em Markdown. -->
# TCC — Plataforma de Orçamentos, Financiamentos, Negócios, Ações e Freelancers

Plataforma web para **simular orçamentos**, organizar **financiamentos**, acompanhar **negócios** e **ações**, além de conectar **clientes e freelancers** para serviços e projetos.  
Este repositório contém o código e a documentação do meu **TCC** (3DS).

---

## Visão Geral

A proposta é criar um site que centralize necessidades comuns de quem quer **planejar dinheiro**, **tomar decisões financeiras** e **contratar/atuar como freelancer** em um único lugar, com uma interface simples e organizada.

### Módulos planejados
- **Orçamentos**
  - Cadastro de receitas e despesas
  - Metas (ex.: economizar para um objetivo)
  - Relatórios mensais (resumo e gráficos)
- **Financiamentos**
  - Simulação (valor, entrada, juros, parcelas)
  - Comparação de cenários
  - Cronograma/estimativa de parcelas
- **Negócios**
  - Ideias e validação básica (checklists)
  - Registro de custos/receitas do negócio
  - Painel simples de desempenho
- **Ações**
  - Carteira (registro manual no início)
  - Rentabilidade estimada e histórico
  - Alertas/observações por ativo
- **Freelancers**
  - Perfil de freelancer (habilidades, portfólio, contato)
  - Solicitação de orçamento (briefing do cliente)
  - Propostas e acompanhamento de status (ex.: enviado, aceito, concluído)

------------------------------------------------------------------------------------------------------------

## Objetivo do Projeto

- Criar uma aplicação web **responsiva e acessível**
- Organizar funcionalidades financeiras de forma **didática**
- Aplicar conceitos de desenvolvimento (front-end/back-end, banco de dados, autenticação, etc.)
- Entregar um produto com **fluxos reais**, mesmo que em versão MVP

--------------------------------------------------------------------------------------------------------------

## Público-alvo

- Pessoas que querem **organizar finanças pessoais**
- Pequenos empreendedores iniciando um **negócio**
- Estudantes e interessados em **investimentos**
- Clientes e profissionais que atuam como **freelancer**

-----------------------------------------------------------------------------------------------------------------

## Principais Funcionalidades (MVP)

- [ ] Cadastro e login (usuários)
- [ ] Painel inicial (resumo financeiro + atalhos)
- [ ] Orçamentos: receitas/despesas + saldo do mês
- [ ] Financiamentos: simulação com ações
- [ ] Freelancers: listar perfis + solicitar orçamento
- [ ] Área do usuário: perfil + preferências

> Observação: A parte de ações/investimentos pode começar como **registro manual** para evitar dependência de APIs externas.

-------------------------------------------------------------------------------------------------------------------------

## Requisitos (Sugeridos)

### Requisitos Funcionais (RF)
- **RF01:** Permitir que o usuário crie conta e faça login
- **RF02:** Permitir cadastrar receitas e despesas
- **RF03:** Exibir resumo mensal (saldo, totais)
- **RF04:** Simular financiamento com taxa e prazo
- **RF05:** Permitir criação e envio de solicitações de orçamento para freelancers
- **RF06:** Permitir que freelancers cadastrem perfil e recebam solicitações

### Requisitos Não Funcionais (RNF)
- **RNF01:** Interface responsiva (mobile e desktop)
- **RNF02:** Boas práticas de segurança (senha criptografada, validações)
- **RNF03:** Performance aceitável (páginas leves, carregamento rápido)
- **RNF04:** Acessibilidade básica (contraste, navegação por teclado, semântica)

--------------------------------------------------------------------------------------------------------------

## Tecnologias (a definir)

> Atualize de acordo com o que você realmente vai usar.

- Front-end: `HTML`, `CSS`, `JavaScript` (ou `React`)
- Back-end: `Node.js/Express` (ou `PHP`, `Java`, etc.)
- Banco de dados: `MySQL` / `PostgreSQL` / `SQLite`
- Versionamento: `Git + GitHub`

-----------------------------------------------------------------------------------------------------------------

## Como Rodar (modelo)

> Preencha quando o projeto já estiver com setup.

1. Clone o repositório:
   ```bash
   git clone https://github.com/Th3usxdd/TCC-do-matheus-3ds.git
-------------------------------------------------------------------------------------------------------------------
cd TCC-do-matheus-3ds

/docs
/src
  /pages
  /components
  /styles
  /assets
/server
README.md
----------------------------------------------------------------------------------------------------------------------
Etapa 1: Pesquisa + definição do escopo (MVP)
Etapa 2: Protótipo (Figma) + fluxos de navegação
Etapa 3: Implementação do front-end
Etapa 4: Back-end + banco de dados
Etapa 5: Testes + ajustes + documentação
Etapa 6: Apresentação final
