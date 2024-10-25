# 1 - Création de balises
```html
<div id="demo"></div>
<button id="btnGo">GO</button>
<script>
document.getElementById('btnGo').onclick = () =>{
    // créer une balise <p></p>
    let p = document.createElement('p'); 
    //<p>Brad PITT</p>
    p.innerHTML = 'Brad PITT';  
    // ajouter une balise dans une autre
    document.getElementById('demo').appendChild(p);
    console.log("abc");
}
</script>
```
# Résultat :
```html
<div id="demo">
    <p>Brad PITT</p>
    <p>Brad PITT</p>
    <p>Brad PITT</p>
</div>
```