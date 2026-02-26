# Comandos Básicos de Git Bash e Git



Este é meu primeiro repositório de estudos utilizando \*Git Bash\* e \*Git\*.  

Aqui reuni os principais comandos básicos que venho utilizando no dia a dia para praticar navegação no terminal e controle de versão.



O objetivo é consolidar minha base em ferramentas essenciais do fluxo de desenvolvimento.


### Comandos Git Bash (Básicos)
```
ls       # Lista arquivos e pastas <br>
ls -a    # Lista todos os arquivos (incluindo ocultos) <br>
pwd      # Mostra o caminho da pasta atual <br>
mkdir    # Cria uma nova pasta <br>
cat      # Mostra o conteúdo de um arquivo <br>
clear    # Limpa o terminal <br>
cd       # Entra em uma pasta <br>
cd ..    # Volta para a pasta anterior <br>
```

### Comandos Git (Básicos)
```
git init              # Inicia um repositório Git <br>
git status            # Mostra o estado atual do repositório <br>
git add .             # Adiciona todos os arquivos para commit <br>
git commit -m ""      # Cria um commit com mensagem <br>
git push              # Envia commits para o repositório remoto <br>
git pull              # Atualiza o repositório local <br>
git clone             # Clona um repositório remoto <br>
git log               # Mostra o histórico de commits <br>
git diff              # Mostra as mudanças antes do commit <br>
git branch            # Lista as branches <br>
git branch nome       # Cria uma nova branch <br>
git branch -d nome    # Deleta uma branch local <br>
git checkout nome     # Muda para outra branch <br>
git checkout -b nome  # Cria e já muda para a branch <br>
git merge nome        # Junta a branch 'nome' na branch atual
```
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

*Objetivo:* servir como guia rápido (cheat sheet) e registrar minha evolução no uso de Git e terminal.

 Em constante aprendizado.