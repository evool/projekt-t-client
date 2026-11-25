# Projekt T — wydania klienta

To repozytorium zawiera wyłącznie publiczne wydania klienta gry **Projekt T**.
Kod źródłowy projektu jest prywatny.

## Instalacja

1. Otwórz [najnowsze wydanie](../../releases/latest).
2. Pobierz paczkę dla swojego systemu:
   - Windows: `projekt-t-windows-x64.zip`
   - Linux: `projekt-t-linux-x64.zip`
3. Rozpakuj archiwum i uruchom `launcher.exe` (Windows) albo `launcher` (Linux).

Launcher sprawdza aktualizacje w tym repozytorium i pobiera nowszą wersję klienta.
Wydania są podpisane; klient odrzuci manifest z nieprawidłowym podpisem.

## Aktualizacje

Klient pobiera wyłącznie `manifest.json` / `manifest-linux.json` oraz binarkę
`projekt-t.exe` / `projekt-t` z najnowszego wydania. Nie trzeba pobierać paczki
ponownie przy każdej aktualizacji.
