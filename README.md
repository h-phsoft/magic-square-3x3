# تعمير الوفق المثلث (3×3) / Magic Triangle Square Generator

[![GitHub](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

> أداة ويب لإنشاء "الوفق المثلث" 3×3 وفق خوارزمية مخصصة — مع دعم جبر الكسر والمفتاح والمغلاق والوسط.  
> A web tool to generate a custom 3×3 Magic Triangle Square — with Fraction Fix, Key, Lock, and Center support.

تم تطوير هذا المشروع بواسطة [h-phsoft](https://github.com/h-phsoft).

---

## 🌐 العرض التجريبي المباشر / Live Demo

جرب الأداة مباشرة على:  
👉 **[https://h-phsoft.github.io/magic-square-3x3/](https://h-phsoft.github.io/magic-square-3x3/)**


---

## 🧩 الميزات / Features

### بالعربية:
- إدخال رقم واحد (≥15) لتوليد الوفق كاملًا.
- خوارزمية مبنية على:  
  `المفتاح = ⌊(الرقم - 12) ÷ 3⌋`  
  ثم زيادة تدريجية بـ 1 في كل خانة.
- خانة **"جبر الكسر"**: تقع حيث كان الرقم `7` في الوفق الأساسي — تُضاف إليها `1 + باقي القسمة` إن وُجد.
- تمييز بصري:  
  - 🔑 **المفتاح** — الخانة التي كان فيها الرقم 1 (الوسط السفلي).  
  - 🔒 **المغلاق** — الخانة التي كان فيها الرقم 9 (الوسط العلوي).  
  - 🎯 **الوسط** — الخانة المركزية (الرقم 5).  
  - 🟣 **جبر الكسر** — تُلون إن وُجد باقي.
- دعم الضغط على `Enter` للرسم السريع.
- واجهة متجاوبة — تعمل على الجوال والحاسوب.
- لا تحتاج خادم — صفحة HTML واحدة!

### In English:
- Enter a single number (≥15) to generate the full magic square.
- Algorithm:  
  `Key = floor((Number - 12) / 3)`  
  Then increment by 1 for each subsequent cell.
- **Fraction Fix Cell**: Located where `7` was in the base square — adds `1 + remainder` if exists.
- Visual Highlights:  
  - 🔑 **Key** — Cell that held `1` (bottom center).  
  - 🔒 **Lock (Ghalaq)** — Cell that held `9` (top center).  
  - 🎯 **Center** — Middle cell (`5`).  
  - 🟣 **Fraction Fix** — Highlighted if remainder > 0.
- Press `Enter` to generate quickly.
- Fully responsive — works on mobile & desktop.
- Zero dependencies — single HTML file!

---

## 🚀 كيفية الاستخدام / How to Use

1. افتح الملف `index.html` في متصفحك مباشرة.  
   *(لا حاجة لخادم — يعمل فورًا)*

2. أدخل رقماً (≥12) في الحقل.  
   مثال: `15` → يولد الوفق الأساسي.

3. اضغط على "أنشئ الوفق" أو `Enter`.

4. شاهد النتيجة مع تمييز الخانات الخاصة.

---

## 🛠️ كيفية الرفع على GitHub Pages / Deployment

اتبع هذه الخطوات البسيطة:

### الخطوة 1: استنساخ المستودع (إذا لم تكن قد فعلت)

git clone https://github.com/h-phsoft/magic-square-3x3.git
cd magic-square-3x3

---

## 📜 الترخيص / License

هذا المشروع مرخص تحت رخصة **MIT** — مفتوح المصدر للاستخدام الشخصي والتجاري.  
✅ يمكنك: الاستخدام، التعديل، التوزيع — حتى تجاريًا — مع الإبقاء على حقوق الملكية.

This project is licensed under the **MIT License** — free to use, modify, and distribute — even commercially — as long as you preserve the copyright notice.

📄 [عرض نص الرخصة الكاملة](LICENSE)

---

## 🤝 المساهمة / Contributing

نرحب بالمساهمات! ❤️  
سواء كنت مطورًا، مصممًا، أو محررًا — مشاركتك تهمنا.

### كيف تساهم؟

1. 🐛 **أبلغ عن خطأ**: افتح [Issue جديد](https://github.com/h-phsoft/magic-square-3x3/issues/new?template=bug_report.md)  
2. 💡 **اقتراح ميزة**: افتح [Issue جديد](https://github.com/h-phsoft/magic-square-3x3/issues/new?template=feature_request.md)  


---

## 📬 التواصل / Contact

لأي استفسار أو اقتراح — نحن هنا لمساعدتك:

📧 **البريد الإلكتروني**: [h.phsoft@gmail.com](mailto:h.phsoft@gmail.com)  
🐙 **GitHub**: [@h-phsoft](https://github.com/h-phsoft)  
🌍 **المشروع الحي**: [h-phsoft.github.io/magic-square-3x3](https://h-phsoft.github.io/magic-square-3x3/)

> "الوفق علم قديم — نعيد إحيائه بتقنية حديثة."  
> "The Magic Square is ancient wisdom — revived with modern tech."

---

## 📜 سياسة الاستخدام / Usage Policy

هذا المشروع مخصص **للأغراض التعليمية، البحثية، والبرمجية فقط**.  
❌ **ممنوع تمامًا** استخدامه لأي غرض:

- مخالف للقوانين المحلية أو الدولية.
- يُشجع على الكراهية، التمييز، أو ازدراء الأديان.
- تجاري دون إذن مسبق من المؤلف.
- ضار أو مسيء بأي شكل.

استخدامك لهذا المشروع يعني موافقتك على هذه الشروط.

---

This project is intended **for educational, research, and programming purposes only**.  
❌ **Strictly prohibited** to use it for any purpose that:

- Violates local or international laws.
- Promotes hate, discrimination, or religious disrespect.
- Commercial use without prior written permission.
- Harmful or abusive in any form.

Your use of this project implies acceptance of these terms.
