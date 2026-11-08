# Git — ściąga (WARP)

Podstawowe polecenia systemu kontroli wersji **Git** wykorzystywane podczas pracy zespołowej z repozytorium na GitHubie.

## Zestawienie poleceń

| Polecenie | Przykład użycia | Znaczenie / opis |
|---|---|---|
| `git clone` | `git clone URL` | Pobranie zdalnego repozytorium i utworzenie lokalnego katalogu projektu. |
| `git status` | `git status` | Sprawdzenie aktualnej gałęzi oraz plików zmienionych, nieśledzonych i przygotowanych do commita. |
| `git add` | `git add docs/warp/git.md` | Dodanie wskazanego pliku do obszaru staging (przygotowanie do zapisu). |
| `git commit` | `git commit -m "docs: add Git cheatsheet"` | Zapis przygotowanych zmian w lokalnej historii projektu z czytelnym komunikatem. |
| `git push` | `git push -u origin feature/git-cheatsheet` | Publikacja lokalnej gałęzi oraz commitów na GitHubie i ustawienie śledzenia zdalnej gałęzi. |
| `git pull` | `git pull --ff-only origin main` | Pobranie i włączenie zmian ze zdalnej gałęzi bez tworzenia nieoczekiwanego merge commita. |
| `git fetch` | `git fetch origin` | Pobranie aktualnych informacji o zmianach w repozytorium zdalnym bez modyfikowania plików roboczych. |
| `git branch` | `git branch` | Wyświetlenie listy lokalnych gałęzi i oznaczenie aktywnej gałęzi gwiazdką (`*`). |
| `git switch` | `git switch -c feature/nazwa` | Utworzenie nowej gałęzi roboczej i natychmiastowe przełączenie się na nią. |
| `git log` | `git log --oneline -5` | Skrócony podgląd pięciu ostatnich commitów w historii gałęzi. |

---

## Przykłady użycia w terminalu

### 1. Pobranie repozytorium i sprawdzenie stanu (`git clone`, `git status`, `git branch`)
```bash
git clone https://github.com/s38248-cell/student-it-knowledge-base.git
cd student-it-knowledge-base
git status
git branch
```

### 2. Synchronizacja gałęzi głównej i utworzenie gałęzi roboczej (`git pull`, `git switch`)
```bash
git switch main
git pull --ff-only origin main
git switch -c feature/git-cheatsheet
```

### 3. Przygotowanie, zapis i publikacja zmian (`git add`, `git commit`, `git push`)
```bash
git add docs/warp/git.md
git commit -m "docs: add Git cheatsheet"
git push -u origin feature/git-cheatsheet
```

### 4. Sprawdzenie historii i zdalnych zmian (`git fetch`, `git log`)
```bash
git fetch origin
git log --oneline -5
```

## Powiązane dokumenty
- [Powrót do strony głównej (README)](../../README.md)
- [UKOS — Bash cheatsheet](../ukos/bash.md)
- [PRG1 — .NET CLI cheatsheet](../prg1/dotnet-cli.md)
