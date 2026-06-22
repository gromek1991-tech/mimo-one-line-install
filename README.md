# MiMo Code – Instalacja jedną linią

**Szybka i czysta instalacja dla Xiaomi MiMo Code** – potężnego terminal-native AI coding agenta.

Repo stworzone specjalnie dla łatwego dostępu do komend instalacyjnych + instrukcje na Androida (Termux).

## Jednoliniowa instalacja (One-Line Install)

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

Przy pierwszym uruchomieniu kreator poprowadzi Cię przez konfigurację:
- MiMo Auto (darmowe na start, zero config)
- Xiaomi MiMo Platform (OAuth)
- Import z Claude Code
- Custom provider (OpenAI-compatible)

## Instalacja na Androidzie (Termux)

1. Zainstaluj **Termux** z F-Droid (zalecane).
2. W Termux:
```bash
pkg update && pkg upgrade
pkg install git curl nodejs
```
3. Zainstaluj MiMo Code:
```bash
curl -fsSL https://mimo.xiaomi.com/install | bash
```
   lub
```bash
npm install -g @mimo-ai/cli
```
4. Uruchom:
```bash
mimo
```

**Uwaga**: Na Termux arm64 mogą być drobne problemy z instalacją (brak pełnego wsparcia bun) – jest aktywny PR na GitHubie Xiaomi dodający wsparcie dla Androida. Jeśli nie działa, zainstaluj na komputerze i połącz się przez SSH.

## Po instalacji

- Użyj `/connect` w TUI, aby podłączyć providery (w tym Xiaomi MiMo z API key z platform.xiaomimimo.com)
- `/models` – wybierz model (np. mimo-v2.5-pro)
- Pełne funkcje: persistent memory (MEMORY.md), agenci (build/plan/compose), sub-agenci, task tracking, compose mode, voice input, /dream i /distill

## Oficjalne linki

- GitHub repo MiMo Code: https://github.com/XiaomiMiMo/MiMo-Code
- Dokumentacja: https://mimo.xiaomi.com/mimocode
- Models & Providers: https://mimo.xiaomi.com/mimocode/models-provider

---

Stworzone z ogniem dla Ciebie na Twoim GitHubie ❤️

Repo: https://github.com/gromek1991-tech/mimo-one-line-install