# Inlämning 2 – CSS

I denna uppgift vidareutvecklas HTML-sidan från inlämning 1 med CSS.

Målet är att skapa en responsiv layout med CSS Grid och Flexbox som fungerar på både mobil och dator.

## Publicerad webbplats

https://ellencodeab.github.io/html-inlamning-2/

## Validering

CSS har validerats med W3C CSS Validator utan fel.

En skärmbild av valideringsresultatet finns i repositoryt.

## Tillgänglighet och Lighthouse

Jag har testat webbplatsens tillgänglighet med Lighthouse i Google Chrome Dev.

Testet gjordes på den publicerade webbplatsen med inställningen Mobile och kategorin Accessibility.

Resultatet blev **100 av 100 poäng**. Lighthouse visade 26 godkända automatiska kontroller.

Jag kontrollerade särskilt färgkontrasten mellan text och bakgrund. Kontrollen *Background and foreground colors have a sufficient contrast ratio* blev godkänd, vilket betyder att Lighthouse inte hittade några problem med färgkontrasten.

Jag sparade två skärmbilder från testet i mitt GitHub-repository:

- `Skärmavbild 2026-10-16 kl. 12.16.55.png` – Lighthouse-resultatet.
- `Skärmavbild 2026-10-16 kl. 12.18.28.png` – kontrollen av färgkontrasten.

Testet visar att webbplatsen klarade Lighthouse automatiska tillgänglighetskontroller. Jag är medveten om att vissa delar av tillgängligheten även behöver kontrolleras manuellt.

## Responsiv design och testning

Webbplatsen har testats i Safari på både dator och olika skärmstorlekar med hjälp av webbläsarens responsiva designläge.

Följande skärmbredder har kontrollerats:

- **320 px:** Test av en smal mobilskärm. Artiklarna visas under varandra och bilderna anpassas till skärmens bredd. Navigeringen, formuläret och sidfoten har kontrollerats. Hela sidan går att scrolla ned till slutet utan synliga layoutproblem.
- **375 px:** Test av en vanlig mobilbredd. Innehållet visas i en kolumn och bilderna anpassas till skärmen.
- **768 px:** Test av en större skärm. Artiklarna visas i två kolumner och bilderna håller sig inom sidans bredd. Även formuläret och sidfoten har kontrollerats.
- **Dator:** Webbplatsen har öppnats och kontrollerats i en vanlig webbläsare för att se att layouten fungerar på större skärmar.

Layouten är byggd med **CSS Grid och Flexbox**. CSS Grid används för att placera artiklarna i kolumner och Flexbox används för navigeringen. Med hjälp av en media query ändras artikellayouten till en kolumn på mindre skärmar.

Vid testerna kontrollerades följande delar:

- Sidans rubrik och navigering.
- Artiklarna och deras placering.
- Bildernas storlek och anpassning.
- Textens läsbarhet.
- Formulärets fält, knappar och placering.
- Sidfotens kontaktuppgifter och länkar.
- Möjligheten att scrolla genom hela sidan.

Inga tydliga problem med överlappande innehåll eller horisontell överflödning upptäcktes vid de testade skärmstorlekarna.

Webbplatsen har även validerats med **W3C CSS Validator**, som inte rapporterade några CSS-fel. En skärmbild av valideringsresultatet finns i GitHub-repositoryt.

## Användning av AI

Under arbetet med Inlämning 2 använde jag ChatGPT för att få hjälp med CSS och förstå hur Grid, Flexbox och responsiv design fungerar.

Jag fick förklaringar och exempel på hur jag kunde bygga upp sidan och anpassa den till olika skärmstorlekar. När något var svårt att förstå kunde jag ställa frågor och gå igenom koden steg för steg.

Jag lade själv in koden i GitHub, gjorde ändringar och sparade arbetet med commits. Sedan publicerade jag sidan med GitHub Pages och kontrollerade hur den såg ut på både dator och mobil, bland annat med en skärmbredd på 375 px.

Jag kontrollerade också CSS-koden med W3C CSS Validator. Resultatet visade inga fel och jag sparade en skärmbild i repositoryt.

ChatGPT hjälpte mig även att gå igenom uppgiftens krav och formulera dokumentationen i README.
