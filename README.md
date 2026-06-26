# 🎨 Carousel Studio Pro

**مولّد كاروسيل احترافي بالذكاء الاصطناعي — مخصص لصانعي محتوى التصميم الجرافيكي**

A powerful single-file web app for generating Instagram & LinkedIn carousels using the Gemini AI API, with 6 professional design styles and multi-format export.

---

## ✨ المميزات / Features

- **6 ستايلات تصميم احترافية:**
  - 🤍 التقني الأبيض (Blueprint Grid + Lime Neon)
  - 🖤 المظلم الفاخر (Dark Premium + Purple Neon)
  - 🍂 المودرن البسيط (Warm Cream + Burnt Orange)
  - ⬛ البروتاليست (Brutalist Bold — Black & White)
  - 🔷 الزجاجي المضيء (Glassmorphism + Sky Blue)
  - 💜 الغرادينت الفاخر (Luxury Gradient — Purple/Pink)

- **5 أحجام للتصدير:**
  | النوع | الحجم | الاستخدام |
  |-------|-------|-----------|
  | كاروسيل عمودي | 1080 × 1350 | Instagram Carousel |
  | كاروسيل طويل | 1080 × 1440 | Tall Portrait |
  | مربع | 1080 × 1080 | Square Post |
  | مصغّر طولي | 1080 × 1920 | Story / TikTok Thumbnail (9:16) |
  | مصغّر عرضي | 1920 × 1080 | YouTube Thumbnail (16:9) |

- **دعم كامل للعربية RTL** مع خطوط Tajawal, Cairo, Almarai
- **توليد المحتوى** بـ Gemini 2.5 Flash API
- **تحكم كامل** في الخط، الحجم، المسافات، عدد السلايدات (4-7)
- **تصدير PNG** بجودة 1:1 عبر html2canvas
- **معاينة فورية** بشاشة كاملة مع تنقل بالأسهم

---

## 🚀 الاستخدام / Usage

### الطريقة البسيطة (بدون سيرفر)
```bash
# فتح مباشر في المتصفح
open index.html
```

### مع Live Server (VS Code)
```bash
# تثبيت extension: Live Server
# Click: Right click → Open with Live Server
```

### Deployment على GitHub Pages
```bash
git init
git add index.html README.md
git commit -m "Initial commit: Carousel Studio Pro"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/carousel-studio.git
git push -u origin main
# Then: Settings → Pages → Deploy from main branch
```

---

## 🔑 إعداد مفتاح Gemini API

1. اذهب إلى [Google AI Studio](https://aistudio.google.com/app/apikey)
2. أنشئ مفتاح API جديد
3. الصقه في خانة **"مفتاح API"** في التطبيق

> **ملاحظة:** مفتاح API لا يُحفظ في أي مكان — يبقى فقط في جلسة المتصفح الحالية.

---

## 📁 هيكل المشروع / Structure

```
carousel-studio/
├── index.html      ← التطبيق الكامل (ملف واحد فقط)
└── README.md       ← هذا الملف
```

التطبيق كله في ملف HTML واحد — CSS, JavaScript, والقوالب كلها مدمجة. لا يحتاج أي تثبيت أو build process.

---

## 🎨 أمثلة على المواضيع

```
أخطاء قاتلة في تصميم الشعارات
كيف تختار الألوان لهوية بصرية متكاملة
قواعد التايبوغرافي التي يتجاهلها المبتدؤون
نصائح لبناء بورتفوليو التصميم الخاص بك
الفرق بين UI وUX للمبتدئين
كيف تحدد سعر خدمات التصميم الخاصة بك
```

---

## 🛠 التقنيات المستخدمة

| التقنية | الاستخدام |
|---------|-----------|
| Vanilla JS | منطق التطبيق والـ State Management |
| CSS Custom Properties | نظام الثيمات المتعدد |
| Google Fonts | Tajawal, Cairo, Almarai, Space Grotesk |
| Gemini 2.5 Flash API | توليد المحتوى بالذكاء الاصطناعي |
| html2canvas 1.4.1 | تصدير السلايدات كصور PNG |

---

## 📜 الترخيص / License

MIT License — يمكن استخدامه وتعديله بحرية.

---

**صُنع بـ ❤️ لمجتمع المصممين العرب**
