# NFTNAFAKA

NFTNAFAKA je projekt digitalnih radova s motivima ljubavi, dijeljenja, pomoći i mira. Ovaj repozitorij čuva izvorni kod prototipa NFT ugovora i web sučelja iz 2025.

## Status za posjetitelje

Javna stranica trenutačno predstavlja projekt. Mintanje putem ovog repozitorija nije omogućeno dok se ne potvrde objavljeni ugovor, njegova mreža, metapodaci i raspoloživost SFT nagrada. Ne šaljite BNB na adresu ugovora na temelju starog teksta stranice.

## Povijesna tehnička verzija

Datoteka `contract` sadrži izvorni kod nacrta Solidity ugovora s ograničenjem od 100 000 NFT-ova, cijenom od 0,05 BNB i predviđenom nagradom od 100 SFT po NFT-u. Te vrijednosti opisuju **kod u repozitoriju**, ne potvrđuju stanje ni ponašanje ugovora na blockchainu. Kod koristi BNB Smart Chain; ovaj NFT projekt nije Polygon projekt tokenizacije nekretnina niti ALIMTU.

U starim datotekama navodi se adresa `0x27a0689189670477e7a8164692b7c2682351cace`. Prije ponovnog uključivanja mintanja treba neovisno usporediti izvorni kod i ABI s ugovorom na [BscScanu](https://bscscan.com/address/0x27a0689189670477e7a8164692b7c2682351cace), provjeriti adresu SFT tokena i stanje nagrada, te testirati cijeli tijek.

## Datoteke

- `index.html` — aktivna javna informativna stranica
- `contract` — povijesni nacrt ugovora; prije nove objave premjestiti u `contracts/NFTNafaka.sol` nakon provjere izvora
- `abi.js`, `app.js`, `style.css`, `vercel.json` — raniji dijelovi sučelja; aktivna stranica ih ne učitava
- `Readme.me`, `NFTNafaka` — stare bilješke; nisu važeće upute za mintanje ni objavu

[Project-NFTNAFAKA](https://github.com/Radmila27456/Project-NFTNAFAKA) je zaseban prototip sučelja za isti NFT projekt, a ne druga kolekcija.

## Prije aktiviranja mintanja

1. Potvrditi mrežu i točnu adresu objavljenog NFT i SFT ugovora.
2. Usporediti funkcije i ABI objavljenog ugovora s kodom; ukloniti pozive nepostojećih funkcija.
3. Provjeriti dostupnost svakog IPFS JSON zapisa i slike te točan broj različitih radova.
4. Provjeriti SFT stanje ugovora i uvjete nagrade; jasno opisati vlasničke ovlasti i isplate.
5. Testirati spajanje novčanika, mrežu, izračun cijene, mint i prikaz rezultata prije javne prodaje.
