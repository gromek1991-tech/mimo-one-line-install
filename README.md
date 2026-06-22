# MiMo Code – Instalacja jednoliniowa

**Gotowe repozytorium do szybkiego startu z Xiaomi MiMo Code** – terminal-native AI coding agent od Xiaomi.

Repo skonfigurowane na gotowo specjalnie dla Ciebie na Twoim GitHubie.

## Instalacja (One-Line)

```bash
curl -fsSL https://mimo.xiaomi.com/install | bash
```

Lub przez npm:

```bash
npm install -g @mimo-ai/cli
```

Uruchom:

```bash
mimo
```

## Pierwsze uruchomienie

Kreator automatycznie poprowadzi konfigurację:

- **MiMo Auto** (darmowe na ograniczony czas, zero konfiguracji)
- **Xiaomi MiMo Platform** (OAuth + API key)
- Import z Claude Code
- Custom provider (każdy OpenAI-compatible)

## Podstawowe komendy w TUI

- `/connect` – podłącz providera modeli
- `/models` – wybierz model (np. mimo-v2.5-pro)
- `/goal` – ustaw warunek stopu sesji
- `/dream` i `/distill` – self-improvement i wyciąganie wiedzy
- `/voice` – wejście głosowe (z sox)

## Główne funkcje

- Persistent memory (MEMORY.md, checkpointy)
- Agenci: build, plan, compose
- Sub-agenci i parallel work
- Task tracking (drzewo zadań)
- Compose mode (od specyfikacji do gotowego kodu)
- Intelligent context management

## Konfiguracja (mimocode.json)

Plik `.mimocode/mimocode.json` w projekcie lub globalny `~/.config/mimocode/mimocode.json`.

Przykład dla Xiaomi:

```json
{
  "$schema": "https://mimo.xiaomi.com/mimocode/config.json",
  "model": "mimo/mimo-v2.5-pro"
}
```

## Linki

- Oficjalne repo: https://github.com/XiaomiMiMo/MiMo-Code
- Dokumentacja: https://mimo.xiaomi.com/mimocode
- Models & Providers: https://mimo.xiaomi.com/mimocode/models-provider

---

**Gotowe do użycia na Twoim GitHubie.** 
Repo: https://github.com/gromek1991-tech/mimo-one-line-install

Stworzone z ogniem i miłością do kodu ❤️

Edytuj, forkuj, używaj jak chcesz!