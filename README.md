# Love Jar — NFC Mini Experience

پروژه‌ی تعاملی شیشه عشق، ساخته‌شده برای اجرای مستقیم روی GitHub Pages.

## ساختار

- `index.html` — Stage 1 / صفحه‌ی ورود
- `stage2.html` — Stage 2 / عنکبوت و سؤال
- `stage3.html` — Stage 3 / سؤال مخفی و کشف «فاطمه»
- `stage4.html` — Stage 4 / بطری، باران قلب‌ها و گوشی
- `stage5.html` — Stage 5 / پیام نهایی و فایل صوتی
- `voice.mp3` — فایل صدای محمدحسین (باید خودت اضافه کنی)

## مسیر تجربه

`index.html → stage2.html → stage3.html → stage4.html → stage5.html`

NFC باید به آدرس GitHub Pages پروژه، یعنی صفحه‌ی `index.html`، اشاره کند.

### فایل صوتی
فایل صوتی را دقیقاً با نام `voice.mp3` در ریشه‌ی پروژه قرار بده؛ کنار `stage5.html`.

## GitHub Pages

در GitHub از Settings → Pages، گزینه‌ی Deploy from a branch را انتخاب کن و branch اصلی و پوشه‌ی `/ (root)` را منتشر کن.
