# GIT
## Primeira aula usando o Git - Atividades
### Nível 1
#### **Atividade 1.1 – Configurando o Git**

**📌 Cenário:**

Identifique-se no Git para associar seus commits ao seu nome e e-mail.

**📂 Instruções:**

1️⃣ Abra seu terminal.

2️⃣ Configure seu nome de usuário globalmente no Git.

3️⃣ Configure seu e-mail globalmente no Git.

**🔍 Pesquise:**

- Como configurar o nome de usuário no Git?
- Como configurar o e-mail no Git?

**✔️ Verifique:**

Pesquise como verificar suas configurações após os comandos.

**🎯 Desafio:**

Tente commitar sem configurar seu nome e e-mail. Observe a mensagem de erro.

---

#### ✅ **Atividade 1.2 – Criando seu Primeiro Repositório**

**📌 Cenário:**

Crie um novo projeto e versionamento com Git.

**📂 Instruções:**

1️⃣ Crie um novo diretório.

2️⃣ Navegue para dentro dele.

3️⃣ Inicialize um repositório Git.

4️⃣ Verifique se o repositório foi criado (procure pela pasta `.git`).

**🔍 Pesquise:**

- Como criar um diretório no terminal?
- Como navegar entre diretórios?
- Como inicializar um repositório Git?
- Como listar arquivos ocultos?

**✔️ Verifique:**

A pasta `.git` deve estar visível dentro do seu novo diretório.

**🎯 Desafio:**

Inicialize um repositório Git dentro de outro. Observe o resultado.

---

#### ✅ **Atividade 1.3 – Adicionando e Commitando Arquivos**

**📌 Cenário:**

Adicione arquivos e registre suas primeiras alterações.

**📂 Instruções:**

1️⃣ Crie um arquivo `meu_primeiro_arquivo.txt`.

2️⃣ Verifique o status do repositório.

3️⃣ Adicione o arquivo ao stage.

4️⃣ Verifique o status novamente.

5️⃣ Faça um commit com mensagem descritiva.

6️⃣ Confira o status mais uma vez.

**🔍 Pesquise:**

- Como criar arquivos via terminal?
- Como usar `git status`?
- Como adicionar arquivos ao stage?
- Como fazer commits com mensagem?

**✔️ Verifique:**

`git status` deve indicar que a árvore está limpa.

**🎯 Desafio:**

Modifique o arquivo após adicioná-lo ao stage. Como incluir as novas mudanças no mesmo commit?

---

#### ✅ **Atividade 1.4 – Visualizando o Histórico**

**📌 Cenário:**

Veja o histórico do seu projeto.

**📂 Instruções:**

1️⃣ No diretório do repositório Git.

2️⃣ Visualize o histórico de commits.

3️⃣ Experimente opções de exibição (curta/detalhada).

**🔍 Pesquise:**

- Como visualizar o histórico (`git log`)?
- Quais opções existem para formatar a saída?

**✔️ Verifique:**

Commits devem aparecer com mensagens, autor e data.

**🎯 Desafio:**

Veja apenas os últimos commits ou o histórico de um arquivo específico.
### Nível 2
#### ✅ **Atividade 2.1 – Criando e Trocando de Branches**

**📌 Cenário:**

Crie uma nova branch para um novo recurso sem misturar com a versão principal.

**📂 Instruções:**

1️⃣ Confira se está na branch principal (`main` ou `master`).

2️⃣ Crie uma nova branch (ex: `feature/nova-funcionalidade`).

3️⃣ Liste as branches para confirmar a criação.

4️⃣ Troque para a nova branch.

5️⃣ Verifique a branch atual.

6️⃣ Crie/modifique um arquivo nessa branch, adicione e commite.

7️⃣ Volte para a principal e verifique se a alteração não aparece.

**🔍 Pesquise:**

- Como ver a branch atual?
- Como criar branches?
- Como listar branches?
- Como mudar de branch?

**✔️ Verifique:**

A alteração feita na nova branch não deve aparecer na principal.

**🎯 Desafio:**

Crie uma branch com um nome já existente. Como criar e trocar para ela em um só comando?

---

#### ✅ **Atividade 2.2 – Realizando Merges Locais**

**📌 Cenário:**

Integre alterações de uma branch de recurso para a principal.

**📂 Instruções:**

1️⃣ Certifique-se de estar na branch principal.

2️⃣ Faça o merge da branch de recurso.

3️⃣ Confira o histórico.

4️⃣ Veja se as alterações foram integradas.

5️⃣ (Opcional) Pesquise como deletar a branch após o merge.

**🔍 Pesquise:**

- Como fazer merge no Git?
- Como deletar branches?

**✔️ Verifique:**

O conteúdo da branch de recurso deve estar na principal.

**🎯 Desafio:**

Qual a diferença entre **Fast-Forward merge** e **Non-Fast-Forward merge**?

---

#### ✅ **Atividade 2.3 – Resolvendo Conflitos de Merge (Simulado)**

**📌 Cenário:**

Simule e resolva um conflito de merge.

**📂 Instruções:**

1️⃣ Crie `branch-conflito-1` e modifique uma linha.

2️⃣ Commit.

3️⃣ Volte para a principal.

4️⃣ Crie `branch-conflito-2` e modifique a mesma linha com conteúdo diferente.

5️⃣ Commit.

6️⃣ Volte para a principal.

7️⃣ Faça o merge da `branch-conflito-1`.

8️⃣ Abra o arquivo e veja os marcadores (`<<<<<<<`, `=======`, `>>>>>>>`).

9️⃣ Resolva o conflito e remova os marcadores.

🔟 Adicione o arquivo ao stage e finalize o commit do merge.

**🔍 Pesquise:**

- Como o Git indica conflitos?
- Quais são os marcadores de conflito?
- Como finalizar o merge após resolver conflitos?

**✔️ Verifique:**

`git status` deve indicar merge concluído.

**🎯 Desafio:**

Qual a diferença entre `merge` e `rebase`?
