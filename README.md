# qrcode-live-reader

1. Add MP3 sound files into the `sounds` folder
2. Name each file with a unique simplified name, like :
- `qrcode1.mp3`, `qrcode2.mp3`, `qrcode3.mp3`, etc.
- `my-item.mp3`, `my-other-item.mp3`, `another-item.mp3`, etc.
- or even `1.mp3`, `2.mp3`, `3.mp3`, etc.
3. Generate QR code images by using these names (without `.mp3`) as text strings for QR codes ([https://www.nayuki.io/page/qr-code-generator-library](you can generate images here))
- QR code `my-item` will trigger `my-item.mp3` when scanned, etc.