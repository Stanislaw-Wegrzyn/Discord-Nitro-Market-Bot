# Discord-Nitro-Market-Bot
Bot odpowiedzialny za nadzorowanie autonomicznym sklepem discord nitro, współpracując ze snajperką nitro poprzez webhook channel.

<h2>Informacje ogólne: </h2>
<ul>
<li> <b>Język:</b> Python </li>
<li> <b>Użyte biblioteki zewnętrzne:</b>
<ul>
    <li>requests</li>
    <li>imaplib</li>
    <li>email</li>
    <li>paramiko</li>
    <li>chat_exporter</li>
    <li>webbrowser</li>
    <li>js2py</li>
    <li>cryptography</li>
    <li>pycoingecko</li>
    <li>discord_components</li>
    <li>discord.py</li>
</ul>
</ul>

<h2> Mechaniki zawarte w programie: </h2>
<ul>
    <li>Lokalna baza danych na podstawie blikow JSON</li>
    <li>Kolejka klijentów i ceny produktów automatycznie i regularnie aktualizowane</li>
    <li>Weryfikacja poprawności tokenów discord urzytkowników poprzez obsługe discord.com/api/v9</li>
    <li>Obsłuaga wielu serwerów vps poprze poołączenie ssh</li>
    <li>Bramka płatności PayPal na podstawie skanowania emaili poprzez imap</li>
    <li>Bramka płatności Crypto na podstawie blockchaina brzy urzuciu api.blockchair.com</li>
</ul>

<h2>Uwagi: </h2>
<ul>
    <li>Plik konfiguracyjny aby program mógł być możliwie uniwersalny</li>
    <li>Zabezpieczenie przed urzywaniem zurzytych hashy crypto</li>
    <li>Zabezpieczenie przed nagłym przerwaniem procedury płatności</li>
    <li>Baza danych na plikach może nie jest najlepszym rozwiązaniem ale oszczędza to czas podczas konfiguracji</li>
  </ul>
  
<h4><i>PS.</i></h4>
<p><i>Program może wyglądać haotycznie ponieważ jest on wciąż w produkcji i użtku</i></p>
