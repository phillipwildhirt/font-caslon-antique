# Mapping/Cartography Font Collection
In creating an ancient mapping application I needed a quick install package. The package includes:

* Caslon Antique
  * Normal
  * Italic
  * Bold
  * Bold Italic
* Essays1743
  * Medium
  * Italic
  * Bold
  * Bold Italic
* Middle Earth (Elvish)
  * Normal
  * Italic
  * Italic Left
  * Bold
  * Bold Italic
  * Expanded
  * Expanded Italic
  * Condensed
  * Condensed Italic
* JSL Ancient
  * Normal
  * Italic


## Usage Example

Add the following to your style sheet:

```css
@import "../node_modules/@phillipwildhirt/font-caslon-antique";
```
A possible usage method could be to also add to your stylesheet:
```css
.jsl-ancient {
    font-family: JSL Ancient, serif;
}

.essays1743 {
  font-family: Essays1743, serif;
}

.caslon {
  font-family: Caslon Antique, serif;
}

.middle-earth {
  font-family: Middle Earth, sans-serif;
}
.middle-earth-condensed {
  font-family: Middle Earth Condensed, sans-serif;
}
.middle-earth-expanded {
  font-family: Middle Earth Expanded, sans-serif;
}
.middle-earth-left {
  font-family: Middle Earth Left, sans-serif;
}
```
 . . . and all you have to do is add the class `jsl-ancient`, `caslon`, etc. to your HTML tag.