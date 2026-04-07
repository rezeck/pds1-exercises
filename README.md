# PDS I — Exercícios (DCC/UFMG)

Repositório com **exercícios em HTML** para a disciplina *Programação e Desenvolvimento de Software I*, ofertada pelo Departamento de Ciência da Computação da UFMG.

**Professor:** Paulo Rezeck.

## Conteúdo

| Aula | Tema | Página |
|------|------|--------|
| 07 | Ponteiros, bits e memória | [`docs/aula07/index.html`](docs/aula07/index.html) |
| 08 | Processamento condicional | [`docs/aula08/index.html`](docs/aula08/index.html) |

A **página inicial** que lista os links está em [`docs/index.html`](docs/index.html).

## Publicar no GitHub Pages

Para os alunos acessarem pelo navegador (sem clonar o repositório):

1. Crie o repositório no GitHub e envie este projeto (`git init`, `git add`, `git commit`, `git remote`, `git push`).
2. No GitHub: **Settings** → **Pages**.
3. Em **Build and deployment** → **Source**, escolha **Deploy from a branch**.
4. Selecione o branch (geralmente `main` ou `master`) e a pasta **`/docs`**. Salve.

Após alguns minutos, o site ficará disponível em:

**`https://<seu-usuario>.github.io/<nome-do-repositorio>/`**

Exemplo: se o usuário for `prezeck` e o repositório `pds1-exercises`, o endereço será:

`https://prezeck.github.io/pds1-exercises/`

A página principal dos exercícios é a raiz do site (o `index.html` dentro de `docs/`).

### Observação

O arquivo `docs/.nojekyll` evita que o GitHub Pages processe o site com Jekyll, o que é adequado para estes arquivos estáticos.

## Estrutura do repositório

```
docs/
  index.html          # índice público (landing)
  .nojekyll
  aula07/index.html   # exercícios da aula 07
  aula08/index.html   # exercícios da aula 08
```

Para incluir novas aulas no futuro, adicione `docs/aulaNN/index.html` e um cartão correspondente em `docs/index.html`.
