# Les variables
```js
 const pi= 3.14;
 const personne ={nom:'Brad',prenom:'PITT'};
 const fruits =['pomme','poire','cerise'];
 let x = 2;
```
## La portée limité du let
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


# Lecture dans le DOM
```html
<div id="demo">Ola</div>

<script>
    // lecture
    let str = document.getElementById('demo').innerHTML;
    console.log(str);
</script>
```

# Ecriture dans le DOM
```html
<div id="demo">Ola</div>

<script>
    // ecriture
    document.getElementById('demo').innerHTML = 'Coucou !!!';
</script>
```

# Le trigger ou le boutton
```html
<button onclick="afficher()">GO</button>
<script>
function afficher(){
   console.log('afficher');
}
</script>
```

