# Stylish Page Gallery
Use Chime's page gallery style with any theme.

```css
/* ---------- chime page gallery snippet ---------- */

body {
--tile-radius: 6px;
}

.responsive-tile-height .page-gallery__field,
.flex-tiles .page-gallery__field {
    text-shadow: none;
    word-wrap: break-word;
    white-space: initial;
    overflow: hidden;
}
.page-gallery__field {
    text-shadow: none;
    overflow: hidden;
    font-size: 0.8em;
    margin: 6px;
}
.page-gallery__filter input {
    width: 40%;
    margin-bottom: 10px;
    margin-left:11px;
}
.page-gallery__filter Label {
    margin: 3px;
    height: 1em;
    width: 1em;
}
.hide-filter .page-gallery__filter{
    display: none;
}
.page-gallery {
    --image-height: 8em;
}
.page-gallery__filter-clear {
    filter: grayscale();
    text-decoration: none;
    margin: 3px;
    height: 1em;
    width: 1em;
}
.page-gallery__image {
    opacity: 100%;
    border-radius: var(--tile-radius) var(--tile-radius) 0px 0px !important;
    box-shadow: none;
    width: 100%;
    background-size: cover;
}
.page-gallery__image:hover {
    opacity: 100%;
    box-shadow: var(--shadow-s);
}
.page-gallery__fallback {
box-shadow: none;
border-radius: var(--radius-s) var(--radius-s) 0px 0px;
background: var(--background-secondary-alt);

}

.page-gallery__fallback:hover {
    background: linear-gradient(to bottom right,
        var(--code-color),
        var(--background-secondary));
        box-shadow: var(--shadow-s);
}

.page-gallery__tile {
    max-width: 100%;
    border: 1px var(--line-style) var(--background-modifier-border);
    border-radius: var(--radius-s);
    display: flex;
    flex-direction: column;
    box-shadow: var(--shadow-s);
}
.flex-tiles .page-gallery__tile {
width: fit-content;
height: flex;
min-width: 10em;
max-width: 25em;
min-height: 10em;
flex-grow: 1;
}
.flex-tiles .page-gallery {
    --columns: auto;
    --gutter-size: 0.75em;
}
.flex-tiles .page-gallery__tiles {
    min-width: 100%;
    justify-content: center;
}

.theme-dark .page-gallery__tile {
    background-color: var(--background-secondary);  
}

.page-gallery__group-title {
    text-shadow: none;
    margin-bottom: 1em;
    font-size: var(--h2-size);
    font-family: var(--h2-font);
    font-weight: var(--h2-weight);
  }

/* @settings

name: 
id: chime-theme
settings:
    -
        id: responsive-tile-height
        title: Responsive Tile Height
        type: class-toggle
        default: true
        description: Make text break and continue on the next line rather than overflowing. Tile heights will change to accommodate the whole text.
    -
        id: flex-tiles
        title: Loose Tiles
        description: Make the tiles resize and rearrange themselves depending on the size of their content. This gets rid of the rigid columnar layout.
        type: class-toggle
        default: false
    -
        id: tile-radius
        title: Tile Border Radius
        description: Control the roundness of the tiles.
        type: variable-number-slider
        default: 6
        min: 0
        max: 40
        format: px
```
