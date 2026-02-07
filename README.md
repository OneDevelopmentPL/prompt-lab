# 🧪 Prompt Lab — Free AI (OpenRouter)

**[▶ Otwórz aplikację](https://onedevelopmentpl.github.io/prompt-lab/)**

Darmowy, nowoczesny laboratorium do testowania i doskonalenia promptów AI. Generuj odpowiedzi w różnych stylach, ucz się technik prompt engineeringu i przechowuj historię swoich eksperymentów — wszystko lokalnie w przeglądarce.

## ✨ Główne cechy

### 🎯 Generowanie odpowiedzi w 5 stylach jednym kliknięciem
- **👶 Dla dziecka (5-8 lat)** — proste wyjaśnienia z porównaniami
- **📚 Naukowy** — akademicki, formalny styl z precyzją
- **🎯 Praktyczny** — konkretne porady gotowe do wdrożenia
- **🎨 Kreatywny** — metafory, analogie i interesujące podejście
- **⚡ Krótko i treściwie** — max 2-3 zdania, bez zbędnych szczegółów

### 📚 Wbudowany poradnik prompt engineeringu
Naucz się kluczowych elementów skutecznego prompta:
- **👤 Rola (Persona)** — kim ma być AI
- **📝 Zadanie (Task)** — jasne polecenie z czasownikami operacyjnymi
- **🎯 Kontekst** — tło zadania i dane wejściowe
- **📋 Format odpowiedzi** — struktura wyniku (tabela, lista, JSON)
- **⛔ Ograniczenia** — czego AI ma unikać
- **📖 Przykłady** — wzorcowe odpowiedzi (Few-shot prompting)

### 🔒 Pełna prywatność
- Wszystkie dane przechowywane **lokalnie w przeglądarce**
- Nie zbieramy kluczy API ani historii
- Kod dostępny na GitHub — sprawdź sam!

### 💾 Historia i eksport
- Automatyczne zapisywanie wszystkich promptów i odpowiedzi
- System oceniania (★★★★★)
- Eksport historii do JSON
- Informacje o użytym modelu AI i czasie wygenerowania

## 🚀 Szybki start

### 1️⃣ Zarejestruj się na OpenRouter
Odwiedź [openrouter.ai](https://openrouter.ai) i utwórz darmowe konto.

### 2️⃣ Wygeneruj klucz API
Przejdź do [ustawień API](https://openrouter.ai/settings/keys) i skopiuj swój klucz.

### 3️⃣ Wklej klucz w Prompt Lab
Otwórz aplikację, wklej klucz w polu "🔑 OpenRouter API Key" i kliknij "Zapisz klucz".

### 4️⃣ Napisz prompt
Wpisz swój prompt w polu tekstowym i kliknij "▶ Wyślij do AI".

### 5️⃣ (Opcjonalnie) Generuj warianty
Zaznacz "📌 Generuj 5 wariantów odpowiedzi" aby uzyskać odpowiedź w 5 różnych stylach!

## ⚙️ Ustawienia

| Opcja | Opis |
|-------|------|
| 🤖 Model | Wybierz model AI (RandomAI, Qwen, Gemma, Llama) |
| 📌 Generuj 5 wariantów | Uzyskaj odpowiedź w 5 różnych stylach |
| 🕐 Pokaż czas wygenerowania | Wyświetl dokładny czas odpowiedzi |
| 🤖 Pokaż użyty model | Pokaż który model został użyty |
| 📦 Export Prompt Pack | Pobierz historię jako JSON |

## ⏳ Czas generowania
Odpowiedź powinna być gotowa za ok. **15-30 sekund**, w zależności od:
- Złożoności zadania
- Wybranego modelu AI
- Obciążenia serwera OpenRouter

## 🛠️ Architektura

**Technologia:**
- Czysty HTML5 + CSS3 + JavaScript (vanilla)
- Brak dependencji, brak bundlera
- API: OpenRouter.ai
- Storage: localStorage

**Pliki:**
```
PromptLab/
├── index.html          # Cała aplikacja (HTML + CSS + JS)
└── README.md          # Ten plik
```

## 🎨 Design
- **Dark mode** zainspirowany GitHub
- Responsywny layout (sidebar + main content)
- Obsługa Markdown (pogrubienie, kod, nagłówki)

## 📊 Przykładowa historia
Każdy prompt przechowuje:
```json
{
  "prompt": "Wyjaśnij czym jest machine learning",
  "response": "...",
  "model": "meta-llama/llama-3.2-3b-instruct",
  "timestamp": "7.02.2026, 14:30:45",
  "rating": 5,
  "variants": false
}
```

## ❓ FAQ

**P: Czy moje prompty są bezpieczne?**
O: Tak! Wszystko jest przechowywane lokalnie w Twojej przeglądarce. Nawet my nie mamy dostępu do Twoich danych.

**P: Ile kosztuje OpenRouter?**
O: OpenRouter oferuje darmowy tier z limitami zapytań. Sprawdź [cennik](https://openrouter.ai/pricing).

**P: Mogę używać inne modele AI?**
O: Tak! Jeśli masz klucz OpenRouter, możesz wybrać dowolny dostępny model z listy.

**P: Jak zgłosić błąd?**
O: Otwórz issue na [GitHub Issues](https://github.com/onedevelopmentpl/prompt-lab/issues).

## 📚 Zasoby

- [OpenRouter API Docs](https://openrouter.ai/docs)
- [Prompt Engineering Best Practices](https://platform.openai.com/docs/guides/prompt-engineering)
- [Few-shot Prompting](https://www.promptingguide.ai/techniques/fewshot)

## 📝 Licencja

MIT — możesz używać, modyfikować i rozpowszechniać ten projekt.

## 👨‍💻 Autor

Developed by **[OneDevelopment](https://github.com/onedevelopmentpl)**

---

**Powodzenia w testowaniu promptów! 🚀**

Jeśli projekt Ci się podoba, daj mu ⭐ na GitHub!
