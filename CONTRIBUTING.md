# Como atualizar sua página pessoal no site do Observatório Oceanográfico

Este site é mantido via GitHub.  
Nenhuma alteração deve ser feita diretamente no repositório principal.

Cada aluno deve editar sua própria página pessoal, enviar as alterações para o seu **fork** e abrir um **Pull Request** para revisão.

---

## 1. Criar uma conta no GitHub

Se você ainda não tem conta no GitHub:

1. Acesse https://github.com
2. Crie sua conta
3. Use preferencialmente um nome de usuário profissional, algo que *lembre* você diretamente, como seu nome ou uma combinação do seu nome e sobrenome. (por exemplo, o meu é andrebelem, que é igual a minha conta id.uff.br)
4. Confirme seu e-mail

Depois disso, envie seu usuário do GitHub para o responsável pelo site (andrebelem@id.uff.br).

---

## 2. Acessar o repositório do site

Acesse o repositório principal do site:

https://github.com/observatorio-oceanografico/observatorio-oceanografico.github.io

Este é o repositório oficial.  
Você não deve editar diretamente nele.

---

## 3. Criar um fork

No GitHub:

1. Acesse o repositório oficial
2. Clique em **Fork**
3. Crie uma cópia do repositório na sua própria conta

O seu fork ficará em um endereço parecido com:

https://github.com/**SEU-USUARIO**/observatorio-oceanografico.github.io

---

## 4. Editar sua página pelo GitHub

Depois de criar o fork, acesse o repositório copiado na sua conta.

O endereço será parecido com:

https://github.com/**SEU-USUARIO**/observatorio-oceanografico.github.io

No seu fork, entre na pasta: *_pages/equipe/*

Procure o arquivo correspondente ao seu nome.

Exemplo: *_pages/equipe/maria-silva.md*

Se o seu arquivo ainda não existir, avise o responsável pelo site antes de criar um novo.

---

## 5. Fazer a edição do arquivo

Clique no arquivo da sua página pessoal. Depois clique no ícone de lápis, no canto superior direito, para editar. Faça apenas as alterações necessárias na sua própria página.

Você pode atualizar, por exemplo:

- formação;
- vínculo com o laboratório;
- projeto atual;
- interesses de pesquisa;
- links para Lattes, ORCID, GitHub ou e-mail institucional;
- pequena descrição pessoal/profissional.

Não altere páginas de outras pessoas.
Não altere arquivos de configuração do site. Porém, se você quiser atualizar a foto, pode enviar a imagem para a pasta de imagens e depois atualizar o link na sua página pessoal. A pasta de imagens está em *assets/img/equipe/*

---

## 6. Salvar a alteração no seu fork

Ao final da página, o GitHub mostrará a área **Commit changes**.
No campo de mensagem, escreva algo simples: *Atualiza perfil de Maria Silva*
Depois selecione a opção para **criar uma nova branch**, se o GitHub oferecer essa alternativa.
Use um nome simples para a branch, por exemplo: *atualiza-perfil-maria-silva*

Clique em: *Commit changes*

---

## 7. Abrir o Pull Request

Depois de salvar a alteração, o GitHub normalmente mostrará um botão: *Compare & pull request*
Clique nele.
Confira se o Pull Request está indo: do seu fork para o repositório oficial do Observatório Oceanográfico.

O destino correto deve ser: *observatorio-oceanografico/observatorio-oceanografico.github.io*

No título do Pull Request, escreva: *Atualiza perfil de Maria Silva*

Na descrição, escreva algo simples: *Atualizei minha página pessoal na seção da equipe.*

Depois clique em: *Create Pull Request*

---

## 8. Padrão básico do perfil

Note que se essa é a primeira vez que você está criando uma página pessoal, o início do arquivo deve ter um bloco chamado `front matter`.

Exemplo:

---
title: "Maria Silva"
permalink: /equipe/maria-silva/
layout: single
author_profile: true
---

Depois disso, escreva o conteúdo em Markdown.

Exemplo:

## Formação

Graduanda em Oceanografia pela Universidade Federal Fluminense.

## Atuação no Observatório Oceanográfico

Atua em atividades relacionadas ao processamento de dados oceanográficos, organização de bases ambientais e apoio a projetos de pesquisa do laboratório.

## Interesses

- Oceanografia costeira
- Mudanças climáticas
- Sensoriamento remoto
- Análise de dados ambientais

## Links

- Lattes: https://lattes.cnpq.br/XXXXXXXXXXXX
- ORCID: https://orcid.org/XXXX-XXXX-XXXX-XXXX
- GitHub: https://github.com/usuario

---

## 11. Cuidados ao escrever

Use texto curto, claro e objetivo.

A página pessoal não deve ser um currículo completo.  
Ela deve apresentar quem você é, o que faz no grupo e quais são seus principais interesses acadêmicos.

Evite:

- textos muito longos;
- linguagem informal demais;
- emojis;
- excesso de links;
- imagens muito grandes;
- copiar e colar o currículo inteiro do Lattes.

Prefira:

- parágrafos curtos;
- listas simples;
- informações verificáveis;
- links oficiais.

---

## 12. Adicionar ou trocar foto

Só adicione foto se houver orientação específica.

Em geral, imagens devem ficar em uma pasta como:

assets/img/equipe/

Use nomes simples:

maria-silva.jpg

Evite imagens muito grandes.  
Antes de enviar, reduza a imagem para um tamanho adequado para web.

Sugestão:

- formato: `.jpg` ou `.png`;
- largura: até 800 px;
- nome do arquivo sem acentos, espaços ou caracteres especiais.

---

## Aguardar revisão

Depois de abrir o Pull Request, aguarde revisão.

O responsável pelo site poderá:

- aprovar;
- pedir ajustes;
- comentar alguma parte do texto;
- corrigir algum detalhe técnico;
- solicitar que você faça novas alterações.

Se forem solicitadas mudanças, faça os ajustes na mesma branch. O Pull Request será atualizado automaticamente.

---
## Agradecimento
Agradecemos a sua contribuição para manter o site do Observatório Oceanográfico atualizado e informativo!