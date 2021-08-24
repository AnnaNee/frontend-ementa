### Fundamentos do HTML e CSS > HTML > Tabelas

# Tabelas

## Tabela de conteúdos obrigatórios
0. [O que são](README.md)
1. [thead](1.%20thead.md)
2. [tbody](2.%20tbody.md)
3. [td](3.%20td.md)
4. [tr](4.%20tr.md)
5. [th](5.%20th.md)
6. [Exercícios](6.%20Exercícios.md)

## O que são

As tabelas são listas de dados em duas dimensões e são compostas por linhas e colunas. Portanto, são muito utilizadas para apresentar dados de uma forma organizada. Um grande exemplo de como as tabelas são importantes é o crescente uso do programa Excel, requisito obrigatório de seleção para muitas empresas.

## Estrutura base de uma tabela

```
<table>
   <thead>
     <tr>
         <th>Presunto 1</th>
         <th>Presunto 2</th>
         <th>Presunto 3</th>
     </tr>
   </thead>
   <tbody>
     <tr>
         <td>Corpo1 linha1</td>
         <td>Corpo2 linha1</td>
         <td>Corpo3 linha1</td>
     </tr>
     <tr>
         <td>Corpo1 linha2</td>
         <td>Corpo2 linha2</td>
         <td>Corpo3 linha2</td>
     </tr>
   </tbody>
   <tfoot>
       <td>Rodapé 1</td>
       <td>Rodapé 2</td>
       <td>Rodapé 3</td>
   </tfoot>
</table>
```
