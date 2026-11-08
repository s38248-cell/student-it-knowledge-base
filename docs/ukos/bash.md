# Bash cheatsheet
## Komendy

| Polecenie | Znaczenie |
|---|---|
| `pwd` | Wyświetlanie ścieżki bieżącego katalogu. |

```bash
pwd
```

| Polecenie | Znaczenie |
|---|---|
| `ls` | Listowanie plików, także ukrytych, w formacie szczegółowym. |

```bash
ls -la
```

| Polecenie | Znaczenie |
|---|---|
| `cd` | Przechodzenie do katalogu i katalogu nadrzędnego. |

```bash
cd docs/ukos
cd ..
```

| Polecenie | Znaczenie |
|---|---|
| `mkdir` | Tworzenie katalogu wraz z brakującymi katalogami nadrzędnymi. |

```bash
mkdir -p docs/ukos
```

| Polecenie | Znaczenie |
|---|---|
| `touch` | Tworzenie pustego pliku lub aktualizacja czasu jego modyfikacji. |

```bash
touch bash.md
```

| Polecenie | Znaczenie |
|---|---|
| `cp` | Kopiowanie pliku; wspomnij o opcji -r dla katalogów. |

```bash
cp bash.md bash-backup.md
```

| Polecenie | Znaczenie |
|---|---|
| `mv` | Przenoszenie i zmiana nazwy pliku. |

```bash
mv bash-backup.md archive.md
```

| Polecenie | Znaczenie |
|---|---|
| `rm` | Usuwanie pliku i ostrzeżenie, że operacja omija kosz. |

```bash
rm archive.md
```

| Polecenie | Znaczenie |
|---|---|
| `cat` | Wyświetlanie zawartości pliku w terminalu. |

```bash
cat bash.md
```
## Linki
[WARP](docs/warp/git.md)