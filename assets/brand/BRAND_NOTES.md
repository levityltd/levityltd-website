# Levity Brand Notes

Source guide: `assets/brand/guide/levity-brand-guide.heic`

## Fonts

- Body copy: Nunito
- Body copy bold: Nunito Bold
- Headlines: Nunito Bold
- Accent: Satisfy

Original guide mapping:

- Body copy: Nourd
- Body copy bold: Nourd Bold
- Headlines: Canva Student, Nourd Bold
- Accent: Buffalo, Canva Student

## Website Font Substitutes

- Nunito substitutes for Nourd, Nourd Bold, and Canva Student headline use.
- Satisfy substitutes for Buffalo and Canva Student accent use.
- Both substitutes are available from Google Fonts and are appropriate for website embedding.

```css
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Satisfy&display=swap");

:root {
  --font-body: "Nunito", system-ui, sans-serif;
  --font-headline: "Nunito", system-ui, sans-serif;
  --font-accent: "Satisfy", cursive;
}
```

## Font Availability Notes

- No font files for Nourd, Canva Student, or Buffalo are currently present in this repository.
- No matching installed font files were found in the standard local macOS font folders checked during setup.
- Nourd appears to be available as a licensed commercial webfont, but it is not a free system or Google font. Use it on the website only after adding a proper webfont license/files.
- Canva Student appears to be a Canva-hosted design font, not a reliably available website font. Treat it as unavailable for live website text unless licensed webfont files are supplied.
- Buffalo appears to be distributed publicly as personal-use font files. Treat it as unavailable for commercial website text unless a commercial/web license is supplied.

## Colors

```css
:root {
  --levity-lilac: #b2a3ed;
  --levity-eggplant: #564f74;
  --levity-limelight: #c1ff72;
  --levity-black: #000000;
  --levity-fog: #d6d4d8;
  --levity-cloud: #fbfaf0;
}
```

Note: the guide label for limelight visually reads as `#c1ff72`; `#clff72` would not be valid CSS because `l` is not a hexadecimal character.
