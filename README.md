<h1> Web-typografie | Bladerunner 2049 </h1>

<p>Tijdens deze opdracht ontwerpen we voor één persoon: Darice. Het doel van deze opdracht is om de scène uit de film Bladerunner 2049 interessanter te maken voor Darice die niet kan horen. Daarnaast is het doel om te gaan experimenteren met html/css. Wat werkt wel en wat werkt niet bij het visueel maken van geluiden?</p>

<p>Eindversie: https://misscage.github.io/web-typography-19-20/Typografie-5.0/closed-captions/index.html</p>

<h3>Identiteit en situatie</h3>
<p>Om succesvol te kunnen ontwerpen is het belangrijk om te kijken naar de identiteit van onder andere de persoon waarvoor je ontwerpt. Dit is één van de principes van de Exclusive Design Principles. Ook is het belangrijk dat je de situatie van dat persoon goed kunt schetsen. Wat houdt de handicap precies in? Wat voor gevolgen heeft het en waar moet ik rekening mee houden?</p> 

<p>Tijdens de kennismaking met Darice heb ik voor mijzelf een aantal punten opgeschreven. Deze punten heb ik in gedachte gehouden tijdens het ontwerpen:
<ul>
  <li>In het dagelijks leven is het vooral moeilijk voor haar om gesprekken te volgen</li>
  <li>“De wereld is gebouwd voor mensen die geen beperking hebben”</li>
  <li>Haar stijl: minimalistisch, kleine kleuraccenten, whitespaces, genuanceerd en toegankelijk</li>
  <li>Captions het liefst in beeld maar let goed op contrast en leesbaarheid</li>
  <li>Fijn als je kunt zien wie er praat, gebruik verschillende kleuren</li>
  <li>Best practice: The Half Of It (Netflix)</li>
  <li>Worst practice: Late Night (Netflix)</li>
 </ul></p>

<p>De uitdaging bij deze opdracht is om zowel de identiteit van Darice mee te nemen, als die van mijzelf en de film. Ik wil graag een mooie balans vinden tussen de stijl van Darice (minimalistisch) en een experimenteel ontwerp.</p>

<p>Een groot deel van de film Bladerunner 2049 heb ik gekeken en al snel had ik de sfeer te pakken. De film heeft een koele, sombere en duistere sfeer en mede door het geluid word je meegesleept. Het gaat onder andere over de grens tussen mens en machine die steeds vager wordt. Door middel van visuele aspecten wil ik proberen om deze sfeer mee te geven aan de film zonder het geluid nodig te hebben.</p>

<h3>Font</h3>
<p>In eerste instantie wilde ik werken met een systeemfont. Dit omdat dit eigenlijk altijd goed leesbaar is om elk device. Daarnaast maakt het de pagina sneller omdat het lettertype niet via een server geladen hoeft te worden. Dit lettertype staat al op de computer of smartphone van de gebruiker.</p>

<p>Later ben ik toch voor het Brenner font gegaan. Zeker wanneer je geen geluiden hoort, is typografie belangrijk voor de sfeer die de video meebrengt. Met het brenner font zijn er veel meer mogelijkheden om het karakter van een stem weer te geven ten opzichte van het systeemfont. Ik kwam er tijdens een gesprek met Darice achter dat zij het fijn vindt als er visueel onderscheid wordt gemaakt tussen de verschillende mensen die spreken. Zo gebruik ik uiteindelijk voor de ‘intercom’ stem een monotype variant van Brenner om de monotone stem van de intercom weer te geven. De “fuck-off skin job” maak ik cursief en oranje om de agressiviteit in zijn stem te laten zien. De letters houd ik klein omdat de man het niet schreeuwt. De voordelen van het brenner lettertype vond ik in dit geval zwaarder wegen dan die van een systeemfont.</p>

<h3>Iteratie 1</h3>
<p>Allereerst heb ik mij gefocust op de basis leren begrijpen van HTML en CSS. Dit duurde even voordat ik het door had, maar toen kon ik wel wat kleine aanpassingen maken aan de video. Ik heb toen classes aangemaakt voor de verschillende stemmen en deze bewerkt. Daarnaast laat ik in de eerste versie de achtergrondkleur naar rood veranderen wanneer er een alarm te horen is. Ook wordt de video groter bij een alarm. Achteraf waren dit natuurlijk kleine aanpassingen, maar ik was op dat moment wel heel tevreden met het feit dat ik dit al bereikt had zonder enige ervaring.</p>

<p>Bekijk hier versie 1: https://misscage.github.io/web-typography-19-20/Typografie-1.0/closed-captions/index.html</p>

<h3>Feedbackmoment 1</h3>
<p>Tijdens het eerste feedbackmoment met Darice kwam naar voren dat ik nog meer aandacht moest besteden aan geluiden visueel maken in combinatie met ondersteunende teksten. Het was voor Darice bijvoorbeeld nog niet helemaal duidelijk wat ik precies bedoelde met het groter maken van de video en een rode achtergrondkleur. De kleuren die ik gebruikte voor het aangeven van verschillende personen vond ze duidelijk en goed leesbaar. Om het nog duidelijker te maken zou ik er eventueel nog labels voor kunnen zetten.</p>

<p>Vasilis gaf aan dat het niet per se nodig is om elk woord apart te laten verschijnen. Daarnaast mochten de visuele aspecten meer overdreven zijn.</p>

