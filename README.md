# MYS CODE

Windows va Linux uchun MYS CODE ilovasi.

## Yuklab olish

- **Windows 10/11 x64:** [MYS-CODE-Windows-1.0.2.zip](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/MYS-CODE-Windows-1.0.2.zip) · [SHA-256 tekshirish fayli](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/SHA256SUMS.txt) · [setup EXE](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/MYS-CODE-Setup-1.0.2.exe).
- **Linux x64 AppImage:** [MYS-CODE-1.0.1-linux-x64.AppImage](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.1/MYS-CODE-1.0.1-linux-x64.AppImage).
- **Debian/Ubuntu x64:** [MYS-CODE-1.0.1-linux-x64.deb](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.1/MYS-CODE-1.0.1-linux-x64.deb).

## Windows ZIP va SHA-256

1. [MYS-CODE-Windows-1.0.2.zip](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/MYS-CODE-Windows-1.0.2.zip) va [SHA256SUMS.txt](https://github.com/MYS707team/MYS_CODE/releases/download/v1.0.2/SHA256SUMS.txt) fayllarini yuklab oling.
2. PowerShell’da ZIP saqlangan papkada `Get-FileHash .\MYS-CODE-Windows-1.0.2.zip -Algorithm SHA256` ni ishga tushiring. Natijani `SHA256SUMS.txt` dagi ZIP qatori bilan solishtiring.
3. ZIP uchun **Extract all** ni tanlang. Ichida setup EXE va uning `.sha256` tekshirish fayli bor.
4. EXE uchun `Get-FileHash .\MYS-CODE-Setup-1.0.2.exe -Algorithm SHA256` natijasini shu tekshirish fayli bilan solishtiring. Hash mos kelmasa, installerni ishga tushirmang.
5. Hash mos bo‘lsa, `MYS-CODE-Setup-1.0.2.exe` ni ochib o‘rnatishni tugating.

SHA-256 yuklangan faylning o‘zgarmaganini tekshiradi; har yangi reliz uchun boshqa qiymat hisoblanadi. Joriy installer raqamli imzolanmagan. ZIP yoki SHA-256 SmartScreen ogohlantirishini avtomatik olib tashlamaydi.

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
