# Legotillverkaren

- A-nivå
- [GitBook](https://coursepress.gitbook.io/1dv021/ovningsuppgifter/del-2/a-niva/legotillverkaren)
- [Lösningsförslag](https://github.com/1dv021/exercise-solution-proposals/tree/master/part-2/lego-maker)


>__VIKTIGT!__ Innan du börjar arbeta med övningsuppgiften är det viktigt att du följer guiden [Att komma igång med en övningsuppgift](https://coursepress.gitbook.io/1dv021/guider/att-komma-igang-med-en-ovningsuppgift) för att lägga till övningsuppgiftens repo till ditt repo för övningsuppgifter.

## Uppgift

Hämta hem övningsuppgiftens repo, lägg till en .gitignore-fil och komplettera enligt nedan.

I denna uppgift ska du komplettera med kod så att objekt, som representerar en enkel legobit, skapas enligt tre olika designmönster, _"Factory Pattern"_, _"Constructor Pattern"_ och _"Constructor/Prototype Pattern"_ .

Övningsuppgiften är uppdelad i tre filer och du ska skriva kod i som skapar objekt enligt nämnda designmönster. Genomför uppgiften genom att arbeta med filerna, och designmönsterna, i tur och ordning.

1. `lego-1-factory-pattern.js` - _"Factory Pattern"_
2. `lego-2-constructor-pattern.js` - _"Constructor Pattern"_
3. `lego-3-constructor-prototype-pattern.js` - _"Constructor/Prototype Pattern"_
4. `lego-4-class.js` - _"Class"_
5. `lego-5-object-create.js` - _"Constructor Pattern with Object.create"_

Genom att använda de olika designmönstren ska objekt skapas som har egenskaper och metoder enligt nedan.

### Egenskaper

- `x`, antal knoppar i horisontell led, standardvärde 2.
- `y`, antal knoppar i vertikal led, standardvärde 4.
- `color`, färg som sträng, standardvärde 'red'.

### Metoder

- `toString`, returnerar en sträng representerande objektet, `® ® ® ®\n® ® ® ®` ska retuneras för ett objekt där `x` är 4 och `y` är 2.
- `render`, skriver ut strängen metoden `toString` returnerar i ett konsolfönster.

## Tips

__Ta del av föreläsning 6 innan du genomför denna uppgift!__

Genom att köra testerna som kommer med övningsuppgiften kan du undersöka om koden du skrivit löst uppgiften (i alla fall enligt testet...).