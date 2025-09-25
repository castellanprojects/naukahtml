## 📝 Notatka: Podstawy HTML i CSS

---

### Tabele HTML: `<table/>`, `<tr/>`, `<td/>`, `<th/>`

Tabele służą do prezentacji danych w formie wierszy i kolumn.

| Tag | Opis | Ważne Atrybuty |
| :--- | :--- | :--- |
| **`<tr>`** | Definiuje **wiersz** tabeli (Table Row). | |
| **`<td>`** | Definiuje **komórkę danych** w wierszu (Table Data). | `rowspan` (łączy wiersze), `colspan` (łączy kolumny) |
| **`<th>`** | Definiuje **komórkę nagłówkową** (Table Header). Tekst jest domyślnie pogrubiony i wyśrodkowany. | `rowspan`, `colspan` |

---

### Formularze HTML: `<form/>` i Elementy Wejścia

Formularze służą do zbierania danych od użytkownika.

| Tag | Opis | Ważne Atrybuty/Typy |
| :--- | :--- | :--- |
| **`<form>`** | Kontener na wszystkie elementy formularza. | `action` (adres do wysłania danych), `method` (np. `GET`, `POST`) |
| **`<input>`** | Pojedyncze pole do wprowadzania danych. | `name` (klucz, pod którym dane są wysyłane), `placeholder` (tekst podpowiedzi) |
| `type="text"` | Standardowe pole tekstowe. | |
| `type="password"` | Tekst jest maskowany (np. kropkami). | |
| `type="email"` | Pole do adresu e-mail (wspiera walidację przeglądarki). | |
| `type="checkbox"` | Pozwala na **wielokrotny** wybór z listy. | |
| `type="radio"` | Pozwala na **pojedynczy** wybór z grupy (wymaga tego samego atrybutu `name`). | |
| **`<select>`** | Tworzy **rozwijaną listę** opcji. | `name` |
| **`<option>`** | Pojedyncza opcja wewnątrz listy `<select>`. | `value` (wartość, która zostanie wysłana) |

---

### Listy HTML: `<ul>`, `<ol>`, `<li>`

Służą do uporządkowanego przedstawienia elementów.

| Tag | Nazwa | Opis | Atrybuty `type` |
| :--- | :--- | :--- | :--- |
| **`<ul>`** | Unordered List (Nieuporządkowana) | Elementy listy oznaczane są markerem (np. kropką). | `disc` (domyślny), `circle`, `square` |
| **`<ol>`** | Ordered List (Uporządkowana) | Elementy są numerowane lub literowane. | `1` (domyślny, liczby), `a` (małe litery), `A` (duże litery), `i` (małe rzymskie), `I` (duże rzymskie) |
| **`<li>`** | List Item | Pojedynczy **element** wewnątrz `<ul>` lub `<ol>`. | |

---

### Struktura Strony i Elementy Semantyczne

Elementy semantyczne dają znaczenie treści, co jest kluczowe dla SEO i dostępności.

* **`<div>`**: **Najbardziej ogólny** element blokowy. Używamy go, gdy **żaden** inny, bardziej specyficzny tag semantyczny nie pasuje. Jest jak "pudełko" na treści.
* **`<main>`**: Główna, **unikatowa** treść dokumentu. Powinien być tylko jeden na stronie.
* **`<header>`**: Sekcja wprowadzająca (np. logo, tytuł, element nawigacyjny).
* **`<nav>`**: Zawiera **główne** linki nawigacyjne strony.
* **`<article>`**: Niezależny, **samodzielny** fragment treści (np. wpis na blogu, artykuł, komentarz).
* **`<section>`**: Ogólny, tematyczny blok treści, często z własnym nagłówkiem.
* **`<footer>`**: Zawiera informacje końcowe dla sekcji lub całej strony (np. dane kontaktowe, prawa autorskie).

---

### Podstawowa Stylizacja Tekstu w CSS

Kaskadowe Arkusze Stylów (CSS) decydują o wyglądzie elementów HTML.

| Właściwość CSS | Opis | Przykłady Wartości |
| :--- | :--- | :--- |
| **`color`** | Ustawia **kolor tekstu**. | `red`, `#336699`, `rgb(50, 100, 150)` |
| **`background-color`** | Ustawia **kolor tła** dla elementu (całego pudełka, nie tylko tekstu). | `white`, `lightgray` |
| **`font-family`** | Definiuje **krój czcionki** (np. `Arial`, `serif`, `monospace`). | `'Helvetica Neue', Arial, sans-serif` |
| **`font-size`** | Ustawia **rozmiar czcionki**. | `16px`, `1.2em`, `120%` |
| **`font-weight`** | Definiuje **grubość czcionki**. | `normal`, `bold`, `400`, `700` |
| **`text-align`** | Wyrównanie tekstu w poziomie. | `left`, `center`, `right`, `justify` |
