# Projeto Git: Ferramentas de Qualidade de Software

Página HTML estática desenvolvida na prática **Primeiros Passos com Git** da disciplina de
Qualidade de Software (Sistemas de Informação, UFSM, Prof. Joel da Silva).

A página apresenta ferramentas de qualidade de software. O repositório exercita o fluxo completo de
gerência de configuração: commits, issue, branch, pull request, pipeline de integração contínua,
tag de versão e publicação automatizada.

> Adaptação: a prática original usa GitLab. Aqui foi usado o GitHub. Equivalências:
> Merge Request → Pull Request, `.gitlab-ci.yml` → GitHub Actions, GitLab Pages → GitHub Pages.

## Página publicada

https://renatopiovesan.github.io/projeto-git/

Publicada automaticamente pelo GitHub Actions a cada push na `main`, depois que o job
`validate-html` passa.

## Estrutura

```
projeto-git/
├── .github/workflows/pages.yml   # pipeline: validação + publicação
├── public/
│   ├── index.html
│   └── style.css
├── .gitignore
└── README.md
```

## Execução

Não há dependências. Para visualizar localmente, abra `public/index.html` no navegador.

Para clonar:

```bash
git clone https://github.com/renatopiovesan/projeto-git.git
cd projeto-git
```
