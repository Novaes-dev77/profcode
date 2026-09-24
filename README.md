# ProfCode

Site do projeto **ProfCode** — página para divulgação das aulas de programação
da Prof. Ada Barros, desenvolvido para a atividade de Git/GitHub/GitHub Pages
da disciplina **Desenvolvimento Front-End para Web**.

## Páginas

- `index.html` — Home
- `musicas.html` — Músicas para estudar
- `contato.html` — Entre em contato (formulário)
- `videos.html` — Vídeos sobre programação
- `disciplinas.html` — Disciplinas ministradas

## Estrutura

```
profcode/
├── index.html
├── musicas.html
├── contato.html
├── videos.html
├── disciplinas.html
├── css/
│   └── style.css
├── js/
│   └── contato.js
└── img/
    ├── prof-ada.svg
    ├── aula-code.svg
    ├── estudo-musica.svg
    ├── videos-tutorial.svg
    └── favicon.svg
```

## Publicando no GitHub Pages

1. Crie um repositório público chamado `profcode` no GitHub.
2. Suba todos os arquivos deste projeto para o repositório (`git add .`,
   `git commit -m "primeira versão do site"`, `git push`, ou pelo Upload Files
   do próprio GitHub).
3. Em **Settings > Pages**, defina a branch `main` e a pasta `/ (root)` como
   fonte e clique em **Save**.
4. Aguarde alguns minutos: o site ficará disponível em
   `https://SEU-USUARIO.github.io/profcode/`.

## Observações

O formulário de contato valida os campos e mostra uma confirmação em tela,
mas não envia e-mails de verdade — este é um site estático hospedado no
GitHub Pages, sem servidor.
