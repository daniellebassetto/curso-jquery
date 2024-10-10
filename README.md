# Respositórios das Aulas de JQuery

## 🔗 Links úteis
📽️ [Playlist do Curso de JQuery do CBF Cursos](https://www.youtube.com/playlist?list=PLx4x_zx8csUiOBWiybY2cIjhNLIUn4JCn)

📘 [Link da documentação](https://jquery.com/)

🖇️ [Link do CDN](https://releases.jquery.com/)

## 🤔 O que é o JQuery?
**jQuery** é uma biblioteca JavaScript rápida e leve, criada para simplificar a manipulação de elementos HTML, eventos, animações e interações em páginas da web. 
Ela foi lançada em 2006 e ganhou popularidade rapidamente por facilitar o desenvolvimento de scripts que antes exigiam mais código com JavaScript puro. 
Seu lema é "Write less, do more" (Escreva menos, faça mais), destacando seu objetivo de reduzir a quantidade de código necessária para tarefas comuns.

Embora frameworks mais recentes, como React, Angular e Vue.js, tenham reduzido a popularidade do jQuery, ele ainda é amplamente usado em muitos projetos 
legados ou em sites que não precisam de uma estrutura mais complexa.

## 🧐 Principais Benefícios
O lema do jQuery é **"Write less, do more"** (Escreva menos, faça mais), destacando seu objetivo de **reduzir a quantidade de código necessária** para realizar tarefas comuns. Com o jQuery, você pode:

- **Selecionar e manipular elementos DOM** com facilidade.
- **Lidar com eventos** como cliques e mudanças de elementos de formulário.
- **Criar animações e efeitos visuais** com poucos comandos.
- **Realizar requisições AJAX** para carregar dados de forma assíncrona e melhorar a experiência do usuário.

## Exemplo de Uso JS puro vs JQuery

```javascript
// Selecionar o botão pelo ID
var button = document.getElementById('myButton');

// Adicionar um listener de evento de clique
button.addEventListener('click', function() {
    // Alterar o texto do botão
    button.textContent = 'Clicado!';
});
```

```javascript
// Selecionar o botão pelo ID e adicionar o evento de clique
$('#myButton').click(function() {
    // Alterar o texto do botão
    $(this).text('Clicado!');
});
```
