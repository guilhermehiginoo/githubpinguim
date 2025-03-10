# Guia de Comandos Git

Este é um resumo dos comandos Git utilizados durante a aula. Ele contém os comandos básicos de Git, suas funções e como configurar repositórios.

## Comandos Básicos

### 1. **Inicialização de Repositório**

- **`git init`**  
  Inicializa um repositório Git vazio no diretório atual.
  
- **`echo README.md > README.md`**  
  Cria um arquivo `README.md` (usado para inicializar o repositório com informações básicas).

### 2. **Verificação de Status**

- **`git status`**  
  Exibe o status atual do repositório, incluindo alterações no diretório de trabalho e no índice.

- **`git status -sb`**  
  Exibe o status de forma resumida e mais compacta, mostrando apenas as informações mais importantes.

### 3. **Commit**

- **`git commit -m "comentário"`**  
  Cria um commit com a mensagem fornecida, registrando as alterações realizadas.

### 4. **Configuração do Git**

- **`git config --global push.autoSetupRemote true`**  
  Configura o Git para, automaticamente, associar o repositório remoto ao repositório local durante o `git clone`.

- **`git config push.default current`**  
  Configura o comportamento de `git push` para enviar apenas a branch atual para o repositório remoto.

### 5. **Obtenção e Envio de Informações**

- **`git pull`**  
  Obtém as alterações do repositório remoto e as integra ao repositório local. 

- **`git push`**  
  Envia as alterações do repositório local para o repositório remoto.

### 6. **Outros Comandos Importantes**

- **`git log`**  
  Exibe o histórico de commits no repositório, mostrando informações como o autor e a mensagem do commit.

- **`git diff`**  
  Exibe as diferenças entre o diretório de trabalho e o índice (ou entre commits).

- **`git branch`**  
  Lista as branches disponíveis ou cria uma nova branch.

- **`git checkout <branch>`**  
  Alterna para a branch especificada.

- **`git merge <branch>`**  
  Mescla as alterações de uma branch para a branch atual.
