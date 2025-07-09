# NLW Agents

Projeto desenvolvido durante o evento NLW (Next Level Week) da Rocketseat, focado em demonstrar conceitos de desenvolvimento web moderno com React.

## 🚀 Tecnologias Utilizadas

### Frontend
- **React 19** - Biblioteca JavaScript para criação de interfaces
- **TypeScript** - Superset do JavaScript com tipagem estática
- **Vite** - Build tool e dev server rápido
- **TailwindCSS 4** - Framework CSS utility-first
- **React Router DOM** - Roteamento para aplicações React
- **TanStack Query** - Gerenciamento de estado servidor/cliente

### UI Components
- **Radix UI** - Primitivos de componentes acessíveis
- **Lucide React** - Biblioteca de ícones
- **shadcn/ui** - Componentes prontos baseados em Radix UI
- **CVA (Class Variance Authority)** - Utilitário para variações de componentes

### Ferramentas de Desenvolvimento
- **Biome** - Linter e formatter JavaScript/TypeScript
- **Ultracite** - Configuração estendida do Biome

## 🏗️ Padrões de Projeto

- **Component Composition** - Composição de componentes com Radix UI
- **Custom Hooks** - Hooks personalizados para lógica reutilizável
- **Provider Pattern** - Context providers para gerenciamento de estado
- **Utility-First CSS** - Abordagem utility-first com TailwindCSS
- **Path Aliases** - Aliases de caminho para imports limpos (`@/components`)

## 🔧 Setup e Configuração

### Pré-requisitos
- Node.js 18+
- npm, yarn ou pnpm

### Instalação

1. Clone o repositório:
```bash
git clone <repository-url>
cd web
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
```

4. Acesse a aplicação em `http://localhost:5173`

### Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── ui/           # Componentes UI reutilizáveis
├── lib/
│   └── utils.ts      # Utilitários e helpers
├── pages/            # Páginas da aplicação
├── app.tsx           # Componente raiz da aplicação
├── main.tsx          # Ponto de entrada da aplicação
└── index.css         # Estilos globais
```

## 🎯 Funcionalidades

- Sistema de roteamento com React Router
- Gerenciamento de estado com TanStack Query
- Interface moderna e responsiva
- Componentes acessíveis com Radix UI
- Tipagem completa com TypeScript
