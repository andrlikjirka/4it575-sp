[Domů](/README.md) / [Dokumentace EDA](/Dokumentace/EDA/README.md) / [Component View](/Dokumentace/EDA/pages/component-view.md)

# Component View

## Primary Presentation
Tento komponentový diagram zobrazuje event-driven architekturu systému pro správu konferencí, který podporuje interakce mezi stovkami řečníků, desítkami zaměstnanců a tisíci účastníků. Architektura je navržena pro rychlou a efektivní odezvu na události v reálném čase, což je nezbytné pro dynamické prostředí konferencí.

![Component diagram](../assets/component-diagram.png)

Vysvětlivka pro diagram:

Komponenta: Jednotka, která zpracovává a reaguje na události (events).

![komponenta](../assets/component-2.png)

Rozhraní: Definuje typy událostí, které komponenty posílají nebo přijímají.

![rozhraní](../assets/component-3.png)

Balíček: Skupina komponent, které jsou součástí většího procesního toku.

![balíček](../assets/component-1.png)

## Element Catalog

- **Web UI**: Uživatelské rozhraní pro web, poskytuje interakci s uživateli prostřednictvím webového prohlížeče.

- **Mobilní UI**: Uživatelské rozhraní optimalizované pro mobilní zařízení, poskytuje interakci s uživateli skrze mobilní aplikace.

- **Mediátor**: Centrální komponenta, která řídí komunikaci mezi uživatelskými rozhraními a backendovými službami, zajišťuje koordinaci a směrování událostí v systému.

- **Služba plánování (Scheduling Service)**: Spravuje kalendáře událostí a plánování přednášek pro konference.

- **Služba správy řečníků (Speaker Management Service)**: Umožňuje řečníkům spravovat jejich profily a přednášky.

- **Hlasovací služba (Voting Service)**: Zpracovává hlasování účastníků o přednáškách a dalších aspektech konference.

- **Služba brandingu (Branding Service)**: Přizpůsobuje vizuální prvky konference pro podporu jednotné značky a identity.

- **Služba přístupu k obsahu (Content Access Service)**: Řídí přístup k obsahu přednášek a dalším materiálům konference.

- **Služba zpětné vazby (Feedback Service)**: Sbírá a analyzuje zpětnou vazbu od účastníků konference.

- **Notifikační služba (Notification Service)**: Poskytuje uživatelům upozornění na změny v rozvrhu a důležité informace týkající se konference.

- **Databázový systém (Database System)**: Ukládá a spravuje data potřebná pro běh konferenčního systému, včetně uživatelských dat a informací o událostech.

Tato komponentová struktura umožňuje efektivní zpracování a distribuci událostí v rámci celého systému, zatímco podporuje škálovatelnost a flexibilitu potřebnou pro efektivní správu konferencí.
## Variability Guide
Systém umožňuje adaptabilitu na základě konfigurace zpracování událostí, což je klíčové pro správu různorodých typů událostí a integraci s různými technologickými stacky bez závislosti na konkrétním poskytovateli.

## Other Information
Architektura je motivována potřebou efektivního zpracování velkého objemu událostí, které jsou typické pro konferenční prostředí, a její design podporuje rychlé šíření informací a umožňuje flexibilní škálování podle aktuálních požadavků a provozních podmínek.