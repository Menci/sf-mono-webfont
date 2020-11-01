# SF Mono Webfont

Downloaded from [Apple Fonts](https://developer.apple.com/fonts/).

Generated with [Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator).

# Build

After building with [Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator), run this command to correct `font-family` in the generated CSS file.

```bash
sed -i "s/'sf_mono'/'SF Mono'/g" stylesheet.css
```
