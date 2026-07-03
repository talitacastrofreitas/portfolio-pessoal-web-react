# 👩‍💻 Portfólio Pessoal & Portal Administrativo - React
Um aplicativo web moderno desenvolvido em **React** que combina o **Portfólio Pessoal** da desenvolvedora **Talita Castro** com a estrutura inicial de um **Portal Administrativo** de acesso restrito (Dashboard).

---
## 🎯 Seções & Recursos da Aplicação
### 🌐 Área Pública (Portfólio Pessoal)
- **Apresentação & Biografia (`/`):** Tela inicial de boas-vindas contendo foto de perfil, cargo profissional ("Analista de Desenv. de Sistemas Web Jr.") e texto descritivo.
- **Barra de Competências:** Indicadores gráficos de progresso representativos de habilidades técnicas nas principais tecnologias do mercado:
  - Figma (layout/protótipos): 100%
  - HTML / HTML5: 90%
  - CSS / CSS3: 65%
  - Bootstrap: 65%
  - Banco de Dados: 40%
  - React JS: 35%
- **Componente de Contato:** Área com dados rápidos de e-mail e canais diretos para envio de mensagens.
- **Componente de Redes Sociais:** Links integrados para canais externos como GitHub, LinkedIn e e-mail.
- **Vitrine de Projetos (`/projetos`):** Seção destinada à exibição da galeria de trabalhos e projetos de desenvolvimento.
### 🔐 Área Administrativa (Dashboard)
- **Tela de Login (`/app`):** Form de login simples para autenticação e controle de sessões.
- **Dashboard (`/aplicativo`):** Painel de entrada pós-autenticação para gestão administrativa interna.
---
## 📂 Estrutura de Pastas
```bash
portfolio-pessoal-web-react/
├── public/
│   ├── favicon.ico          # Ícone da aba do navegador
│   └── index.html           # Documento HTML base
├── src/
│   ├── App/
│   │   ├── Login/           # Componente de controle de acesso (/app)
│   │   └── aplicativo/      # Dashboard interno restrito (/aplicativo)
│   ├── Site/
│   │   ├── components/
│   │   │   └── Header/      # Menu e barra de navegação global
│   │   ├── pages/
│   │   │   ├── Contato/     # Seção de contato integrada
│   │   │   ├── Home/        # Home do portfólio (textos, avatar e barra de competências)
│   │   │   │   ├── Image/   # Imagem de perfil (talita.jpg)
│   │   │   │   ├── home.css # Estilização das seções da home
│   │   │   │   └── index.js # Lógica de renderização da página inicial
│   │   │   ├── Projetos/    # Galeria de projetos desenvolvidos (/projetos)
│   │   │   └── RedesSociais/# Ícones com links de redirecionamento (GitHub, LinkedIn)
│   │   └── site.jsx         # Orquestrador do layout do site (Header + Home)
│   ├── App.jsx              # Configuração do roteamento principal (React Router Dom)
│   ├── index.css            # Definições globais de layout e tipografia
│   └── index.js             # Inicialização do React no container raiz
├── package.json             # Declaração de dependências e scripts do npm
└── README.md                # Documentação do projeto
```
---
## 🛠️ Tecnologias Utilizadas
- **React v18:** Biblioteca base para a construção das interfaces reativas.
- **React Router Dom (v6):** Roteador dinâmico declarativo de páginas (`BrowserRouter`, `Routes`, `Route`).
- **Bootstrap 5:** Grid responsivo, formulários e barras de progresso (`progress-bar`).
- **CSS3 (Customizado):** Estilização para cores e fontes personalizadas do site.
- **FontAwesome (Icons):** Ícones sociais integrados (GitHub, LinkedIn).
---
## 💻 Como Rodar o Projeto Localmente
### Requisitos:
Certifique-se de possuir o [Node.js](https://nodejs.org/) instalado em sua máquina.
### Passos:
1. Abra o terminal na pasta do projeto.
2. Instale as dependências executando:
   ```bash
   npm install
   ```
3. Inicialize a aplicação em modo de desenvolvimento:
   ```bash
   npm start
   ```
4. O navegador abrirá automaticamente o link: [http://localhost:3000](http://localhost:3000).
