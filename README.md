<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-escuro.svg">
  <img src="assets/banner-claro.svg" width="100%" alt="Eduardo Chamorra, fundador da Convello">
</picture>

<p align="center">
  <a href="https://convello.com.br"><img src="https://img.shields.io/badge/convello.com.br-3665e4?style=flat-square&logoColor=white" alt="convello.com.br"></a>
  <a href="https://r12company.com"><img src="https://img.shields.io/badge/R12_Company-57606a?style=flat-square" alt="R12 Company"></a>
</p>

Construo e opero software que empresas usam para vender e atender pelo WhatsApp: do produto ao servidor, passando por atendimento com IA e cobrança.

## O que estou construindo

**[Convello](https://convello.com.br)**: CRM multiempresa com WhatsApp e IA.
- Atendimento pelo WhatsApp (API oficial da Meta e conexão pelo aparelho), Instagram e ligações, tudo na mesma tela.
- IA que atende o cliente, qualifica, agenda visita e passa para o corretor na hora certa.
- Funil de vendas, imóveis, site da empresa com domínio próprio, disparos e relatórios.
- Em produção, atendendo imobiliárias e empresas de serviço.

**Convello Desk**: aplicativo de mesa para a equipe atender a fila de conversas sem abrir o navegador.

**Convello Voice**: agente de IA que liga e conversa por voz pelo WhatsApp.

**Kubra**: gateway de pagamento com checkout, produtos e integrações.

Além disso, CRMs sob medida para revendas de veículos e empresas de serviço de campo.

## Projeto aberto

**[AgentDesk](https://github.com/eddchdev/agentdesk)**: quadro operacional para coordenar várias sessões do Claude Code como uma equipe (servidor MCP e app desktop em Electron).

## Tecnologias

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,react,vite,tailwind,nodejs,java,spring,postgres,redis,docker,nginx,cloudflare,linux,tauri,electron,git&perline=8&theme=dark">
  <img src="https://skillicons.dev/icons?i=ts,react,vite,tailwind,nodejs,java,spring,postgres,redis,docker,nginx,cloudflare,linux,tauri,electron,git&perline=8&theme=light" alt="TypeScript, React, Vite, Tailwind, Node.js, Java, Spring, PostgreSQL, Redis, Docker, nginx, Cloudflare, Linux, Tauri, Electron e Git">
</picture>

Também no dia a dia: Fastify, Drizzle ORM, BullMQ, API oficial do WhatsApp, Baileys, Instagram Graph API e IA com Gemini, OpenAI e Claude.

## Como eu trabalho

- **Produção em primeiro lugar:** backup antes de mexer, validação depois de subir e caminho de volta sempre pronto.
- **Isolamento entre clientes:** em sistema multiempresa, o dado de uma empresa nunca aparece para outra, e isso é testado.
- **Teste antes do código:** correção vem com um teste que falha sem ela.
- **Segurança como rotina:** auditoria periódica de dependências, servidores e código.
