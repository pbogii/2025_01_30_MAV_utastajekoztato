## MÁV utastájékoztató

Ez a projekt egy egyszerű táblázat amelyet **HTML** és **CSS** segítségével hoztam létre. Könnyen kezelhető és átlátható ezmiatt felhasználó barát. ٩(◕‿◕｡)۶


### Funkciók (*≧ω≦*)	
- vonatok indulása, érkezése
- állomások, vonatok indulási vágányának száma
- letisztult, egyszerű kinézet

### Használat
Megnyitható a : `https://pbogii.github.io/2025_01_30_MAV_utastajekoztato/` linken. Egyszerűen eligazodható, átlátható weboldal. (*￣▽￣)b
#### Élő demó (ﾉ◕ヮ◕)ﾉ*:･ﾟ✧

A projekt élőben kipróálható az alábbi linken:  
[ MÁV Utastájékoztató](https://pbogii.github.io/2025_01_30_MAV_utastajekoztato/)

### Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>MÁV Utastájékoztató</h1>
    <table>
        <tr>
            <th>Vonatszám</th>
            <th>Indulás</th>
            <th>Érkezés</th>
            <th>Állomás</th>
        </tr>
        <tr>
            <td>1234</td>
            <td>12:30</td>
            <td>14:00</td>
            <td>Budapest</td>
        </tr>
    </table>
</body>
</html>
```

## CSS Stílusok
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f8f9fa;
    text-align: center;
}

table {
    width: 80%;
    margin: 20px auto;
    border-collapse: collapse;
}
```

### Fejlesztési lehetőségek
- [ ] Igaz adatok lekérése és ezeknek időhöz fűzött megjelenítése
- [ ] Keresési és szűrési lehetőségek mint pl.: menetrendek.hu-n
- [x] Interaktívabb megjelenés

