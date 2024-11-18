## Guia Rápido de Comandos Git

**O que é Git?**

O Git é um sistema de controle de versão distribuído, essencial para o desenvolvimento de software. Imagine-o como um pedreiro que constrói e modifica uma casa (seu projeto). Cada tijolo colocado e cada mudança feita são registradas, permitindo que você volte no tempo e veja como a casa era em qualquer momento.

**Analogia da Construção:**

| Comando | Descrição | Exemplo |
|---|---|---|
| `git init` | Inicializa um novo repositório Git no diretório atual. | `git init` |
| `git add` | Marca arquivos para serem incluídos no próximo commit. | `git add index.html` |
| `git commit` | Salva as mudanças permanentemente. | `git commit -m "Adicionando nova funcionalidade"` |
| `git status` | Mostra o estado atual do repositório. | `git status` |
| `git branch` | Cria, lista ou deleta branches. | `git branch feature` |
| `git checkout` | Muda para um branch existente. | `git checkout feature` |
| `git merge` | Mescla as alterações de um branch em outro. | `git merge feature` |
| `git pull` | Baixa as alterações de um repositório remoto para o local. | `git pull origin main` |
| `git push` | Envia as alterações locais para um repositório remoto. | `git push origin main` |
| `git clone` | Clona um repositório existente para o seu computador. | `git clone https://github.com/user/repo.git` |
| `git rm` | Remove arquivos do repositório. | `git rm old_file.txt` |
| `git revert` | Desfaz um commit específico. | `git revert <commit-hash>` |
| `git reset` | Reverte para um estado anterior. | `git reset --hard HEAD~1` |
| `git stash` | Guarda as alterações temporariamente. | `git stash` |
| `git config` | Configura o Git. | `git config --global user.name "Seu Nome"` |
**Fluxos de Trabalho**

[Diagrama do Git Flow]

* **Git Flow:** Um modelo tradicional com branches para desenvolvimento, staging e produção.
* **GitHub Flow:** Um modelo mais simples e direto, focado em branches de features e pull requests.

**Dicas e Truques**

* **Aliases:** Crie atalhos para comandos longos: `git config --global alias.co checkout`
* **Hooks:** Automatize tarefas como formatação de código e testes.
* **Visualização:** Use ferramentas como o GitKraken para uma interface gráfica.

**Recursos Adicionais:**

* **Documentação oficial:** [link para a documentação do Git]
* **Tutoriais online:** [link para tutoriais interativos]

