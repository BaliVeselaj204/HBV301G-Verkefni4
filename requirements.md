# Niðurstöður kröfusöfnunar
## Notendakröfur
- UR-1 Viðskiptavinur þarf að geta valið fjölda miða á vefsíðunni.
- UR-2 Viðskiptavinur þarf að geta greitt fyrir miðana sína í gegnum vefsíðuna.
- UR-3 Viðskiptavinur þarf að geta séð upplýsingar um viðburði þegar hann er að skoða vefsíðuna.
- UR-4 Viðskiptavinur þarf að fá miðana sína afhenta sem QR kóða með SMS skilaboðum.
- UR-5 Viðskiptavinur þarf að geta notað miðan sinn með því að sýna QR kóða sem var sendur til hans eftir miðakaup.
- UR-6 Viðburðarstjóri þarf að geta skráð nýja viðburði á vefsíðuna.

## Virkniskröfur
- FR-1 Kerfið skal birta staðsetningu, tíma, miðaverð og stutta lýsingu fyrir hvern viðburð.
- FR-2 Kerfið skal senda viðskiptavini QR kóða fyrir keyptan miða með SMS skilaboðum eftir að greiðsla er staðfest.
- FR-3 Kerfið skal uppfæra framboð miða eftir staðfest kaup þannig að bæði netsala og afgreiðsla noti uppfært framboð.

## Viðskiptareglur
- BR-1 Sama miðan má ekki selja oftar en einu sinni.

## Ytri skil 
- UI-1 Kerfið skal tengjast ytri greiðsluþjónustu til að afgreiða greiðslur fyrir miða.

## Takmarkanir
- C-1 Kerfið þarf að vera vefsíða.
- C-2 Netsala og sala í afgreiðslu skulu nota sama gagnagrunn.

## Atriði sem þarf að kanna nánar
- Hvaða greiðsluþjónustu á kerfið að tengjast og hvers konar greiðslumáta þarf að styðja?
- Hvernig fær kerfið símanúmer viðskiptavinar fyrir afhendingu miða?
- Fær hver miði sérstakan QR-kóða eða er einn QR-kóði fyrir alla miða í sömu pöntun?
- Eru miðar teknir frá á meðan greiðsla fer fram og hvenær verða þeir aftur lausir ef kaup klárast ekki?
- Hvernig á kerfið að bregðast við ef greiðsla er staðfest en SMS-skilaboð berast ekki til viðskiptavinar?
- Hversu langur tími má líða frá staðfestri greiðslu þar til viðskiptavinur fær miðana með SMS?
- Er sannprófun QR-kóða við inngang hluti af Bookit og hver á að framkvæma hana?
- Hver á að geta leiðrétt villur í pöntunum og hvaða breytingar á kerfið að leyfa?
