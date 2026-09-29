<div align="center">

# Lucas Gonçalves Cavanha

### Full Stack Developer • Produtos de ponta a ponta • IA aplicada

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&repeat=true&width=760&height=45&lines=C%23+%7C+.NET+%7C+PHP+%7C+Angular+%7C+React;Python+%7C+Flutter+%7C+IA+aplicada;APIs+%7C+Integra%C3%A7%C3%B5es+%7C+Docker;SQL+Server+%7C+PostgreSQL+%7C+MongoDB;Construindo+produtos+de+ponta+a+ponta)](https://git.io/typing-svg)

Desenvolvo aplicações web, apps mobile, APIs, integrações e produtos de software completos, conectando **frontend, backend, dados, IA e infraestrutura**.

</div>

---

## Sobre mim

Sou desenvolvedor Full Stack com experiência na construção e evolução de sistemas de negócio, aplicações web, apps mobile, APIs e integrações entre plataformas.

Gosto de trabalhar no produto como um todo: entender o problema, estruturar a solução, modelar dados, desenvolver backend e frontend, integrar serviços externos, preparar deploy e acompanhar a evolução da aplicação. Boa parte do que construo é multi-tenant desde o desenho: um sistema, vários clientes.

Minha experiência passa por **C#/.NET, Python, PHP, Angular, React, Flutter, SQL Server, PostgreSQL, MongoDB e Docker**, além de pipelines de IA aplicados a produto real (não só protótipo) e GitHub/Azure DevOps no fluxo de desenvolvimento.

---

## Stack

### Linguagens & Backend

<p>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,php,laravel,py,ts,js" alt="C#, .NET, PHP, Laravel, Python, TypeScript e JavaScript" />
</p>

`C#` `.NET` `ASP.NET Core` `PHP` `Laravel` `Python` `FastAPI` `TypeScript` `JavaScript` `REST APIs` `Webhooks`

### Frontend & Mobile

<p>
  <img src="https://skillicons.dev/icons?i=angular,react,nextjs,vue,flutter,dart,html,css,tailwind,sass" alt="Angular, React, Next.js, Vue, Flutter, Dart, HTML, CSS, Tailwind e Sass" />
</p>

`Angular` `React` `Next.js` `Vue` `Flutter` `HTML` `CSS` `Tailwind CSS` `Sass`

### Bancos & Dados

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase,firebase" alt="PostgreSQL, MongoDB, Supabase e Firebase" />
</p>

`SQL Server` `PostgreSQL` `MongoDB` `Supabase` `Firebase`

### DevOps & Ferramentas

<p>
  <img src="https://skillicons.dev/icons?i=docker,azure,git,github,vercel,vscode" alt="Docker, Azure, Git, GitHub, Vercel e VS Code" />
</p>

`Docker` `Azure DevOps` `Azure Repos` `Hangfire` `Git` `GitHub` `Vercel` `VS Code`

---

## O que eu construo

```text
Backend & APIs         → regras de negócio, autenticação, integrações e webhooks
Frontend & Mobile      → interfaces web, apps Flutter, dashboards e sistemas internos
IA & Automação         → pipelines de geração de conteúdo com LLMs, jobs agendados, scraping
Dados                  → modelagem e acesso a SQL Server, PostgreSQL e MongoDB
Integrações            → comunicação entre sistemas, marketplaces e plataformas externas
Infraestrutura         → Docker, deploy, ambientes e pipelines de desenvolvimento
Produtos               → solução completa, da ideia até a aplicação funcionando
```

---

## Projetos em destaque

### FrameUp
**Otimizador de desempenho para Windows voltado a jogos competitivos (CS2, Valorant, Apex, R6).**

Produto autoral, do app à distribuição: aplicativo desktop (WPF/.NET) com medição própria de
frametime via ETW (sem injetar em processo de jogo), motor de tweaks reversível, com backup do
valor original e ponto de restauração antes de qualquer alteração, sistema de licenciamento próprio
(HWID + criptografia compartilhada entre cliente e servidor) e servidor de ativação em ASP.NET
Core. Inclui site de vendas e empacotamento com atualização delta.

**Stack:** C# • .NET (WPF) • ASP.NET Core • SQLite • ETW • Windows

---

### ConnectCar
**CRM multi-tenant para concessionárias e revendas de veículos.**

Plataforma dividida em cinco serviços que desenvolvo e mantenho: frontend em Angular com
dashboards de vendas e estoque; API principal em .NET (Clean Architecture, EF Core, SQL Server,
Hangfire, SignalR) cobrindo o funil de vendas, emissão de NFe/NFSe e gateways de pagamento; módulo
de GED em Laravel para gestão documental; integrador de anúncios que sincroniza estoque com
portais como iCarros, UsadosBr e Shopcar; e um serviço dedicado de integração com WhatsApp via
Evolution API.

**Stack:** C# • .NET • ASP.NET Core • Angular • PHP (Laravel) • SQL Server • SignalR • Hangfire • JWT

---

### Kenanto
**Plataforma de marketplace multi-plataforma, do catálogo ao checkout.**

App mobile em Flutter, API assíncrona em FastAPI (Python) com MongoDB e autenticação por OTP,
painel administrativo em Vue 3 + Vite e site institucional em Next.js. São quatro frentes que
integro em torno da mesma base de dados e das mesmas regras de negócio (catálogo, precificação,
carrinho e cupons).

**Stack:** Flutter • Python • FastAPI • MongoDB • Vue • Next.js • React

---

### Motor de conteúdo com IA (Feax + Be2B)
**Plataforma multi-tenant de automação de conteúdo com IA e SEO/GEO.**

Worker .NET que coleta notícias de nicho, gera artigos por um pipeline de LLM em etapas (curadoria
→ análise → redação → edição), aplica gates de qualidade **em código** (similaridade com a fonte,
tamanho mínimo, frases banidas por marca) antes de liberar qualquer publicação automática, e serve
os blogs via Angular SSR com JSON-LD, cumprindo o contrato de GEO: conteúdo completo sem depender
de JavaScript. Fila editorial com aprovação humana e custo de cada chamada de LLM logado no banco.

**Stack:** .NET • Hangfire • PostgreSQL • Angular (SSR) • Microsoft.Extensions.AI • Schema.NET

---

### Landing pages de conversão
**HAAR by RUPP** (salão de beleza) e **Corte & Estilo**, páginas com foco em performance e
conversão: HTML/SCSS/JS vanilla, build com Parcel, otimização de imagem (WebP/WOFF2 gerados no
build) e zero dependência de runtime em produção, publicadas em Cloudflare Pages/Vercel.

**Stack:** HTML • SCSS • JavaScript • Parcel

---

### EliteLeads
**Dashboard interno de onboarding de clientes, do pagamento ao briefing.**

Painel em Next.js que recebe o webhook de pagamento do Asaas, cadastra o cliente, dispara o email
de boas vindas via Resend com o link do formulário e acompanha briefings e prompts gerados. O fluxo
inteiro é automático: o cliente paga e o processo segue sem intervenção manual.

**Stack:** Next.js • JavaScript • Asaas • Resend • Vercel

---

### Ferramentas & automação
**shopcar-importer**: scraper em Python que importa o estoque público de uma loja no portal
ShopCar e gera uma planilha já no formato do sistema de gestão do cliente, com matching fuzzy de
marca/modelo. **pytomd**: conversor local de PDF para Markdown (Streamlit + PyMuPDF), 100%
offline, sem depender de serviço externo.

**Stack:** Python • BeautifulSoup • Pandas • Streamlit • PyMuPDF

---

## Repositórios open source

Dez projetos que escrevi do zero para deixar o código aberto. Cada um existe para mostrar uma
decisão de engenharia inteira, não só que a tecnologia foi usada: todos têm README explicando o
porquê das escolhas e CI no GitHub Actions que roda de verdade, e a maioria traz suíte de testes e
Docker.

### Backend e .NET

| Repositório | O que demonstra | Stack |
|---|---|---|
| **[dotnet-saas-multitenant](https://github.com/lucas-goncalves-cav/dotnet-saas-multitenant)** | SaaS multi-tenant onde o isolamento é garantido pela camada de persistência: nenhuma query no projeto menciona `TenantId`. Global query filters mais uma guarda no `SaveChanges`, porque filtro não protege escrita. 50 testes, e o CI confere o SQL gerado contra SQL Server real. | .NET 9 • EF Core • SQL Server • JWT |
| **[dotnet-clean-architecture-api](https://github.com/lucas-goncalves-cav/dotnet-clean-architecture-api)** | Clean Architecture aplicada de verdade: Result Pattern no lugar de exceção para fluxo esperado, validação com FluentValidation e dependências apontando para dentro. | .NET 9 • EF Core • Docker |
| **[webhook-delivery-service](https://github.com/lucas-goncalves-cav/webhook-delivery-service)** | A infraestrutura por trás de webhooks estilo Stripe: assinatura HMAC, retry com backoff exponencial e jitter, dead letter queue e histórico de entrega. | .NET 9 • SQL Server • Docker |
| **[asaas-integration-demo](https://github.com/lucas-goncalves-cav/asaas-integration-demo)** | Integração de pagamento construída para o gateway ser trocável: adapter por provedor, modelo de status interno, webhook idempotente e máquina de estados que aguenta evento fora de ordem. | .NET 9 • HttpClient resiliente |
| **[design-patterns-dotnet](https://github.com/lucas-goncalves-cav/design-patterns-dotnet)** | Padrões GoF em cenários reais: cada um mostra primeiro o código que dói, depois o refactor, com teste provando que o comportamento é o mesmo. | C# • xUnit |

### Frontend

| Repositório | O que demonstra | Stack |
|---|---|---|
| **[angular-admin-starter](https://github.com/lucas-goncalves-cav/angular-admin-starter)** | Base de painel administrativo pronta para reuso: standalone components, signals, autenticação, guards de rota, dark mode e componentes reaproveitáveis. | Angular 19 • TypeScript • Tailwind |
| **[react-dashboard](https://github.com/lucas-goncalves-cav/react-dashboard)** | Separação entre estado de servidor e estado de cliente, que é onde a maioria dos dashboards se perde: React Query para um, Zustand para o outro. Gráficos em SVG escritos à mão, sem biblioteca. | React 19 • TypeScript • Vitest |

### Dados e infraestrutura

| Repositório | O que demonstra | Stack |
|---|---|---|
| **[sql-server-recipes](https://github.com/lucas-goncalves-cav/sql-server-recipes)** | Referência prática de SQL Server com comparações de consulta ruim e boa, índices, CTEs e window functions. Os ganhos de performance no README foram medidos, não estimados. | T-SQL • SQL Server 2022 |
| **[dev-infrastructure-docker](https://github.com/lucas-goncalves-cav/dev-infrastructure-docker)** | Ambiente de desenvolvimento inteiro em um comando: SQL Server, PostgreSQL, MongoDB, Redis, RabbitMQ, MinIO, Mailpit e Seq, com profiles, health checks e Makefile. | Docker Compose • Shell |
| **[pdf-to-markdown](https://github.com/lucas-goncalves-cav/pdf-to-markdown)** | Conversor de PDF para Markdown que infere hierarquia de títulos pelo tamanho da fonte, recupera listas e tabelas e valida upload por magic bytes. | Python 3.13 • FastAPI • pdfplumber |

---

## Engenharia que valorizo

- Código legível e fácil de manter
- APIs bem definidas e integrações confiáveis
- Separação clara de responsabilidades
- Modelagem de dados orientada ao domínio
- Gates de qualidade em código, nunca "confiar que vai dar certo" (nem no LLM, nem no prompt)
- Observabilidade e tratamento de falhas
- Segurança e validação no backend
- Automação de processos repetitivos
- Produtos pensados além da interface

---

## Atualmente

```csharp
var lucas = new Developer
{
    Role = "Full Stack Developer",
    MainStack = new[] { "C#", ".NET", "Angular", "React" },
    AlsoUses = new[] { "PHP", "Python", "Flutter" },
    Databases = new[] { "SQL Server", "PostgreSQL", "MongoDB" },
    DevOps = new[] { "Docker", "Azure DevOps", "GitHub", "Hangfire" },
    Interests = new[] { "APIs", "IA aplicada", "Integrações", "SaaS", "Automação" }
};
```

---

## Contribution Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucas-goncalves-cav/lucas-goncalves-cav/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lucas-goncalves-cav/lucas-goncalves-cav/output/github-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/lucas-goncalves-cav/lucas-goncalves-cav/output/github-snake.svg" />
</picture>

</div>

---

<div align="center">

**Construindo software para resolver problemas reais.**

`github.com/lucas-goncalves-cav`

</div>
</content>
