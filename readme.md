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
------
##### Layoult Fluído
É sair do mundo dos pixels e entrar no mundo maravilhoso que é a porcentagem

|Tamanho dos dispositvos|
|--------------|
|Mobile: 368px|
|Desktop: 1280px|
|Tablet: 768px|

##### Lembrando sempre que são medidas relativas, o cenário de medidas está variando muito 😊

----------

##### Enfim e como utilizar o design responsivo ?🤔

Através das media queries 

```css
@media(min-width: 368px) and (max-width:768px){
<!--código aqui-->
}
```
#### Leia-se minímo de 368px até o máximo de 768px. Ou seja, indo do modo mobile até tablet
---------
### Para dar aquele help

* Alguns links úteis: https://bit.ly/2SZFvCW
* Método bem: https://tableless.com.br/bem-um-novo-metodo-para-seu-css/
* Site para  ícones fofos: https://www.flaticon.com/
* Para pegar aquelas imagens dignas de aplausos: https://unsplash.com/
