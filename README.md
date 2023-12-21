# Chrome Focus Mode

Created following the tutorial: <https://developer.chrome.com/docs/extensions/get-started/tutorial/scripts-activetab>

## Icon Generation

Using ImageMagick (installed by `sudo apt install imagemagick`)

```sh
mkdir -pv images/
convert -size 16x16 -background white -fill blue -pointsize 12 -gravity center label:FM images/icon16.png
convert -size 32x32 -background white -fill blue -pointsize 24 -gravity center label:FM images/icon32.png
convert -size 48x48 -background white -fill blue -pointsize 36 -gravity center label:FM images/icon48.png
convert -size 128x128 -background white -fill blue -pointsize 96 -gravity center label:FM images/icon128.png
```
