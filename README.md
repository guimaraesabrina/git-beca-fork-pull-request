# Exercício Prático - Colaboração no Git 🤝

## Objetivo

O objetivo deste exercício é permitir que os alunos pratiquem o processo de colaboração usando o Git. Eles realizarão um fork de um repositório, criarão um arquivo, darão push para sua própria versão do repositório e, em seguida, abrirão um merge request para incorporar suas alterações ao repositório principal.

## Passos

### 1. Faça um Fork do Repositório

1. Faça um fork desse repositório :)

### 2. Clone o Repositório Forked

```bash
git clone <URL_do_seu_fork>
```

### 3. Crie uma Nova Branch (Opcional)

```bash
git checkout -b nome_da_sua_branch
```

*Nota: Criar uma nova branch é uma prática recomendada, mas opcional neste caso.*

### 4. Adicione Seu Arquivo

Crie um novo arquivo no formato Markdown (`.md`). Pode ser uma breve introdução sobre você, suas habilidades, ou qualquer coisa relevante ao exercício.

```bash
touch seu_nome.md
```

### 5. Adicione, Faça o Commit e Dê Push

```bash
git add seu_nome.md
git commit -m "Adicionando meu arquivo"
git push origin nome_da_sua_branch
```

### 6. Abra um Merge Request

1. Vá até o seu repositório forked no GitHub.
2. Clique em "New Pull Request".
3. Selecione a branch que você acabou de criar.
4. Adicione uma descrição para o seu Pull Request.
5. Clique em "Create Pull Request".

## Dúvida Comum

**Dúvida: Cada aluno precisa criar uma branch nova para isso?**

Não é obrigatório, mas é uma prática recomendada. Usar branches separadas ajuda a organizar melhor as contribuições e evita conflitos desnecessários. Se você estiver trabalhando em equipe, cada membro pode criar sua própria branch para realizar as alterações. Entretanto, em projetos pequenos ou exercícios simples, todos podem trabalhar na branch principal. Certifique-se de discutir e decidir sobre a abordagem adequada para o projeto específico.
