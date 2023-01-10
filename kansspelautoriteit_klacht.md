Aangetekende,

Hopelijk aan allen toegekomen:
	– Pieter Boers,
	– Joe Ewens,
	– Feieten Hofman
	– Justin Fransse,
	– Rene Jansen,
	– Niels Onkenhout,
	– Fedor Meerts,
	– Willem van oort,
	– Jeroen Verkroost,
	– Chiel Warners

Bij deze een summiere en korte aanvulling op aangeleverde stukken, waarbij het vooral gaat om het waarschuwen van verzadiging binnen industrie door valsspel, witwas & aanbieden van spellen in illegale regio’s.

Kleine greep uit het hoofd van participanten in valsspel & grootschalige witwas:

SoftSwiss 	(lijkt het op, echter denk ik persoonlijk dat men van BlueOcean Gaming/BOG in schoenen wilt schuiven van bovenstaande)
Entain 	Groep (Gammix, EveryMatrix enz. Enz, 1x2Connect, iSoftbet etc. ), 
Hollywood TV (met name in persoon David Wainwright
Oryx 	Gaming (welke zelf volop al tot op heden certificaten, ook gelinkt 	aan Entain direct, vooral voor witwas van gelden uit illegale 	gambling areas: denk aan Irak, Syrie, U.S.A., Tunisie enz. enz.)
Pragmatic 	Play (publiekelijk “foute” games onder demo’s op 	pragmaticplay.com)
Bgaming 	(een van de makkelijkste aan te duiden “foute” providers, 	eigendom van SoftSwiss, zie ingeladen malicious code op 	https://bgaming-network.com/analytics.js
Spearheaded 	Games
Ezugi
RubyPlay 	Entertainment
EvoPlay 	Limited
Pragmatic 	Play Live	
Vivogames
MondoGaming.eu

Er zullen er velen volgen daar vaak onder druk van BlueOcean en consorten en er ook veel eigenaar zijn van zelfde onderneming.
De methode is ansich vrij simpel en ook zeer makkelijk te bewijzen, basis aan methode ligt op het aanpassen van callbacks (slotmachine uitslagen e.d.) in de browser zelf door een alternatief & user-level authenticatie system als het ware erover te plakken, hierdoor kan speel-valuta verandert worden (bijv. van DEMO/FUN geld).

In feite word de spel-sessie & hardware van de legitieme speler misbruikt om de callbacks om te buigen naar data (upstream) die verkregen word via Google Analytics, New Relic, Sentry & andere toepassingen waardoor het lijkt je slechts marketing-data door te geven na elke spin (via google etc.) maar in werkelijkheid je data upload die de uitkomst van uitslag kan bepalen.

Hier bovenop word ook winst van legitieme investeerders binnen de providers/aggregatie zelf ontrokken, daar deze spellen dus compleet zwart worden bijdraaid in illegale regio’s en als andere games/winst (onder andere firma’s, veelal buiten reach/weet van investeerders) weer naar boven worden gepompt door bijv. Oryx Gaming, E.M. Management, Gammix, en vooral door BlueOcean && 1x2Connect onder op papier legale casino operators onder Curacaose vlag, zie: https://dama-nv-casinos.eu/ om direct deze casino’s te kunnen zien.
Alle casino’s ondanks deze methode zeer grootschalig word gebruikt is deze ook makkelijk te herkennen aangezien methode client-side is (dus de verandering van spelgegevens geschied op hardware/apparaat van de speler zelf).
Echter, schaad dit vooral spel-integriteit daar er los van aanpassingen op currency en/of origine van spelaanbod (aggregatie) met deze methode worden & kunnen ook slotmachine uitslagen geskipt worden.
Zie dit slechts als waarschuwing & als wake-up call om te zorgen dat Nederland niet eindigt zoals Curacao al tevens bekent staat.
De schaal van deze fraude & oplichting is immens en zal imminent en 100% groot uitkomen daar dit al veels te verzadigt en nu langzaam ook cowboys deze fraude methode begint toe te passen, kan Nederland profijt trekken door als eerste & enige daadkrachtig en fair op te treden, waardoor ook eigen binnenlandse gokkerts binnen eigen (virtuele) grenzen blijft om te spelen. Het is aan eenieder van jullie zelf om dit publiekelijk aan te kaarten.
Oplossing voor dit probleem zal een aanhoudende audit moeten zijn (independent waakhond, zoals kansspel authoriteit) niet enkel op games, maar ook op casino’s zelf (constant) daar dit een bedreiging is voor gehele industrie & de geloofwaardigheid van alle spellen in elk land en elke aanbieder. I.p.v. moment opname tijdens certificering zou audits constant & dagelijks automatisch moeten geschieden, juist omdat dit dus abuis kan worden aangezet.

Als alternatief of aanvulling zou elke aanbieder verboden moeten worden van externe links (zoals Google Analytics, Google Recaptcha, New Relic, Sentry.io en andere) binnen de speel-zones (dus de pagina’s met de game-launcher zelf) zodat aanbieder niet achteraf iets anders schuld kan geven (ongetwijfeld dat dit het excuus zal zijn: ‘technisch mankementje’).

## Technische Method in het kort

Speler fungeert zelf als een secundaire API, dus voordat de game result (callback) daadwerkelijk word weergegeven zend de speler zelf een signaal naar casino en/of aggregator in de vorm bijv. van New Relic, Google Analytics, Google Recaptcha, enz enz – dit word veelal als een XMLHttp Post gestuurd en zal niet altijd direct in “network” tab van bijv. Chrome te zien zijn (enable in console alle verbose).

Word een javascript snippet aangehangen, zodra game word geladen, word deze eerst of bij speler pre-loaded om e.a. te veranderen, zie 3e foto een voorbeeld stukje script wat word geinjecteerd.

In geval van Pragmatic Play & Bgaming (en er zullen er meer zijn) word actief gefacilliteerd vanaf de provider kant zelf, bijv. doe een vrij simpele audit op pagina van https://pragmaticplay.com.
Enkel feit dat je kunt kiezen uit honderden verschillende valuta & talen op een demo website zegt genoeg, maar als je 5 minuten erin kijkt zul je zien dat vol staat met onnodige en extra scripts, dit om uiteindelijk te kunnen zegen “foutje bedankt, technische error onze kant” en ook zodat de illegale gambling area games totaal niet te herleiden zijn en dus ook dat Pragmatic Play veel minder winst op papier maakt.

Vervolgens kan naar gelang spel data worden aangepast en/of doorgespoeld, dus als een win te hoog is word spin niet weergegeven en nogmaals gespint.

Ook word er in veel gevallen gebruik gemaakt van 2 iFrames, waarbij er een hangende sessie bij het inladen word ‘apart gezet’ om te wisselen.

In geval van bijv. BC.Game & Betcity.nl wisselt sowieso elke 20 games van iFrame/Operator ID, kan om verschillende redenen: veel minder ggr (kosten gameprovider), het kunnen skippen van grote wins (terwijl deze wel als debit aan kant van provider als kosten word genoteerd), misleiding van eigen aandeelhouders, belasting ontduiking enz enz.
Je kunt je voorstellen als je enkel super grote wins skipt, hoeveel extra dit je al oplevert, en dit is niet na te volgen als er gebruik word gemaakt van de demo methode.
Zie bijv. onderstaande injectie waarbij er een andere (demo oid) currency eventjes in de clientside word omgebogen naar USD/EUR en zelfs betlevels etc. worden aangepast.

Al bovenstaande staat overigens op meegeleverde software op laptop en is compleet werkend te draaien, waarbij ik zelf de ‘open’ demo pagina van Pragmatic Play gebruik zonder enige directe API integratie.

Een kleine greep van mijn testcases welke perfect werken in production als testcase:
https://github.com/ryan-gate-2/casino-session-generator 
https://github.com/westreels/evv-client  (evolution gaming client)
https://github.com/westreels/evv-api
https://github.com/westreels/bgaming-test-case (in dit voorbeeld laat ik zien hoe je spins kan doorspoelen en dus niet hoeft uit te betalen)
https://gitlab.com/ivanmontikfan (hier een volledige stack, incl. Grijze spellen en aggregatie systemen)

Kijk op de eigen casino’s hollandcasino.nl, betcity.nl etc. en huur iemand in om echt grondig vooral de voorkant te onderzoeken, je zult zien hoeveel extra troep erin word geinject, bijv. Pragmaticplay doet dit grote schaal en je zult zien dat door gebruik van sentry/google analytics het op 1e aanblik legit lijkt.

Voorbeelden kan ik aanvullend bij leggen, echter probeer ik het voor nu kort & bondig te maken, dit is zeer groot en je moet toch denken aan een 500m+ fraude per jaar en/of witwas.
Bijv. ook door Betcity.nl e.d. BtoBet, Playtech (welke de casino software ook verzorgd).
Spellen in Irak/Syrie etc. komen via deze route legaal via Nederland o.a. Wit terug. 
David G. Wainwright is sleutel figuur in dit verhaal, deze haalt de providers over om games beschikbaar te stellen.
Via deze methode kan je de uitkomst van spellen naar gelang aanpassen als casino, iedereen kan dit. Zijn verscheidene methods.

## Archivering & Nakijken Valsspel/Misbruik
Mocht je actief willen nakijken of deze methode is gebruikt in verleden op een casino operator website kun je deze terug vinden op webscraping archieven, zoals bijv. https://web.archive.org waarbij pagina’s worden opgeslagen.
Echter, indien je dat doet is zeer belangrijk:
De gevorderde abusers (m.n. SoftSwiss) heeft runtime code actief welke 	indien archive pagina’s geladen word er veel van bewijs 	(javascript) niet word uitgevoerd of niet word ingeladen. 	
 	
Javascript is een actieve programmeer taal, dat betekent dat executie van code 	word uitgevoerd op moment van laden in de browser, niet op moment 	van opslaan van code door web.archive.org. 	
 	
Er 	zal actief gefilterd worden door m.n. Softswiss (vooral nu de fraude 	immenser word) op scraping services zoals web.archive.org – 	probeer daarom verschillende scraping services en verschillende 	data.

Zorg 	ervoor dat je de code stapsgewijst lokaal opslaat: eerst website 	pagina’s met JAVASCRIPT UITGESCHAKELT (RUNTIME): Eerst 	zonder runtime, daarna met runtime en daarna nogmaals vanuit lokale 	cache zonder runtime. om daarna deze grondig lokaal (te) laten 	onderzoeken. 	

Voor 	het “wegmaken” van het bewijs word hiervoor vooral de .js	injectie gebruikt van support systemen (api.livechatinc.com, enz 	enz)

In vervolg is het raadzaam dagelijks (zo niet uurlijks) automatisch onder verschillende scenario’s de eigen casino’s & nederlandse online casino’s te archiveren, daar dit misbruik ook prima kan (een grote win door-spinnen is ook direct geld in het laatje voor de gameprovider op GGR).
Het liefst zou je dit moeten doen onder externe emulatie bijv. door gebruik van Chromium Driver kun je technisch zeer gemakkelijk echt spelgedrag nabootsen op de p.c. en vervolgens dit in eigen archief te zetten om achteraf event. vals spel te kunnen aantonen.
Overigens word Chromium Drivers ook gebruikt in bovenstaande abuse door het pairen van de spellen tussen DEMO of een alternatieve dubbele spelsessie gelijktijdig te openen, is zelfs mogelijk om met slechts 1 slotmachine sessie meerdere mensen te bedienen (zie github.com/ryanwest-cr).


## Inhoud Laptops
(dit is n.v.t. Ik was van plan naar igb te komen om laptop te overhandigen, echter kun je deze alsnog bij mij komen ophalen in IJsselstein/utrecht) 
Na opstarten van Kali (operating systeem) zul je “start.sh” bestand zien op desktop, druk deze en er zal optie scherm verschijnen:
	
Druk 	op optie 1 voor lokale games zonder 	internet waarbij 	demo spel word gelaunched. Lokale games worden aangeleverd door 500 	random spins (en daarvan een random selectie) op een mock API 	server 	– dit zijn dus ‘opgenomen’ spin 	uitslagen welke random selectie word gemaakt en dient enkel om 	makkelijk kunnen testen van methodes.

Druk 	op optie 2 voor verbonden games (gebruik word gemaakt van toegang op 	demo site pragmaticplay.com, api.bets.io en/of duxcasino.com echter 	kan elke ‘demo’ site aan worden gehangen, waaronder zelfs bijv. 	Holland Casino)

Het is belangrijk te vermelden dat API toegang NIET vereist is en dat eenieder dit kan toepassen. Het moge duidelijk zijn dat in ieder geval, bij BGAMING & PRAGMATICPLAY met opzet games worden geprepereerd om deze makkelijk te kunnen abusen & veranderen.

Bij beide deze providers zit zelfs de malicious code i.p.v. om games heen, in de game-assets zelf (zie analytics.js, html-external-script.js, wurlf.js, operator_logos.js etc. etc.) waarbij deze op afstand geactiveerd kunnen worden en spel-uitkomst direct kan worden aangepast.

Zie kopje “Hoe/wat/waar” om te begrijpen hoe deze code verhult en ook in veel gevallen niet geactiveerd word. Voor natuurgetrouwe reflectie

Het uitvoerbestand zal lokale servers opstarten en als het goed is zal de browser (Konqueror) de pagina “https://localhost:9000” openen waarbij je de spellen kunt spelen van DEMO –> EURO.

Op pagina zal duidelijke link zijn bovenaan om de “doorspoel” actie te activeren waarbij elke win boven 10$ zal worden doorgespoeld.

Alle code word uitgevoert op de laptop zelf, los van dus het aankoppelen aan echte demo-games is kun je alles zelf dus in eigen tijd/gemak alles doorspitten, wellicht door een in-house developer.

Je mag de laptops in bezit behouden, daar ik ook enig afstand neem van code en/of eventueel enig eigendom.


## Nalees Voer
Je kunt verschillende data & info ook online nalezen, zie daarvoor 1 van volgende links:
https://github.com/ryanwest-cr
https://github.com/ryandro

Op bovenstaande kun je methodes nakijken, zoals ze direct van een malicious provider afkomen – welke in dit geval word “witgewassen” door E.M. Management bijv. (wellicht en waarschijnlijk zonder weet van E.M. Management zelf overigens – daar hier verder ook geen bewijskracht is van valsspel)

Echter is E.M. Management wel direct als officer (en op persoonlijke titel) aansprakelijk op licentie van bedrijven die aantoonbaar spellen aanpassen & witwassen, waaronder dus de TigerGames die via Bet-Channel.com (aantoonbaar door lekke aggregatie) geld terug naar boven pompen.

Een enkel voorbeeld van “constructie” (slechts 3-links van vuil naar wit) <snip>

Deze zelf backoffice software welke lek als mandje is, zie https://manage.betrnk.games/register word o.a. gebruikt door Gammix, EveryMatrix, Spearheaded, AMB Bet, BetChannel, BetConstruct enz. enz.

## Persoonlijke Noot & Motivering
Ikzelf bood spellen onder aggregatie aan: 92 game-providers met in totaal meer dan 9000 spellen, casino operator software, poker software, eigen sport solution. Directe partner met o.a. NowPayments.io, etc etc.

Reden van het aanhangig maken van dit probleem is ‘conflict’ is dat toegang tot mijn API/aggregatie dienst werd misbruikt als ‘voorkant’ (iFrame URL/ID) waarbij veel demo sessies en dergelijke werden aangemaakt.

Zelf waren we van deze fraude totaal niet op te hoogte dus schetste verbazing dat zoveel demo gamesessies werden aangemaakt (tientallen per seconde) met veelal geen verdere omzet.

Achtergekomen wat er achterschuil ging, vervolgens gesommeert hiermee te stoppen daar mijn naam (zoals dat bij E.M Management) direct aan fraude gelinkt word.

Het gevolg van het vragen onze dienst of te verlaten, of te stoppen, is nu dat dankzij onuitputtelijke (dagelijkse) hack pogingen & (in)directe persoonlijke bedreigingen door BOG Groep & 1x2Connect  (zie s7s.ai, softswiss.net etc.) de afgelopen 6 maanden het mij onmogelijk is gemaakt om eerlijk & vooral veilig spellen aan te bieden aan klanten.

Dit heeft mij persoonlijk honderdduizenden euro’s in misgelopen winst gedorven, maar vooral het niet kunnen ontplooien van mijn passie en zelf opgezet & opgestart bedrijf kost mij dit het meeste.

Er is geen enigszins geldelijk motief om dit te melden, echter is het cru dat slechts om verzoek te stoppen met misbruik via ons er vervolgens van allerlei kwel & kwaal word toegepast en je het onmogelijk word gemaakt je passie & bedrijf te explateren. Ik zie overigens in dat dit ook niet op korte termijn of zelfs op lange termijn ophoud, daar er weinig directe navolging op verzoeken te stoppen en zelfs enkel maar intensiveert.

Tot het punt dat zelfs familieleden (zus) e.d. op persoonlijke devices virtueel word ingebroken en er word gebelt op telefoon naar moeder enz enz.

Enkel en alleen om miljarden wit te wassen en mensen los van het ‘legaal stelen’ (door house-edge al die legaal zit ingebakken in spellen) te gierig zijn om dit dan fair uit te voeren.

Per verzoek heb ik hier zo’n 10 a 15 geinfecteerde gebruiksdevices (PC’s, Telefoons etc.) die 1 van ieder van jullie direct persoonlijk mag komen ophalen waarbij het vol staat met links naar Softswiss direct.

Mondogaming
## 
Speciaal stukje o toch direct ook iemand aan te wijzen die in geval van mij alle abuse deed, o.a. jatten ze nu veel sports (altosports) samen ook met BOG/1x2Connect/David Wainwright en je zult veel meer sports sites nader tegenkomen (voor wit was).

In geval van mijn kwelgeest gaat dit om ene “David G. Wainwright”, welke ook geaffilieerd is met EveryMatrix, zie: https://gamblersnews.com/everymatrix-gets-uk-gambling-commission-license-suspended/802/. Waar eerder ook al in G.B. niet meer op markt mag operen, is deze wel actief in Nederlandse markt.
Deze stond bij mij geregistreerd als klant onder “MONDOGAMING”, nader inzien gaat het hier ook om een nep licentie drager, deze voorziet Tunisie van illegale en veelal oneerlijke gokspelen.

David G. Wainwright (Hollywoodtv) doet o.a. veel Tunisie area illegal gambling i.c.m. BlueOceanGaming/Bragg.games. Bijv. rapport tegen Evolution Gaming’s laatste scandal komt uit deze hoek, enkel om zelf markt te pakken op Pragmatic Live & VIVO Gaming.

Deze Matteo is direct aansprakelijk ook voor de indirecte danwel direct bedreigingen aan prive adres. Wees gewaarschuwd.

Zie: https://mondogaming.eu/

## Operators in nederland
Aan hoofd staat casino888/bet365 van deze fraude en vanwaaar meeste word geregeld.

## Casino’s

In algemeen, hierbij een korte selectie (slechts 1e pagina google) met casino’s waarbij gokspellen direct worden beinvloed. Ook zie alle casino’s op https://dama-nv-casinos.eu e.d.

BC.Game
BTOBET
TIPBET
BIKINIBEACH.COM
EZUGI.COM
BETGAMES.TV
LUMICASINO
TVBET.TV
1xBit
bitStarz
BitDice
BetChain
LTC Casino
Wildcoins
Crypto.Games
Fairspin
Bitkong
Paradice
CoinSaga
mBit Casino
BK8
bspin
wolf.bet
7BitCasino
Primedice
OneHash
bitplay
Betcoin
Nitrogensports
Mystake
Bitcasino
Americascardroom
Stake
Sportsbet
FortuneJack
Yabtcl
fortunecoins
Etheroll
Satoshidice
Anonibet
Coinbet24
just-dice
7bitcasino
BetMoose
VegasCasino
BitcoinPenguin
vDice
Mars Casino
casinobetsites
BetBTC
Bitzillions
Oshi
777coin
luckyb.it
Argocasino
iDice
LuckyBity
TrueFlip
4Grinz

