# 🗓️ Poranny Automat Raportowy – n8n Workflow

Ten workflow w n8n automatycznie wysyła codzienny poranny raport na Telegram.  
Zbiera dane z kilku źródeł, generuje czytelny podsumowujący komunikat i wysyła go o stałej godzinie.

## 🔧 Co robi workflow?

- ⏰ Uruchamia się codziennie o **07:07** dzięki Schedule Trigger  
- 🤖 Pobiera **żart z OpenAI**  
- 📅 Pobiera **dzisiejsze wydarzenia z Google Calendar**  
- ⛅ Pobiera **bieżącą pogodę z OpenWeatherMap**  
- 📝 Pobiera **zadania z Google Tasks**  
- 🗃 Łączy dane z DataTable (np. ID czatu Telegram)  
- 🧩 Składa wszystko w raport w kodzie JavaScript  
- 📤 Wysyła wiadomość na **Telegram**

## 📄 Co znajduje się w raporcie?

- Pogoda dla wskazanego miasta  
- Temperatura, odczuwalna, ciśnienie, wiatr, zachmurzenie  
- Lista wydarzeń z kalendarza (z godzinami)  
- Lista zadań  
- „Żart dnia” z AI  
- Formatowanie w Markdown

## 🎯 Cel

Automatyzacja porannej rutyny – jeden raport, codziennie, bez żadnej interakcji.
