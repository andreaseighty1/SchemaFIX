# SchemaFIX

## Kort om vad det är

SchemaFIX är ett verktyg för dig som schemalägger personal på ett fritidshem. Du beskriver din personal, era pass och era bemanningskrav — appen pusslar ihop ett förslag på en arbetsvecka, och du finputsar resten direkt i schemavyn.

Det är byggt av en schemaläggare för andra schemaläggare. Inga abonnemang, ingen molnlagring, inga konton. Bara en sida i din webbläsare som hjälper dig pussla ihop nästa termins schema.

---

## Pitch på två rader

**SchemaFIX** hjälper dig schemalägga personalen på fritids — utan att behöva pussla i Excel eller köpa ett dyrt program. Beskriv personalen och bemanningskraven, klicka *generera*, finputsa direkt i veckovyn.

---

## Varför finns det

Schemaläggning på fritids är ett pussel som ser bedrägligt enkelt ut tills man försöker. En person jobbar 75% och kan inte börja före åtta. En annan ska helst stänga, men inte alla dagar. Öppning ska täckas, stängning ska täckas, och ingen ska få fler timmar än sin tjänstegrad. Sen kommer fredagen, som vissa fritids kör som en helt vanlig vardag medan andra rullar med olika tider varje vecka.

I de flesta verktyg får du antingen:
- en tom kalender och ingen hjälp, eller
- ett dyrt komplett system som man måste lära sig en termin innan man kan använda

SchemaFIX är ett mellanting: tillräckligt smart för att göra själva pusselarbetet, tillräckligt enkelt för att du faktiskt vågar prova en söndag kväll.

---

## Vad du kan göra

**Lägg till personal med riktiga begränsningar.** Inte bara "tjänstegrad 80%" utan också *"kan inte börja före åtta"*, *"jobbar bara eftermiddagar"*, *"är ledig på onsdagar"*, *"får bara ta de här passen"*. Du kan också ge en specifik person en regel som bara gäller på en specifik dag.

**Bygg en passbank.** Definiera de pass ni faktiskt kör — öppning, mellan, stängning, eftermiddagspass — med start, slut och vilka dagar de gäller. Du kan begränsa hur många personer som får tilldelas samma pass (för att inte få tre stycken på samma 16:45-pass).

**Sätt bemanningskrav per tid.** Säg att från 06:00 ska det finnas minst en, från 14:00 minst tre, fram till 17:45. Du kan dela upp kraven på avdelningar (avdelning A behöver 1, avdelning B behöver 2) eller ha gemensamma krav som alla räknas in i.

**Generera tre alternativ.** Appen pusslar fram tre olika versioner av samma vecka — en med fokus på bemanning, en med fokus på exakta veckotimmar, en balanserad. Du jämför, väljer den som känns bäst, eller kör en blandning.

**Finputsa direkt i veckovyn.** Klicka på en stapel och ändra start- eller sluttid. Veckotimmarna räknas om medan du skriver, så du ser direkt om personen får för många eller för få timmar. Det är så de bästa kommersiella schemaverktygen funkar — *generera utkast → manuell finjustering* — men utan prislappen.

**Fredagshantering på dina villkor.** Tre alternativ per person:
- *Passbank* — fredag genereras automatiskt som vilken vardag som helst
- *Fast tid* — samma fredag varje vecka (eller alltid ledig)
- *Rull* — varierar enligt en cykel på 1–20 veckor (med möjlighet till central mall)

**Avdelningar med färgkod.** Varje stapel i schemat färgmarkeras efter avdelning så du snabbt ser vem som hör hemma var.

**Spara, exportera, dela.** Allt sparas i en JSON-fil som du själv har kontroll över. Skicka den till en kollega eller spara backup innan du börjar fippla.

---

## Vad det *inte* är (för transparens)

- **Inte ett produktionssystem.** Allt körs i din webbläsare på din dator. Inga konton, ingen synkning mellan enheter, ingen användarhantering.
- **Ingen frånvaro- eller semesterhantering.** Den här versionen handlar om att bygga en *typvecka*. Sjukdomar och vab gör du själv ovanpå.
- **Ingen lönerapportering.** Det här är ett pusselverktyg, inte ett HR-system.
- **Ett fritids åt gången.** Om du schemalägger flera enheter får du ha en fil per fritids tills vidare.
- **PDF-utskrift kommer.** Just nu kan du bara skriva ut via webbläsarens skriv-ut-funktion.
- **Det här är beta.** Saker kan ändras, och det kan finnas buggar. Säkra dina filer ofta.

---

## Komma igång på 10 minuter

1. **Lägg till era avdelningar.** Färgkoda dem så ni ser dem tydligt i schemat.
2. **Lägg till passbanken.** Vilka pass har ni? Öppning, stängning, mellan? Lägg in dem med tider.
3. **Lägg till personalen.** För varje person: avdelning, tjänstegrad, vilka pass de får ta, ev. regler om när de kan börja/sluta. Välj fredagshantering: passbank, fast tid eller rull.
4. **Sätt bemanningskraven.** Hur många behövs vid olika tider? Gör det per avdelning eller gemensamt.
5. **Klicka *Generera schemaförslag*.** Appen ger tre alternativ — välj det du gillar bäst.
6. **Finputsa.** Klicka på en stapel i schemavyn för att ändra tider direkt. Timmar räknas om medan du skriver.

Det första försöket är aldrig perfekt. Det är heller inte poängen — poängen är att du börjar 80% framme istället för från noll.

---

## Bra att veta

**Data.** All din information ligger lokalt på din dator (i webbläsarens lagring eller i den fil du sparar). Inget skickas någonstans. Du kan exportera och importera när du vill.

**Pris.** Gratis. Öppet. Ingen registrering.

**Kompatibilitet.** Funkar i moderna webbläsare (Chrome, Firefox, Safari, Edge).

**Återkoppling.** Hittade du något konstigt? Saknas en funktion? Hör gärna av dig — det är så det här blir bättre.

---

*SchemaFIX · ett verktyg för fritidshemsschemaläggare*
