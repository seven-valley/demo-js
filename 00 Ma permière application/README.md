# 1 - Les variables
```js
 const pi= 3.14;
 const personne ={nom:'Brad',prenom:'PITT'};
 const fruits =['pomme','poire','cerise'];
 let x = 2;
```
## La portée limitée du let
```js
let age = 18
 if (age >18){
    let info ='ok';
 }
 console.log(info);
 for (let i=0;i < 3;i++){
    console.log(i);
 }
 console.log(i);
```


# 2- Lecture dans le DOM
```html
<div id="demo">Ola</div>

<script>
    // lecture
    let str = document.getElementById('demo').innerHTML;
    console.log(str);
</script>
```

# 3 - Ecriture dans le DOM
```html
<div id="demo">Ola</div>

<script>
    // ecriture
    document.getElementById('demo').innerHTML = 'Coucou !!!';
</script>
```

# 4 - Le trigger ou le bouton
```html
<button onclick="afficher()">GO</button>
<script>
function afficher(){
   console.log('afficher');
}
</script>
```
# 5 -Lecture de la saisie utilisateur
```html
<input id="nom" placeholder="Votre Prénom ICI">
<br><br>
<button onclick="afficher()">GO</button>
<script>
function afficher(){
    // lecture
    let info = document.getElementById('nom').value;
    console.log(info);
}
</script>
```
