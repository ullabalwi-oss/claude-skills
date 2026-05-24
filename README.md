# 🧠 Claude Skills — open source AI tools in Polish & English

> **Polskie narzędzia AI dla Claude. Budowane przez praktyka, dla praktyków.**
> Polish-first AI skills for Claude. Built by a practitioner, for practitioners.

---

## 👋 O autorce / About the Author

Cześć, jestem **Urszula** — specjalistka AI w automatyzacji, tworząca narzędzia Claude Skills po polsku i angielsku.

Hi, I'm **Urszula** — an AI automation specialist building Claude Skills in Polish and English.

- 🇵🇱 Pierwsza polska kolekcja Claude Skills open source
- 🌍 Every skill available in both Polish and English
- 🔧 Built for real workflows, not just demos
- 📬 [LinkedIn](https://www.linkedin.com/in/urszula-balwisz-4aa03234b/) | [GitHub](https://github.com/ullabalwi-oss/claude-skills)

---

## 📦 Skills

| Skill | PL | EN | Opis / Description |
|---|---|---|---|
| [wytlumacz](./skills/wytlumacz/) | ✅ | ✅ | Wyjaśnia pojęcia z AI, biznesu, marketingu — przez analogie i przykłady / Explains concepts via analogies & examples |

> Więcej skillów wkrótce. More skills coming soon.

---

## 🚀 Jak używać / How to Use

### Instalacja w Claude Code / Install in Claude Code

```bash
# Skopiuj folder wybranego skilla do swojego projektu
# Copy the skill folder to your project

cp -r skills/wytlumacz /your-project/.claude/skills/
```

Następnie w pliku `CLAUDE.md` lub jako system prompt dodaj zawartość `SKILL.md`.

Then reference the `SKILL.md` content in your `CLAUDE.md` or system prompt.

### Struktura / Structure

```
skills/
└── wytlumacz/
    ├── pl/
    │   └── SKILL.md        # Wersja polska
    └── en/
        └── SKILL.md        # English version
```

---

## 🗺️ Roadmap

- [x] `wytlumacz` — wyjaśniacz pojęć (PL + EN)
- [ ] `video-prompt-builder` — prompty do generowania wideo AI
- [ ] `saas-subscription-auditor` — audyt subskrypcji SaaS
- [ ] `linkedin-post-writer` — posty LinkedIn po polsku
- [ ] `youtube-script-formatter` — skrypty YouTube

---

## 🤝 Współpraca / Contributing

Masz pomysł na skill? Otwórz Issue albo wyślij PR.
Got a skill idea? Open an Issue or send a PR.

---

## 📬 Zostań w kontakcie / Stay in Touch

Buduję to publicznie. Każdy commit = potencjalny post na LinkedIn.

- **LinkedIn:** [Urszula Balwisz](https://www.linkedin.com/in/urszula-balwisz-4aa03234b/)

⭐ Jeśli to przydatne — zostaw gwiazdkę! / If this is useful — leave a star!

---

*Made with Claude*
