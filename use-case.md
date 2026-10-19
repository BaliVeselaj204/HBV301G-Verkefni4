# Notkunartilvik

## Helstu notkunartilvik

Greinið helstu notkunartilvik sem komu fram við úrvinnslu kröfusöfnunarinnar. Bætið við línum eftir þörfum

| ID | Heiti | Aðalgerandi | Markmið |
|---|---|---|---|
| UC-1 | Kaupa miða á netinu | Viðskiptavinur | Kaupa miða án aðstoðar starfsmanns og fá hann sendan með SMS eða QR-kóða |
| UC-2 | Selja miða í afgreiðslu | Starfsmaður í afgreiðslu | Selja viðskiptavini miða á staðnum og greiða með posa, þannig að salan skráist í sama gagnagrunn og netsalan |
| UC-3 | Skrá viðburð | Viðburðastjóri | Skrá viðburð í kerfið svo hægt sé að selja miða á hann |


## Ítarleg lýsing á einu notkunartilviki

**ID:** UC-1  
**Heiti:** Kaupa miða á netinu  
**Aðalgerandi:** Viðskiptavinur  
**Aukagerendur:** Greiðsluþjónusta (ytri aðili)

## Forsendur
- Viðburður er skráður í kerfinu og miðar á hann eru til sölu.
- Viðskiptavinur hefur aðgang að vefsíðu kerfisins.

## Eftirskilyrði
- Salan er skráð í gagnagrunninn og framboð miða er uppfært.
- Greiðslan hefur verið afgreidd.
- Viðskiptavinur hefur fengið miðann sendan með SMS eða sem QR-kóða.

## Aðalflæði
1. Viðskiptavinur opnar vefsíðuna og velur viðburð.
2. Kerfið sýnir upplýsingar um viðburðinn: staðsetningu, tíma, verð og stutta lýsingu.
3. Viðskiptavinur velur fjölda miða.
4. Kerfið athugar framboð í gagnagrunninum og staðfestir að nógu margir miðar séu til.
5. Viðskiptavinur fer í greiðslu og velur greiðsluleið.
6. Greiðsluþjónustan afgreiðir greiðsluna og kerfið fær staðfestingu.
7. Kerfið skráir söluna í gagnagrunninn.
8. Kerfið sendir viðskiptavini miðann með SMS eða sem QR-kóða.

## Valflæði
- A1: Viðskiptavinur er með aðgang og skráir sig inn áður en hann kaupir, í stað þess að kaupa án aðgangs.
  Flæðið heldur svo áfram í skrefi 3.

## Undantekningar
- E1: Of fáir miðar eru til. Kerfið lætur viðskiptavin vita og hann velur færri miða eða annan viðburð.
- E2: Greiðslan mistekst eða er hafnað. Kerfið lætur viðskiptavin vita og hann getur reynt aftur.
  Engin miðar eru skráðir sem seldir.
- E3: Viðskiptavinur gerir villu í pöntun og biður starfsmann um að leiðrétta hana.

## Forgangur
- Hár. Þetta er kjarnavirkni kerfisins og styður BO-1 (Auka sölu miða á netinu um 10% innan þriggja mánaða).

## Tíðni notkunar
- Mjög oft, í hvert sinn sem viðskiptavinur kaupir miða á netinu. Erfitt að segja nákvæmlega hversu oft.

## Viðskiptareglur
- BR-1: Sama miðann má ekki selja tvisvar. Netsala og afgreiðsla nota sama gagnagrunn til að tryggja það.

## Forsendur (Assumptions)
- Greiðslur fara í gegnum ytri greiðsluþjónustu (ytri skil).
- Ekki þarf að stofna aðgang til að kaupa miða.
- Kerfið er sniðmát fyrir miðakerfi sem fyrirtæki nota.

## Annað
- Kerfið hefur ekki sitt eigið vefsvæði (bookit.is). Mögulega birtist „powered by Bookit“ á vefsíðum fyrirtækjanna.
