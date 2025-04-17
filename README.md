# BioAlgoRytmika (BAR) - Wprowadzenie do algorytmiki i programowania dla studentów biotechnologii
### author: Jan Paweł Jastrzębski
Principles of BioAlgoRithms: Educational Resources and Exercises
================================================================

## 📌 Czym jest algorytmika?

**Algorytmika** to dziedzina informatyki zajmująca się projektowaniem i analizą **algorytmów**, czyli skończonych ciągów jasno zdefiniowanych kroków prowadzących do rozwiązania danego problemu.

W kontekście nauk biologicznych, algorytmy można wykorzystać m.in. do:
- automatyzacji analiz bioinformatycznych,
- przetwarzania danych eksperymentalnych,
- projektowania procesów laboratoryjnych i technologicznych.

---

## 🧩 Co to jest algorytm?

**Algorytm** to przepis na wykonanie zadania. Musi być:
- **skończony** (ma początek i koniec),
- **jednoznaczny** (każdy krok jest dokładnie określony),
- **wykonywalny** (można go wykonać krok po kroku).

### 🔍 Przykład algorytmu:
> **Algorytm zaparzenia herbaty:**
> 1. Zagotuj wodę.  
> 2. Umieść torebkę herbaty w kubku.  
> 3. Zalej torebkę wrzątkiem.  
> 4. Odczekaj 3–5 minut.  
> 5. Wyjmij torebkę.  
> 6. (Opcjonalnie) Dodaj cukier lub cytrynę.

---

## 🔁 Czym jest flowchart?

**Flowchart** (schemat blokowy) to graficzne przedstawienie algorytmu. Używa się w nim kształtów (np. prostokątów, rombów) do oznaczania poszczególnych kroków, decyzji, startu i końca.

📖 [Wikipedia – Flowchart](https://en.wikipedia.org/wiki/Flowchart)  
🛠️ Narzędzie online: [Google Draw.io (diagrams.net)](https://app.diagrams.net/)

---

## 🖥️ Czym jest programowanie?

**Programowanie** to proces zamiany algorytmu na język zrozumiały dla komputera (czyli kod). Dzięki programowaniu możemy tworzyć automatyczne analizy, skrypty obliczeniowe i narzędzia wspierające prace laboratoryjne i technologiczne.

Najczęściej używanym językiem w naukach przyrodniczych jest **Python** – prosty, czytelny i bardzo wszechstronny.

---

## 📚 Polecane materiały do nauki

### 🎥 Krótki kurs algorytmiki i programowania w Pythonie:
➡️ [Kurs na YouTube – playlist](https://youtube.com/playlist?list=PLupAQRy_4upI89UgfwjnORI0rQBd9axKv&si=FZ0pTSOpxyRWlliJ)

### ☁️ Wprowadzenie do Google Colab – środowiska do pisania i uruchamiania kodu w chmurze:
➡️ [Google Colab – intro](https://youtu.be/wlRT_MZOvBE?si=Y_rFsfFZqTH1rIg7)

### 📊 Tworzenie schematów blokowych (flowchart):
- [draw.io (diagrams.net)](https://app.diagrams.net/)
- [Flowchart → Kod (flowchart 2 code) – kurs](https://youtu.be/iF65fR67g7c?si=JZ4a_A-8sRKjaXqd)
- [Kod → Flowchart (code2flow)](https://code2flow.com/)
- [Tworzenie i uruchamianie kodu z poziomu flowcharta – Flowgorithm](http://www.flowgorithm.org/)

---

## ✅ Zadanie do wykonania

### 📌 Temat: Tworzenie algorytmu i kodu dla procedury biologicznej lub procesu technologicznego

1. **Podzielcie się na 2-osobowe zespoły.**
2. Wybierzcie dowolną procedurę laboratoryjną lub proces technologiczny, np.:
   - PCR,
   - projektowanie starterów,
   - NGS,
   - elektroforeza,
   - ELISA,
   - miareczkowanie,
   - produkcja piwa lub jogurtu,
   - badanie zawartości alkoholu w winie/piwie.
3. Stwórzcie **algorytm tej procedury w formie flowchartu** (np. w Google Draw.io).
4. Następnie **zakodujcie algorytm w wybranym języku programowania**, np. Python, Flowgorithm, itp.
5. Udostępnijcie gotowy skrypt i flowchart w formie linku (np. Google Drive lub GitHub).
6. Upewnijcie się, że kod można uruchomić (najlepiej w Google Colab).

💡 **Tip:** Używajcie narzędzi online jak [draw.io](https://app.diagrams.net/) do rysowania i [Google Colab](https://colab.research.google.com/) do pisania kodu – wszystko działa w przeglądarce!

---

## 📦 Szablony

### 🧩 Szablon opisu algorytmu (flowchart)

```
**Tytuł procedury:** np. "Izolacja DNA"

**Cel:** Krótki opis celu procedury.

**Wejście (Input):**
- Lista potrzebnych danych lub materiałów.

**Wyjście (Output):**
- Oczekiwany rezultat (np. oczyszczone DNA).

**Kroki algorytmu:**
1. [Krok 1: np. Pobranie próbki]
2. [Krok 2: np. Liza komórek]
3. ...
n. [Zakończenie procedury]

**Decyzje w algorytmie (opcjonalne):**
- Czy jakość próbki jest odpowiednia? → Tak/Nie
- Czy objętość jest wystarczająca? → Tak/Nie

**Rysunek flowcharta:** [wklej link do pliku w draw.io lub screen]
```

---

### 📓 Szablon skryptu w Pythonie (np. w Colab)

```python
# Tytuł: Algorytm procedury XYZ
# Autorzy: Imię i Imię
# Opis: Kodowanie procedury XYZ na podstawie stworzonego flowcharta

def procedura_xyz():
    print("Start procedury XYZ")

    # Krok 1
    print("Krok 1: [opis kroku]")

    # Krok 2
    print("Krok 2: [opis kroku]")

    # Decyzja
    decyzja = input("Czy warunek X jest spełniony? (tak/nie): ")
    if decyzja.lower() == "tak":
        print("Wykonuję gałąź A algorytmu.")
    else:
        print("Wykonuję gałąź B algorytmu.")

    # Krok końcowy
    print("Procedura zakończona.")

# Uruchomienie procedury
procedura_xyz()
```

--- 

## 📬 W razie pytań...

Pytania można kierować bezpośrednio do prowadzącego: bioinformatyka@gmail.com. 
Powodzenia i miłego programowania! 👨‍🔬👩‍💻
