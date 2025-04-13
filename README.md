<!DOCTYPE html><html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COSA BLOCCA LE TUE FINANZE? 💵</title>
    <style>
        body { background-color: #d8e2dc; font-family: Arial, sans-serif; color: #333; padding: 20px; }
        h1 { color: #556b5d; text-align: center; }
        .gold { color: #c9a93f; }
        .container { max-width: 600px; margin: auto; background-color: #ffffff; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .btn { display: block; width: 100%; margin-top: 10px; padding: 10px; background-color: #556b5d; color: #fff; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; }
        .btn-gold { background-color: #c9a93f; color: #fff; }
        .result { margin-top: 20px; }
        .shop { margin-top: 30px; }
        .shop h2 { color: #556b5d; }
        a { text-decoration: none; color: white; }
    </style>
</head>
<body><h1>COSA BLOCCA LE TUE FINANZE? <span class="gold">💵</span></h1><div class="container">
    <label>Nome:</label>
    <input type="text" id="nome" style="width: 100%; padding: 8px;"><label>Cognome:</label>
<input type="text" id="cognome" style="width: 100%; padding: 8px;">

<label>Data di nascita (gg/mm/aaaa):</label>
<input type="text" id="data" style="width: 100%; padding: 8px;">

<button class="btn" onclick="calcolaBlocchi()">Scopri cosa ti blocca</button>

<div class="result" id="risultato"></div>

<div class="shop">
    <h2>Vuoi lavorare in profondità sulle tue finanze?</h2>
    <button class="btn btn-gold"><a href="https://www.selenenavarra.com" target="_blank">Prenota Lettura Matrice del Destino - 99€</a></button>
    <button class="btn btn-gold"><a href="https://www.selenenavarra.com" target="_blank">Corso Triangolo della Fortuna - 44€</a></button>
</div>

</div><script>
function calcolaBlocchi() {
    const nome = document.getElementById('nome').value;
    const cognome = document.getElementById('cognome').value;
    const data = document.getElementById('data').value;

    let output = `<h2 class='gold'>Risultato per ${nome} ${cognome}</h2>`;

    output += `<p><strong>Numero del Destino:</strong> Inserire il calcolo reale e decodifica specifica.</p>`;
    output += `<p><strong>Numeri Karmici:</strong> Se presenti: mostrare numeri e spiegazione. Se assenti: "Assenti".</p>`;
    output += `<p><strong>Numeri Mancanti:</strong> Mostrare numeri mancanti e loro significato come blocco finanziario.</p>`;
    output += `<p><strong>Blocco Finanziario:</strong> Spiegazione dettagliata in base ai numeri emersi.</p>`;
    output += `<p><strong>Consiglio per sbloccare:</strong> Azioni pratiche personalizzate per armonizzare le energie mancanti.</p>`;

    document.getElementById('risultato').innerHTML = output;
}
</script></body>
</html>
