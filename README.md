# Grafikų Sistema — Procurement Schedule Generator

Interaktyvus įrankis Litgrid AB viešųjų pirkimų grafikų rengimui
ir generavimui, įvertinant nedarbo ir šventines dienas.

## Apie projektą

**Litgrid AB** — Lietuvos elektros perdavimo operatorius, pirkimus
organizuojantis pagal Lietuvos Respublikos pirkimų, atliekamų
vandentvarkos, energetikos, transporto ar pašto paslaugų srities
perkančiųjų subjektų įstatymą (PSĮ).

Pirkimo organizatorius (Pirkimų skyriaus darbuotojas) parengia
pirkimo grafiką, kuriame standartinis terminas išskaidomas į etapus,
leidžiančius efektyviai valdyti pirkimo proceso eigą.

## Grafikų tipai

| Tipas | Pavadinimas | Paskirtis | Gavėjai |
|---|---|---|---|
| **A** | Detalus pirkimų grafikas | Vidinis valdymas ir stebėjimas | Pirkimo proceso dalyviai |
| **B** | Sutrumpintas pirkimų grafikas | Pridedamas prie pirkimo sąlygų | Tiekėjai ir visuomenė |

### A tipo grafiko ypatumai
- Taikomi standartiniai terminai **arba** išimtys su pastabų lauku
- Pastabų laukas privalomas, kai išlipama iš standartinio termino
- Matomi visi pirkimo proceso etapai

### B tipo grafiko ypatumai
- Tik pagrindiniai pirkimo vykdymo etapai
- Pastabų laukas neatvaizduojamas
- Skirtas išoriniam naudojimui

## Pirkimo būdai

Grafikų generavimas palaikomas šiems pirkimo būdams (pagal PSĮ).
> ⚠️ Žodžiu vykdomiems pirkimams ir CPO pirkimams grafikai

## Įvedami duomenys

Kiekviename grafike privaloma užpildyti:

1. **Pirkimo pavadinimas**
2. **Pirkimo iniciatorius**
3. **Pirkimo organizatorius**
4. **Pirkimo pradžios data** (laikoma pirkimo paraiškos priskyrimo data)

## Įrankio funkcionalumas

- 📋 Pirkimo būdo pasirinkimas
- 📅 Automatinis etapų skaičiavimas darbo dienomis
- 🗓️ Lietuvos šventinių ir nedarbo dienų įskaičiavimas
- ✏️ Atskiro etapo trukmės koregavimas
- ⚠️ Privalomas pastabų laukas nukrypus nuo standartinio termino
- 👁️ Grafiko peržiūra prieš generavimą
- 📄 Generavimas Excel (.xlsx) formatu — A ir B tipai atskirai

## Generavimo formatas

**Rekomenduojamas formatas: Excel (.xlsx)**

- Universalus — tinkamas DVS ir kitiems dokumentų valdymo sistemoms
- Vizualiai struktūruotas su etapų spalviniu žymėjimu
- Lengvai pridedamas prie pirkimo dokumentų
- Palaikomas visose organizacijose be papildomos programinės įrangos

## Stilistika

- 🎨 Korporatyvinis, profesionalus dizainas
- 🔵 Litgrid spalvų paletė (mėlyna / balta)
- 🏢 Litgrid logotipo atspindys įrankyje

## Teisinė bazė

- LR Pirkimų, atliekamų vandentvarkos, energetikos, transporto ar
  pašto paslaugų srities perkančiųjų subjektų įstatymas (PSĮ)
- Litgrid AB standartiniai pirkimų terminai

## Failai

| Failas | Aprašymas |
|---|---|
| `index.html` | Pagrindinis įrankio failas |
| `terminai.json` | Standartiniai pirkimų terminai pagal būdą |
| `sventes.json` | Lietuvos šventinių dienų sąrašas (2025–2028) |

## Statusas

🚧 Aktyviai kuriama

## Atsakingas

Arūnas Jurgelaitis — Head of Procurement, Litgrid AB
