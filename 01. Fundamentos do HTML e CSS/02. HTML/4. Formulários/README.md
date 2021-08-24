### Fundamentos do HTML e CSS > HTML > Formulários

# Formulários

## Tabela de conteúdos obrigatórios
0. [O que são](README.md)
1. [form](1.%20form.md)
2. [input](2.%20input.md)
3. [placeholders](3.%20placeholders.md)
4. [checkbox](4.%20checkbox.md)
5. [radio buttons](5.%20radio%20buttons.md)
6. [buttons](6.%20buttons.md)
7. [Exercícios](7.%20Exercícios.md)

## Tabela de conteúdos opcionais
1. Botões com a tag `<button></button>`
2. Múltiplos grupos de botões `radio`
3. Inputs do tipo `<textarea></textarea>`

## O que são

Formulários HTML são um dos principais pontos de interação entre um usuário e um web site ou aplicativo. Eles permitem que os usuários enviem dados para o web site. Na maior parte do tempo, os dados são enviados para o servidor da web, mas a página da web também pode interceptar para usá-los por conta própria.

Um formulário HTML é feito de um ou mais widgets. Esses widgets podem ser campos de texto (linha única ou de várias linhas), caixas de seleção, botões, checkboxes ou radio buttons. A maior parte do tempo, estes elementos são emparelhados com uma legenda que descreve o seu objetivo.

## Estrutura base de um formulário

```
<form action="/pagina-processa-dados-do-form" method="post">
  <div>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" />
  </div>
  <div>
    <label for="email">E-mail:</label>
    <input type="email" id="email" />
  </div>
  <div>
    <label for="msg">Mensagem:</label>
    <textarea id="msg"></textarea>
  </div>
  <div class="button">
    <button type="submit">Enviar sua mensagem</button>
  </div>
</form>
```
