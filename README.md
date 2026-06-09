# Luiz Carlos Cavadinha

**Desenvolvedor Full Stack Jr | React · Next.js · TypeScript · Node.js**

Desenvolvo aplicações web full stack com foco em interfaces previsíveis, integração com APIs REST e tratamento de erros. Tenho experiência prática em projetos reais na Fábrica de Software do UNIPÊ, com clientes institucionais e metodologia Scrum.

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=LCCavadinha&show_icons=true&theme=transparent&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&cache_seconds=0&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LCCavadinha&layout=compact&theme=transparent&hide_border=true&title_color=58a6ff&text_color=c9d1d9&cache_seconds=0)

---

## Stack

**Front-end**
React · Next.js · TypeScript · JavaScript ES6+ · HTML5 · CSS3 · TailwindCSS · Material UI · Zod · Axios · React Hook Form · Vite

**Back-end**
Node.js · Express · Sequelize · MySQL · FastAPI · Django (AdminLTE)

**Ferramentas**
Git · GitHub · GitLab · Docker · Scrum · Postman

---

## Projetos

### Remédio Certo – Sistema Web de Gestão de Estoque Hospitalar
`Next.js 14` `TypeScript` `TailwindCSS` `shadcn/ui` `FastAPI` `MySQL` `JWT` `Railway` `Vercel`

Sistema web completo para controle de estoque de medicamentos hospitalares, com alertas automáticos, rastreabilidade por lote e relatórios em tempo real. Projeto acadêmico desenvolvido em grupo para a disciplina de Análise e Projeto de Sistemas I — UNIPÊ 2026.1.

**Minha atuação como Full Stack:**

*Frontend*
- Arquitetura completa do frontend com Next.js 14 App Router e TypeScript strict
- Implementação de todos os módulos: Dashboard, Medicamentos, Estoque, Movimentações, Alertas, Unidades, Usuários e Relatórios
- Sistema de autenticação com JWT, interceptor axios para renovação automática em erro 401 e redirecionamento protegido
- Formulários com react-hook-form 7.54.2 + zod com validações contextuais (CNPJ com dígitos verificadores, senha separada por criação/edição, quantidade máxima contra saldo de estoque)
- Tema claro/escuro completo com next-themes e variáveis CSS
- Layout responsivo mobile-first com sidebar, drawer mobile e header com dropdown de alertas
- Tela de confirmação antes de registrar movimentações
- Carrossel de screenshots na landing page com animação CSS
- Deploy via Vercel com CI/CD automático na branch main

*Backend (contribuição)*
- Integração com API FastAPI: alinhamento de contratos, correção de campos e tipagens
- Parser de mensagens de alerta (`alertaParser.ts`) com regex para extrair dados estruturados
- Redirecionamento inteligente dos alertas para movimentações pré-preenchidas

- Formulário de entrada com lote livre e validade com máscara dd/mm/aaaa bloqueando datas passadas
- Formulário de saída com select de lote existente e validade preenchida automaticamente
- Busca dinâmica por campo selecionado (Medicamento, Princípio Ativo, Lote, Validade) no estoque
- Filtros com busca em tempo real, validação de data fim após data início e botão limpar filtros
- Destaque visual de lotes vencidos com fundo vermelho em tabela e cards mobile
- Badge de alertas pendentes no sidebar e sino do header

[Deploy](https://remedio-certo-app.vercel.app) · [Repositório](https://github.com/LCCavadinha/remedio-certo-app)

---

### IAvalia – Plataforma de Correção Automatizada de Provas via IA
`React 19` `TypeScript` `Vite` `Material UI` `Zod` `Axios` `react-router-dom`

Front-end de plataforma web para correção automática de provas de múltipla escolha via IA. Desenvolvido na Fábrica de Software do UNIPÊ para cliente real.

- Formulários com validação por schema Zod, com mensagens de erro por campo
- Integração com APIs REST via Axios com tratamento de erros centralizado
- Arquitetura de serviços separada por domínio
- Roteamento com react-router-dom
- Upload de arquivos CSV com validação de formato e tamanho

> Projeto em desenvolvimento ativo | repositório privado

---

### Sistema Full-Stack de Gerenciamento de Filmes
`Node.js` `Express` `Sequelize` `MySQL` `React` `TypeScript` `Axios` `React Hook Form`

Aplicação full-stack com API REST em arquitetura MVC e frontend tipado.

**Back-end**
- CRUD completo com Express e Sequelize
- UUID como chave primária
- Middleware de validação de dados
- Tratamento centralizado de erros com AppError
- Testes via Postman

**Front-end**
- Consumo de API com Axios
- Formulários com React Hook Form
- Gerenciamento de estado com useState e useEffect
- Sincronização em tempo real com o banco

[Repositório](https://github.com/LCCavadinha/Trabalho_filmes)

---

### Pokédex – Next.js + TypeScript
`Next.js` `TypeScript` `TailwindCSS` `PokeAPI`

Aplicação consumindo API pública com busca dinâmica e renderização condicional.

- Filtro em tempo real
- Layout responsivo com TailwindCSS
- Controle de estado e renderização condicional

[Deploy](https://ws-frontend-fabrica25-2-chi.vercel.app) · [Repositório](https://github.com/LCCavadinha/wsFrontend-Fabrica25.2)

---

### Quicklist – JavaScript Puro
`JavaScript` `HTML5` `CSS3`

Aplicação de lista de compras com foco em controle de estado, renderização previsível e experiência do usuário sob falhas. O objetivo foi praticar fundamentos essenciais de front-end sem frameworks, simulando manualmente conceitos comuns em bibliotecas como React.

**Conceitos praticados**
- Estado como fonte da verdade
- Renderização baseada em estado
- Fluxo unidirecional de dados
- Separação entre lógica e interface

**Funcionalidades**
- Lista inicial com itens pré-carregados
- Adição de itens com validação de entrada
- Marcação e desmarcação de itens como concluídos
- Remoção de itens
- Feedback visual para ações do usuário
- Tratamento explícito de estado vazio

**CSS**
- Variáveis CSS para cores e tipografia
- Mobile-first com media queries
- Flexbox para layout previsível
- Checkbox customizado sem biblioteca

[Repositório](https://github.com/LCCavadinha/Rocketseat_projets/tree/desafio_lista_de_compras)

---

## Formação

- ADS – Análise e Desenvolvimento de Sistemas | UNIPÊ (2025–2026)
- Full Stack | Rocketseat
- Ciência de Dados e IA Generativa com Python | SECTRAS (20h)

---

## Contato

[LinkedIn](https://www.linkedin.com/in/luiz-carlos-souza-costa-cavadinha-2646aa279) · [GitHub](https://github.com/LCCavadinha) · [Email](luizcarlos.souzacosta@yahoo.com.br)

