# MiMo Code – Instalacja jedną linią (Polska wersja)

**Gotowa, czysta i kompletna instalacja** dla **Xiaomi MiMo Code** – potężnego, terminal-native AI coding agenta od Xiaomi.

To repozytorium zawiera wszystko, co potrzebujesz, aby szybko uruchomić MiMo Code na komputerze (PC, Linux, macOS, WSL) – bez zbędnych komplikacji.

## 🚀 Szybka instalacja (One-Line Install)

Najprostszy sposób – jedna komenda:

```bash
curl -fsSL https://mimo.xiaomi.com/install | bash
```

Alternatywa przez npm (szczególnie na Windows):

```bash
npm install -g @mimo-ai/cli
```

## Uruchomienie

Po instalacji wystarczy wpisać:

```bash
mimo
```

## Pierwsze uruchomienie i konfiguracja

Przy pierwszym starcie MiMo Code uruchomi interaktywny kreator, który pomoże Ci wybrać metodę dostępu do modelu:

- **MiMo Auto** – darmowy dostęp na ograniczony czas (zero konfiguracji)
- **Xiaomi MiMo Platform** – logowanie OAuth + Token Plan
- **Import z Claude Code** – szybkie przeniesienie istniejącej konfiguracji
- **Custom Provider** – dodanie dowolnego API kompatybilnego z OpenAI

## Podstawowe komendy w interfejsie (TUI)

- `/connect` – podłączenie providerów i kluczy API (w tym Xiaomi MiMo)
- `/models` – wyświetlenie dostępnych modeli i wybór (np. `mimo/mimo-v2.5-pro`)
- `/goal` – ustawienie warunku zakończenia zadania
- `/dream` i `/distill` – samodoskonalenie agenta

## Główne funkcje MiMo Code

- **Persistent Memory** – pamięć projektu (MEMORY.md) działa między sesjami
- **Agenci**: `build` (domyślny), `plan`, `compose`
- **Sub-agenci** i równoległa praca
- **Task tracking** z drzewem zadań
- **Compose Mode** – pełny workflow od specyfikacji do gotowego kodu
- **Voice Input** (opcjonalnie)
- **Self-improvement** poprzez /dream i /distill

## Oficjalne źródła

- Główne repozytorium MiMo Code: [github.com/XiaomiMiMo/MiMo-Code](https://github.com/XiaomiMiMo/MiMo-Code)
- Dokumentacja: [mimo.xiaomi.com/mimocode](https://mimo.xiaomi.com/mimocode)
- Modele i providery: [mimo.xiaomi.com/mimocode/models-provider](https://mimo.xiaomi.com/mimocode/models-provider)

---

**Repozytorium gotowe do użytku.** 
Sklonuj je, używaj komend i ciesz się potężnym AI coding agentem.

Stworzone specjalnie dla Ciebie na Twoim GitHubie ❤️

Repo: https://github.com/gromek1991-tech/mimo-one-line-install