# EZ COAT / NEXTCOAT — Biznesplan (rynek USA)

Profesjonalny biznesplan (raport dla inwestora, format A4) wraz z mini brandbookiem
dla projektu marki chemii budowlanej NEXT Industries, kierowanej na rynek USA.

Dokument został opracowany **wyłącznie** na podstawie dostarczonego materiału źródłowego
oraz wskazanego kontekstu. Wartości wstępne oznaczono jako *„Założenie wymagające
potwierdzenia"*, a braki jako *„Dane do uzupełnienia"*.

## Zawartość repozytorium

| Plik | Opis |
|------|------|
| `EZ-COAT-NEXTCOAT-Biznesplan.pdf` | Raport A4 pionowo, 28 stron — wersja do druku / dla inwestora |
| `EZ-COAT-NEXTCOAT-Biznesplan-standalone.html` | Ta sama treść w jednym, przenośnym pliku HTML (logo osadzone w base64) |
| `index.html` | Wersja edytowalna (odwołuje się do plików w `assets/`) |
| `assets/ez-coat-logo.png` | Logo EZ COAT (godło / badge) |
| `assets/nextcoat-logo.png` | Logo NEXTCOAT (logotyp poziomy z sygnetem) |

## Struktura dokumentu

1. Streszczenie projektu
2. Geneza i koncepcja
3. Problemy wykonawców i problem rynkowy
4. Rozwiązanie i portfolio produktów
5. Produkty priorytetowe na start
6. Ekonomika produktów
7. Logistyka kontenerowa
8. Model biznesowy w USA
9. Współpraca partnera polskiego i amerykańskiego
10. Wsparcie sprzedaży przez AI
11. Zapotrzebowanie finansowe
12. Organizacja w Polsce i USA
13. Dokumentacja i wymagania regulacyjne
14. Budowa produktu markowego
15. Kluczowe przewagi
16. Ryzyka projektu
17. Cele na pierwsze 12 miesięcy
18. Architektura marek NEXT Industries
19. Porównanie nazw: EZ COAT i NEXTCOAT
20. Mini brandbook
21. Informacje wymagające potwierdzenia

## Generowanie PDF z HTML

PDF został wygenerowany z `index.html` przy użyciu [WeasyPrint](https://weasyprint.org/):

```bash
pip install weasyprint
weasyprint index.html EZ-COAT-NEXTCOAT-Biznesplan.pdf
```

## Marka i kolory

Kolory odczytano bezpośrednio z dostarczonych znaków:

- **EZ COAT** — amber `#FCC40C`, grafit `#222220`
- **NEXTCOAT** — czerwień `#D81824` (gradient do `#98040F`), grafit-navy `#0B1821`

Odpowiedniki CMYK / Pantone oraz nazwy krojów pismowych — *dane do uzupełnienia*.
