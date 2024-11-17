# PVA4 - Programování a vývoj aplikací
## Lekce 11: Login

## Obsah

- Pro design aplikace můžete využít své stávající layouty.
- Cvičení realizujte bez využití databází.

### 1
- Vytvořte přihlašovací stránku login.php, na které uživatel bude realizovat přihlášení. Uživatelské údaje ve tvaru email a heslo, budete mít prozatím uloženy v poli.
- Uživatelské heslo bude chráněno Vašim uníkátním algoritmem, za využití hashe a salt.
- Pokud uživatel zadá neplatné údaje, je uživateli zobrazena zpráva `Neplatné přihlašovací jméno a/nebo heslo`
- Po úspěšném přihlášení, je uživateli zobrazena z práva Jméno `Příjmení, vítejte zpět.` např. `Jarmilka Testovací, vítejte  zpět.`

### 2
- Vytvořte stránku `kalkulacka.php`, která bude přístupná jen přihlášenému uživateli.
- V menu se na všech stránkách objeví odkaz na kalkulačku.
- Kalkulačka bude vypočítávat výše měsíční splátky hypotéky.


měsíční splátka = `[P * r * (1 + r)^n] / [(1 + r)^n - 1]`

kde:

- `P` = výše hypotéky
- `r` = měsíční úroková sazba
- `n` = celkový počet měsíčních splátek


Úroková sazba:

|Fixace|Sazba v %|
|------|---------|
|1 rok|5,99|
|2 roky|5,49|
|3 roky|5,29|
|4 roky|5,29|
|5 let|5,29|
|8 let|5,39|
|10 let|5,39|
|15 let|5,49|
|20 let|6,59|

### 3
- Vytvořte stránku historie výpočtů.
- na stránce se budou zobrazovat všechny historické kalkulace, které uživatel vyzkoušel.
