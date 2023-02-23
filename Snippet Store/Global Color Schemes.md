# Global Color Schemes
This snippet contains all the color schemes for **Chime**. As a snippet, it can be used with any theme you have installed (Note: inevitably, this snippet only has a full effect on *certain themes*).
Great if you want to shake up your favourite theme with some extra colors. 

```css

/* ----- default (Macaroon) theme ----- */


 .theme-macaroon.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-red-rgb: 225, 120, 132;
    --color-red: #e17884;
    --color-green-rgb: 117, 194, 151;
    --color-green: #75c297;
    --color-orange-rgb: 241, 144, 112;
    --color-orange: #f19070;
    --color-yellow-rgb: 255, 168, 46;
    --color-yellow: #dcb46f;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 136, 198, 227;
    --color-blue: #88c6e3;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 220, 118, 167;
    --color-pink: #dc76a7;
    --color-base-00: #fffdf8;
    --color-base-05: #faf3f1;
    --color-base-10: #f0e9e4;
    --color-base-20: #e7d8d8;
    --color-base-25: #d9c9ca;
    --color-base-30: #cec2c577;
    --color-base-35: #b5a7ac;
    --color-base-40: #b6a4b2;
    --color-base-50: #a391a3;
    --color-base-60: #867786;
    --color-base-70: #685a68;
    --color-base-100: #594f67;
  }
 .theme-macaroon.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --color-red-rgb: 225, 120, 132;
    --color-red: #e17884;
    --color-green-rgb: 117, 194, 151;
    --color-green: #75c297;
    --color-orange-rgb: 241, 144, 112;
    --color-orange: #f19070;
    --color-yellow-rgb: 255, 168, 46;
    --color-yellow: #dcb46f;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 136, 198, 227;
    --color-blue: #88c6e3;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 220, 118, 167;
    --color-pink: #dc76a7;
    --color-base-00: #3b3347;
    --color-base-10: #413b4e;
    --color-base-20: #2f2837;
    --color-base-25: #55546e;
    --color-base-30: #4e4560;
    --color-base-35: #545e76;
    --color-base-40: rgb(98, 111, 134);
    --color-base-50: rgb(125, 127, 149);
    --color-base-60: rgb(103, 129, 148);
    --color-base-70: #7f83a1;
    --color-base-100: #a0a7c4;
  }

  /* ----- Ash Theme ----- */

  .theme-crystal.theme-light .vertical-tab-nav-item {
    color: var(--text-muted);
  }
  
  .theme-crystal .nav-file-title:hover,
  .theme-ash-old .nav-file-title:hover {
    color: var(--interactive-accent) !important;
  }

  .theme-crystal {
    --nav-item-color-active: var(--color-accent);
  }
  .theme-crystal .nav-folder.mod-root > .nav-folder-title {
    color: var(--color-accent);
    font-weight: 900;
    font-size: 1.25em;
  }
  
  .theme-crystal.theme-light {
    color-scheme: light;
    --icon-color-focused: var(--interactive-accent);
    --highlight-mix-blend-mode: darken;
    --vault-name-color: var(--color-accent-1);
    --accent-h: 0;
    --accent-s: 69%;
    --accent-l: 59%;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-red-rgb: 255, 0, 0;
    --color-red: #c75d5d;
    --color-green-rgb: 8, 185, 78;
    --color-green: #a2bb79;
    --color-orange-rgb: 246, 78, 0;
    --color-orange: #d58b69;
    --color-yellow-rgb: 255, 128, 0;
    --color-yellow: #c9b174;
    --color-cyan-rgb: 0, 179, 149;
    --color-cyan: #96b7aa;
    --color-blue-rgb: 0, 181, 197;
    --color-blue: #79a2ae;
    --color-purple-rgb: 82, 131, 238;
    --color-purple: #969cc1;
    --color-pink-rgb: 126, 88, 216;
    --color-pink: #b69ac2;
    
    --color-base-00: #e8e8e8;
    --color-base-05: #e2e2e2;
    --color-base-10: #dadada;
    --color-base-20: #a8a8a8;
    --color-base-25: #959595;
    --color-base-30: #7b7b7b4c;
    --color-base-35: #757575;
    --color-base-40: #5e5e5e;
    --color-base-50: #8d8d8d;
    --color-base-60: #2f3234;
    --color-base-70: #717171;
    --color-base-100: #000000;
    --background-secondary: var(--color-base-60);
    
    /* 
    --color-base-00: #e2e9ed;
    --color-base-05: #c5d5de;
    --color-base-10: #ccd9e1;
    --color-base-20: #2c323b;
    --color-base-25: #bac5d0;
    --color-base-30: #5f728f41;
    --color-base-35: #e05f5f;
    --color-base-40: #9facbb;
    --color-base-50: #5877a2;
    --color-base-60: #7a5757;
    --color-base-70: #617686;
    --color-base-100: #222222;
    */
  }


  .theme-crystal.theme-dark {
    color-scheme: dark;
    --vault-name-color: var(--color-accent-1);
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --accent-h: 0;
    --accent-s: 65%;
    --accent-l: 62%;
    --mono-rgb-100: 255, 255, 255;
    --color-red-rgb: 228, 111, 125;
    --color-red-rgb: 255, 0, 0;
    --color-red-rgb: 255, 0, 0;
    --color-red: #d96943;
    --color-green-rgb: 8, 185, 78;
    --color-green: #a2bb79;
    --color-orange-rgb: 246, 78, 0;
    --color-orange: #d58b69;
    --color-yellow-rgb: 255, 128, 0;
    --color-yellow: #c9b174;
    --color-cyan-rgb: 0, 179, 149;
    --color-cyan: #96b7aa;
    --color-blue-rgb: 0, 181, 197;
    --color-blue: #79a2ae;
    --color-purple-rgb: 82, 131, 238;
    --color-purple: #969cc1;
    --color-pink-rgb: 126, 88, 216;
    --color-pink: #b69ac2;
    /*
    --color-base-00: #32373e;
    --color-base-10: #3c4249;
    --color-base-20: #1d1f22;
    --color-base-25: #4e545c;
    --color-base-30: #575e6765;
    --color-base-35: #697179;
    --color-base-40: #7b848e;
    --color-base-50: #8b949f;
    --color-base-60: #919ba6;
    --color-base-70: #757b82;
    --color-base-100: #a1abb7;
    */
    --color-base-00: #2d323a;
    --color-base-10: #3a3f42;
    --color-base-20: #26272e;
    --color-base-25: #262323;
    --color-base-30: #373d48;
    --color-base-35: #546a76;
    --color-base-40: rgb(105, 122, 142);
    --color-base-50: rgb(74, 98, 138);
    --color-base-60: rgb(122, 139, 165);
    --color-base-70: #65707d;
    --color-base-100: #a4acb5;
  }

 /* ----- old ash theme ----- */

 .theme-ash-old.theme-light .vertical-tab-nav-item {
    color: var(--text-muted);
  }
  .theme-ash-old .nav-folder.mod-root > .nav-folder-title {
    color: var(--color-accent);
    font-weight: 700;
  }


  .theme-ash-old {
    --nav-item-color-active: var(--color-accent);
  }

  .theme-ash-old.theme-light {
    color-scheme: light;
    --icon-color-focused: var(--interactive-accent);
    --highlight-mix-blend-mode: darken;
    --vault-name-color: var(--color-accent-1);
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --accent-h: 0 !important;
    --accent-s: 79% !important;
    --accent-l: 59% !important;
    --color-red-rgb: 255, 0, 0;
    --color-red: #ff0000;
    --color-green-rgb: 8, 185, 78;
    --color-green: #00c445;
    --color-orange-rgb: 246, 78, 0;
    --color-orange: #f64e00;
    --color-yellow-rgb: 255, 128, 0;
    --color-yellow: #ff8000;
    --color-cyan-rgb: 0, 179, 149;
    --color-cyan: #00b395;
    --color-blue-rgb: 0, 181, 197;
    --color-blue: #00b5c5;
    --color-purple-rgb: 82, 131, 238;
    --color-purple: #5283ee;
    --color-pink-rgb: 126, 88, 216;
    --color-pink: #7e58d8;
    --color-base-00: #e2e9ed;
    --color-base-05: #c5d5de;
    --color-base-10: #ccd9e1;
    --color-base-20: #2c323b;
    --color-base-25: #bac5d0;
    --color-base-30: #5f728f41;
    --color-base-35: #e05f5f;
    --color-base-40: #9facbb;
    --color-base-50: #5877a2;
    --color-base-60: #7a5757;
    --color-base-70: #617686;
    --color-base-100: #222222;
  }
  .theme-ash-old.theme-dark {
    color-scheme: dark;
    --vault-name-color: var(--color-accent-1);
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --accent-h: 5 !important;
    --accent-s: 59% !important;
    --accent-l: 60% !important;
    --color-red-rgb: 228, 111, 125;
    --color-red-rgb: 255, 0, 0;
    --color-red: #ff0000;
    --color-green-rgb: 8, 185, 78;
    --color-green: #00c445;
    --color-orange-rgb: 246, 78, 0;
    --color-orange: #f64e00;
    --color-yellow-rgb: 255, 128, 0;
    --color-yellow: #ff8000;
    --color-cyan-rgb: 0, 179, 149;
    --color-cyan: #00b395;
    --color-blue-rgb: 0, 181, 197;
    --color-blue: #00b5c5;
    --color-purple-rgb: 82, 131, 238;
    --color-purple: #5283ee;
    --color-pink-rgb: 126, 88, 216;
    --color-pink: #7e58d8;
    --color-base-00: #2d323a;
    --color-base-10: #483437;
    --color-base-20: #26272e;
    --color-base-25: #262323;
    --color-base-30: #373d48;
    --color-base-35: #765454;
    --color-base-40: rgb(105, 122, 142);
    --color-base-50: rgb(142, 81, 81);
    --color-base-60: rgb(202, 112, 112);
    --color-base-70: #65707d;
    --color-base-100: #b5a4a4;
  }



  /* ----- spring theme ----- */

 
  .theme-spring.colored-bold-and-italic {
    --bold-color: rgb(135, 204, 135);
  }

  .colorful-headings.theme-spring {
    --h1-color: rgb(142, 202, 127);
    --h2-color: rgb(126, 216, 188);
    --h4-color: rgb(227, 185, 114);
    --h3-color: rgb(239, 165, 180);
    --h5-color: rgb(200, 207, 85);
    --h6-color: rgb(104, 189, 203);
  }
.colorful-headings-alt.theme-spring {
--h1-color: rgb(156, 196, 129);
--h2-color: rgb(175, 209, 145);
--h3-color: rgb(179, 216, 115);
--h4-color: rgb(190, 218, 106);
--h5-color: rgb(213, 218, 61);
--h6-color: rgb(215, 214, 141);
}
  .theme-spring.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --accent-h: 81 !important;
    --accent-s: 68% !important; 
    --accent-l: 58% !important;
    --color-base-00: #fdfff5;
    --color-base-05: #f4f8e2;
    --color-base-10: #e7eed4;
    --color-base-20: #e3efd2;
    --color-base-25: #ddeace;
    --color-base-30: rgb(186, 209, 177);
    --color-base-35: #a5c1a1;
    --color-base-40: #96c09f;
    --color-base-50: #8cb59b;
    --color-base-60: #82a196;
    --color-base-70: #608b76;
    --color-base-100: #467262;
  }
  .theme-spring.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --accent-h: 79 !important;
    --accent-s: 80% !important;
    --accent-l: 69% !important;
    --color-red-rgb: 228, 111, 125;
    --color-red: #e46f7d;
    --color-green-rgb: 165, 209, 140;
    --color-green: #a5d18c;
    --color-orange-rgb: 251, 179, 108;
    --color-orange: #fbb36c;
    --color-yellow-rgb: 255, 222, 115;
    --color-yellow: #ffde73;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 86, 174, 214;
    --color-blue: #56aed6;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 255, 148, 200;
    --color-pink: #ff94c8;
    --color-base-00: #414e44;
    --color-base-10: #45594b;
    --color-base-20: #37463d;
    --color-base-25: #556951;
    --color-base-30: #4e624b;
    --color-base-35: #6b8669;
    --color-base-40: rgb(119, 161, 116);
    --color-base-50: rgb(143, 163, 141);
    --color-base-60: rgb(137, 161, 118);
    --color-base-70: #a0ae8e;
    --color-base-100: #c5ccac;
  }

  /* ----- novelist theme + novel css class ----- */
  
.theme-novelist .markdown-preview-view br {
    content: '';
    display: block;
    margin-top: 10px;
}

/* --- dividers --- */
.theme-novelist:not(.is-mobile) .markdown-rendered hr::before, .theme-novelist .markdown-source-view hr::before{
    font-size: 1.5em;
    content: '🕮';
    font-weight: 500;
    display: inline-block;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    transform-origin: 50% 50%;
    padding: 0.35rem;
    color: var(--background-modifier-border-hover);
    background-color: var(--background-primary);
    z-index: 1;
    
}
/* ------- colorful headings ------ */

/* --- normal, light mode --- */
  .theme-novelist.theme-light.colorful-headings{
    --h1-color: #9e7759;
    --h2-color: #b58a62;
    --h3-color: #cd9b6d;
    --h4-color: #d29035;
    --h5-color: rgb(210, 170, 51);
    --h6-color: rgb(222, 173, 26);
  }

  /* --- alternate --- */
  .theme-novelist.colorful-headings-alt .inline-title,
  .theme-novelist.colorful-headings-alt h1, .theme-novelist.colorful-headings-alt .HyperMD-header-1,
  .theme-novelist.colorful-headings-alt h2, .theme-novelist.colorful-headings-alt .HyperMD-header-2,
  .theme-novelist.colorful-headings-alt h3, .theme-novelist.colorful-headings-alt .HyperMD-header-3,
  .theme-novelist.colorful-headings-alt h4, .theme-novelist.colorful-headings-alt .HyperMD-header-4,
  .theme-novelist.colorful-headings-alt h5, .theme-novelist.colorful-headings-alt .HyperMD-header-5,
  .theme-novelist.colorful-headings-alt h6, .theme-novelist.colorful-headings-alt .HyperMD-header-6 {
    -webkit-background-clip: text;
    color: transparent;
}
.theme-novelist.colorful-headings-alt h1, .theme-novelist.colorful-headings-alt HyperMD-header-1, 
.theme-novelist.colorful-headings-alt .inline-title {
background-image: linear-gradient(rgb(244, 205, 11), rgb(216, 171, 57));
}
.theme-novelist.colorful-headings-alt h2, .theme-novelist.colorful-headings-alt HyperMD-header-2 {
    background-image: linear-gradient(#f4ba69, rgb(210, 170, 51));
    }
.theme-novelist.colorful-headings-alt h3, .theme-novelist.colorful-headings-alt HyperMD-header-3 {
    background-image: linear-gradient(#dfb535, #d29035);
    }
.theme-novelist.colorful-headings-alt h4, .theme-novelist.colorful-headings-alt HyperMD-header-4 {
        background-image: linear-gradient(#f1a73f, #b7895d);
}
.theme-novelist.colorful-headings-alt h5, .theme-novelist.colorful-headings-alt HyperMD-header-5 {
    background-image: linear-gradient(#f1ae6f, #b47f4e);
}
.theme-novelist.colorful-headings-alt h6, .theme-novelist.colorful-headings-alt HyperMD-header-6 {
    background-image: linear-gradient(#f08e34, #946d4f);
}

  .theme-novelist.theme-dark.colorful-headings{
    --h1-color: rgb(228, 191, 163);
    --h2-color: rgb(215, 179, 145);
    --h3-color: rgb(207, 166, 129);
    --h4-color: rgb(191, 157, 108);
    --h5-color: rgb(203, 177, 99);
    --h6-color: rgb(195, 165, 75);
  }
  
  .theme-novelist.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-base-00: #faf8f0;
    --color-base-05: #f2eadb;
    --color-base-10: #f4f0e9;
    --color-base-20: #f4eee3;
    --color-base-25: #ccb8a0;
    --color-base-30: #e1d5c9;
    --color-base-35: #cebcac;
    --color-base-40: #c1a88f;
    --color-base-50: #a2988f;
    --color-base-60: #9f7b5f;
    --color-base-70: #7b6c65;
    --color-base-100: #524f4d;
  }
  .theme-novelist.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --color-base-00: #4d3d2e;
    --color-base-10: #574534;
    --color-base-20: #3a2e20;
    --color-base-25: #574c40;
    --color-base-30: #5f4b38;
    --color-base-35: #847163;
    --color-base-40: rgb(146, 130, 111);
    --color-base-50: rgb(167, 153, 146);
    --color-base-60: rgb(188, 172, 162);
    --color-base-70: #cabbac;
    --color-base-100: #dacfbc;
  }

  /* ----- nord theme ----- */
   .theme-nord.colorful-headings {
   /* --h1-color: #5E81AC;
    --h2-color: #7da0c3;
    --h3-color: #85b4cf;
    --h4-color: #80b5c3;
    --h5-color: #81b8c2;
    --h6-color: #8FBCBB;*/
    --h1-color: var(--color-red);
    --h2-color: var(--color-orange);
    --h3-color: var(--color-yellow);
    --h4-color: var(--color-green);
    --h5-color: var(--color-cyan);
    --h6-color: var(--color-blue);
} 
.theme-nord.colorful-headings-alt{
    --h1-color: #5E81AC;
    --h2-color: #81A1C1;
    --h3-color: #88C0D0;
    --h4-color: #8FBCBB;
    --h5-color: #A3BE8C;
    --h6-color: #EBCB8B;
}

.theme-nord.colored-bold-and-italic {
    --bold-color: var(--color-blue);
    --italic-color: var(--color-green);
}


  .theme-nord {
    --accent-h: 92 !important;
    --accent-s: 28% !important;
    --accent-l: 65% !important; 
  }
  .theme-nord.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-red-rgb: 191, 97, 106;
    --color-red: #BF616A;
    --color-green-rgb: 163, 190, 140;
    --color-green: #A3be8c;
    --color-orange-rgb: 208, 135, 112;
    --color-orange: #d08770;
    --color-yellow-rgb: 235, 203, 139;
    --color-yellow: #ebcb8b;
    --color-cyan-rgb: 136, 192, 208;
    --color-cyan: #88c0d0;
    --color-blue-rgb: 129, 161, 193;
    --color-blue: #81a1c1;
    --color-purple-rgb: 94, 129, 172;
    --color-purple: #5e81AC;
    --color-pink-rgb: 180, 142, 173;
    --color-pink: #b48ead;
    --color-base-00: #ffffff;
    --color-base-05: #f1f3f6;
    --color-base-10: #edf0f4;
    --color-base-20: #E5E9F0;
    --color-base-25: #dbe0e9;
    --color-base-30: #D8DEE9;
    --color-base-35: #ced4de;
    --color-base-40: #bec5d2;
    --color-base-50: #abb4c4;
    --color-base-60: #99a3b6;
    --color-base-70: #848fa4;
    --color-base-100: #4a5364;
  }
  .theme-nord.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --color-red-rgb: 191, 97, 106;
    --color-red: #BF616A;
    --color-green-rgb: 163, 190, 140;
    --color-green: #A3be8c;
    --color-orange-rgb: 208, 135, 112;
    --color-orange: #d08770;
    --color-yellow-rgb: 235, 203, 139;
    --color-yellow: #ebcb8b;
    --color-cyan-rgb: 136, 192, 208;
    --color-cyan: #88c0d0;
    --color-blue-rgb: 129, 161, 193;
    --color-blue: #81a1c1;
    --color-purple-rgb: 94, 129, 172;
    --color-purple: #5e81AC;
    --color-pink-rgb: 180, 142, 173;
    --color-pink: #b48ead;
    --color-base-00: #2E3440; 
    /* --color-base-00:  #3B4252; */
    --color-base-10: #383f4c;
     --color-base-20: #3B4252; 
    /*--color-base-20:  #2E3440; */
    --color-base-25: #474e5f;
    --color-base-30: #434C5E;
    --color-base-35: #50596b;
    --color-base-40: #4C566A;
    --color-base-50: #5f697e;
    --color-base-60: #7d8698;
    --color-base-60: #979fb1;
    --color-base-70: #b5bdcc;
    --color-base-100: #cad0de;
  }

  /* ----- classic obsidian theme ----- */
 .theme-classic.theme-light {
  color-scheme: light;
  --highlight-mix-blend-mode: darken;
  --mono-rgb-0: 255, 255, 255;
  --mono-rgb-100: 0, 0, 0;
  --color-red-rgb: 233, 49, 71;
  --color-red: #E93147;
  --color-green-rgb: 8, 185, 78;
  --color-green: #08B94E;
  --color-orange-rgb: 236, 117, 0;
  --color-orange: #ec7500;
  --color-yellow-rgb: 224, 172, 0;
  --color-yellow: #e0ac00;
  --color-cyan-rgb: 0, 191, 188;
  --color-cyan: #00bfbc;
  --color-blue-rgb: 8, 109, 221;
  --color-blue: #086DDD;
  --color-purple-rgb: 120, 82, 238;
  --color-purple: #7852EE;
  --color-pink-rgb: 213, 57, 132;
  --color-pink: #D53984;
  --color-base-00: #ffffff;
  --color-base-05: #fcfcfc;
  --color-base-10: #fafafa;
  --color-base-20: #f6f6f6;
  --color-base-25: #e3e3e3;
  --color-base-30: #e0e0e0;
  --color-base-35: #d4d4d4;
  --color-base-40: #bdbdbd;
  --color-base-50: #ababab;
  --color-base-60: #707070;
  --color-base-70: #5a5a5a;
  --color-base-100: #222222;
}
.theme-classic.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --color-red-rgb: 251, 70, 76;
    --color-red: #fb464c;
    --color-orange-rgb: 233, 151, 63;
    --color-orange: #E9973F;
    --color-yellow-rgb: 224, 222, 113;
    --color-yellow: #E0DE71;
    --color-green-rgb: 68, 207, 110;
    --color-green: #44CF6E;
    --color-cyan-rgb: 83, 223, 221;
    --color-cyan: #53DFDD;
    --color-blue-rgb: 2, 122, 255;
    --color-blue: #027aff;
    --color-purple-rgb: 168, 130, 255;
    --color-purple: #a882ff;
    --color-pink-rgb: 250, 153, 205;
    --color-pink: #FA99CD;
    --color-base-00: #1e1e1e;
    --color-base-10: #242424;
    --color-base-20: #262626;
    --color-base-25: #2a2a2a;
    --color-base-30: #363636;
    --color-base-35: #3F3F3F;
    --color-base-40: #555;
    --color-base-50: #666;
    --color-base-60: #999;
    --color-base-70: #bababa;
    --color-base-100: #dadada;
}
  
/* ----- light & bright theme ----- */

.theme-light-and-bright {
  --h1-weight: 600;
  --h2-weight: 600;
  --h3-weight: 600;
  --h4-weight: 600;
  --h5-weight: 600;
  --h6-weight: 600;
}
.theme-light-and-bright.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-red-rgb: 228, 111, 125;
    --color-red: #e46f7d;
    --color-green-rgb: 165, 209, 140;
    --color-green: #a5d18c;
    --color-orange-rgb: 251, 179, 108;
    --color-orange: #fbb36c;
    --color-yellow-rgb: 255, 222, 115;
    --color-yellow: #ffde73;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 86, 174, 214;
    --color-blue: #56aed6;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 255, 148, 200;
    --color-pink: #ff94c8;
    --color-base-00: hsl(calc(0 + var(--accent-h)), 100%, 99.5%);
    --color-base-05: hsl(calc(0 + var(--accent-h)), 40%, 96.5%);
    --color-base-10: hsl(calc(0 + var(--accent-h)), 30%, 95.9%);
    --color-base-20: hsl(calc(0 + var(--accent-h)), calc(var(--accent-s) - 5%), calc(95% - calc(var(--accent-l)/100)));
    --color-base-25: hsl(calc(0 + var(--accent-h)), 80%, 42%);
    --color-base-30: hsl(calc(0 + var(--accent-h)), calc(var(--accent-s) - 55%), 89%);
    --color-base-35: hsl(calc(0 + var(--accent-h)), 70%, 88%);
    --color-base-40: hsl(calc(0 + var(--accent-h)), 65%, 86%);
    --color-base-50: hsl(calc(0 + var(--accent-h)), 18%, 63%);
    --color-base-60: hsl(calc(0 + var(--accent-h)), 55%, 72%);
    --color-base-70: hsl(calc(0 + var(--accent-h)), 5%, 55%);
    --color-base-100: hsl(calc(0 + var(--accent-h)), 5%, 30%);
  }
  .theme-light-and-bright.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --color-red-rgb: 228, 111, 125;
    --color-red: #e46f7d;
    --color-green-rgb: 165, 209, 140;
    --color-green: #a5d18c;
    --color-orange-rgb: 251, 179, 108;
    --color-orange: #fbb36c;
    --color-yellow-rgb: 255, 222, 115;
    --color-yellow: #ffde73;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 86, 174, 214;
    --color-blue: #56aed6;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 255, 148, 200;
    --color-pink: #ff94c8;
    --color-base-00:hsl(calc(0 + var(--accent-h)), 11%, 15.5%);
    --color-base-10: hsl(calc(0 + var(--accent-h)), 11.5%, 18.5%);
    --color-base-20: hsl(calc(0 + var(--accent-h)), 10%, 12%);
    --color-base-25: hsl(calc(0 + var(--accent-h)), 11.5%, 10%);
    --color-base-30: hsl(calc(0 + var(--accent-h)), 12%, 23%);
    --color-base-35: hsl(calc(0 + var(--accent-h)), 14%, 11%);
    --color-base-40: hsl(calc(0 + var(--accent-h)), 16%, 12%);
    --color-base-50: hsl(calc(0 + var(--accent-h)), 18%, 55%);
    --color-base-60: hsl(calc(0 + var(--accent-h)), 20%, 13%);
    --color-base-70: hsl(calc(0 + var(--accent-h)), 15%, 45%);
    --color-base-100: hsl(calc(0 + var(--accent-h)), 15%, 75%);
  }

  /* --- dividers --- */
  .theme-light-and-bright .markdown-rendered hr::before, .theme-light-and-bright .markdown-source-view hr::before {
    font-size: 1.5em;
    content: '✦';
    display: inline-block;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    transform-origin: 50% 50%;
    padding: 0.35rem;
    color: var(--background-modifier-border);
    background-color: var(--background-primary);
    z-index: 1;
}

  /* ----- solarized theme ----- */
  .theme-solarized.colorful-headings {
    --h1-color: var(--color-cyan);
    --h2-color: var(--color-blue);
    --h3-color: var(--color-purple);
    --h4-color: var(--color-pink);
    --h5-color: var(--color-red);
    --h6-color: var(--color-orange);
  }
  .theme-solarized.colorful-headings-alt {
    --h1-color: var(--color-orange);
    --h2-color: var(--color-yellow);
    --h3-color: var(--color-green);
    --h4-color: var(--color-cyan);
    --h5-color: var(--color-blue);
    --h6-color: var(--color-purple);
  }
  .theme-solarized {
    --accent-h: 18 !important;
    --accent-s: 80% !important;
    --accent-l: 44% !important;
    --color-red-rgb: 220, 50, 47;
    --color-red: #dc322f;
    --color-green-rgb: 133, 153, 0;
    --color-green: #859900;
    --color-orange-rgb: 203, 75, 22;
    --color-orange: #cb4b16;
    --color-yellow-rgb: 181, 137, 0;
    --color-yellow: #b58900;
    --color-cyan-rgb: 42, 161, 152;
    --color-cyan: #2aa198;
    --color-blue-rgb: 38, 139, 210;
    --color-blue: #268bd2;
    --color-purple-rgb:108, 113, 196;
    --color-purple: #6c71c4;
    --color-pink-rgb: 211, 54, 130;
    --color-pink: #d33682;
  }
  .theme-solarized.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-base-00: #fdf6e3;
    --color-base-05: #f4efde;
    --color-base-10: #f1ecda;
    --color-base-20: #eee8d5;
    --color-base-25: #eee8d5;
    --color-base-30: #ddd6c1;
    --color-base-35: #ccc5ae;
    --color-base-40: #a7b4b4;
    --color-base-50: #93a1a1;
    --color-base-60: #839496;
    --color-base-70: #657b83;
    --color-base-100: #586e75;
  }
  .theme-solarized.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --color-base-00: #002b36;
    --color-base-10: #06333f;
    --color-base-20: #073642;
    --color-base-25: #0c404d;
    --color-base-30: #173c47;
    --color-base-35: #3a4e54;
    --color-base-40: #3e545c;
    --color-base-50: #536668;
    --color-base-60: #586b6d;
    --color-base-70: #657c7e;
    --color-base-100: #8a9a9c;
}



/* ----- gruvbox theme ----- */

.theme-gruvbox.colorful-headings {
    --h1-color: var(--color-red);
    --h2-color: var(--color-orange);
    --h3-color: var(--color-yellow);
    --h4-color: var(--color-green);
    --h5-color: var(--color-cyan);
    --h6-color: var(--color-blue);
}
.theme-gruvbox.colorful-headings-alt {
    --h1-color: var(--color-green);
    --h2-color: var(--color-cyan);
    --h3-color: var(--color-blue);
    --h4-color: var(--color-purple);
    --h5-color: var(--color-pink);
    --h6-color: var(--color-red);
}
.theme-gruvbox.theme-light {
    --accent-h: 2 !important;
    --accent-s: 75% !important;
    --accent-l: 46% !important;
    --color-red-rgb: 204, 36, 29;
    --color-red: #cc241d;
    --color-green-rgb: 152, 151, 26;
    --color-green: #98971a;
    --color-orange-rgb: 214, 93, 14;
    --color-orange: #d65d0e;
    --color-yellow-rgb: 215, 153, 33;
    --color-yellow: #d79921;
    --color-cyan-rgb: 104, 157, 106;
    --color-cyan: #689d6a;
    --color-blue-rgb: 69, 133, 136;
    --color-blue: #458588;
    --color-purple-rgb: 177, 98, 130;
    --color-purple: #b16282;
    --color-pink-rgb: 211, 54, 130;
    --color-pink: #d33682;
  }
.theme-gruvbox.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-base-00: #fbf1c7;
    --color-base-05: #f2e5bc;
    --color-base-10: #f2e5bc;
    --color-base-20: #f2e5bc;
    --color-base-25:  #ebdbb2;
    --color-base-30: #d5c4a1;
    --color-base-35: #bdae93;
    --color-base-40: #a89984;
    --color-base-50: #928374;
    --color-base-60: #928374;
    --color-base-70: #7c6f64;
    --color-base-100: #665c54;
  }
  .theme-gruvbox.theme-dark {
    --accent-h: 6 !important;
    --accent-s: 96% !important;
    --accent-l: 59% !important;
    --color-red-rgb:251, 73, 52;
    --color-red: #fb4934;
    --color-green-rgb: 184, 186, 38;
    --color-green: #b8bb26;
    --color-orange-rgb: 255, 135, 55;
    --color-orange: #ff8737;
    --color-yellow-rgb: 215, 153, 33;
    --color-yellow: #fabd2f;
    --color-cyan-rgb: 142, 192, 124;
    --color-cyan: #8ec07c;
    --color-blue-rgb: 131, 165, 152;
    --color-blue: #83a598;
    --color-purple-rgb: 211, 134, 155;
    --color-purple: #d3869b;
    --color-pink-rgb: 241, 168, 203;
    --color-pink: #f1a8cb;
  }
  .theme-gruvbox.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --color-base-00: #282828;
    --color-base-10: #282828;
    --color-base-20: #1d2021;
    --color-base-25: #3c3836;
    --color-base-30: #413b37;
    --color-base-35: #665c54;
    --color-base-40: #7c6f64;
    --color-base-50: #928374;
    --color-base-60: #a89984;
    --color-base-70: #beb19f;
    --color-base-100: #c5baa9;
}

/* ----- anytype theme ----- */

.theme-anytype.colored-bold-and-italic {
    --bold-color: var(--color-blue);
    --italic-color: var(--color-green);
}

.theme-anytype.colorful-headings {
    --h1-color: var(--text-normal);
    --h2-color: var(--text-normal);
    --h3-color: var(--text-normal);
    --h4-color: var(--text-normal);
    --h5-color: var(--text-normal);
    --h6-color: var(--text-normal);
}
.theme-anytype.colorful-headings-alt {
    --h1-color: var(--color-blue);
    --h2-color: var(--color-cyan);
    --h3-color: var(--color-green);
    --h4-color: var(--color-yellow);
    --h5-color: var(--color-orange);
    --h6-color: var(--color-red);
    

}
.theme-anytype.colorful-headings h1, .theme-anytype.colorful-headings .HyperMD-header-1 {
    background-color: rgba(var(--color-red-rgb), 0.2 );
    padding: 5px 10px 5px 10px;
}
.theme-anytype.colorful-headings h2, .theme-anytype.colorful-headings .HyperMD-header-2 {
    background-color: rgba(var(--color-orange-rgb), 0.3 );
    padding: 5px 10px 5px 10px;
}
.theme-anytype.colorful-headings h3, .theme-anytype.colorful-headings .HyperMD-header-3 {
    background-color: rgba(var(--color-yellow-rgb), 0.3 );
    padding: 5px 10px 5px 10px;
}
.theme-anytype.colorful-headings h4, .theme-anytype.colorful-headings .HyperMD-header-4 {
    background-color: rgba(var(--color-green-rgb), 0.3 );
    padding: 5px 0px 5px 10px;
}
.theme-anytype.colorful-headings h5, .theme-anytype.colorful-headings .HyperMD-header-5 {
    background-color: rgba(var(--color-cyan-rgb), 0.3 );
    padding: 3px 10px 3px 10px;
}
.theme-anytype.colorful-headings h6, .theme-anytype.colorful-headings .HyperMD-header-6 {
    background-color: rgba(var(--color-blue-rgb), 0.3 );
    padding: 3px 10px 3px 10px;
}

.theme-anytype {
    --accent-h: 45 !important;
    --accent-s: 100% !important;
    --accent-l: 50% !important;
    --callout-title-color: var(--text-normal);
    --callout-quote: 216, 216, 216;
    --callout-radius: 5px;
    --color-red-rgb: 220, 83, 40;
    --color-red: #DC5328;
    --color-green-rgb: 139, 208, 49;
    --color-green: #8BD031;
    --color-orange-rgb: 241, 177, 56;
    --color-orange: #F1B138;
    --color-yellow-rgb: 234, 213, 60;
    --color-yellow: #EAD53C;
    --color-cyan-rgb: 107, 200, 186;
    --color-cyan: #6BC8BA;
    --color-blue-rgb: 90, 171, 235;
    --color-blue: #5AABEB;
    --color-purple-rgb: 60, 100, 231;
    --color-purple: #3C64E7;
    --color-pink-rgb: 152, 89, 200;
    --color-pink:  #9859C8;
  }

/* --- callouts --- */
.theme-anytype.theme-light .callout {
    background-color: rgba(var(--callout-color), 0.3);
}
.theme-anytype.callout-outlined .callout {
    background-color: transparent !important;
    border-width: 2px;
    border-color: rgba(var(--callout-color), 0.75);
}
.theme-anytype.callout-bordered .callout {
    background-color: rgba(var(--callout-color), 0.3);
    border-width: 2px;
}
.theme-anytype.theme-dark .callout {
    background-color: rgba(var(--callout-color), 0.3);
}
.theme-anytype .callout-icon .svg-icon {
    color: var(--text-normal);
}
.theme-anytype .callout-fold .svg-icon {
    color: var(--text-normal);
}

.theme-anytype.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-base-00: #ffffff;
    --color-base-05: #f8f8f8;
    --color-base-10: #f1f1f1;
    --color-base-20: #fafafa;
    --color-base-25:  #f2f2f2;
    --color-base-30: rgb(230, 230, 230);
    --color-base-35: #d4d4d4;
    --color-base-40: #bdbdbd;
    --color-base-50: #a2a0a0;
    --color-base-60: #7b7b7b;
    --color-base-70: #999999;
    --color-base-100: #2f2f2f;
  }
  .theme-anytype.theme-dark {
    color-scheme: dark;
    --background-modifier-border: #323130;
    --highlight-mix-blend-mode: lighten;
    --color-base-00: #21201e;
    --color-base-10: #32312f;
    --color-base-20: rgb(28, 26, 23);
    --color-base-25: #21201e;
    --color-base-30: #2e2c29;
    --color-base-35: #484643;
    --color-base-40: #605d5a;
    --color-base-50: #7b7974;
    --color-base-60: #9c9994;
    --color-base-70: #aeaba6;
    --color-base-100: #ffffff;
}

/* --------- chinchilla theme --------- */

/* ------ light mode ------ */
.theme-chinchilla.theme-light {
    --color-base-00: white;
    --color-base-05: rgb(251, 251, 251);
    --color-base-10: #f6f6f6;
    --color-base-20: #fbfbfb;
    --color-base-25: #f8f8f8;
    --color-base-30: #f1f1f1;
    --color-base-35: #e7e7e7;
    --color-base-40: #e1e1e1;
    --color-base-50: #aeaeae;
    --color-base-60: #a3a3a3;
    --color-base-70: #888888;
    --color-base-100: #000000;
}
.theme-chinchilla {
        --accent-h: 184 !important;
        --accent-s: 46% !important;
        --accent-l: 66% !important;
        --color-red-rgb: 245, 167, 167;
        --color-red: #f5a7a7;
        --color-green-rgb: 150, 207, 173;
        --color-green: #96cfad;
        --color-orange-rgb: 224, 189, 155;
        --color-orange: #e0bd9b;
        --color-yellow-rgb:219, 209, 176;
        --color-yellow: #dbd1b0;
        --color-cyan-rgb: 166, 199, 199;
        --color-cyan: #a6c7c7;
        --color-blue-rgb: 147, 177, 210;
        --color-blue: #93b1d2;
        --color-purple-rgb:175, 158, 228;
        --color-purple: #af9ee4;
        --color-pink-rgb: 213, 139, 175;
        --color-pink: #d58baf;
    }
    
    /* ------ dark mode ------ */
    
    .theme-chinchilla.theme-dark {
    
    /* Base Colors */
    /* replace these with the main colors of your theme */
        --color-base-00: #5b5b5b;
        --color-base-10: #515151;
        --color-base-20: #4f4f4f;
        --color-base-25: #4d4d4d;
        --color-base-30: #676767;
        --color-base-35: #414141;
        --color-base-40: #3d3d3d;
        --color-base-50: #a4a4a4;
        --color-base-60: rgb(156, 156, 156);
        --color-base-70: #a1a1a1;
        --color-base-100: rgb(255, 255, 255);

    }
    
    /* ------ classes ------ */
    
    /* ---- colorful headings ---- */
    
    /* -- normal -- */
.theme-chinchilla.colorful-headings {
    --h1-color: rgb(115, 195, 195);
    --h2-color: rgb(145, 214, 214);
    --h3-color: rgb(149, 217, 209);
    --h4-color: rgb(162, 213, 202);
    --h5-color: rgb(171, 218, 203);
    --h6-color: rgb(188, 214, 201);
}

    /* -- alternate -- */
.theme-chinchilla.colorful-headings-alt {
    --h1-color: var(--color-blue);
    --h2-color: var(--color-cyan);
    --h3-color: var(--color-green);
    --h4-color: var(--color-yellow);
    --h5-color: var(--color-orange);
    --h6-color: var(--color-red);
}
    
/* ---- colorful bold and italic ---- */
.theme-chinchilla.colored-bold-and-italic {
    --bold-color: var(--color-blue);
    --italic-color: var(--color-purple);
}

/* ------ typography ------ */


    
    

/* ----- celestial theme ----- */

/* --- vault title --- */
.theme-celestial.theme-light.colorful-headings {
    --h1-color: #8ac9de;
    --h2-color: #94d1e6;
    --h3-color: #abd0dc;
    --h4-color: #b2c7da;
    --h5-color: #b2bccf;
    --h6-color: #b4b5dd; 
}
.theme-celestial.theme-dark.colorful-headings-alt {
    --h1-color: #5684d9;
    --h2-color: rgb(119, 148, 214);
    --h3-color: #6e9dc7;
    --h4-color: #609eb8;
    --h5-color: rgb(89, 155, 181);
    --h6-color: #7194a9;
}
.theme-celestial.theme-dark.colorful-headings {
    --h6-color: #898fe1;
    --h5-color: rgb(94, 133, 224);
    --h4-color: #579fde;
    --h3-color: #c5eeff;
    --h2-color: #94d0e7;
    --h1-color: #ceebff;
}
.theme-celestial .nav-folder.mod-root > .nav-folder-title::before {
    content: var(--theme-decoration);
    padding-right: 8px;
    text-align: center;
}
.theme-celestial .nav-folder.mod-root > .nav-folder-title{
    color: var(--color-accent-2) !important;
    font-size: 1.2em;
    font-weight: bold;
    text-align: center;
}

/* --- dividers --- */
.theme-celestial .markdown-rendered hr::before, .theme-celestial .markdown-source-view hr::before{
    font-size: 1.5em;
    content: var(--theme-decoration);
    display: inline-block;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  transform-origin: 50% 50%;
  padding: 0.35rem;
  color: var(--color-accent-1);
  background-color: var(--background-primary);
  z-index: 1;
}

.theme-celestial.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --accent-h: 42 !important;
    --accent-s: 100% !important;
    --accent-l: 50% !important;
    --color-red-rgb: 255, 114, 114;
    --color-red: rgb(255, 145, 114);
    --color-green-rgb: 170, 199, 83;
    --color-green: #aac753;
    --color-orange-rgb: 247, 153, 70;
    --color-orange: #f79946;
    --color-yellow-rgb: 251, 193, 48;
    --color-yellow: #fbc130;
    --color-cyan-rgb: 111, 210, 147;
    --color-cyan: #6fd293;
    --color-blue-rgb: 86, 214, 201;
    --color-blue: #56d6c9;
    --color-purple-rgb: 106, 160, 217;
    --color-purple: #6aa0d9;
    --color-pink-rgb: 148, 113, 231;
    --color-pink: #9471e7;
    --color-base-00: #fff9eb;
    --color-base-05: #fff2dd;
    --color-base-10: #ffefd6;
    --color-base-20: #ffefd6;
    --color-base-25: #fbe0ba;
    --color-base-30: #fbe0ba;
    --color-base-35: #f2d17d;
    --color-base-40: #ecbf5f;
    --color-base-50: #f0b36e;
    --color-base-60: #d99e5a;
    --color-base-70: #af7d43;
    --color-base-100: rgb(155, 109, 87);
    --theme-decoration: '☀️';
  }
  .theme-celestial.theme-dark {
    color-scheme: dark;
    --highlight-mix-blend-mode: lighten;
    --background-modifier-border: #3b3f56;
    --mono-rgb-0: 0, 0, 0;
    --mono-rgb-100: 255, 255, 255;
    --accent-h: 41 !important;
    --accent-s: 100% !important;
    --accent-l: 100% !important;
    --color-red-rgb: 228, 111, 125;
    --color-red: #e46f7d;
    --color-green-rgb: 165, 209, 140;
    --color-green: #a5d18c;
    --color-orange-rgb: 251, 179, 108;
    --color-orange: #fbb36c;
    --color-yellow-rgb: 255, 222, 115;
    --color-yellow: #ffde73;
    --color-cyan-rgb: 111, 210, 194;
    --color-cyan: #6fd2c2;
    --color-blue-rgb: 86, 174, 214;
    --color-blue: #56aed6;
    --color-purple-rgb: 181, 132, 199;
    --color-purple: #b584c7;
    --color-pink-rgb: 255, 148, 200;
    --color-pink: #ff94c8;
    --color-base-00: #2a3141;
    --color-base-10: #25273a;
    --color-base-20: #1d1f2f;
    --color-base-25: #3a435d;
    --color-base-30: #1d1f2f;
    --color-base-35: #3b445d;
    --color-base-40: #515b71;
    --color-base-50: #5f6980;
    --color-base-60: #70778e;
    --color-base-70: #8890a6;
    --color-base-100: #989eb2;
    --theme-decoration: '☾';
    --h1-color: rgb(255, 255, 255);
    --h2-color: white;
    --h3-color: white;
    --h4-color: white;
    --h5-color: white;
    --h6-color: white;
  }
.theme-celestial.theme-dark blockquote {
    border-radius: 50px;
    padding: 1em 1.5em 1em 1.5em;
}
.theme-celestial.theme-dark .markdown-rendered hr, .theme-celestial.theme-dark .markdown-source-view hr {
    border-color: var(--text-faint);
}


/* ----- notion theme ----- */
/* - bold and italic colors - */
.theme-notion.colored-bold-and-italic {
    --bold-color: var(--color-red);
    --italic-color: var(--color-blue);
}

/* - dividers - */
.theme-notion hr {
    margin: 0px;
    border-width: 1px;
    opacity: 0.5;
}

/* --- headings ---- */
.theme-notion.colorful-headings, .novel, .theme-notion.colorful-headings-alt {
    --h1-color: var(--text-normal);
    --h2-color: var(--text-normal);
    --h3-color: var(--text-normal);
    --h4-color: var(--text-normal);
    --h5-color: var(--text-normal);
    --h6-color: var(--text-normal);
}

/* - colorful headings -*/
.theme-notion.theme-light.colorful-headings h1, .theme-notion.theme-light.colorful-headings .HyperMD-header-1 {
    background-color: rgba(var(--color-red-rgb), 0.13);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-light.colorful-headings h2, .theme-notion.theme-light.colorful-headings .HyperMD-header-2 {
    background-color: rgba(var(--color-orange-rgb), 0.13);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-light.colorful-headings h3, .theme-notion.theme-light.colorful-headings .HyperMD-header-3 {
    background-color: rgba(var(--color-yellow-rgb), 0.15);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-light.colorful-headings h4, .theme-notion.theme-light.colorful-headings .HyperMD-header-4{
    background-color: rgba(var(--color-green-rgb), 0.13);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-light.colorful-headings h5, .theme-notion.theme-light.colorful-headings .HyperMD-header-5 {
    background-color: rgba(var(--color-blue-rgb), 0.13);
    padding: 3px 10px 3px 10px;
}
.theme-notion.theme-light.colorful-headings h6, .theme-notion.theme-light.colorful-headings .HyperMD-header-6 {
    background-color: rgba(var(--color-purple-rgb), 0.13);
    padding: 3px 10px 3px 10px;
}
.theme-notion.theme-dark.colorful-headings h1, .theme-notion.theme-dark.colorful-headings .HyperMD-header-1 {
    background-color: rgba(var(--color-red-rgb), 0.26);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-dark.colorful-headings h2, .theme-notion.theme-dark.colorful-headings .HyperMD-header-2 {
    background-color: rgba(var(--color-orange-rgb), 0.26);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-dark.colorful-headings h3, .theme-notion.theme-dark.colorful-headings .HyperMD-header-3 {
    background-color: rgba(var(--color-yellow-rgb), 0.26);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-dark.colorful-headings h4, .theme-notion.theme-dark.colorful-headings .HyperMD-header-4 {
    background-color: rgba(var(--color-green-rgb), 0.26);
    padding: 5px 10px 5px 10px;
}
.theme-notion.theme-dark.colorful-headings h5, .theme-notion.theme-dark.colorful-headings .HyperMD-header-5 {
    background-color: rgba(var(--color-blue-rgb), 0.26);
    padding: 3px 10px 3px 10px;
}
.theme-notion.theme-dark.colorful-headings h6, .theme-notion.theme-dark.colorful-headings .HyperMD-header-6 {
    background-color: rgba(var(--color-purple-rgb), 0.26);
    padding: 3px 10px 3px 10px;
}
/* - colors and font - */
.theme-notion {
    --accent-h: 210 !important;
    --accent-s: 77% !important;
    --accent-l: 51% !important;
    --callout-quote: 120, 119, 116;
  }

/* - alternate colorful headings - */


.theme-notion.colorful-headings-alt h2, .theme-notion.colorful-headings-alt .HyperMD-header-2,
.theme-notion.colorful-headings-alt h3, .theme-notion.colorful-headings-alt .HyperMD-header-3,
.theme-notion.colorful-headings-alt h4, .theme-notion.colorful-headings-alt .HyperMD-header-4 {
    background-color: var(--color-gray);
    padding: 5px 4px 5px 4px;
    border-bottom: none !important;
}
.theme-notion.colorful-headings-alt h5, .theme-notion.colorful-headings-alt .HyperMD-header-5,
.theme-notion.colorful-headings-alt h6, .theme-notion.colorful-headings-alt .HyperMD-header-6 {
    background-color: var(--color-gray);
    padding: 3px 0px 4px 4px;
    border-bottom: none !important;
}



/* --- callouts --- */
.theme-notion.theme-light .callout {
    background-color: rgba(var(--callout-color), 0.1);
}

.theme-notion.theme-dark .callout {
    background-color: rgba(var(--callout-color), 0.2);
}

.theme-notion .callout-title-inner {
    margin-left: 1em;
}

/* - blockquotes - */
.theme-notion .markdown-rendered blockquote {
    border-color: var(--text-normal);
}

/* - checkboxes - */
.theme-notion input[type=checkbox]:not(:checked) {
    border: 1.7px solid var(--text-normal);
}
/* - lists - */
.theme-notion, .theme-anytype {
    --list-marker-color: var(--text-normal);
}

.theme-notion input[type=checkbox] {
border-radius: 0px;
}
.theme-notion.theme-light {
    color-scheme: light;
    --highlight-mix-blend-mode: darken;
    --mono-rgb-0: 255, 255, 255;
    --mono-rgb-100: 0, 0, 0;
    --color-base-00: #ffffff;
    --color-base-05: #f5f5f5;
    --color-base-10: #f0f0f0;
    --color-base-20: #f5f5f5;
    --color-base-25: #e1e1e1;
    --color-base-30: #cecece;
    --color-base-35: #c7c7c7;
    --color-base-40: #afafaf;
    --color-base-50: #989898;
    --color-base-60: #7b7b7b;
    --color-base-70: #5f5f5f;
    --color-base-100: #000000;
    --color-red-rgb: 212, 76, 71;
    --color-red: #D44C47;
    --color-green-rgb: 79, 131, 68;
    --color-green: #4f8344;
    --color-orange-rgb: 217, 115, 13;
    --color-orange: #D9730D;
    --color-yellow-rgb: 203, 145, 47;
    --color-yellow: #CB912F;
    --color-cyan-rgb: 88, 148, 138;
    --color-cyan: #58948a;
    --color-blue-rgb: 51, 126, 169;
    --color-blue: #337EA9;
    --color-purple-rgb: 144, 101, 176;
    --color-purple: #9065B0;
    --color-pink-rgb: 193, 76, 138;
    --color-pink:  #C14C8A;
    --color-gray-rgb: 245, 245, 245;
    --color-gray: #f2f2f2;
  }
  .theme-notion.theme-dark {
    color-scheme: dark;
    --background-modifier-border: #323130;
    --highlight-mix-blend-mode: lighten;
    --color-base-00: #191919;
    --color-base-10: #2d2d2d;
    --color-base-20: #202020;
    --color-base-25: #21201e;
    --color-base-30: #21201e;
    --color-base-35: #363636;
    --color-base-40: #535353;
    --color-base-50: #707070;
    --color-base-60: #5d5d5d;
    --color-base-70: #a0a0a0;
    --color-base-100: rgba(255, 255, 255, 0.81);
    --color-red-rgb: 212, 76, 71;
    --color-gray: #363636a3;
    --color-red: #D44C47;
    --color-green-rgb: 79, 131, 68;
    --color-green: #4f8344;
    --color-orange-rgb: 217, 115, 13;
    --color-orange: #D9730D;
    --color-yellow-rgb: 203, 145, 47;
    --color-yellow: #CB912F;
    --color-cyan-rgb: 88, 148, 138;
    --color-cyan: #58948a;
    --color-blue-rgb: 51, 126, 169;
    --color-blue: #337EA9;
    --color-purple-rgb: 144, 101, 176;
    --color-purple: #9065B0;
    --color-pink-rgb: 193, 76, 138;
    --color-pink:  #C14C8A;    
}




/* @settings

name: Chime Color Schemes
id: chime-colors
settings:
  -
    id: Color-thenes
    title: Color Scheme
    type: class-select
    default: theme-default
    options:
      -
        label:
        value: theme-default
      -
        label: Macaroon
        value: theme-macaroon
      -
        label: Ash
        value: theme-crystal
      -
        label: Ash (old)
        value: theme-ash-old
      -
        label: Anytype
        value: theme-anytype
      -
        label: Celestial
        value: theme-celestial
      -
        label: Chinchilla
        value: theme-chinchilla
      -
        label: Spring
        value: theme-spring
      -
        label: Novelist
        value: theme-novelist
      -
        label: Nord
        value: theme-nord
      -
        label: Notion
        value: theme-notion
      -
        label: Solarized
        value: theme-solarized
      -
        label: Gruvbox
        value: theme-gruvbox
      -
        label: Obsidian
        value: theme-classic
      -
        label: Light & Bright
        value: theme-light-and-bright
*/
```
