# GH

## 1. Instalação do GH
- **Linux**: `sudo apt install gh` (Ubuntu/Debian)
- **MacOS**: `brew install gh`
- **Windows**: `choco install gh` ou usando o instalador disponível no site oficial

## 2. Autenticação
- `gh auth status`: Exibe informações sobre a sessão atual, incluindo o usuário autenticado e as permissões concedidas.
- `gh auth login`: Faz login na sua conta GitHub.
- `gh auth logout`: Desconecta a sessão atual do GitHub CLI.

## 3. Comandos Principais

### 3.1 Repositórios
- `gh repo`: Clonar, criar, listar, visualizar e gerenciar repositórios no GitHub.

### 3.2 Issues
- `gh issue`: Criar, visualizar, listar e gerenciar issues em um repositório.

### 3.3 Pull Requests
- `gh pr`: Criar, visualizar, listar e gerenciar pull requests.

### 3.4 Gists
- `gh gist`: Criar, visualizar e gerenciar Gists (compartilhamento de trechos de código ou arquivos).

### 3.5 Releases
- `gh release`: Criar, listar e gerenciar releases em um repositório.

### 3.6 Organizações
- `gh org`: Listar organizações, visualizar informações sobre uma organização específica e gerenciar afiliações.

### 3.7 Projetos
- `gh project`: Interagir com projetos no GitHub, usados para organizar e rastrear o trabalho.

## 4. Ferramentas e Funcionalidades Avançadas

### 4.1 Navegação e Acesso
- `gh browse`: Abre uma página específica do repositório atual no navegador.

### 4.2 Codespaces
- `gh codespace`: Interagir com GitHub Codespaces, incluindo criação, listagem, acesso e gerenciamento de codespaces.

### 4.3 Ações do GitHub (GitHub Actions)
- **Cache**
  - `gh cache`: Gerencia o cache de ações do GitHub, usado para armazenar artefatos de compilação e dependências.
  
- **Execuções**
  - `gh run`: Interagir com execuções de workflows (ações), permitindo visualizar, disparar, cancelar e gerenciar execuções.

- **Workflows**
  - `gh workflow`: Gerenciar e visualizar workflows de GitHub Actions.