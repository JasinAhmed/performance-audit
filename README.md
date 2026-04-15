# Performance Audit 

Doe een Performance audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [INSTRUCTIONS](https://github.com/fdnd-task/performance-audit/blob/main/docs/INSTRUCTIONS.md).



### SportCity website

Ik heb de website van SportCity getest.  
Dit is een fitness website waar je informatie kunt vinden over sportscholen, abonnementen en locaties.

*(<img width="1910" height="861" alt="image" src="https://github.com/user-attachments/assets/21dba824-6399-47a8-a7c9-0b357b9d2bcd" />)*


## Testresultaten

### Lighthouse (Mobile & Desktop)
<img width="772" height="858" alt="image" src="https://github.com/user-attachments/assets/82f9de53-51d8-4f2c-b890-1b2ff70721ca" />

<img width="752" height="833" alt="image" src="https://github.com/user-attachments/assets/7f8a8ba3-c92f-4563-adf9-39caf3a9c089" />


### PageSpeed Insights (Core Web Vitals)
<img width="1906" height="904" alt="Schermafbeelding" src="https://github.com/user-attachments/assets/7a566d13-d212-48af-a0ad-e99f3b4ae55e" />

### WebPageTest (Waterfall)
![Waterfall](https://github.com/user-attachments/assets/6fdffdba-91dd-46f3-baf3-1d197db3a19e)


## Samenvatting van bevindingen

Ik heb de website getest met Lighthouse, PageSpeed Insights en WebPageTest.  

Wat mij vooral opvalt:

- De website is **trager op mobiel dan op desktop**
- JavaScript is **te zwaar** en kost veel tijd (±5,8s)
- Er wordt **veel onnodige code geladen** (JS en CSS)
- De website laadt **grote bestanden (±7.8 MB)**, vooral video’s
- Er zijn **lange taken**, waardoor de website traag reageert
- Afbeeldingen hebben geen vaste grootte, waardoor de layout verspringt

Alle tools laten eigenlijk dezelfde problemen zien.  
Ook echte gebruikersdata (CrUX) bevestigt dat deze problemen impact hebben.

## Conclusie

De website werkt goed op desktop, maar **op mobiel is de performance minder goed**.  
De grootste problemen zijn JavaScript en grote bestanden.

## Aanbevelingen

- JavaScript opschonen en kleiner maken  
- Video’s optimaliseren of lazy loading gebruiken  
- Ongebruikte CSS en JavaScript verwijderen  
- Afbeeldingen vaste afmetingen geven  


Voor de volledige analyse en uitleg, zie de Wiki van deze repository.


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
