[Domů](/README.md) / [Architektonická rozhodnutí](/ADR/README.md) / [ADR o celkové architektuře systému](/ADR/celkova-architektura.md)

# Architektonické rozhodnutí o celkové architektuře systému

Datum vytvoření: 03.01.2024

## Status
Návrh

## Context
Pro systém pro správu konferencí je třeba vybrat vhodnou celkovou architektu systému

## Decision
Rozhodli jsme se mít celkovou architekturu podle principů SOA (service oriented architecture). Hlavní komponentou bude ESB (enterprise service bus), který bude rozesílat požadavky na jednotlivé služby.
Tyto služby budou pokrývat specifickou část funkcionalit, např. služba pro správu obsahu, rozvrhování, uživatele, atd. Podrobnosti lze nalézt v dokumentaci. 
Jednotlivé služby budou separátně nasazeny v cloudu.

## Consequences 
Implementací architektury SOA docílíme rozdělení aplikace na funkční celky, což nám pomůže jednoduše udržovat kód, testovat a rozšiřovat. Systém budeme moci rozšiřovat o další služby.
Díky separátnímu nasazení jednotlivých služeb do cloudu budeme moci jednoduše nastavit škálování podle vytíženosti.
Implementace SOA bude s sebou nést zvýšené požadavky na správu kvůli potřebě komunikace mezi službami a ESB.
