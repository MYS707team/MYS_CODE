# MYS CODE

Windows va Linux uchun MYS CODE ilovasi.

## Yuklab olish

- **Windows 10/11 x64:** [MYS-CODE-Setup-1.0.2.exe](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/MYS-CODE-Setup-1.0.2.exe).
- **Linux x64 AppImage:** [MYS-CODE-1.0.1-linux-x64.AppImage](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.1/MYS-CODE-1.0.1-linux-x64.AppImage).
- **Debian/Ubuntu x64:** [MYS-CODE-1.0.1-linux-x64.deb](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.1/MYS-CODE-1.0.1-linux-x64.deb).

## O‘rnatish

Windows’da setup EXE faylini ochib, o‘rnatishni tugating. Microsoft Edge WebView2
Runtime kerak. Avvalgi ilova ishlayotgan bo‘lsa, tray menyusidagi **Quit and stop sessions** bilan to‘liq yoping. Setup mavjud o‘rnatmani yangilaydi; sozlamalar va sessiyalar saqlanadi. Ilovani oching va hisobingizga kiring.

Linux AppImage uchun yuklangan fayl joylashgan papkada:

```sh
chmod +x MYS-CODE-1.0.1-linux-x64.AppImage
./MYS-CODE-1.0.1-linux-x64.AppImage
```

AppImage uchun FUSE mavjud bo‘lmasa:

```sh
APPIMAGE_EXTRACT_AND_RUN=1 ./MYS-CODE-1.0.1-linux-x64.AppImage
```

Debian/Ubuntu uchun yuklangan fayl joylashgan papkada:

```sh
sudo apt install ./MYS-CODE-1.0.1-linux-x64.deb
```

Ilovani ilovalar menyusidan yoki `mys-code` buyrug‘i bilan oching.

Python, mahalliy xizmat, brauzer extensioni va skills installer ichida.
Alohida source ZIP yoki Python yuklab olish kerak emas.

## Brauzer extensionini ulash

1. Ilovada **Settings → Browser extension → Open extension folder** ni oching.
2. Chrome’da `chrome://extensions`, Windows Edge’da `edge://extensions` sahifasini oching.
3. **Developer mode** ni yoqing, **Load unpacked** ni bosing va ochilgan extension
   papkasini tanlang. Desktop’da extension ID’ni tasdiqlang va AI sahifasini yangilang.

Yangilanishdan so‘ng brauzer extensionini **Reload** qiling va AI sahifalarini
yangilang. Linux yangilanishini shu relizdagi yangi installer orqali o‘rnating.

macOS uchun installer hozir mavjud emas.

Windows 1.0.2 o‘rnatilgach, yangi versiya uchun yuqori o‘ngdagi **Update** yoki
**Settings → Updates → Install update** ni bosing. **Auto update** yoqilganida
ilova trayda va AI chatlar ulanmagan bo‘lsa, bo‘sh sessiyalar avtomatik
to‘xtatiladi va yangilanish o‘rnatiladi.
