# Vivendo Em Terapia - TODO

## Landing Page & Autenticação
- [x] Landing page acolhedora com apresentação do app e benefícios
- [x] CTA clara para cadastro/login
- [x] Sistema de autenticação OAuth integrado
- [ ] Página de login com redirecionamento

## Sistema de Assinatura & Pagamento
- [x] Integração Stripe (planos mensal e anual)
- [ ] Página de seleção de plano
- [x] Checkout Stripe
- [x] Gerenciamento de assinatura (renovação automática, cancelamento)
- [x] Controle de acesso a conteúdo exclusivo baseado em assinatura

## Dicas Diárias & Conteúdo
- [x] Integração com LLM para gerar dicas diárias de bem-estar
- [x] Armazenamento de dicas no banco de dados
- [ ] Exibição de dicas diárias no dashboard do assinante
- [x] Histórico de dicas recebidas

## Exercícios Terapêuticos
- [x] Biblioteca de exercícios (respiração, mindfulness, journaling, etc.)
- [ ] Interface interativa para exercícios
- [x] Rastreamento de exercícios realizados
- [ ] Histórico de exercícios no dashboard

## Fórum de Comunidade Anônimo
- [x] Schema de tabelas para fórum (tópicos, respostas, categorias)
- [x] Rotas tRPC para criar/listar/responder tópicos
- [x] Sistema de anonimato (usuários como "Anônimo #123")
- [x] Categorias de tópicos (Ansiedade, Depressão, Relacionamentos, Trabalho, Geral)
- [x] Interface de fórum com lista de tópicos
- [x] Página de detalhes do tópico com respostas
- [x] Filtro e busca de tópicos
- [x] Sistema de reputação/pontos por respostas úteis
- [x] Moderação automática (filtro de palavras ofensivas)
- [ ] Notificações quando alguém responde a tópico do usuário

## Chat em Tempo Real
- [x] Implementação de chat com WebSocket/Socket.io
- [ ] Interface de chat na plataforma
- [x] Histórico de mensagens
- [x] Notificações de novas mensagens

## Agendamento de Sessões
- [x] Sistema de agendamento com calendário
- [x] Disponibilidade do terapeuta
- [x] Confirmação de agendamento
- [ ] Lembretes de sessão de sessões agendadas no dashboard

## Dashboard do Usuário
- [x] Visão geral do perfil e assinatura
- [x] Histórico de dicas recebidas
- [x] Histórico de exercícios realizados
- [x] Próximas sessões agendadas
- [ ] Acesso ao chat com terapeuta

## Painel Administrativo (Terapeuta)
- [ ] Gerenciamento de clientes
- [ ] Visualização de sessões agendadas
- [ ] Envio de conteúdos/dicas personalizadas
- [ ] Histórico de interações com clientes

## Notificações por E-mail
- [ ] Notificação de agendamento de sessão
- [ ] Notificação de nova dica diária disponível
- [ ] Notificação de exercício pendente
- [ ] Lembrete pré-sessão

## Design & UI/UX
- [ ] Design cósmico/futurista (gradiente azul/violeta, efeitos de luz)
- [ ] Tipografia bold, sem serifa, com brilho luminoso
- [ ] Orbs planetários e lens flares
- [ ] Responsividade para mobile e desktop
- [ ] Testes de acessibilidade

## Testes & Qualidade
- [ ] Testes unitários (Vitest)
- [ ] Testes de integração
- [ ] Testes de segurança (autenticação, pagamento)
- [ ] Testes de responsividade

## Deployment & Publicação
- [ ] Configuração de variáveis de ambiente
- [ ] Testes em ambiente de produção
- [ ] Publicação da plataforma


## Redesign - Tema Profissional de Consultório
- [x] Atualizar paleta de cores (tons suaves: azul, verde, roxo pastel)
- [x] Redesenhar landing page com layout profissional
- [x] Atualizar CSS global com novo tema
- [x] Logo do app (Coração + Cérebro + Folha)
- [ ] Redesenhar páginas do fórum
- [ ] Redesenhar interface de chat
- [ ] Redesenhar dashboard do usuário


## PWA - Progressive Web App
- [x] Criar manifest.json com informações do app
- [x] Adicionar service worker (sw.js) para offline
- [x] Atualizar index.html com meta tags de PWA
- [ ] Gerar ícones em múltiplos tamanhos (72x72 até 512x512)
- [ ] Gerar splash screens para iOS
- [ ] Testar instalação em Android
- [ ] Testar instalação em iOS
- [ ] Validar funcionamento offline


## SEO - Search Engine Optimization
- [x] Meta tags otimizadas (title, description, keywords)
- [x] Open Graph tags (Facebook, LinkedIn)
- [x] Twitter/X card tags
- [x] JSON-LD schema (WebApplication, Organization)
- [x] Sitemap.xml
- [x] robots.txt
- [x] Canonical tags
- [x] DNS prefetch para recursos externos
- [ ] Google Search Console integration
- [ ] Bing Webmaster Tools integration
- [ ] Submeter sitemap ao Google
- [ ] Otimizar velocidade de carregamento (Core Web Vitals)
- [ ] Criar blog com artigos sobre saúde mental
- [ ] Adicionar FAQ schema
- [ ] Implementar breadcrumbs
