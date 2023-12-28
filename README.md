# 4IT575 - Seminární práce
Seminární práce z předmětu Softwarové architektury

## Obsah
- [Zadání práce](#uživatelé)
- [Architektonická rozhodnutí](./ADR/README.md)
- [Dokumentace architektury (SOA)](./Dokumentace/SOA/README.md)
- [Dokumentace architektury (EDA)](./Dokumentace/EDA/README.md)

## Úkol:
1.	Na základě níže popsaných požadavků navrhněte dvě architektury vhodné pro implementaci dané aplikace.
2.	Navržené architektury zdokumentujte.
3.	V závěru zhodnoťte, která z vybraných architektur je výhodnější a proč.

> **Poznámka:**
> Pokud ze zadání přímo nevyplyne nějaká skutečnost, kterou potřebujete znát, domluvte se ve skupině, a sami ji dodefinujte, tak jako byste se na ni doptali zákazníka.


## Popis aplikace
Organizátor konferencí potřebuje systém pro správu konferencí, které pořádá, a to jak pro řečníky, tak pro účastníky.

### Uživatelé 
stovky řečníků, desítky zaměstnanců akce, tisíce účastníků

### Požadavky
-	účastníci mají přístup k rozvrhu přednášek online, včetně přidělení místností
-	řečníci mohou spravovat přednášky (zadávat, upravovat, měnit)
-	účastníci mohou "hlasovat o zvýšení/ snížení počtu přednášek".
-	pořadatel může na poslední chvíli účastníky informovat o změnách v rozvrhu (pokud se účastníci přihlásí).
-	každá konference (s odlišným tématem) může mít vlastní brand
-	prezentace řečníků jsou přístupné online pouze účastníkům
-	systém hodnocení prostřednictvím webové stránky, e-mailu, SMS nebo telefonu

### Další souvislosti
- Konference probíhají po celé Evropě.
- Velmi malý podpůrný personál.
- "Hustý" provoz: v době konání konference extrémně rušno.
- Organizátor konference chce snadno "skinovat" stránky.
