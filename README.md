# Amora — Gestão inteligente para negócios doces

SaaS de gestão e vendas para pequenos negócios de alimentação.  
Stack: React + TypeScript + Vite + Tailwind CSS + shadcn/ui (base reutilizável) + Supabase/PostgreSQL.

## Módulos
Dashboard, Produtos, Ingredientes, Receitas, Precificação, Pedidos, Clientes, Estoque, Produção, Financeiro, Loja Online, Relatórios, Equipe e Configurações.

## Princípios
- Multi-tenant com `organization_id`
- RLS no Supabase
- Mobile-first e PWA
- Dados reais, sem funcionalidades falsas
- Componentes reutilizáveis e arquitetura escalável

## Desenvolvimento
```bash
npm install
npm run dev
```

Copie `.env.example` para `.env.local` e configure o Supabase.
