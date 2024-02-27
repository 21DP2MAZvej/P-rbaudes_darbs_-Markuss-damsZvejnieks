# P-rbaudes_darbs_-Markuss-damsZvejnieks
Programmēšanas priekšmetā PD par Laravel.
Kas ir API? 
API (Application programming interface) ir rīks, kas ļauj divām sistēmas programmām sadarboties viena ar otru.
- Kā deklarēt mainīgo PHP valodā?
    Tiek izmantots $ šis simbols, pēc kura ir jāraksta mainīgā nosaukums un pēc = zīmes ir vērtība.
- Kādu arhitektūru izmanto Laravel, paskaidro kā tā strādā:
  Laravel izmanto Model-View-Controller (MVC) arhitektūru. Tā atdala modeļu daļas, kā piemēram prezetācijas loģiku veidojot kodu tīrāku un vieglāk pārvaldāmu un uzturējamu. Modelis: attēlo datu struktūru, parasti kartojot datu bāzes tabulās.Programmā Laravel modeļi tiek izmantoti, lai mijiedarbotos ar datu bāzi, izpildītu vaicājumus un definētu attiecības starp dažādām tabulām.
- Kas ir ORM, kāpēc to izmanto tīra SQL vietā?   ORM (Object-Relational Mapping), kas piedāvā elegantu un vienkāršu abstrakciju mijiedarbībai ar datu bāzi.
- Uzraksti Eloquent ORM pieprasījumu modelim User, kur nepieciešams iegūt visus
lietotājus kuriem reitings ir lielāks par 4. Lietotāju tabulas struktūra- $users = User::where('rating', '>', 4)->get();
