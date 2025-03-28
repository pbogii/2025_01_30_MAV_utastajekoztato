## MÁV utastájékoztató

Ez a projekt egy egyszerű táblázat amelyet **HTML** és **CSS** segítségével hoztam létre. Könnyen kezelhető és átlátható ezmiatt felhasználó barát. ٩(◕‿◕｡)۶


### 📌 Funkciók
- 🚉 Induló és érkező vonatok listázása táblázatban
- ⏰ Állomás, indulási és érkezési idők megjelenítése
- 🎨 Felhasználóbarát, letisztult dizájn

### 🚀 Használat
Egyszerűen nyisd meg a `https://github.com/pbogii/2025_01_30_MAV_utastajekoztato` weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.
#### 🌍 Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[🔗 MÁV Utastájékoztató](https://github.com/pbogii/2025_01_30_MAV_utastajekoztato)

### 🏗️ Alap HTML szerkezet
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

## 🎨 CSS Stílusok
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

### 🔧 Fejlesztési lehetőségek
- [ ] 🔄 Dinamikus adatbetöltés API-n keresztül
- [ ] 🔍 Keresési és szűrési lehetőségek
- [x] 📱 Reszponzív megjelenítés mobileszközökre

