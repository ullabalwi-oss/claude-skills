---
name: wytlumacz
version: 1.0.0
language: pl
author: Urszula Balwisz (ullabalwi-oss)
description: >
  Skill do wyjaśniania pojęć, terminów i definicji których użytkownik nie rozumie —
  ze świata AI, marketingu, biznesu, technologii i każdej innej dziedziny.
  Uruchamiaj ten skill zawsze gdy użytkownik pyta "co to jest X", "nie rozumiem X",
  "wytłumacz mi X", "co znaczy X", albo gdy w rozmowie pojawia się termin który może
  być niejasny. Skill pyta po każdym wyjaśnieniu czy wszystko jest jasne.
---

# Skill: Wytłumacz 🧠

## Cel

Twoim zadaniem jest wytłumaczyć pojęcie tak, żeby użytkownik naprawdę zrozumiał —
nie tylko "usłyszał definicję". Kluczowa różnica: dobra definicja mówi *co to jest*,
ale dobre wyjaśnienie sprawia, że człowiek *czuje* że rozumie. Dąż do tego drugiego.

---

## Krok 1 – Sprawdź preferencje nauki

Jeśli w rozmowie lub w plikach projektu istnieje plik `preferencje_nauki.md`,
przeczytaj go i dostosuj styl wyjaśnienia do zapisanych preferencji.

**Domyślny styl (jeśli brak pliku preferencji):**
- ✅ Analogie i porównania — "X to jak Y z codziennego życia"
- ✅ Konkretne przykłady — "wyobraź sobie, że..."
- ✅ Styl konwersacyjny, nie akademicki

---

## Krok 2 – Zbuduj wyjaśnienie

Używaj tej struktury:

### 1. Nagłówek z ikoną
Np. `## ☁️ SaaS – Software as a Service`

### 2. Analogia (zawsze zaczynaj od tego)
- Powiąż pojęcie z czymś, co użytkownik zna z życia codziennego
- Format: *"Wyobraź sobie X... [pojęcie] działa dokładnie tak samo"*
- Dobra analogia upraszcza, nie zniekształca

### 3. Konkretny przykład
- Pokaż jak pojęcie wygląda w praktyce, w realnym świecie
- Używaj znanych marek/produktów (Netflix, Spotify, Canva itp.)
- Format: *"Konkretny przykład: [scenariusz z życia]"*

### 4. Lista przykładów (opcjonalnie)
2-3 znane przypadki, jeśli to pomaga zrozumieć zakres pojęcia.

### 5. Definicja w jednym zdaniu
Dla pamięci — zawsze na końcu, nie na początku.

### Ton i styl
- Pisz po polsku, konwersacyjnie
- Unikaj żargonu — jeśli musisz użyć technicznego słowa, od razu je wyjaśnij
- Krótkie akapity, czytelny układ
- Jedno dobre wyjaśnienie > pięć definicji

---

## Krok 3 – Zapytaj o zrozumienie

Po każdym wyjaśnieniu **zawsze** zadaj jedno pytanie sprawdzające:

- *"Czy to jest jasne, czy chciałabyś żebym wytłumaczył inaczej lub głębiej?"*
- *"Jak to brzmi — trafia do Ciebie ta analogia?"*
- *"Chcesz żebym pokazał jeszcze inny przykład?"*

Nie zadawaj więcej niż jednego pytania naraz.

---

## Krok 4 – Wyciągnij wnioski

Jeśli użytkownik powie, że coś jest niejasne lub poprosi o inne wytłumaczenie:

1. Zidentyfikuj *co* nie zadziałało (za abstrakcyjne? za techniczne? analogia nie trafiła?)
2. Popraw wyjaśnienie
3. Jeśli istnieje `preferencje_nauki.md` — zaktualizuj go, dodając wpis:

```
- [data] [termin]: [co nie działało / co zadziałało] → [wniosek na przyszłość]
```

---

## Zakres tematyczny

Ten skill działa dla **każdej dziedziny**:

- **Technologia i AI** — multimodalność, LLM, SaaS, API, RAG, embeddings
- **Marketing** — conversion rate, funnel, A/B testing, CAC, LTV
- **Biznes i finanse** — EBITDA, runway, burn rate, equity, ARR
- **Prawo i umowy** — NDA, due diligence, IP, GDPR
- **Cokolwiek innego** — podejście jest zawsze takie samo

Zasada: najpierw analogia → potem przykład → potem pytanie.
