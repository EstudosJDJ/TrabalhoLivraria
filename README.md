# Sistema de Gerenciamento de Biblioteca Escolar 


## 📚 Descrição do Projeto
Sistema simplificado de gerenciamento de biblioteca escolar desenvolvido utilizando conceitos de análise e desenvolvimento de sistemas. O projeto inclui uma aplicação web e mobile integrada para facilitar o controle de empréstimos e devoluções de livros.


## 🎯 Objetivo
Desenvolver um sistema completo que permita o gerenciamento eficiente de uma biblioteca escolar, incluindo cadastro de livros, alunos, controle de empréstimos e geração de relatórios.


## 👥 Equipe de Desenvolvimento


### **Danilo Leal Hoffoman** - *Full Stack Developer & Project Lead*
- **Front-end:** Desenvolvimento da aplicação principal
- **Back-end:** Implementação das funções principais
  - ToggleCategoria
  - ToggleTema
  - Card/Categoria
  - Slides
- **Banco de dados:** Consultas de livros disponíveis


### **João Paulo Caramuru** - *UI/UX Designer*
- **Front-end:** Design e interface do usuário
- Responsável pela experiência visual e usabilidade do sistema


### **Matheus Cribari** - *Database Administrator*
- **Banco de dados:**
  - Cadastro de alunos
  - Cadastro de livros
  - Estruturação e manutenção do banco de dados


### **Jonathan Maia** - *Database Architect*
- **Banco de dados:**
  - Modelo relacional
  - Scripts SQL de criação e configuração


### **João Gabriel Garcia** - *Systems Analyst*
- **Outros:** Criação de diagramas UML e documentação técnica
- **Readme.md**


## 🛠️ Tecnologias Utilizadas


### Front-end
- HTML5, CSS3, JavaScript, Typescript
- Framework: Expo
- Design responsivo para web e mobile


### Back-end
- Linguagem: Javascript, Typescript
- Arquitetura MVC


### Banco de Dados
- Sistema: SQLite/MySQL
- Modelagem relacional
- Scripts automatizados


### Ferramentas de Desenvolvimento
- **Versionamento:** Git/GitHub
- **Diagramação:** Draw.io / Lucidchart
- **IDE:** Visual Studio Code
- **Testes:** Unitários e de integração


## ⚙️ Funcionalidades


### Em Desenvolvimento
- 🔄 Registro de Empréstimos e Devoluções
- 🔄 Consulta de Empréstimos por aluno
- 🔄 Relatórios de dados
- 🔄 Cadastro de Livros (Título, Autor, ISBN, Editora, Ano)
- 🔄 Cadastro de Alunos (Nome, Matrícula, Turma)
- 🔄 Toggle de Categorias e Temas
- 🔄 Cards informativos
- 🔄 Consulta de livros disponíveis


### Planejadas
- 📋 Geração de relatórios (livros mais emprestados)
- 📱 Aplicação mobile integrada
- 🔍 Sistema de busca avançada


## 🚀 Como Executar


### Instalação
```bash
# Clone o repositório
git clone https://github.com/EstudosJDJ/TrabalhoLivraria/

# Entre no diretório
cd sistema-biblioteca

# Instale as dependências
npm install

# Garanta que possui o expo instalado globalmente
npm install -g expo-cli
# ou
npx expo install

# Configure o banco de dados
 A decidir


# Execute o sistema
 A decidir
```


