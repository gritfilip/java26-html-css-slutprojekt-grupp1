Grit Lyftarna

Om projektet:

Vi har gjort en hemsida för ett påhittat gym som heter Grit Lyftarna.
Vi har byggt hemsidan med HTML, CSS och Bootstrap för att den ska fungera på både mobil och dator.

Gruppmedlemmar:

- Filip: Grundmall, navbar (ifrån Bootstrap), footer, startsidan (index), teamet sidan och CSS
- Ivan: Har gjort en skiss som vi utgått ifrån.
- Robin
- Baha

Länkar:

GitHub Pages:
GitHub: https://github.com/gritfilip/java26-html-css-slutprojekt-grupp1
Kanban: https://github.com/users/gritfilip/projects/4

Skisser och inspiration:

Vi har utgått från en skiss som Ivan gjort.
Bootstrap har haft inspiration med, navbaren och dark/light mode är därifrån:
https://getbootstrap.com/docs/5.3/components/navbar/#how-it-works
https://getbootstrap.com/docs/5.3/customize/color-modes/#dark-mode

Vi har också hämtat inspiration från andra gymsidor:

- SATS: https://www.sats.se/
- Nordic Wellness: https://nordicwellness.se/
- The Raw Gym: https://therawgym.se/

Inspiration till sponsorslidern:

https://www.youtube.com/watch?v=Reu0hHbis5w

Mobilvy och dark mode/light mode:

Vi har jobbat med mobile first och använt Grid, Flexbox och media queries
för att anpassa sidan till olika skärmstorlekar.
På mobil använder vi Bootstraps hamburgarmeny.

dark mode/Light mode:

Vi har använt Bootstrap tillsammans med egen CSS för att få light och dark mode att fungera.

Bilder och ikoner:

Bilderna på hemsidan är hämtade via Google och skapade med chatgpt.
Ikoner från Feather Icons: https://feathericons.com/

Kända problem:

Tillgänglighetstester:

Har testat tillgängligheten på index.html och teamet.html.

Tangentbord: Testat tab, shift + Tab och enter. Man kan ta sig runt på hemsidan med hjälp av detta och allt fungerar att trycka på. Hamburgaremeny öppnar sig osv och länkar fungerar.

Hoppa till innehåll: Har skapat en "skip-link" som är det första som kommer fram när man trycket tab och trycker man enter tar den en till main.

150 % zoom: Har testat båda sidorna och allt går fortfarande att läsa och använda.

Kontrast: Testat med Chrome Devtools i både dark mode och light mode. Fick ändra några röda och guldfärgade färger för att klara contrast ratio enligt WCAG AA.
https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html
https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html

Minskad rörelse: Har lagt till reduced motion och testat med Chrome Devtools. Animationerna stängs av om användaren har valt att ha minskad rörelse.

Sponsorslidern: Vid minskad rörelse visas bilderna som vanliga bilder istället för att röra sig.

Bilder: Har använt <picture> på teamet-sidan för att anpassa bilderna efter skärmstorleken. Vid ändring från mobile till tablet och uppåt kommer en annan bild.

Projektuppdatering: Design och HTML-struktur för gymwebbplats

Arbetet med gymwebbplatsen har tagit ett stort kliv framåt. Jag har nyligen färdigställt en första skiss som sätter den visuella ramen och layouten för hela projektet. Fokus i skissen har varit att skapa en modern, energifylld och användarvänlig känsla som uppmuntrar besökaren att utforska vårt träningsutbud.

Utifrån skissen har jag påbörjat det praktiska kodningsarbetet och gjort strukturella ändringar på flera av HTML-sidorna. Bland annat har navigationsmenyn uppdaterats för att göra det enklare att hitta till schemat för gruppträning, medlemsvillkor och kontaktsida. Rubriker, textblock och sektioner för bilder har optimerats för att säkerställa god tillgänglighet och en tydlig informationshierarki.

Nästa steg i utvecklingen blir att förfina CSS-stylingen för att matcha skissens färger och typografi exakt, samt att säkerställa att sidorna är helt responsiva och fungerar sömlöst på både mobiler och datorer. 