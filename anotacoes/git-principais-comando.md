# 📘 Principais Comandos do Git

Este arquivo reúne os comandos essenciais do Git utilizados no dia a dia de um desenvolvedor.

---

## Configuração Inicial

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
git config --list
```

## 2. Criação e inicialização de repositório



```bash
git init

```

-   **Finalidade:** Cria um repositório Git local na pasta atual. Usado ao iniciar um projeto do zero.

## 3. Verificação de status e histórico

```bash
git status         # Mostra arquivos modificados, adicionados ou pendentes
git log            # Exibe o histórico de commits
git log --oneline  # Histórico resumido (muito usado no dia a dia)

```

## 4. Ciclo básico de versionamento (ESSENCIAL)

**Fluxo clássico:** editar → `git add` → `git commit`

```bash
git diff                   # Ver alterações feitas
git add arquivo.js         # Adicionar arquivo específico para commit
git add .                  # Adicionar todos os arquivos
git commit -m "Mensagem"   # Criar um commit com mensagem clara

```

## 5. Trabalhando com branches

```bash
git branch                 # Lista branches locais
git branch nome-branch     # Cria uma branch
git checkout nome-branch   # Troca de branch
git checkout -b nome-branch # Cria e já troca para a branch
git merge nome-branch      # Mescla uma branch na atual

```

## 6. Repositórios remotos (GitHub, GitLab, etc.)

```bash
git remote add origin URL  # Conectar repositório remoto
git push origin main       # Enviar código para o remoto
git pull                   # Baixar atualizações
git clone URL              # Clonar um repositório existente

```

## 7. Desfazendo erros (MUITO IMPORTANTE)

```bash
git restore --staged arquivo.js  # Remover arquivo do stage
git restore arquivo.js           # Desfazer alterações locais
git reset --hard HASH_COMMIT     # Voltar para um commit anterior (com cuidado)

```

## 8. Comandos úteis no dia a dia

```bash
git stash      # Guarda alterações temporariamente
git stash pop  # Recupera alterações guardadas
git show       # Mostra detalhes de um commit

```

----------

## 9. Comandos que um FullStack Júnior DEVE saber

Se você souber usar bem estes, já está acima da média:

-   `git init`
    
-   `git status`
    
-   `git add`
    
-   `git commit`
    
-   `git log`
    
-   `git branch`
    
-   `git checkout -b`
    
-   `git merge`
    
-   `git pull`
    
-   `git push`
    
-   `git clone`