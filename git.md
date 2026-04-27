# Comandos Git

### ✔️ Adicionar os arquivos pela 1º vez:

1. git init  
2. git add .
3. git commit -m "feat: projeto inicial"
4. git remote add origin https://github.com/seu-usuario/nome-do-repo.git
5. git branch -M main 
6. git push -u origin main

### ✔️ Atualizar 
1. git status
2. git add .
3. git commit -m "feat: descreva o que você fez"
4. git push

### ✔️ Criar uma nova branch

- git checkout -b feat/estilizacao-inicial
- git add .
- git commit -m "feat: iniciar estilização do projeto"
- git push origin feat/estilizacao-inicial

> Tipo	Quando usar
- feat/nova funcionalidade
- fix/correção de erro
- style/visual/CSS
- chore/configuração
- refactor/melhoria de código
- docs/documentação

### ✔️ Atualizar uma branch 
1. git add .
2. git commit -m "feat: ajustar estilos"
3. git push origin feat/estilizacao-inicial


### ✔️ Fazer merge de várias branches na main

1. Ver todas as branches existentes: git branch

2. Atualizar informações do repositório: git fetch

3. Ir para a branch main: git checkout main

4. Atualizar a main: git pull origin main

5. Fazer merge de cada branch: 
git merge feat/login
git merge feat/estilizacao-inicial
git merge fix/navbar

6. Enviar main atualizada para o GitHub: git push origin main