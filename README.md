# Atsiskaitomasis HTML/CSS darbas

## Kodėl ne Bootstrap?

Pora dalykų man nėra gerai suprantami:

1. Kaip iš dizaino atgaudyti, kokias Bootstrap kombinacijas naudoti, siekiant atitaikyti pixel-perfect. Panašus iššūkis ir renkantis dirbti vien su paprastu CSS: norisi įžvelgti dizaine kažkokį dėsningumą, o ne tiesiog aklai hardcodinti absoliučiai kiekvieną šriftų ir tarpų dydį. DRY principas.

2. Kaip koreguoti/papildyti Bootstrap CSS, išlaikant sistemiškumą. Tikriausiai tą geriausia valdyti su SASS, ko dar kurse nepradėjome. Bootstrap SASS sistemoje žinant ką pakeisti, pakeitimas darniai prisitaiko prie sistemos, pvz. užtektų pakeisti $primary spalvos kintamąjį, ir susiję atspalviai prie to prisitaikytų; tuo tarpu vien per CSS tektų sužiūrėti visas susijusias vietas ir priderinti rankiniu būdu.
