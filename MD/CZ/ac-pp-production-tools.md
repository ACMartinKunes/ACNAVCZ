---
title: "Evidence nářadí a pomůcek"
author: Autocont
ms.custom: na
ms.date: 02/26/2018
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: Human Translation
ms.sourcegitcommit: 
ms.openlocfilehash: 
ms.contentlocale: cs-cz
ms.lasthandoff: 02/26/2018

---

# <a name="pp-production-tools.md"></a>Evidence nářadí a pomůcek

Modul Evidence nářadí a pomůcek řeší problematiku evidence nářadí, pomůcek, forem a jiných potřeb obvykle evidovaných pomocí skladové evidence systému. Tento modul je postaven nad základy evidence majetku, s ohledem na sjednocení evidence pro potřeby sledování dlouhodobého majetku a evidence výrobní, tj. půjčování nářadí a pomůcek.

## Instalace

**Objekty modulu**

Objekty add-on modulu Evidence nářadí a pomůcek jsou označeny verzí **PT**.

**Další součásti instalace**

Add-on modul vyžaduje Dynamics NAV Starter Pack a Extended Pack. 

## Nastavení

**Nastavení modulu**

Základní nastavení se provede v nabídce: Oblasti / proPRODUKTIVITU / Evidence nářadí a pomůcek / Nastavení.
Je nutné nastavit minimálně jednu šablonu deníku evidence nástrojů. V šabloně je možno volit výchozí **Typ položky**, pokud by byla potřeba definovat deník jen pro jeden pohyb např. **Půjčení**. Dále je potřeba nastavit číselnou řadu dokladů, pomocí kterých se budou pohyby sledovat.
Pro každou šablonu deníku (případně list deníku) je možno definovat kontroly povinných údajů v deníku při účtování pohybu s nářadím v tabulce **Nastavení typů položky evidence nástrojů**.

**Typy poškození**

Nastavení typů poškození slouží pro rozlišení poškozených evidovaných kusů, ať s ohledem na pozdější statistické vyhodnocování, tak pro případné náhrady ze stran zaměstnanců, kteří poškozené nářadí či pomůcky vrací.
Pro zadání typu poškození jsou k dispozici pole **Kód**, **Popis** a **EAN**, ve kterém je možno definovat čárový kód pro případné využití čteček čárových kódů.

**Karta evidence nástrojů**

Karta kusové evidence dostupná v nabídce Oblasti / proPRODUKTIVITU / Evidence nářadí a pomůcek / Evidence nástrojů se používá pro sledování a evidenci všech informací o používaných pomůckách, přípravcích a nářadí.
Na záložce Evidence nástrojů je možno nastavit a sledovat údaje spojené s vlastní evidencí. V poli **EAN** je možno nastavit čárový kód pro umožnění použití čteček čárových kódů, v poli **Číslo police** je možno evidovat přesné místo uložení a dále zde jsou kalkulovaná pole s napočtenými hodnotami celkového množství a množství nářadí volného k zapůjčení.

## Použití

### Evidence nářadí a pomůcek

V nabídce Oblasti / proPRODUKTIVITU / Evidence nářadí a pomůcek je možno vybrat z přednastavených deníků evidence.
V deníku je možno volit mezi 4 typy pohybů:
* Příjem – slouží k zařazení evidovaného množství nářadí
* Výdej – slouží k vyřazení nářadí z evidence
* Půjčení
* Vrácení

Při účtování deníků lze evidovat množství, číslo pracovníka, který si nářadí půjčuje či vrací. Dále je obvykle požadováno sledovat kód poškození, kterým lze vyjádřit stav vraceného nářadí a následně je možné řešit nápravu či výměnu nákupem či výrobou nové položky. Pole Evidenční číslo slouží ke sledování půjčování kusových položek s unikátním evidenčním číslem pro přesnější rozlišení evidovaných pomůcek. Tato evidence vyžaduje účtovat množství pouze po 1 kusu.

### Údržba

Evidence nad modulem majetek umožňuje při existenci granule Controlling Fixed Assets sledovat údržbu evidovaných nářadí a pomůcek pomocí položek údržby. A to údržbu vznikající ze standardních nákupních dokladů, např. nákupní objednávka, nebo položky údržby vznikající interní spotřebou v denících zboží.

### Historie

Při účtování deníku vznikají položky, které je možno zobrazit pomocí klávesové zkratky **Ctrl+F7** z **Karty evidence nářadí** nebo z **Deníku evidence nářadí**, případně Oblasti / proPRODUKTIVITU / Evidence nářadí a pomůcek / Historie



## <a name="see-also"></a>Viz také  
[AC Productivity pack](ac-pp-productivity-pack.md)  