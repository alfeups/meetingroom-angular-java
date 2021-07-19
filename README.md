# Meeting room desenvolvido com Angular e Java.
<p> Projeto proposto pela Digital Innovation One e apresentado pela Kamila Santos.</p><br/>

# Requisitos básicos:
<li>Spring Initialzr (Spring Web; Spring Data JPA; H2 Database; Lombok);
<li>IntelliJ ou IDE da sua escolha para trabalhar com Java;
<li>JDK;
<li>Angular;

``` sudo apt install -g @Angular/cli ```

<li>VS code;
<li>Bootstrap;

``` npm install bootstrap jquery --save ``` 

<li>NodeJS;

``` sudo apt install nodejs ```

<li>npm;

``` sudo apt install npm ```

<li>JQuery;



# Possiveis erros no processo

## Bootstrap no node_modules faltando:

``` npm install --save bootstrap ```

``` and then add in angular.json at "styles": ```

``` "node_modules/bootstrap/dist/css/bootstrap.min.css" ```

<p> Run the Project (Watch if youre in the right folder you can check it with typing in terminal ls and and then you should see node_modules, src etc.)</p>

``` ng serve ```

## Desabilitar o strictPropertyInitialization

<p> O strictPropertyInitialization obriga a inicializar as propriedades que não são opcionais, portanto, ir em 'tsconfig.json' e adicionar no campo "angularCompilerOptions": {... </p> 

``` "strictPropertyInitialization": false ``` 

