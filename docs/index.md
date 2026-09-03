---
hide:
  - navigation
  - toc
---

# Gmina Środa Śląska

Waste collection for Gmina Środa Śląska.

All data  based on source: [https://srodowisko.srodaslaska.pl/gospodarka-odpadami/harmonogram-odbioru-odpadow-komunalnych/](https://srodowisko.srodaslaska.pl/gospodarka-odpadami/harmonogram-odbioru-odpadow-komunalnych/).

Support by [github issues](https://github.com/ksciana/waste_collection/issues).

## Configuration via configuration.yaml
```yaml
waste_collection_schedule:
  sources:
    - name: gmina_sroda_slaska_pl
      args:
        location_id: LOCATION_ID
```

### Configuration Variables

**location_id**  
*(string) (required)*

## Example

```yaml
waste_collection_schedule:
  sources:
    - name: gmina_sroda_slaska_pl
      args:
        location_id: brodno
```

## Location definition

Replace `LOCATION_ID` with following `Id`:

| Id | Location | Details |
| --: | --- | --- |
| brodno | Brodno | |
| bukowek | Bukówek | |
| cesarzowice | Cesarzowice | |
| chwalimierz | Chwalimierz | |
| ciechow | Ciechów | |
| gozdawa | Gozdawa | |
| jastrzebce | Jastrzębce | |
| jugowiec | Jugowiec | |
| juszczyn | Juszczyn | |
| kobylniki | Kobylniki | |
| komorniki | Komorniki | |
| kryniczno | Kryniczno | |
| kulin | Kulin | |
| ligotka | Ligotka | |
| lipnica | Lipnica | |
| lisiny | Lisiny | |
| michalow | Michałów | |
| odyniec | Odyniec | |
| ogrodnica | Ogrodnica | |
| peczkow | Pęczków | |
| proszkow | Proszków | |
| przedmoscie | Przedmoście | |
| rakoszyce | Rakoszyce | |
| rzeczyca | Rzeczyca | |
| sroda_sl_i_rejon | Środa Śląska I rejon | Środa Śląska Rej I: Baczyńskiego, Basztowa, Białoskórnicza, Boya-Żeleńskiego, Brodatego H., Chwalimierska, Cmentarna, Czereśniowa, Daszyńskiego, Dojazdowa, Flamandzka, Floriańska, Górna, Gruszkowa, Jabłkowa, Jagiellońska, Kajakowa, Karnasa, Kilińskiego, Konstytucji 3 Maja, Kopernika, Korwina, Kościuszki, Księżnej Jadwigi, Księżycowa, Łanowa, Łąkowa, Mickiewicza, Mleczarska, Morelowa, Ogrodowa, Oławska, Parkowa, Partyzantów, Piastów Śląskich, Plac Solny, Plac Wolności, Probusa H., Przyszkolna, Rakoszycka, Różana, Skłodowskiej-Curie, Słoneczna, Słowackiego, Spokojna, Stawowa, Strzelecka, Szkolna, Śląska, Śliwkowa, Wąska, Wierzbowa, Willowa, Winnicza, Winogronowa, Wiśniowa, Wrocławska, Zaciszna, Żwirki i Wigury. |
| sroda_sl_ii_rejon | Środa Śląska II rejon |  Środa Śląska Rej II: 1 Maja, Akacjowa, Bluszczowa, Bociania, Chabrowa, Dębowa, Działkowa, Fiołkowa, Goździkowa, Hallera, Irysowa, Jarzębinowa, Jastrzębia, Jaśminowa, Jesionowa, Kasztanowa, Klonowa, Kolejowa, Konwaliowa, Krucza, Legnicka, Lipowa, Makowa, Malczycka, Miła, Młynarska, Mostowa, Na Polance, Nasturcjowa, Ogrody Zamkowe, Orla, Rumiankowa, Sikorskiego, Sokola, Spacerowa, Spółdzielcza, Stacyjna, Storczykowa, Św. Andrzeja, Świdnicka, Targowa, Topolowa, Trakt św. Jakuba, Traugutta, Tulipanowa, Waniliowa, Wiejska, Wrzosowa, Żurawia |
| sroda_sl_milosza | Środa Śl. Miłosza | |
| sroda_sl_ogrodnicka | Środa Śl. Ogrodnicka | |
| sroda_sl_reymonta | Środa Śl. Reymonta | |
| swiete | Święte | |
