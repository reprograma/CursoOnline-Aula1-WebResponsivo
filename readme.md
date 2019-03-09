# Workshop Online - Aula 1 - Web responsivo

### Design Responsivo, o que é ?
Design responsivo nada mais é, do que o site estar adaptado em várias telas e tentar atingir o máximo de dispositivos possíveis.
 Exemplo: uol.com.br
Se decidirmos trabalhar com design responsivo, então temos que usar o layoult fluído e a tag meta viewport

##### Tag meta view port
Importante utilizar a seguinte metatag antes do fechamento </head> 
Essa tag vai passar instruções para o browser renderizar o conteúdo do site conforme o tamanho do dispositivo.
```sh
 <meta name="viewport" content="width=device-width, initial-scale=1">
```

##### Layoult Fluído
É sair do mundo dos pixels e entrar no mundo maravilhoso que é a porcentagem

|Tamanho dos dispositvos|
|--------------|
|Mobile: 400px|
|Desktop: 1280px|
|Tablet: 768px|

##### Enfim e como utilizar o design responsivo ?

Através das media queries 

```css
@media(min-width: 368px) and (max-width:768px){
<!--código aqui-->
}
```
Leia-se minímo de 368px até o máximo de 768px 
Ou seja, indo de mobile até a medida de tablet 
