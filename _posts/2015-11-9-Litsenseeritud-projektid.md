---
layout: post
comments: true
title: Mis juhtub projektiga litsentsi valikul?
---

Kuidas on tarkvara litsentsid mõjutanud projektikäiku?

<b>PHP</b>

Juhtusin hiljuti kuulama loengut PHP loojalt Rasmus Lerdorfilt. Tema esialgne idee oli teha veebi C API ning näidata kasutajatele, kui lihtne on C-d kasutada veebiga suhtlemiseks ning jagas seda kõigile. Vastupidiselt aga tema arvamusele, et inimesed hakkavad ka tema näitel nii tegema, hakkas ta hoopis kirju saama inimestelt, kes palusid üht või teist funktsionaalsust juurde lisada PHP-le, see viis Lerdorfi esialgu küll koodi täiustamiseni kuid hiljem läbi põlemiseni, sest päringuid koodi muutmiseks tuli meeletult palju. Olles ühel hetkel arusaanud, et nii edasi ei saa, otsustas ta kasutajatel lubada ise teha otse koodi muudatusi ning suuresosas tänu sellele, muutus PHP selliseks nagu ta täna on (populaarseim veebi arendus keel).
Viide: https://www.youtube.com/watch?v=ZPvC_HGNqQE (Siin räägib ta sellest lähemalt, loengu esimesed 15minutit umbes)

<b>http://www.xmule.ws/ // XMULE</b>

Okei, see on huvitav siin, jõlkudes natukene internetis, et millest siis kirjutada sattusin sellise pärli otsa. Kuid siiski mainin ära, et mul pole täielikku fakti põhist tõendust alljärgnevale tekstile. xMule oli Linuxil põhinev P2P faili jagamise programm, mis oli litsenseeritud GPLi litsentsiga. Oma alguse sai ta Windowsil põhinevast P2P jagamise programmist, seda forkides, see tähendab tal pidi olema samasugune litsents (GPL). Ühe asutaja jutu kohaselt [1] saavutas ta 50 000 kasutajalise baasi. Luues programmile täiendusi ning neid avavarana üleslaadides forkiti tema koodi, muudeti nimi xmule-st aMuleks ning võeti ära tema nimi copyrightist ning peale seda hakkas ta saama ähvarduskirju ja ka tapmis ähvardusi forki kasutajate poolt ning muud anti propagandat. Iga muudatus, mis ta tegi oli litsentsi tõttu avalik ka tema vastastele ning kuna aMule-s oli rohkem inimesi, siis läksid muudatused kiiremini "live"-i forkis, aga mitte main branchis. Peale mitut aastat võitlust, mees sulges projekti.
Täpsemalt saab lugeda siit:
1. http://farmdev.com/thoughts/80/why-you-should-not-license-your-code-as-gpl/ (otsige sellist teksti: posted by Theodore R. Smith on Monday Aug 19th, 2013 at 12:10p.m.)

<b>Microsofti .NET raamistiku avavaraks muutmine</b>

2014 aastal muutis Microsoft oma .NET raamistiku avavaraks ning see on juba tänaseks loonud väga huvitavaid kooslusi. Näiteks on võimalik .NET jooksutada serveri poolselt Linuxis ning alles hiljutine uudis siin: https://blog.openshift.com/open-source-power-microsoft-dotnet-openshift/ ning seda toetab nii Red Hati Linuxi meeskond kui ka Microsofti meeskond. Ilmselt avavaraliseks minekuga tekib rohkem .NET kasutajaid, kui palju? Eks seda näeme paari aasta pärast.
