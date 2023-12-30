[Domů](/README.md) / [Architektonická rozhodnutí](/ADR/README.md)

# Architektonické rozhodnutí o nasazení systému do cloudového prostředí

Datum vytvoření: 30.12.2023

## Status
Schválené

## Context
Organizátor konferencí vyžaduje komplexní systém pro správu konferencí, který je přizpůsobený potřebám stovky řečníků, desítky zaměstnanců akce a tisíců účastníků. Systém musí umožňovat efektivní správu rozvrhů, prezentací, a poskytovat možnost hodnocení a hlasování prostřednictvím různých kanálů, včetně SMS a telefonu. Důležitý je i vzhled stránek, který musí být snadno přizpůsobitelný pro jednotlivé konference.
## Decision
Rozhodli jsme se pro nasazení systému do cloudového prostředí s integrací SMS a telefonní brány od společnosti Twilio. Nasazení do cloudu umožní škálovatelnost a flexibilitu, což je klíčové vzhledem k "hustému" provozu během konferencí. 
## Consequences
Nasazením systému pro správu konferencí do cloudového prostředí a integrací SMS a telefonní brány od Twilio získáváme významně zvýšenou škálovatelnost a dostupnost, což je zásadní pro zvládání vysoké návštěvnosti a různorodých požadavků během konferencí. Současně cloudové řešení přináší výhody v podobě snížení provozních nákladů, lepšího zabezpečení dat, vyšší spolehlivosti a zlepšení dostupnosti aktuálních informací pro účastníky, což celkově vylepšuje uživatelský zážitek a efektivitu systému.