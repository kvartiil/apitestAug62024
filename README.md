# apitestAug62024

Refresh paneb pöörduma api poole ja toob sisendi, sisend rakendatakse järgmise refreshi ajal (esimene refresh toob sisse sisendi ja salvestab selle, teine rakendab - seega kui vaadata konsooli tulemit, siis see jõuab ekraanile järgmise refreshi läbi).
Konsoolil: "Apist sisse tulev:" näitab sisse tulevat infot.
Sisendiks on hetkel ainult mudelite sisend, muu tuleb veel teha.
Sisendit toodab hetkel randomapi, sisendi valemid on natuke kallutatud, hetkel ei tule sealt olukorda, kus midagi oleks "keskmine", kuid see on random valemi probleem, mitte rakenduse probleem. Sisulises testis asendatakse random sisulise backendiga.
