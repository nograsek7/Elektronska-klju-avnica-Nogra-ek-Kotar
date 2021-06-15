# Elektronska-ključavnica-Nograšek-Kotar
Odklepanje elektronske ključavnice s pomočjo številčnice. Če hočemo odkleniti vrata potrebujemo vpisati pravilno štirimestono kodo. Če vtipkamo napačno zaporedje se ključavnica ne odpre. Ker nisva imela elektronske ključvnice sva jo nadomestila z LED diodama. Rdeča sveti kadar je ''ključavnica' zaprta oziroma štirimestna koda ni pravilna. Zelena dioda pa ponazarja pravilen vpis kode, kar pomeni da se ključavnica odpre. Ključavnica je v odprtem stanju 5 sekund, saj moramo od številčnice priti do vrat preden se nam zaprejo.

Seznam uporabljenih materialov in komponent:

- 1x Arduino UNO
- 17x žice
- 2x LED dioda (zelena, rdeča)
- 1x rele 5V
- 1x zener dioda 
- 1x NPN tranzistor(BC 547C)
- 2x 220Ω upor
- 1x 24kΩ upor
- 1x številčnica 4X4

Postopek:

Na začetku povežemo številčnico z arduinom. Nato prenesemo program in preverimo ali se številčnica odziva. Ko nam to uspe lahko simuliramo in priklučimo "ključavnico" (v našem primeru sta to 2 led diodi), ter rele. Sedaj je vezje pripravljeno na preizkus in uporabo.

Predlagane izboljšave:

Uporava kvalitetnejšega materiala. Midva bi zamenjala predusem rele, saj sva imela velike težave z stikom. Vendar je vseeno delovalo.
