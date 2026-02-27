# Comandos Básicos de Git Bash e Git



Este é meu primeiro repositório de estudos utilizando \*Git Bash\* e \*Git\*.  

Aqui reuni os principais comandos básicos que venho utilizando no dia a dia para praticar navegação no terminal e controle de versão.

O objetivo é consolidar minha base em ferramentas essenciais do fluxo de desenvolvimento.


### Comandos Git Bash (Básicos)
```
ls       # Lista arquivos e pastas 
ls -a    # Lista todos os arquivos (incluindo ocultos) 
pwd      # Mostra o caminho da pasta atual 
mkdir    # Cria uma nova pasta 
cat      # Mostra o conteúdo de um arquivo 
clear    # Limpa o terminal 
cd       # Entra em uma pasta 
cd ..    # Volta para a pasta anterior 
```

### Comandos Git (Básicos)
```
git init              # Inicia um repositório Git 
git status            # Mostra o estado atual do repositório
git add .             # Adiciona todos os arquivos para commit
git commit -m ""      # Cria um commit com mensagem

git fetch             # Busca atualizações do repositório remoto (sem alterar sua branch atual)
git pull              # Baixa e já integra as atualizações do repositório remoto
git push              # Envia commits para o repositório remoto

git clone             # Clona um repositório remoto
git log               # Mostra o histórico de commits
git diff              # Mostra as mudanças antes do commit

git branch            # Lista as branches
git branch nome       # Cria uma nova branch
git branch -d nome    # Deleta uma branch local
git checkout nome     # Muda para outra branch
git checkout -b nome  # Cria e já muda para a branch
git merge nome        # Junta a branch 'nome' na branch atual
```
### Organização das Branches

<p align="left">
  <img src="https://github.com/user-attachments/assets/0193f997-a1d2-4591-8321-5ee2753c580f" width="500" />
</p <br>

### Tipos de Commit (Conventional Commits)
```
feat:     desenvolvimento de nova funcionalidade
fix:      correção de bug
docs:     mudanças na documentação
style:    ajustes de formatação (sem alterar lógica)
refactor: refatoração sem nova funcionalidade ou correção
perf:     melhoria de performance
test:     criação ou correção de testes
```
