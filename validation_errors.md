# Hittade fel

Här listar jag alla fel jag har hittat i projektet och till delat dem ett fel/ärende nummer.

## Validering på validator.w3.org

### index.html

#### F1

Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.
From line 42, column 9; to line 42, column 36

>        <img src="images/kaffe.svg">

#### F2

Error: Duplicate ID meny.
From line 56, column 5; to line 56, column 23
ion>↩↩ <section id="meny">↩

#### F3

Warning: The first occurrence of ID meny was here.
From line 32, column 5; to line 32, column 23
ion>↩↩ <section id="meny">↩

#### F4

Error: The heading h5 (with computed level 5) follows the heading h3 (with computed level 3), skipping 1 heading level.
From line 49, column 9; to line 49, column 12

> ↩ <h5>Ostmac

#### F7

Ej fungerande länk :
Länken till kontaktsidan fungerarinte, pågrund av att URLen pekar på ikke existerande fil.
Rätt URL: kontakt.html

#### F8

Knapp för nyhets premuration är div, vilket inte är tillåtet
Rätt element för denna typ av koppling skall vara button

#### F9

Kontrast fel, länkar i header och footer har i kontrast vid hover ett värde som understiger 4.5:1
Lägg till ny css-variabel för --color-primary-hover med värde #ffcccc

### kontakt.html

#### F5

Warning: Consider adding a lang attribute to the html start tag to declare the language of this document.
From line 1, column 16; to line 2, column 6
TYPE html>↩<html>↩<head
For further guidance, consult Declaring the overall language of a page and Choosing language tags.
If the HTML checker has misidentified the language of this document, please file an issue report.

#### F6

Error: The value of the for attribute of the label element must be the ID of a non-hidden form control.
From line 35, column 9; to line 35, column 28 > <label for="e-post">E-post

### css/compontents.css

#### F10

Färgen #ffffff är hårdkodad och skall omvandlas till variable --color-surface

#### F11

Färgen #b9a58f är hårdkodad och skall omvandlas till variable.
Färgen ger dessutom inte en korrekt kontrast och skall därför ändras till #61574b som ger 7.0:1 i kontrast.

### css/layout.css

#### F10

Färgen #ffffff är hårdkodad och skall omvandlas till variable --color-surface
