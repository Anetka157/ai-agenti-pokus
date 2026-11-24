# ai-agenti-pokus

Pokusný repozitář pro experimentování s AI agenty a jejich využitím při programování.

## Používání agentů

### Co jsou agenti?

Agenti jsou autonomní AI entity, které mohou:
- **Plánovat** - rozkládat složité úkoly na menší kroky
- **Vykonávat akce** - používat nástroje (přečíst soubor, spustit příkaz, vyhledat kód, atd.)
- **Iterovat** - na základě výsledků upravovat svůj postup
- **Spolupracovat** - předávat úkoly jiným agentům

### Jak agenti pracují v tomto repozitáři

1. **Zadání úkolu** - Popište, co potřebujete (např. "vytvoř REST API pro uživatele")
2. **Analýza** - Agent prozkoumá kódovou bázi, pochopí strukturu projektu
3. **Plánování** - Navrhne kroky k řešení
4. **Implementace** - Postupně vytváří/upravuje soubory, spouští testy
5. **Verifikace** - Kontroluje, že vše funguje (lint, testy, build)

### Typické scénáře použití

| Scénář | Popis |
|--------|-------|
| **Nová funkce** | "Přidej autentifikaci s JWT tokeny" |
| **Refactoring** | "Rozděl velkou třídu UserService na menší služby" |
| **Oprava bugu** | "Uživatelé nemohou resetovat heslo - najdi a oprav příčinu" |
| **Dokumentace** | "Vygeneruj OpenAPI specifikaci pro všechna endpointy" |
| **Testy** | "Napiš integrační testy pro objednávkový proces" |

### Best practices

- **Buďte specifičtí** - čím přesněji popíšete úkol, tím lepší výsledek
- **Poskytněte kontext** - sdílejte relevantní soubory, schéma DB, API specifikace
- **Iterujte** - neváhejte agentovi dávat zpětnou vazbu ("to není přesně to, co jsem chtěl, uprav to takto...")
- **Kontrolujte výsledky** - vždy si ověřte generovaný kód před commitem

### Dostupné nástroje agentů

Agenti mají k dispozici tyto nástroje:
- **Čtení/písání souborů** - `read_file`, `create_new_file`, `edit_existing_file`
- **Prohledávání kódu** - `grep_search`, `file_glob_search`
- **Terminál** - `run_terminal_command` (spouštění testů, buildu, lintingu)
- **Web** - `search_web`, `fetch_url_content` (pro vyhledávání dokumentací)
- **Skills** - `read_skill` (předdefinované postupy pro specifické úkoly)

---

*Tento repozitář slouží k experimentování a učení se pracovat s AI agenty efektivně.*

## O Cline

Cline je AI coding agent, který podporuje práci s AI agenty. V tomto repozitáři má Cline přístup k nástrojům:

- **Čtení/písání souborů** – `read_file`, `create_new_file`, `edit_existing_file`
- **Prohledávání kódu** – `grep_search`, `file_glob_search`
- **Terminál** – `run_terminal_command` (spouštění testů, buildu, lintingu)
- **Web** – `search_web`, `fetch_url_content` (pro vyhledávání dokumentací)
- **Skills** – `read_skill` (předdefinované postupy pro specifické úkoly)

Agenty se záměrně plánují, implementují a verifikují úkoly. Připojte tu sekci k názvu repozitáře.
