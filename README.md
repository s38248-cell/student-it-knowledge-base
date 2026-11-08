# Student IT Knowledge Base

## Cel projektu
Wspólna baza wiedzy IT tworzona w parze, gromadząca najważniejsze ściągi z przedmiotów pierwszego semestru.

## Opis
Repozytorium stanowi uporządkowany zbiór dokumentacji Markdown rozwijany przy użyciu gałęzi (`feature/*`), Pull Requestów oraz wzajemnego Code Review na GitHubie.

## Spis treści i dokumentacja przedmiotów

| Przedmiot | Temat ściągi | Link do dokumentu |
|---|---|---|
| **UKOS** | Podstawowe polecenia terminala Bash | [UKOS — Bash cheatsheet](docs/ukos/bash.md) |
| **WARP** | Praca z systemem kontroli wersji Git | [WARP — Git cheatsheet](docs/warp/git.md) |
| **PRG1** | Obsługa projektów C# przez .NET CLI | [PRG1 — .NET CLI cheatsheet](docs/prg1/dotnet-cli.md) |

- [UKOS (`docs/ukos/bash.md`)](docs/ukos/bash.md) — nawigacja po katalogach, operacje na plikach i wyświetlanie zawartości.
- [WARP (`docs/warp/git.md`)](docs/warp/git.md) — klonowanie, gałęzie, commity, synchronizacja i przegląd historii.
- [PRG1 (`docs/prg1/dotnet-cli.md`)](docs/prg1/dotnet-cli.md) — tworzenie, budowanie, uruchamianie i czyszczenie projektów konsolowych .NET.

## Instrukcja korzystania
1. Sklonuj repozytorium na swój komputer:
   ```bash
   git clone https://github.com/s38248-cell/student-it-knowledge-base.git
   cd student-it-knowledge-base
   ```
2. Przed rozpoczęciem nowej zmiany zaktualizuj gałąź `main`:
   ```bash
   git switch main
   git pull --ff-only origin main
   ```
3. Utwórz osobną gałąź roboczą (`git switch -c feature/nazwa`), wprowadź zmiany, wykonaj commit i otwórz Pull Request do `main`.

## Autorzy
- **Student A:** `@s38248-cell`
- **Student B:** `@DanOstap`
