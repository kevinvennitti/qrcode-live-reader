# QR code audio live reader

1. Add MP3 sound files into the `sounds` folder
2. Name each file with a unique simplified name, like :
- `qrcode1.mp3`, `qrcode2.mp3`, `qrcode3.mp3`, etc.
- `my-item.mp3`, `my-other-item.mp3`, `another-item.mp3`, etc.
- or even `1.mp3`, `2.mp3`, `3.mp3`, etc.
3. Generate QR code images by using these names (without `.mp3`) as text strings for QR codes ([you can generate images here](https://www.nayuki.io/page/qr-code-generator-library))
4. Now, when you scan a QR code with the code `my-item`, it will play `my-item.mp3` audio ✨

### Features
- No code to edit! 
- Can scan classic (dark QR code on bright background) and inverted (bright QR code on dark background) QR codes (even both)
- When you scan another QR code, previous audio automatically stops and new audio plays
- If you scan non-related QR code, it ignores it