<h3>Iteratie 2</h3>
<p>Na de eerst feedbacksessie ben ik gelijk gaan kijken naar de captions die niet woord per woord hoeven te verschijnen, zoals Vasilis aangaf. Dit heb ik dan ook weggehaald. Wel gaf Darice aan dat het niet duidelijk was dat Officer K "Within cells interlinked" drie keer herhaald. Hier zag ik dan ook gelijk de oplossing van de woorden apart laten verschijnen per span. Het is dus nu niet meer door de gehele video maar alleen waar het echt nodig is.</p>

<p>Ook heb ik labels toegevoegd aan de captions zodat het in één oogopslag duidelijk is wie er praat. Daarbij heb ik de kleuren rood, blauw en oranje gebruikt. Rood voor de intercom stem om aan te geven dat dit de tegenovergestelde partij is die niet altijd even vriendelijk is. Blauw voor Officer K om de koele toon in zijn stem weer te geven en om aan te geven dat hij onderdanig is aan de intercom stem. Oranje voor de 'passer-by' die Officer K uitscheldt om de scherpte en agressiviteit in zijn stem weer te geven.</p>

<p>Omdat ik inmiddels de basis van HTML en CSS doorhad, ben ik mij nu gaan focussen op het toevoegen van elementen / nonsense en out of the box denken. Zo heb ik een lijn toegevoegd wanneer je het hoge alarm hoort om als het ware een heartbeat weer te geven. De lijn loopt eerst horizontaal door het scherm en schiet vervolgens omhoog. Dit suggereert de hoge pieptoon. Omdat Darice graag meer ondersteunende tekst wilde, heb ik bij het eerste alarm 'BUZZZ' in het scherm laten komen. Het volgende geluid wilde ik proberen meer visueel te maken door twee icoontjes van een alarm weer te geven.</p>

<p>Tijdens de tweede helft van de eerst scene (de test) laat ik de video langzaam groter worden. Het geluid in de video op dat moment trekt je echt mee in de scene. Dit hoopte ik te creëren met het groter maken van de video.</p>

<p>Bekijk hier versie 2: https://misscage.github.io/web-typography-19-20/Typografie-4.0/closed-captions/index.html</p>

<h3>Feedbackmoment 2</h3>
<p>Het tweede feedbackmoment heeft mij inzichten gegeven hoe ik de final touches kan maken voor deze opdracht. Darice gaf aan de effecten prima te vinden, maar zou graag nog ondersteunende tekst willen zien bij een geluid. Daarnaast is het scherm nog niet responsive gemaakt waardoor de uitlijnen niet klopte op het scherm van Darice. Daar wil ik ook nog naar kijken.</p>

<p>Vasilis was tijdens dit tweede feedbackmoment over het algemeen positief. Ik was al goed bezig met experimenteren, maar dit kan misschien nog wel een stapje verder. Hier wil ik in de laatste week dus nog een slag in proberen te slaan. Ook gaf Vasilis aan dat het scherm niet per se responsive hoeft te zijn. Als ik nog tijd over heb, wil ik dit proberen. Maar ik leg hier niet de focus op. Tijdens het eerste feedbackmoment gaf Vasilis aan dat het niet per se nodig is om elk woord apart te laten verschijnen. Tijdens het tweede feedbackmoment gaf Vasilis aan dat ik het op deze manier beter had gedaan door het alleen toe te passen op het moment dat Officer K ‘within cells interlinked’ drie keer moet herhalen.</p>

<h3>Iteratie 3</h3>
<p>Na het tweede feedbackmoment heb ik nog gekeken hoe ik nog meer effecten kon toevoegen aan de video. Zo heb ik geprobeerd de opmerking van de passer-by nog 'scherper' over te laten komen door op dat moment heel veel oranje puntjes op het scherm te laten komen. Deze gaan daarna ook gelijk weer weg omdat het een korte, maar agressieve opmerking is.</p>

<p>Daarnaast heb ik nog toevoegingen aan het stuk van 'de test' gedaan. Het scherm wordt steeds lichter om uiteindelijk dezelfde kleur als de video te krijgen. Op deze manier wordt je nog meer in de scene gezogen. Wanneer de intercom zegt 'we're done' verkleint de video weer naar zijn originele formaat om, als het ware, inneens weer terug te zijn in de werkelijkheid. Verder heb ik nog geprobeerd een beetje verder te werken aan de tweede scene van het videofragment. Ik heb de video laten bewegen en een achtergrondkleur laten veranderen, maar verder was er helaas niet veel tijd meer voor mij.</p>

<p>Bekijk hier te laatste versie: https://misscage.github.io/web-typography-19-20/Typografie-5.0/closed-captions/index.html</p>

<h3>Conclusie en reflectie</h3>
<p>Over het algemeen ben ik heel tevreden met wat ik heb kunnen bereiken in een korte tijd zonder enige ervaring. Door heel veel op internet te zoeken en af en toe dingen te vragen aan andere studenten of aan Chelsea ben ik veel verder gekomen. Wat ik lastig vond, was de positionering van elementen en het responsive maken van mijn ontwerp. Ik heb gemerkt dat er heel veel manieren en 'regeltjes' zijn om elementen een positie te geven op het scherm. Het één werkt niet samen met het ander enzovoorts. Hier was ik soms veel tijd aan kwijt en zou ik in het vervolg ook meer over willen leren.</p>

<h3>Bronnen</h3>
https://raidboxes.io/nl/blog/webdesign-development/typographie-grundlagen-webfonts-tipps/<br>
https://css-tricks.com/almanac/<br>
https://exclusive-design.vasilis.nl/<br>
https://www.youtube.com/watch?v=gWai7fYp9PY<br>
https://stackoverflow.com/<br>
https://www.w3schools.com/<br>
