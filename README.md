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

## O que são **Branches**?

As **branches** (ou ramificações) no Git são como diferentes linhas de desenvolvimento dentro de um repositório. Elas permitem que você crie versões paralelas do seu código, onde você pode fazer alterações e testar novas ideias sem afetar o código principal. 

Por exemplo, você pode criar uma branch para testar um novo recurso ou uma funcionalidade e, caso funcione bem, pode mesclar essa branch de volta na `main` (ou qualquer outra branch principal). Se não funcionar, você pode simplesmente descartar a branch sem afetar o restante do projeto.

### Fluxo comum de uso de branches:

1. Cria-se uma branch para desenvolver novas funcionalidades ou realizar testes.  
2. Após finalizar o desenvolvimento e testar, você pode **mesclar** essas alterações de volta à branch principal (geralmente chamada de `main`).

Assim, **branches** ajudam a manter o código organizado e seguro, permitindo testar e desenvolver de maneira isolada, sem afetar a estabilidade do projeto principal.

## Conclusão

Esses são os comandos essenciais que você precisará para gerenciar e configurar seus repositórios Git de maneira eficaz.
