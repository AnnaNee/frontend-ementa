### Fundamentos do HTML e CSS > HTML > Tags básicas

# Tags básicas

## Tabela de conteúdos obrigatórios
0. [O que são](README.md)
1. [div](1.%20div.md)
2. [p](2.%20p.md)
3. [h1](3.%20h1.md)
4. [script](4.%20script.md)
5. [link](5.%20link.md)
6. [body](6.%20body.md)
7. [head](7.%20head.md)
8. [title](8.%20title.md)
9. [Exercícios](9.%20Exercícios.md)

## Tabela de conteúdos opcionais
1. Listas ordenadas
2. Listas não ordenadas
3. A tag `<span></span>`
4. Quebras de linha

## O que são

As tags HTML são responsáveis pela marcação do documento HTML. São elas quem vão definir quais conteúdos devem aparecer na nossa página, e algumas delas também podem dizer qual estilo esse conteúdo terá (tamanho, negrito, itálico etc).

Uma tag do HTML possui a seguinte forma:
1. Toda tag abre com `<>`;
2. Toda tag fecha com `</>`;
3. Toda tag tem um nome, que precede o símbolo de abertura de tag. Exemplo: `<div>`, onde o nome da tag é `div`;
4. A maioria das tags possuem um par que abre e outro que fecha. Exemplo: `<div>` e `</div>`;
5. Algumas outras tags HTML são _self-closing_ (auto-fechadas). Exemplo: `<img />`;
6. As tags podem conter atributos, que devem ficar dentro da tag de abertura. Exemplo: `<img src="">`, onde `src` é o nome do atributo e `""` é o valor;
7. Os atributos são compostos por chave e valor. O valor é entre aspas e pode ser vazio. Exemplo: `<input placeholder="Seu nome aqui">`;
8. Você pode aninhar tags (colocar uma dentro da outra), ou qualquer bloco de texto. Exemplo: `<div><img /></div>`, onde temos uma tag `img` dentro de uma tag `div`.

## Estrutura base de um HTML

```
<!DOCTYPE html>
<head>
  <title>Título do meu site</title>
  <script type="text/javascript" src="local/do/arquivo.js"></script>
  <link rel="stylesheet" href="estilos_daora.css">
</head>
<body>
  <h1>Que site daora!</h1>
  <p>Veja meu belo catálogo de presuntos.</p>
</body>
```
