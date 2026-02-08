<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lar Fresh</title>
  <style>
    body { font-family: Arial; margin: 2%; background: #f9f9f9; color: #333; }
    header { text-align: center; background: #4CAF50; color: white; padding: 20px; }
    h1 { margin: 0; font-weight: 300; }
    .whatsapp { background: #25D366; color: white; padding: 12px 25px; text-decoration: none; border-radius: 8px; display: inline-block; font-weight: bold; }
    form { margin: 20px 0; }
    input, select { padding: 8px; width: 200px; margin: 5px 0; }
  </style>
</head>
<body>
  <header>
    <h1>Lar Fresh</h1>
    <p>Transport express – Fruits &amp; Légumes frais</p>
  </header>

  <h2>Nos calibres</h2>
  <ul>
    <li>Caisse dix kilos</li>
    <li>Caisse vingt kilos</li>
    <li>Palette standard</li>
  </ul>

  <h2>Contact</h2>
  <address>
    05 vingt zéro zéro quatre zéro zéro zéro zéro – Rue des Orangers, Casablanca
  </address>

  <h2>Devis rapide</h2>
  <form action="mailto:transportexpressmaroc@gmail.com" method="post">
    <label>Nom :</label><input type="text" name="Nom" required><br>
    <label>Tél. :</label><input type="tel" name="Téléphone" required><br>
    <label>Calibre :</label>
    <select name="Calibre">
      <option>10kg</option>
      <option>20kg</option>
      <option>Palette</option>
    </select><br>
    <input type="submit" value="Envoyer">
  </form>

  <h2>Via WhatsApp</h2>
  <a href="https://wa.me/212520400000?text=Bonjour%2C%20devis%20pour%20Lar%20Fresh" 
     class="whatsapp" target="_blank">
    Demander un devis
  </a>
</body>
</html>
