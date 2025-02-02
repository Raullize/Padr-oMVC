# 🏗️ Estrutura Padrão para Projetos MVC

Este repositório contém uma estrutura básica para projetos em **MVC (Model-View-Controller)**, seguindo um padrão bem organizado e utilizando componentes modernos para o desenvolvimento de aplicações web. Esta estrutura foi criada para servir como base para projetos futuros, com a separação clara de responsabilidades e facilidades para o desenvolvimento, manutenção e escalabilidade.

## 🧩 O que é MVC?

O padrão **MVC** (Model-View-Controller) é uma arquitetura de software que separa a aplicação em três componentes principais:

- **📦 Model (Modelo)**: Responsável pela lógica de negócios e comunicação com o banco de dados.
- **🖼️ View (Visão)**: Responsável pela exibição de dados e interface com o usuário.
- **🎮 Controller (Controle)**: Gerencia a interação do usuário e as respostas do sistema, sendo responsável por receber as requisições e enviar as respostas adequadas, interagindo com o modelo e a visão.

## 🗂️ Estrutura do Projeto

A estrutura do projeto segue a seguinte hierarquia de diretórios e arquivos:

```bash
/
├── /01-bd           # 📊 Estrutura do banco de dados
├── /assets          # 🎨 Arquivos estáticos como imagens, CSS e JavaScript
├── /source          # 💻 Código fonte principal da aplicação
│   ├── /App         # 🎯 Contém os controladores principais da aplicação
│   ├── /Boot        # 🔧 Arquivos de inicialização e configuração do sistema
│   ├── /Core        # 🧠 Núcleo do sistema, classes principais e funcionalidades base
│   ├── /Models      # 📦 Modelos, lógica de negócios e interação com o banco de dados
│   ├── /Support     # 🛠️ Classes de suporte, como helpers e serviços auxiliares
├── /storage         # 📁 Arquivos gerados pela aplicação, como logs, cache, uploads, etc.
├── /themes          # 🎨 Templates e elementos visuais do frontend (views)
├── .gitignore       # 🙈 Arquivo que define os arquivos e pastas a serem ignorados pelo Git
├── .htaccess        # 🔗 Arquivo de configuração para servidores Apache (rotas, URL amigáveis)
├── composer.json    # 📦 Arquivo de dependências do Composer
├── index.php        # 🚪 Ponto de entrada da aplicação (geralmente inicializa o Boot e as rotas)
└── readme.md        # 📄 Este arquivo
```
