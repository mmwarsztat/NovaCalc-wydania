# NovaCalc — wydania

Gotowe instalatory programu **NovaCalc** (kalkulator wyrażeń z profilami stalowymi,
Metal-Montaż). Kod źródłowy leży w osobnym, prywatnym repozytorium — tutaj są tylko
pliki do pobrania.

## Licencja

Program jest własnością **METAL-MONTAŻ SPÓŁKA Z OGRANICZONĄ ODPOWIEDZIALNOŚCIĄ** i służy
do pracy na jej rzecz. Prawo korzystania mają pracownicy i współpracownicy Spółki; wygasa
ono z końcem zatrudnienia lub współpracy. Przekazywanie programu osobom spoza Spółki
wymaga pisemnej zgody. NovaCalc **nie jest** wolnym oprogramowaniem.

Osobny punkt mówi, że program **nie odpowiada za wyniki obliczeń** — każdy wynik wymaga
sprawdzenia przez osobę o odpowiednich kwalifikacjach, zanim trafi do projektu, oferty
czy na budowę.

Pełna treść: [`LICENSE`](LICENSE). Tę samą pokazuje instalator jako stronę do
zatwierdzenia przy pierwszej instalacji.

## Instalacja

Weź najnowszy `NovaCalc-<wersja>-instalator.exe` z zakładki
[Releases](../../releases/latest) i uruchom go. Instalator jest per-użytkownik:
nie pyta o hasło administratora, zakłada skróty na pulpicie i w menu Start.

Zainstalowany program **sam sprawdza przy starcie**, czy jest nowsza wersja, i pyta,
czy ją zainstalować. Drugi raz pobierać ręcznie już nie trzeba.

## `latest.json`

Plik dołączony do każdego wydania. Czyta go sam program (Tauri updater) — zawiera numer
najnowszej wersji, adres instalatora i jego podpis. Ludziom nie jest do niczego potrzebny.
