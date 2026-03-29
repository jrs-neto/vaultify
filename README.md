# Vaultify - Storage & File Sharing Platform

## Plataforma moderna de armazenamento e compartilhamento de arquivos | Portfólio Profissional

<br />

<div align="center">
  <img src="https://img.shields.io/badge/-Next_JS-black?style=flat-square&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
  <img src="https://img.shields.io/badge/-TypeScript-black?style=flat-square&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=flat-square&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  <img src="https://img.shields.io/badge/-Appwrite-black?style=flat-square&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  <img src="https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen" alt="Status: Concluído">
</div>

---

<br />

## Overview

**Vaultify** é uma aplicação **fullstack** desenvolvida com **Next.js 15**, **TypeScript** e **Appwrite**, com foco em reproduzir cenários reais de plataformas de armazenamento e gerenciamento de arquivos.

O projeto foi evoluído com melhorias próprias em arquitetura, interface e funcionalidades, com o objetivo de demonstrar habilidades práticas em desenvolvimento moderno.

**Objetivo:** Demonstrar **domínio técnico em desenvolvimento fullstack moderno**, com autenticação, upload de arquivos, painel de controle e compartilhamento entre usuários.

<br />

## Diferenciais

- Arquitetura organizada com Server Actions
- Integração com Appwrite (Auth, Database e Storage)
- Interface responsiva e escalável
- Estrutura preparada para evolução contínua como produto SaaS

> [!NOTE]
>
> Este projeto foi inicialmente baseado em um tutorial, mas foi **refatorado e evoluído com melhorias próprias**, incluindo organização arquitetural, tipagem forte e preparação para cenários reais de produção.

<br />

O projeto foi estruturado com os seguintes objetivos:

- Demonstrar **competência técnica em Next.js 15 e TypeScript**
- Aplicar **integração com BaaS (Backend as a Service) via Appwrite**
- Evidenciar **arquitetura limpa e organização de código em um projeto fullstack**
- Simular **regras de negócio de uma plataforma de arquivos real**
- Servir como **case técnico para recrutadores**

<br />

## Competências Técnicas Demonstradas

- Desenvolvimento **Fullstack** com Next.js 15 (App Router)
- Autenticação com **OTP via e-mail** usando Appwrite
- Upload e gestão de arquivos com **Appwrite Storage**
- Consultas dinâmicas ao **Appwrite Database**
- Tipagem forte com **TypeScript**
- Componentes reutilizáveis com **ShadCN UI**
- Estilização responsiva com **TailwindCSS**
- Server Actions e Server Components do Next.js
- Separação de responsabilidades e arquitetura em camadas
- Estrutura escalável e pronta para produção

<br />

## Impacto Técnico e Métricas

| Indicador                      | Valor                             |
| ------------------------------ | --------------------------------- |
| Stack principal                | Next.js 15 + Appwrite             |
| Tipos de arquivo suportados    | Documentos, Imagens, Vídeo, Áudio |
| Funcionalidades implementadas  | 8+                                |
| Autenticação                   | OTP por e-mail (Appwrite)         |
| Armazenamento                  | Appwrite Storage (cloud)          |
| Banco de dados                 | Appwrite Database                 |
| Design System                  | ShadCN UI + TailwindCSS           |
| Uso educacional e profissional | ✅                                |

<br />

## Funcionalidades do Projeto

| Funcionalidade                                 | Status |
| ---------------------------------------------- | ------ |
| Autenticação com OTP por e-mail                | ✅     |
| Upload de arquivos (doc, imagem, vídeo, áudio) | ✅     |
| Visualização e gerenciamento de arquivos       | ✅     |
| Download de arquivos                           | ✅     |
| Compartilhamento de arquivos entre usuários    | ✅     |
| Renomear e excluir arquivos                    | ✅     |
| Dashboard com resumo de armazenamento          | ✅     |
| Busca global de arquivos                       | ✅     |
| Ordenação por data, nome e tamanho             | ✅     |
| Design responsivo (mobile-first)               | ✅     |

<br />

## Arquitetura do Projeto

Estrutura organizada para facilitar **manutenção, escalabilidade e leitura técnica**:

```text
📦 Vaultify
 ┣ 📂 app
 ┃ ┣ 📂 (auth)          # Páginas de autenticação
 ┃ ┗ 📂 (root)          # Páginas protegidas (dashboard, arquivos)
 ┣ 📂 components        # Componentes reutilizáveis (UI + negócio)
 ┃ ┗ 📂 ui              # Componentes ShadCN
 ┣ 📂 constants         # Constantes e configurações globais
 ┣ 📂 lib
 ┃ ┣ 📂 actions         # Server Actions (file, user)
 ┃ ┗ 📂 appwrite        # Clientes e configuração do Appwrite
 ┣ 📂 public            # Assets estáticos
 ┣ 📂 styles            # CSS global
 ┣ 📂 types             # Tipagens TypeScript
 ┣ 📜 .env.local        # Variáveis de ambiente (não versionado)
 ┗ 📜 next.config.ts
```

<br />

## Tecnologias Utilizadas

- **Frontend & Framework**
  - Next.js 15 (App Router)
  - React 19
  - TypeScript

- **Backend & BaaS**
  - Appwrite (Auth, Database, Storage)
  - Node Appwrite SDK

- **Estilização & UI**
  - TailwindCSS
  - ShadCN UI
  - Recharts (gráficos)

- **Ferramentas**
  - Git & GitHub
  - ESLint
  - npm

<br />

## Como Executar

**1️⃣ Clone o repositório**

```bash
git clone https://github.com/jrs-neto/vaultify
```

**2️⃣ Acesse a pasta do projeto**

```bash
cd vaultify
```

**3️⃣ Instale as dependências**

```bash
npm install
```

**4️⃣ Configure as variáveis de ambiente**

Crie o arquivo `.env.local` na raiz do projeto com o seguinte conteúdo:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```

> Obtenha as credenciais criando um projeto em [appwrite.io](https://appwrite.io/).

**5️⃣ Execute a aplicação**

```bash
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000) no seu navegador.

<br />

## Roadmap

### 🔜 Próximas melhorias

- [ ] Dark mode
- [ ] Login com Google (OAuth)
- [ ] Login com e-mail e senha (além do OTP atual)
- [ ] Foto de perfil personalizada
- [ ] Criação de pastas nas seções de arquivos
- [ ] Pastas protegidas com senha
- [ ] Sistema de favoritos

### 🚀 Melhorias avançadas

- [ ] Self-hosting (hospedagem em servidor próprio)

<br />

## Contribuições

Sugestões, melhorias e pull requests são bem-vindos.

Você pode contribuir com:

- Melhorias arquiteturais
- Refatorações
- Testes automatizados
- Documentação

<br />

## Licença

Este projeto está sob licença **MIT** — livre para uso educacional e profissional.

<br />

## Autor

**José — Full Stack Developer | JavaScript | Next.js | AWS (em evolução)**

🔗 **GitHub:** https://github.com/jrs-neto

🔗 **LinkedIn:** https://www.linkedin.com/in/jrodrigues-neto/

🔗 **Portfólio:** https://jrs-neto.github.io/Portfolio/

Projeto desenvolvido para **aprendizado contínuo**, **demonstração técnica** e **portfólio profissional**.
