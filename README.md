# NodeProp - Soluções Digitais

> Projeto de design responsivo aplicando o conceito de Mobile First utilizando CSS3 puro (sem framework) e consumindo biblioteca o JQuery para exibir e ocultar o menu mobile.

<p align="center">
  <img src="img/mockup.PNG" alt="Telas responsivas"/>
</p>

<p align="center"> <!-- Não funciona no escopo acima, por isso tem seu próprio  -->
  Mockup obtido em <a href="https://br.freepik.com/">Freepik</a>
</p>

## Menu mobile

Importanto o [JQuery](https://code.jquery.com/).
```html
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
```

Foram usados os métodos `show()` e `hide()` para o menu mobile.
```html
<script>
  $(".btn-menu").click(function () {
    $(".menu").show(); //Exibe os itens do menu.
  });
  
  $(".btn-close").click(function () {
    $(".menu").hide(); //Oculta os itens.
  });
</script>
```
