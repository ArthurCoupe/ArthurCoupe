<h1 align="center">Arthur Coupê</h1>

<p align="center">
Engenheiro de software full stack · CTO na <b>Next Business</b> · Brasília, DF<br>
Construo sistemas de gestão que rodam em produção todos os dias, com agentes de IA no fluxo de desenvolvimento e sem abrir mão de teste, revisão e segurança.<br>
<sub>Full stack software engineer and CTO at Next Business. I ship production management systems with AI agents, with tests, review and security built in.</sub>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/arthurcoupeg/"><img src="https://img.shields.io/badge/LinkedIn-arthurcoupeg-C8102E?style=flat-square&logo=linkedin&logoColor=white"></a>
<img src="https://img.shields.io/badge/e--mail-arthurcoupedev%40gmail.com-C8102E?style=flat-square&logo=gmail&logoColor=white">
</p>

---

### Em números (julho a outubro de 2026)

| 4+ anos de experiência | 4.000+ commits | 800+ pull requests mergeados | 400+ migrations PostgreSQL |
|:---:|:---:|:---:|:---:|

Quase tudo em repositórios privados de clientes. O gráfico de contribuições abaixo conta esse trabalho; o código fica com quem é dono dele.

### O que construí

- **ERP para agroindústria** (produção rural e distribuição de alimentos): jornada do lote, inventário, DRE gerencial com rateios, regime de caixa e competência, painéis executivos e ETL a partir do ERP legado. Em uso diário pela gestão. `React` `Node.js` `PostgreSQL` `Supabase`
- **CRM da Next Business**: funil comercial, contratos, financeiro com MRR e TCV separados, fechamento mensal, captação do site, avisos por e-mail e assistente de IA. Em produção desde setembro de 2026. `TanStack Start` `Supabase` `Vercel`
- **CRM sob medida para cliente**: primeira versão em produção uma semana depois do contrato, com captação por landing page, atribuição de campanha, papéis de acesso e IA com teto de gasto. `TypeScript` `Supabase`
- **SaaS jurídico** (em construção): captura de intimações (DJEN) e movimentações (DataJud), leitura por IA com citação do trecho e revisão obrigatória do advogado. Multi-tenant.

### Como trabalho com IA

Desenvolvo com agentes de IA, num harness que eu mesmo construí e instalo em cada projeto ([versão pública](https://github.com/ArthurCoupe/ai-agents-harness)):

- 24 agentes especializados (banco, backend, frontend, segurança, revisor adversarial, entre outros)
- hooks de limite com 142 casos de teste, que barram ação perigosa antes de ela acontecer
- portões de qualidade por perfil de projeto (site, CRM, SaaS, app), rodados antes de cada PR
- revisão em duas passadas, em contexto isolado: critério de pronto contra teste, depois defeito fora dos critérios
- memória de longo prazo num vault (Obsidian + git) com decisões, lições e estado de cada projeto

O agente não decide sozinho o que vai para produção: merge, migration e mudança de segurança passam por revisão humana com prova escrita.

### Segurança por padrão

Row Level Security com FORCE · MFA (TOTP) para dado financeiro · CSP com nonce · testes de IDOR no CI · varredura de segredos com gitleaks · IA do produto só sugere, nunca executa ação externa

### Cursos (2026)

Anthropic, Claude Academy: Building with the Claude API, Claude Platform 101, Introduction to Model Context Protocol, Model Context Protocol: Advanced topics, AI Fluency for builders e Building effective human-agent teams · Linux Foundation: Developing Secure Software (LFD121) · Hugging Face: Agents Course · [todos no LinkedIn](https://www.linkedin.com/in/arthurcoupeg/details/certifications/)

### Stack

<p>
<img src="https://skillicons.dev/icons?i=ts,js,react,nodejs,postgres,supabase,vercel,vite,tailwind,py,fastapi,mysql,docker,githubactions,cloudflare,git&perline=8">
</p>

### Projetos públicos

**[ai-agents-harness](https://github.com/ArthurCoupe/ai-agents-harness)**: Harness de engenharia para agentes de IA, com 24 agentes especialistas, hooks de limite com teste próprio, portões de verificação por perfil de projeto e revisão em duas passadas. Node puro, sem dependências, MIT.

**[CRMNextDemo](https://github.com/ArthurCoupe/CRMNextDemo)**: Demonstração com dados fictícios do CRM da Next Business: funil, contratos, financeiro com MRR e TCV, onboarding e assistente de IA.

**[GestaoAgro](https://github.com/ArthurCoupe/GestaoAgro)**: Demonstração com dados fictícios de um ERP para agroindústria: DRE gerencial, caixa, orçamento, ciclo produtivo do lote e contaminação.
