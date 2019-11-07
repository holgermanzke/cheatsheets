# Notes

## Visual Studio Code

- nach Komponenten einen commit machen

### prettier

- sobald logische Fehler im Quellcode auftreten, funktioniert Prettier nicht mehr (X in der StatusBar) -> Bereiche auskommentieren, bis Prettier wieder funktioniert

## CSS / SCSS

Am Anfang in den Body:

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

### Struktur

- scss
  - styles.scss
  - partials
    - \_global.scss
    - \_variables.scss
    - ...

Immer in die \_global.scss:

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

## bootstrap

[Device Größen](https://getbootstrap.com/docs/4.3/layout/grid/#grid-options)

## NPM

- wenn package.json vorhanden -> `npm install`(alle Abhängigkeiten werden installiert)

## SASS / \*.scss

- Einbindung ins Projekt
