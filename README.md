# site2
<html lang="lv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projekts “Drošība sociālajos tīklos”</title>
    <style>
        .hidden {
            display: none;
        }
    </style>
  <h2>PROJEKTS. DROŠĪBA SOCIĀLĀJOS TĪKLOS.</h2>
</head>
<body>
    <h1 onclick="toggleVisibility('merkis')">Mērķis:</h1>
    <p id="merkis" class="hidden">Informēt cilvēkus par drošības noteikumiem internētā, lai izvairītos no nepatīkamiem vai gan arī bīstamam situācijām.</p>

    <h1 onclick="toggleVisibility('uzdevumi')">Uzdevumi:</h1>
    <p id="uzdevumi" class="hidden">Informēt par personas datu aizsardzību; Pastastīt kā pasargāt sevi no uzlaušanas; Pastastīt kur vērsties pēc palīdzības.</p>

  </head>
  <body>
      <h1 onclick="toggleVisibility('anketa')">Anketas rezultāti 1:</h1>
      <p id="anketa" class="hidden">Pēc aptaujas rezultātiem var redzēt, ka gandrīz puse no cilvēkiem (53,3%) bija uzlauti un saskārās ar briesmām internetā. Un 46,7% no cilvēkiem nekad nav saskārušies ar šādām problēmām un nebija pakļauti uzlaušanas riskam.</p>
     <li> <a href= "Screenshot 2024-03-25 094640.jpg">Anketas rezultāti 1: </a> </li>
    </head>
    <body>
        <h1 onclick="toggleVisibility('anketa1')">Anketas rezultāti 2:</h1>
        <p id="anketa1" class="hidden">Daudzi zina(53,3%), kā rīkoties uzlaušanas gadījumā, taču ir arī daudzi, kas nezina(46,7%), ko darīt, kas vēlreiz apliecina šīs tēmas aktualitāti.
         <li> <a href= "Screenshot 2024-03-25 094927.jpg">Anketas rezultāti 2: </a> </li></p>
       </head>
        <body>
            <h1 onclick="toggleVisibility('anketa2')">Anketas rezultāti 3:</h1>
            <p id="anketa2" class="hidden">Esam pārsteigti, ka 40% aptaujāto datu aizsardzībai izmanto īpašas programmas. Bet 60% aptaujāto nav nevienas aizsardzības savām ierīcēm.</p>
           <li> <a href= "Screenshot 2024-03-25 094959.jpg">Anketas rezultāti 3: </a> </li>

          <h2>LOGOTIPS:</h2>
          <li> <a href= "LOGO.jpg">Logotips </a> </li>

          <h2>INTERFACE:</h2>
          <li> <a href= "interface.pdf">Interface here!!! </a> </li>

   

    <script>
        function toggleVisibility(id) {
            var element = document.getElementById(id);
            if (element.classList.contains('hidden')) {
                element.classList.remove('hidden');
            } else {
                element.classList.add('hidden');
            }
        }
    </script>
</body>
</html>
