# Wiki Pages
Use the `wiki-page` css class with any theme with this snippet.

```css

/* --- wiki-page (wiki page) css class --- */
.wiki-page {
    --file-line-width: 100%;
    --font-text-size: 0.9em; 
    --h1-color: var(--text-normal);    
    --h2-color: var(--text-normal);    
    --h3-color: var(--text-normal);    
    --h4-color: var(--text-normal);    
    --h5-color: var(--text-normal);    
    --h6-color: var(--text-normal);   
    --h1-size: 1.5em; 
    --h2-size: 1.2em;
    --h3-size: 1.1em;
    --h4-size: 1em;
    --h5-size: 0.99em;
    --h6-size: 0.98em;
    --h1-line-height: 1.8em;
    --font-text: 'Archivo', Arial, sans-serif;
    --h1-font: 'Linux Libertine', 'Georgia', 'Times', serif;
    --h1-weight: normal;
    --inline-title-color: var(--text-normal);
    --radius-s: 0px;
    --radius-m: 0px;
}

.wiki-page.markdown-rendered hr::before, .wiki-page.markdown-source-view hr::before{
    display: none !important;
}
.wiki-page .inline-title {
    border-bottom: 1px solid var(--background-modifier-border) !important;
    line-height: 0.5em;
    margin-bottom: 1em;
    font-family: var(--h1-font);
    font-weight: var(--h1-weight);
}


.wiki-page .frontmatter-container {
    display: none;
}
.wiki-page h1{
    border-bottom: 1px solid var(--background-modifier-border) !important;
    background-color: transparent !important;
    padding: 0px !important;
    overflow: hidden;
}
.wiki-page h2,
.wiki-page h3,
.wiki-page h4,
.wiki-page h5,
.wiki-page h6 {
    background-color: transparent !important;
    padding: 0px !important;
    overflow: hidden;
    border-bottom: none !important
}
.wiki-page img {
    width: 25% !important;
    float: right;
    clear: right;
    margin: 1em;
}
.wiki-page.markdown-source-view img {
    float: none;
    clear: none;
    width: 50%;
    margin-right: auto;
    margin-left: auto;
}
.wiki-page .callout img, .wiki-page .blockquote img {
    width: 100% !important;
    float: none;
    clear: none;
    display: block;
    margin-right: auto;
    margin-left: auto;
}
.wiki-page.markdown-rendered blockquote {
    display: flexbox;
    width: flex;
    text-align: left;
    overflow: hidden;
    margin: 1em 1em 1em 0px;
    border-radius: var(--radius-s);
}



.wiki-page.markdown-preview-view .callout[data-callout*=info] {
    float: right;
    clear: right;
    width: 25%;
    background-color: var(--background-primary);
    padding: 0px;
    border-radius: var(--radius-s);
    box-shadow: var(--shadow-s);
    border: 1px solid var(--background-modifier-border);
}
.wiki-page.markdown-source-view .callout[data-callout*=info] {
    width: 25%;
    margin-left: auto;
    margin-right: auto;
    background-color: var(--blockquote-background-color);
    padding: 7px;
    border-radius: var(--radius-s);
    border: 1px solid var(--background-modifier-border);
}

.wiki-page.markdown-preview-view .callout[data-callout*=info] .callout-content {
    width: 100%;
    display: block;
    margin-left: auto;
    margin-right: auto;
    padding:5px;

}
.wiki-page.markdown-preview-view .callout[data-callout*=info] .callout-title {
    font-size: var(--h3-size);
    font-weight: var(--h3-weight);
    color: var(--text-normal);
    padding: 5px;
    background-color: rgba(var(--color-yellow-rgb), 0.2);
    width: 100%;
    margin: 0px;
}
.wiki-page .callout h1,
.wiki-page .callout h2,
.wiki-page .callout h3,
.wiki-page .callout h4,
.wiki-page .callout h5,
.wiki-page .callout h6 {
    font-size: var(--h3-size);
    font-weight: var(--h3-weight);
    text-align: center;
    color: var(--text-normal);
    padding: 5px !important;
    line-height: 1.25em;
    background-color: rgba(var(--color-yellow-rgb), 0.2) !important;
    width: 100%;
    border-bottom: none !important;
}

.wiki-page.markdown-preview-view .callout[data-callout*=info] .callout-icon .svg-icon{
    padding-right: 0.2em;
    width: 1.3em; 
    height: 1.3em;
    color: inherit;
}
.wiki-page.markdown-preview-view .callout {
    display: flexbox;
    width: flex;
    margin: 1em;
}

.wiki-page.markdown-preview-view .callout-title {
    width: fit-content;
    font-size: var(--h3-size);
}
.wiki-page hr {
    border-width: 1px;
    overflow: hidden;
}

.wiki-page.markdown-preview-view table {
    margin-left: 1em;
    margin-right: 1em;
    min-width: 35.5%;
    text-align: center;
}
.wiki-page th {
    text-align: center;
}
.wiki-page .dataview.inline-field-key {
    font-size: inherit;
}

```
