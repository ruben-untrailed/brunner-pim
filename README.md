# Brunner PIM (Product Informatie Management)

Brunner PIM is een in-house, op maat gemaakte webapplicatie voor het centraal beheren van productinformatie, technische specificaties en marketplace-koppelingen (zoals Bol.com, Obelink, Decathlon en Amazon). 

Het systeem is ontworpen als een Single Page Application (SPA) met een focus op snelheid, gebruiksvriendelijkheid en directe database-synchronisatie via Supabase.

---

## ✨ Functionaliteiten

* **Beveiligde Toegang:** Afgeschermd met een inlogscherm via Supabase Authentication.
* **Productbeheer:** Overzichtelijke lijst van alle producten met zoek- en filterfunctionaliteit (zoeken op naam, EAN of MPN).
* **Dynamische Attributen:** Het systeem toont dynamisch de benodigde invoervelden op basis van de gekoppelde marketplace-categorie (d.m.v. template mapping).
* **Marketplace Integratie:** Specifieke tabbladen voor het beheren van categorie-ID's en content voor Bol, Obelink, Decathlon en Amazon (bijv. Amazon bulletpoints en zoektrefwoorden).
* **Live Opslaan:** Directe opslag in de database zonder de pagina te herladen.
* **Afbeeldingen Preview:** Visuele weergave van ingevoerde afbeeldings-URL's.

---

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (CSS Variables, Grid/Flexbox), Vanilla JavaScript.
* **Backend / Database:** [Supabase](https://supabase.com/) (PostgreSQL, REST API, Auth).
* **Beveiliging:** Row Level Security (RLS) & Client-side HTML-escaping tegen XSS.

---

## 🚀 Installatie & Configuratie

Om dit project lokaal of op een nieuwe server te draaien, moet de Supabase backend correct worden geconfigureerd.

### 1. Repository Clonen
```bash
git clone [https://github.com/jouw-gebruikersnaam/brunner-pim.git](https://github.com/jouw-gebruikersnaam/brunner-pim.git)
cd brunner-pim
