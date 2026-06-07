# Gerador de Senha

Projeto de formulário de cadastro com gerador de senhas seguras integrado, desenvolvido com HTML, CSS e JavaScript puro.

## Funcionalidades

- Formulário de cadastro com campos de nome, e-mail, senha e confirmação de senha
- Gerador de senhas com opções configuráveis:
  - Quantidade de caracteres
  - Inclusão de letras (maiúsculas e minúsculas)
  - Inclusão de números
  - Inclusão de símbolos (`(){}[]=></,.!@#$%&*-+`)
- Botão de copiar a senha gerada para a área de transferência
- Painel do gerador abre e fecha ao clicar no link

## Tecnologias

- HTML5
- CSS3 (Flexbox, Google Fonts: Montserrat e Inter)
- JavaScript (Vanilla JS, Clipboard API)

## Como usar

1. Clone o repositório ou baixe os arquivos
2. Abra o arquivo `index.html` no navegador
3. No formulário de cadastro, clique em **"Clique aqui"** para abrir o gerador de senhas
4. Configure as opções desejadas e clique em **"Criar senha"**
5. Copie a senha gerada e utilize no campo de senha do formulário

## Estrutura do projeto

```
password_generator/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
└── img/
    └── bg-form.jpg
```
