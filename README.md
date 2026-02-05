# Jest Testing - Opdrachten 

Een verzameling hands-on opdrachten om Jest testing te leren voor JavaScript en React.

## Wat is Jest?

Jest is een testing framework voor JavaScript. Het helpt je automatisch te checken of je code werkt zoals verwacht, zonder elke keer handmatig te testen in de browser.

## Waarom Testen?

**"Kan ik niet gewoon zelf testen in de browser?"**

Ja, maar:
- Handmatig testen kost 5-10 minuten per keer
- Na elke code wijziging moet je ALLES opnieuw testen
- Je vergeet makkelijk edge cases
- Naarmate je app groeit wordt dit onhoudbaar

**Met Jest:**
- Schrijf tests 1x (10 minuten)
- Run alle tests in 2 seconden: `npm test`
- Tests vangen bugs voordat gebruikers ze zien
- Je krijgt vertrouwen om code te wijzigen

**Break-even:** Na 2-3 code wijzigingen heb je de tijd terugverdiend. Daarna is het pure winst!

## Opdrachten

### JavaScript Basis (3 opdrachten)
1. **Todo Item Validatie** - Basis matchers (`toBe`, `toEqual`)
2. **Wachtwoord Checker** - Objecten en arrays testen
3. **Producten Sorteren** - Arrays en `toContain`

### JavaScript met Setup (2 opdrachten)
4. **ShoppingCart Class** - `beforeEach` en class methods
5. **Game Score Tracker** - Setup/teardown lifecycle

### React Components (3 opdrachten)
6. **ProfileCard Component** - Basis rendering tests
7. **LikeButton Component** - User events en state
8. **SearchBar Component** - Input handling en conditional rendering

## Installatie

### 1. Gebruik deze template
1. Klik op de groene knop **"Use this template"** bovenaan deze pagina
2. Kies **"Create a new repository"**
3. Geef je repository een naam (bijv. `mijn-jest-opdrachten`)
4. Klik op **"Create repository"**
5. Clone je nieuwe repository via de GitHub desktop app

### 2. Installeer Jest en dependencies
```bash
npm install --save-dev jest @testing-library/react @testing-library/jest-dom @testing-library/user-event jsdom @babel/preset-react @babel/preset-env babel-jest identity-obj-proxy
```

### 3. Test of het werkt
```bash
npm test
```

## Meer info

Voor uitgebreide uitleg over setup, matchers en component testing, zie de [Jest Cheat Sheet](https://jschaik.github.io/React-Cheat-Sheet/pages/jest/index.html).

## Tips

- Begin met de JavaScript opdrachten voordat je React test
- Run tests vaak: `npm test`
- Gebruik watch mode: `npm run test:watch`
- Lees error messages goed - ze helpen je!
