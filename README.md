# راستا | Rasta

**هر متن، در جای درست خودش.**  
**Right-align only what you choose.**

راستا افزونه‌ای برای راست‌چین کردن بخش‌های دلخواه وب‌سایت‌ها و گفتگوهای هوش مصنوعی است.  
Rasta is a Chrome extension for right-aligning selected parts of websites and AI chats.

[دانلود افزونه / Download extension](./rasta-chrome-extension.zip) · [راهنمای فارسی](#راهنمای-فارسی) · [English guide](#english-guide)

---

## راهنمای فارسی

### راستا چه کاری انجام می‌دهد؟

اگر متن فارسی در یک سایت یا چت هوش مصنوعی چپ‌چین نمایش داده شود، با راستا می‌توانید **فقط بخش موردنظر** را با موس انتخاب و راست‌چین کنید. افزونه متن اصلی را بازنویسی نمی‌کند و کل صفحه را تغییر نمی‌دهد.

### امکانات

- انتخاب بخش با حرکت موس و کلیک
- انتخاب بلوک بزرگ‌تر با نگه‌داشتن `Alt`
- کلیک دوباره برای بازگردانی بخش راست‌چین‌شده
- واگرد آخرین تغییر و بازگردانی همهٔ تغییرهای صفحه
- رابط فارسی و انگلیسی
- تم روشن و تیره برای پاپ‌آپ

### نصب در Chrome

> **مهم:** این مخزن فایل ZIP افزونه را دارد. باید آن را استخراج کنید؛ فایل ZIP را مستقیماً با **Load unpacked** انتخاب نکنید.

1. [فایل افزونه را دانلود کنید](./rasta-chrome-extension.zip).
2. فایل ZIP را استخراج کنید.
3. در Chrome به `chrome://extensions` بروید و **Developer mode** را روشن کنید.
4. روی **Load unpacked** بزنید.
5. پوشهٔ `rastechin` را انتخاب کنید؛ پوشه‌ای که فایل `manifest.json` داخل آن است.
6. صفحه‌هایی را که از قبل باز بوده‌اند، یک‌بار بازخوانی کنید.

### روش استفاده

1. در یک وب‌سایت معمولی، روی آیکون راستا بزنید و **شروع انتخاب متن** را انتخاب کنید.
2. موس را روی متن ببرید تا محدودهٔ انتخاب مشخص شود؛ سپس کلیک کنید.
3. برای انتخاب بخش بزرگ‌تر، `Alt` را نگه دارید.
4. برای برگرداندن یک تغییر، دوباره روی همان بخش کلیک کنید یا **واگرد آخرین تغییر** را بزنید.
5. برای حذف همهٔ تغییرهای صفحه، از **بازگردانی همهٔ بخش‌های این صفحه** استفاده کنید.
6. برای خروج از حالت انتخاب، `Esc` یا دکمهٔ **پایان** را بزنید.

برای تغییر زبان، از دکمهٔ **English / فارسی** بالای پاپ‌آپ استفاده کنید. دکمهٔ تم نیز میان حالت روشن و تیره جابه‌جا می‌شود.

### میانبرها

| عملکرد | میانبر |
| --- | --- |
| روشن یا خاموش کردن انتخابگر | `Alt + Shift + R` |
| واگرد آخرین تغییر | `Alt + Shift + Z` |
| خروج از حالت انتخاب | `Esc` |

می‌توانید میانبرهای افزونه را در `chrome://extensions/shortcuts` تغییر دهید.

### نکات مهم

- راست‌چین‌های اعمال‌شده با **بازخوانی صفحه پاک می‌شوند**؛ اما انتخاب زبان و تم ذخیره می‌شود.
- افزونه در صفحات داخلی Chrome، فروشگاه افزونه‌ها و برخی صفحات محافظت‌شده اجرا نمی‌شود.
- نتیجهٔ نمایش متن‌های ترکیبی فارسی و انگلیسی ممکن است به ساختار و CSS سایت بستگی داشته باشد.
- اگر حتی دکمه‌های پاپ‌آپ کار نمی‌کنند، در `chrome://extensions` بخش **Errors** افزونه را بررسی کنید.

---

## English guide

### What is Rasta?

Rasta lets you use your mouse to **right-align a specific section** of a website or AI chat. It does not rewrite the original text or align the entire page.

### Features

- Hover and click to select a section
- Hold `Alt` to target a larger block
- Click an aligned section again to restore it
- Undo the last change or reset all changes on the current page
- Persian and English interface
- Light and dark popup themes

### Install in Chrome

> **Important:** Extract the extension ZIP first. Do not select the ZIP itself with **Load unpacked**.

1. [Download the extension ZIP](./rasta-chrome-extension.zip) and extract it.
2. Open `chrome://extensions` and enable **Developer mode**.
3. Click **Load unpacked**.
4. Select the `rastechin` folder containing `manifest.json`.
5. Reload any tabs that were already open.

### How to use

1. On a regular website, open the Rasta popup and click **Start selecting text**.
2. Hover over a passage to preview the target, then click to right-align it.
3. Hold `Alt` to target a larger block.
4. Click an aligned section again to restore it, or use **Undo last change**.
5. Use **Reset all sections on this page** to remove the page's changes.
6. Press `Esc` or click **Finish** to exit selection mode.

Switch between **English / فارسی** at the top of the popup. The theme button switches between light and dark modes.

### Shortcuts

| Action | Shortcut |
| --- | --- |
| Toggle the picker | `Alt + Shift + R` |
| Undo last change | `Alt + Shift + Z` |
| Exit selection mode | `Esc` |

You can customize extension shortcuts at `chrome://extensions/shortcuts`.

### Notes

- Alignment changes disappear when the page is reloaded. Language and theme preferences are saved.
- Chrome internal pages, the Chrome Web Store, and some protected pages do not allow the extension to run.
- Mixed-language rendering can depend on a website's HTML and CSS.
- If even the popup buttons do not respond, check the extension's **Errors** at `chrome://extensions`.

---

## سازنده | Creator

**سید امیر رضا محمدزاده**

- Telegram: [ITZeta](https://t.me/ITZeta) · [Mohammadzadeh_ads](https://t.me/Mohammadzadeh_ads)
- YouTube: [IT_Zeta](https://www.youtube.com/@IT_Zeta)
