# Portfólio Vinicius Araujo

Site de portfólio SPA (Single Page Application) desenvolvido com SvelteKit e Tailwind CSS, inspirado em https://gpalmaj.xyz/.

## Características

- ✨ Design minimalista e dark mode sofisticado
- 📱 Responsividade total (mobile-first)
- 🎯 Navegação sticky com scroll suave
- 🃏 Cards sutis para experiências e projetos
- 🏷️ Habilidades exibidas como tags/pílulas
- ⚡ Desenvolvido com SvelteKit e Tailwind CSS

## Seções

- **Hero**: Apresentação com nome e subtítulo
- **Sobre Mim**: Breve descrição pessoal
- **Experiência Profissional**: Timeline com 4 experiências (Milênio Capital, MPA Tecgraf/PUC-Rio, Monitor PUC-Rio, DSI GTEC PUC-Rio)
- **Habilidades**: Tags divididas em categorias (Linguagens, Frameworks, Databases, Ferramentas, Idiomas)
- **Contato**: Links para e-mail, GitHub e LinkedIn

## Instalação e Desenvolvimento

### Pré-requisitos

- Node.js 18+ 
- npm, pnpm ou yarn

### Instalar dependências

```bash
npm install
```

### Desenvolver

```bash
npm run dev

# ou para abrir automaticamente no navegador
npm run dev -- --open
```

O servidor irá rodar em `http://localhost:5173/`

### Build de produção

```bash
npm run build
```

### Preview de produção

```bash
npm run preview
```

## Estrutura do Projeto

```
src/
├── routes/
│   ├── +page.svelte        # Página principal do portfólio
│   ├── +layout.svelte      # Layout global
│   └── layout.css          # Estilos globais
├── lib/                    # Bibliotecas e utilitários
└── app.html                # Template HTML global
```

## Tecnologias

- **SvelteKit**: Framework de desenvolvimento web
- **Tailwind CSS**: Framework de CSS utility-first
- **Svelte**: Framework de componentes reativos
- **TypeScript**: Tipagem estática (quando necessário)

## Dados Pessoais

- **Nome**: Vinicius Araujo
- **Perfil**: Desenvolvedor de Software | Estudante de Ciência da Computação
- **E-mail**: viniaraujoaraujova@gmail.com
- **GitHub**: github.com/viniaraujo68
- **LinkedIn**: linkedin.com/in/vinicius-barros-pessoa-de-araujo-182462257/

## Licença

Este projeto é de código aberto e está disponível sob a licença MIT.