## 📁 Estrutura do Projeto
```
biblioteca-expo/
├── .config/
│   ├── eas-cli-nodejs/
│   │   └── user-settings.json
│   └── npm/
│       └── node_global/
│           ├── bin/
│           └── lib/
├── .expo/
│   ├── types/
│   │   └── router.d.ts
│   ├── web/
│   │   └── cache/
│   │       └── production/
│   │           └── images/
│   │               └── favicon/
│   │                   └── favicon-48.png
│   ├── devices.json
│   └── README.md
├── .git/
│   ├── branches/
│   ├── hooks/
│   │   ├── applypatch-msg.sample  
│   │   ├── commit-msg.sample  
│   │   ├── fsmonitor-watchman.sample  
│   │   ├── post-update.sample  
│   │   ├── pre-applypatch.sample  
│   │   ├── pre-commit.sample  
│   │   ├── pre-merge-commit.sample  
│   │   ├── prepare-commit-msg.sample  
│   │   ├── pre-push.sample  
│   │   ├── pre-rebase.sample  
│   │   ├── pre-receive.sample  
│   │   ├── push-to-checkout.sample  
│   │   ├── sendemail-validate.sample  
│   │   └── update.sample
│   ├── info/
│   │   └── exclude
│   ├── logs/
│   │   ├── refs/
│   │   └── HEAD
│   ├── objects/
│   │   └── ...
│   ├── refs/
│   │   ├── heads/
│   │   │   └── main
│   │   └── tags/
│   ├── COMMIT_EDITMSG
│   ├── config
│   ├── description
│   ├── HEAD
│   └── index
├── app/
│   ├── (tabs)/
│   │   ├── _layout.tsx
│   │   ├── explote.tsx
│   │   └── index.tsx
│   ├── _layout.tsx
│   └── +not-found.tsx
├── assets/
│   ├── fonts/
│   │   └── SpaceMon-Regular.ttf
│   └── images/
│       ├── adaptive-icon.png  
│       ├── icon.png  
│       ├── partial-react-logo.png  
│       ├── react-logo.png  
│       ├── react-logo@2x.png  
│       ├── react-logo@3x.png  
│       └── splash-icon.png
├── components/
│   ├── ui/
│   │   ├── IconSymbol.ios.tsx
│   │   ├── IconSymbol.tsx
│   │   ├── TabBarBackground.ios.tsx
│   │   └── TabBarBackground.tsx
│   ├── Card.jsx  
│   ├── Categoria.jsx  
│   ├── Collapsible.tsx  
│   ├── ExternalLink.tsx  
│   ├── HapticTab.tsx  
│   ├── HelloWave.tsx  
│   ├── ParallaxScrollView.tsx  
│   ├── Slide.jsx  
│   ├── ThemedText.tsx  
│   └── ThemedView.tsx
├── constants/
│   ├── Card.ts
│   ├── Categorias.ts
│   ├── Colors.ts
│   ├── Style.ts
│   └── Slides.ts
├── data/
│   └── livros.json
├── hooks/
│   ├── useColorScheme.ts
│   ├── useColorScheme.web.ts
│   └── useThemeColor.ts
├── scripts/
│   └── reset-project.js
├── .gitignore
├── .eslintrc.config.js
├── expo-env.d.ts
├── generated-icon.png
├── package.json
├── package-lock.json
├── README.md
├── Replit.nix
└── tsconfig.json

## 📊 Status do Desenvolvimento


| Funcionalidade         | Responsável         | Status           |
|   ---                  |      ---            |      --          |
| Interface Principal    | Danilo              | ✅ Concluído    |
| Cadastro de Livros     | Cribari             | 🔄 Em andamento |
| Cadastro de Alunos     | Cribari             | ✅ Concluído    |
| Consultas              | Danilo              | 🔄 Em andamento |
| Modelo Relacional      | Jonathan            | 🔄 Em andamento |
| Scripts SQL            | Jonathan            | 🔄 Em andamento |
| Diagramas UML          | João Gabriel        | 🔄 Em andamento |
| Empréstimos/Devoluções | -                   | ⏳ Pendente     |


## 🧪 Testes
- Testes unitários implementados
- Testes de integração em desenvolvimento
- Testes de interface planejados


## 🤝 Contribuição
Para contribuir com o projeto, siga as diretrizes:
1. Faça um fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request


---
*Projeto desenvolvido para o curso de Desenvolvimento de Sistemas da escola de ensino médio técnico Cedtec*
