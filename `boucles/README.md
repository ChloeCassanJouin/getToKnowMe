# Boucles en JavaScript

Les boucles permettent de répéter une action plusieurs fois.

---

## 🔁 Boucle for classique

```js
for (let i = 0; i < 5; i++) {
  console.log("Tour n°" + i);
}
🔎 Décryptage :
let i = 0 : on initialise un compteur i

i < 5 : tant que i est inférieur à 5, on continue

i++ : on augmente i de 1 à chaque tour

Résultat : affiche "Tour n°0", "Tour n°1", ..., jusqu’à "Tour n°4"

## 🔁 Boucle for...of
js
Copier
Modifier
const fruits = ["pomme", "banane", "cerise"];

for (const fruit of fruits) {
  console.log("Fruit : " + fruit);
}
🔎 Décryptage :
for...of parcourt chaque élément d’un tableau

À chaque tour, la variable fruit prend la valeur de l’élément suivant
