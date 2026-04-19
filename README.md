# 🚀 Alianderson Dev — AI-Powered LMS Platform

Plataforma **LMS moderna com Inteligência Artificial**, desenvolvida como **projeto de portfólio** por **Alianderson Dev**, focada em arquitetura real de SaaS, e-learning e aplicações escaláveis.

> Projeto criado para demonstrar domínio em **Full-Stack Development, React, Next.js, IA aplicada e CMS Headless**.

---

## 🧠 Visão Geral

Este projeto simula uma **plataforma de cursos online (LMS)** com recursos encontrados em produtos reais do mercado:

- 📚 Cursos organizados por módulos e aulas
- 🎥 Streaming profissional de vídeo
- 🔐 Autenticação e controle de acesso por planos
- 🤖 Tutor com IA treinado no conteúdo da plataforma
- 📊 Progresso do aluno
- 🛠️ Painel administrativo customizado

---

## 🎯 Objetivo do Projeto

Demonstrar, em um único projeto:

- Arquitetura real de **LMS / SaaS**
- Integração de **IA em produção**
- Controle de acesso por assinatura
- CMS customizado com Sanity
- Boas práticas de código, organização e escalabilidade

---

## 🛠️ Stack Tecnológica

- **Next.js 16** (App Router)
- **React 19**
- **TypeScript**
- **Sanity** (Headless CMS)
- **Clerk** (Auth + Billing)
- **Mux** (Streaming de vídeo)
- **OpenAI GPT-4o** (Tutor IA)
- **Tailwind CSS + Shadcn UI**

---

## 📚 Conceitos do LMS

| Conceito | Descrição |
|--------|----------|
| Curso | Conjunto de módulos sobre um tema |
| Módulo | Capítulo do curso |
| Aula | Vídeo + conteúdo textual |
| Plano | Nível de acesso (Free / Pro / Ultra) |
| Tutor IA | Assistente que responde com base no conteúdo |

---

## 🤖 Tutor com Inteligência Artificial

O tutor utiliza **GPT-4o** com busca semântica (RAG), permitindo:

- Responder dúvidas com base no conteúdo real dos cursos
- Citar aulas e módulos relevantes
- Ajudar o aluno durante o aprendizado

Disponível apenas para planos avançados.

---

## 🛠️ Administração de Conteúdo

O projeto demonstra **duas abordagens de CMS**:

| Rota | Descrição |
|----|----------|
| `/admin` | CMS customizado usando Sanity App SDK |
| `/studio` | Sanity Studio tradicional |

Isso mostra domínio tanto de **backoffice sob medida** quanto de soluções prontas de mercado.

---

## 📹 Vídeo & Streaming

- Upload e gerenciamento via **Mux**
- Streaming adaptativo
- Tokens de reprodução assinados
- Preparado para escala profissional

---

## 🔐 Autenticação e Controle de Acesso

- Autenticação com **Clerk**
- Controle de planos e permissões
- Gating de conteúdo por assinatura
- Estrutura pronta para monetização

---

## 📊 Funcionalidades do Aluno

- Marcar aulas como concluídas
- Acompanhar progresso do curso
- Interface moderna e responsiva
- Base pronta para certificados

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos

- Node.js 18+
- pnpm
- Contas: Sanity, Clerk, Mux, OpenAI

### Instalação

```bash
git clone https://github.com/aliandersondev/lms.git
cd lms
pnpm install
pnpm dev
