# Szablony HTML
**Co to jest?** xD

Są to szablony HTML, które możesz użyć do swojego projektu. Są one głównie zrobione pod rzeczy szkolne, lecz możesz zmienić tekst i dostosować je pod siebie.

## Przykładowe zdjęcia
![image](https://user-images.githubusercontent.com/68116256/165793522-bd8e9af7-060a-447f-8102-346ecfecb7db.png)

## Użycie
### CSS
Aby użyć szablonów wystarczy, że dołączysz ten arkusz CSS.
```css
<link rel="stylesheet" href="https://github.com/jacekz123/html-templates/raw/main/style.css">
```
#### Personalizacja
Możesz spersonalizować kolor. Aby to zrobić, musisz w sekcji 
```html
<head></head>
```
wkleić ten kod:
```html
<style>
:root{
  --hsl-color: x !important;
  }
</style>
```
`x` zastępujesz cyfrą z zakresu 0-360 (jest to wartosć `hue`). Aby tę wartość określić, udaj się na [tę](https://www.w3schools.com/colors/colors_hsl.asp) stronę i wybierz kolor (tam wartość będzie oznaczona jako `H`).
### Kod HTML
Aby użyć jednego z szablonów wystarczy, że skopiujesz kod CSS i wkleisz do pliku .html odpowiednie linijki kodu. Możesz póżniej edytować go - np. zmienić nagłówek. Wszystkie szablony znajdziesz tu: [templates.md](templates.md)
## Pozostałe informacje
Szablony były tworzone w oparciu o własne pomysły, a także książki Nowej Ery i egzaminy CKE.
