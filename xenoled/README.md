# پکیج سئو و محتوای ۶ ماهه — زنولد

برنامه کامل سئو، محتوا و مقالات برای [xenoled.lighting](https://xenoled.lighting/)

---

## شروع سریع

1. **برنامه کلی** → [`6-MONTH-MASTER-PLAN.md`](6-MONTH-MASTER-PLAN.md)
2. **تقویم هفته‌ای** → [`content-calendar/month-01.md`](content-calendar/month-01.md)
3. **اولین مقاله** → [`articles/01-cheragh-khati-led.md`](articles/01-cheragh-khati-led.md)
4. **About Us** → [`page-copy/about-us.md`](page-copy/about-us.md)

---

## ساختار پوشه

```
xenoled/
├── README.md                    ← این فایل
├── 6-MONTH-MASTER-PLAN.md       ← نقشه راه مصور ۶ ماه
├── SEO-AUDIT-AND-STRATEGY.md    ← ممیزی اولیه سایت
├── KPI-REPORT-TEMPLATE.md       ← قالب گزارش پایان ۶ ماه
│
├── content-calendar/            ← تقویم ماهانه (۶ فایل)
│   ├── month-01.md … month-06.md
│
├── articles/                    ← ۳۷ مقاله کامل آماده انتشار
│   ├── 01-cheragh-khati-led.md
│   ├── 02-magnetic-vs-track.md
│   └── … (تا 37-false-ceiling.md)
│
├── landing-pages/               ← ۴ صفحه لندینگ
│   ├── retail-store.md
│   ├── restaurant.md
│   ├── free-consultation.md
│   └── lux-calculator.md
│
└── page-copy/                   ← متن صفحات سایت
    ├── about-us.md
    ├── homepage-meta.md
    └── category-descriptions.md
```

---

## فهرست ۳۷ مقاله

| # | فایل | عنوان | هفته |
|---|------|-------|------|
| 01 | `01-cheragh-khati-led.md` | چراغ خطی LED چیست؟ | ۲ |
| 02 | `02-magnetic-vs-track.md` | تفاوت مگنتی و ریلی | ۲ |
| 03 | `03-downlight-guide.md` | راهنمای چراغ سقفی | ۳ |
| 04 | `04-store-lighting.md` | نورپردازی فروشگاه | ۳ |
| 05 | `05-flexible-light.md` | چراغ فلکسیبل LED | ۴ |
| 06 | `06-invisible-frame.md` | فریم گچی نامرئی | ۴ |
| 07 | `07-magnetic-installation.md` | نصب چراغ مگنتی | ۵ |
| 08 | `08-48v-magnetic.md` | ولتاژ ۴۸ ولت | ۵ |
| 09 | `09-color-temperature.md` | دمای رنگ نور | ۶ |
| 10 | `10-cri-guide.md` | CRI و Ra | ۶ |
| 11 | `11-belt-light.md` | چراغ کمربندی | ۷ |
| 12 | `12-ultra-slim.md` | چراغ اسلیم اولترا | ۷ |
| 13 | `13-kitchen-mistakes.md` | اشتباهات آشپزخانه | ۸ |
| 14 | `14-gallery-lighting.md` | نورپردازی گالری | ۸ |
| 15 | `15-restaurant-lighting.md` | نورپردازی رستوران | ۹ |
| 16 | `16-hotel-lighting.md` | نورپردازی هتل | ۱۰ |
| 17 | `17-lux-calculation.md` | محاسبات Lux | ۱۰ |
| 18 | `18-case-study-retail.md` | Case Study فروشگاه | ۱۱ |
| 19 | `19-brand-comparison.md` | مقایسه برندها | ۱۲ |
| 20 | `20-warranty-guide.md` | گارانتی LED | ۱۲ |
| 21 | `21-isiri-standard.md` | استاندارد ISIRI | ۱۳ |
| 22 | `22-ip-rating.md` | IP Rating | ۱۳ |
| 23 | `23-dimming-dali.md` | Dimming و DALI | ۱۴ |
| 24 | `24-facade-lighting.md` | نورپردازی نما | ۱۴ |
| 25 | `25-moisture-proof.md` | چراغ ضد رطوبت | ۱۵ |
| 26 | `26-magnetic-wiring.md` | برق‌کشی مگنتی | ۱۵ |
| 27 | `27-smart-lighting.md` | نورپردازی هوشمند | ۱۶ |
| 28 | `28-case-study-office.md` | Case Study دفتر کار | ۱۶ |
| 29 | `29-tehran-local.md` | نورپردازی تهران | ۱۷ |
| 30 | `30-track-light-guide.md` | چراغ ریلی | ۱۸ |
| 31 | `31-decorative-light.md` | چراغ دکوراتیو | ۱۸ |
| 32 | `32-bedroom-lighting.md` | نورپردازی اتاق خواب | ۱۹ |
| 33 | `33-case-study-villa.md` | Case Study ویلا | ۱۹ |
| 34 | `34-ugr-glare.md` | UGR و خیرگی | ۲۰ |
| 35 | `35-linear-recessed-vs-surface.md` | خطی توکار vs روکار | ۲۱ |
| 36 | `36-clinic-lighting.md` | نورپردازی کلینیک | ۲۲ |
| 37 | `37-false-ceiling.md` | سقف کاذب | ۲۳ |

---

## نحوه انتشار در WordPress

هر فایل مقاله شامل:
- `title` — عنوان سئو
- `meta_description` — توضیحات متا
- `slug` — آدرس URL پیشنهادی
- `focus_keyword` — کلیدواژه اصلی
- متن کامل + FAQ + CTA

**مراحل:**
1. فایل `.md` را باز کنید
2. در WordPress → نوشته‌ها → افزودن
3. Title و Meta را در Yoast وارد کنید
4. تصویر شاخص ۱۲۰۰×۶۳۰ اضافه کنید
5. ۳ لینک داخلی به دسته محصول
6. منتشر کنید و در GSC بررسی ایندکس کنید

---

## آمار پکیج

| مورد | تعداد |
|------|-------|
| مقالات کامل | ۳۷ |
| لندینگ | ۴ |
| متن صفحات | ۳ |
| تقویم ماهانه | ۶ |
| کل کلمات (تقریبی) | ۵۰,۰۰۰+ |

---

*زنولد — xenoled.lighting — ۰۲۱-۸۸۷۱۶۳۷۵*
