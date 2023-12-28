[Domů](/README.md) / [Architektonická rozhodnutí](/ADR/README.md) / [Integrace SMS a telefonní brány (ADR)](/ADR/integrace-sms-telefonni-brany.md)

# Architektonické rozhodnutí o integraci SMS a telefonní brány

Datum vytvoření: 28.12.2023

## Status
Schválené

## Context
Systém pro správu konferencí musí účastníkům umožňovat hodnocení a hlasování o přednáškách prostřednictvím SMS a telefonu.

## Decision
Rozhodli jsme se integrovat SMS a telefonní bránu od společnosti Twilio. Twilio je společností Gartner označován za leadera v oblasti cloudových poskytovatelů telekomunikačních služeb. 

## Consequences 
Díky integraci SMS a telefonní brány bude účastníkům konferencí umožněno hodnocení a hlasování o přednáškách prostřednictvím odesílání SMS zpráv a usktučňováním telefonnických hovorů. Aplikace pro správu konferencí bude integrována s cloudovou platformou Twilio, díky čemuž bude možné programově přijímat hlasovací SMS zprávy a telefonní hovory od účastníků konferencí nebo jim naopak odesílat potvrzení o přijetí jejich hlasů.
