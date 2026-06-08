# مُنجز — نظام التخطيط الشخصي

<div align="center">

![مُنجز](https://img.shields.io/badge/مُنجز-نظام_التخطيط_الشخصي-8b5cf6?style=for-the-badge&labelColor=1f2937)
![HTML](https://img.shields.io/badge/HTML-Single_File-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Hardcoded_Dark_Theme-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla_ES6+-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-Ready-5a0fc8?style=flat-square&logo=pwa&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-34d399?style=flat-square)

**نظام تخطيط شخصي متكامل — ملف HTML واحد — يعمل بدون إنترنت**

[المميزات](#-المميزات) • [لقطات الشاشة](#-لقطات-الشاشة) • [التثبيت](#-التثبيت) • [الاستخدام](#-الاستخدام) • [البنية التقنية](#-البنية-التقنية)

</div>

---

## 🎯 نبذة

**مُنجز** هو نظام تخطيط شخصي مبني بالكامل في ملف HTML واحد (~436KB)، مستوحى من فلسفة GTD وأدوات مثل Notion وTodoist. يعمل محلياً بدون أي سيرفر أو اتصال بالإنترنت، ويدعم اللغة العربية بالكامل مع واجهة RTL أصيلة.

```
لا سيرفر  •  لا قاعدة بيانات  •  لا اشتراك  •  بياناتك عندك فقط
```

---

## ✨ المميزات

### 🗂️ إدارة المشاريع
- **مساحات العمل** — نظّم مشاريعك في workspaces منفصلة مع أيقونات وألوان
- **جدول المشاريع الشجري** — عرض هرمي: مساحة العمل ← المشروع ← المهام
- **3 طرق عرض للمهام** — قائمة جدول / Kanban / Time Boxing
- **Kanban Board** — drag & drop مع إدارة columns مخصصة

### ✅ إدارة المهام
- **Brain Dump** — صندوق أفكار سريع مع تحويل للمهام
- **Detail Panel** — تفاصيل كاملة: أولوية، أهمية، موعد، subtasks، milestones
- **حقل الأهمية** — مهم / أقل أهمية (لمصفوفة أيزنهاور)
- **Breadcrumbs** — مسار التنقل: مساحة العمل ← المشروع ← المهمة
- **المهام المتكررة** — يومي / أسبوعي / شهري / مخصص

### 🧠 أدوات التحليل
- **مصفوفة أيزنهاور** — تصنيف تلقائي بناءً على الإلحاح + الأهمية
- **علاقات المهام** — blocks / related / duplicate / depends مع رسم بياني
- **Dashboard** — KPIs، تقدم المشاريع، المواعيد القادمة، إحصائيات

### 📚 المعرفة والتعلم
- **مصادر التعلم** — روابط، كتب، فيديوهات، كورسات
- **Notebook متعدد النوتس** — لكل مصدر دفتر ملاحظات كامل
- **Rich Text Editor** — Bold، Headers، Lists، Code، Images، Links
- **المذكرة الشخصية** — تدوينات يومية مع ربط بالمهام

### 📊 Dashboard
- KPI Cards — مهام / مكتملة / متأخرة / مصادر
- تقدم كل مشروع مع progress bar
- المهام العاجلة والمرتفعة الأولوية
- المواعيد القادمة خلال 14 يوم
- المراجعة الأسبوعية

### 🎨 التخصيص
- **6 ألوان accent** — بنفسجي، أخضر، برتقالي، أزرق، وردي، ذهبي
- **4 خلفيات** — من الداكن جداً إلى الرمادي الفحمي
- **4 أحجام خط** — 13 / 15 / 16 / 18 px
- **Cover + Icon لكل عنصر** — Emoji، رابط صورة، أو رفع ملف
- الإعدادات تُحفظ في localStorage

### 💾 البيانات
- **Auto-save** — حفظ تلقائي في localStorage كل دقيقة
- **تصدير JSON** — نسخة احتياطية كاملة (مشاريع + مذكرة + مصادر + علاقات)
- **تصدير Excel** — sheet لكل مشروع + المذكرة + المصادر
- **استيراد JSON** — مع خيار دمج أو استبدال
- **استيراد Excel** — مهام من ملفات xlsx

### 📱 الجوال
- **PWA Ready** — قابل للتثبيت على الموبايل
- **Responsive** — يعمل على الموبايل والتابلت
- **Sidebar** — يتحول لـ slide-in drawer على الموبايل
- **Bottom Sheet** — modals تطلع من الأسفل على الموبايل

---

## 🚀 التثبيت

### الطريقة الأسهل — فتح مباشر
```bash
# نزّل الملف وافتحه في أي متصفح
open منجز.html
```

### للتطوير — تشغيل من سيرفر محلي (مُوصى به)
```bash
# Python
python -m http.server 8080
# ثم افتح: http://localhost:8080/منجز.html

# Node.js
npx serve .
# ثم افتح: http://localhost:3000/منجز.html

# VS Code
# ثبّت extension: Live Server → كليك يمين على الملف → Open with Live Server
```

> **ملاحظة:** التشغيل من `file://` يعمل بشكل كامل ما عدا بعض محدودية PWA و fetch requests. استخدم سيرفر محلي للتجربة الكاملة.

---

## 📖 الاستخدام

### أول تشغيل
1. افتح `منجز.html` في المتصفح
2. ستجد 3 مشاريع تجريبية جاهزة للاستكشاف
3. اضغط **المظهر** في أسفل السايدبار لتخصيص الألوان والخط

### إنشاء مساحة عمل ومشروع
```
السايدبار → + (بجانب مساحات العمل) → أدخل الاسم والأيقونة → حفظ
السايدبار → مشروع جديد → اختر مساحة العمل → حفظ
```

### إضافة مهام
```
Brain Dump → اكتب أفكارك → حوّلها لمهام
أو: افتح مشروع → + إضافة مهمة جديدة
```

### استيراد بيانات
```
نسخ احتياطي → استيراد JSON → اختر ملف .json
```

---

## 🏗️ البنية التقنية

```
منجز.html (436 KB)
├── <style>          — CSS كامل بدون CSS Variables (لضمان التوافق)
├── <body>
│   ├── #sidebar     — Navigation + Workspaces
│   ├── #main
│   │   ├── #topbar  — Search + Breadcrumb
│   │   └── #content — Views (dump/projects/dashboard/...)
│   └── Modals       — Task/Project/Workspace/Relations/Recurring
└── <script>         — ~2500 سطر JavaScript vanilla
```

### القرارات التقنية

| القرار | السبب |
|--------|-------|
| ملف واحد | سهولة النقل والمشاركة، لا dependencies |
| بدون CSS Variables | توافق Android Chrome من `content://` |
| localStorage | استمرارية البيانات بدون سيرفر |
| Vanilla JS | لا build step، يعمل مباشرة |
| SheetJS (CDN) | تصدير/استيراد Excel |

### هيكل البيانات
```javascript
// المشاريع
PROJECTS = {
  p1: {
    id, name, icon, cover, color,
    tasks: [{id, title, priority, importance, date, done, status, duration, subtasks, ...}],
    kanban: [{id, name, color}]
  }
}

// مساحات العمل
WORKSPACES = [{id, name, icon, color, projectIds}]

// المذكرة
JOURNAL = [{id, text, linkedTaskId, createdAt}]

// مصادر التعلم  
RESOURCES = [{id, title, type, url, status, notes: [{id, title, content, createdAt}]}]

// العلاقات
RELATIONS = [{id, task1, task2, type}] // blocks/related/duplicate/depends

// المهام المتكررة
RECURRING = [{id, title, freq, priority, projectId, startDate, lastRun}]
```

---

## 📋 صفحات التطبيق

| الصفحة | الوصف |
|--------|-------|
| 🧠 Brain Dump | صندوق أفكار سريع |
| 📁 المشاريع | جدول شجري بالمشاريع والمساحات |
| 📊 Dashboard | نظرة عامة وKPIs |
| ⚡ مصفوفة أيزنهاور | تصنيف المهام بالإلحاح والأهمية |
| 🏠 مساحات العمل | إدارة workspaces والمشاريع |
| 📅 المراجعة الأسبوعية | أسئلة توجيهية أسبوعية |
| ✏️ المذكرة | تدوينات يومية |
| 📚 مصادر التعلم | كتب، روابط، فيديوهات مع notebook |
| 🔗 علاقات المهام | رسم بياني للعلاقات بين المهام |
| 🔁 المهام المتكررة | مهام دورية تلقائية |
| 💾 النسخ الاحتياطي | تصدير واستيراد البيانات |

---

## 🔄 التوافق

| البيئة | الحالة |
|--------|--------|
| Chrome / Edge (Desktop) | ✅ كامل |
| Firefox (Desktop) | ✅ كامل |
| Safari (Desktop) | ✅ كامل |
| Chrome (Android) | ✅ كامل |
| Safari (iOS) | ✅ كامل |
| Samsung Internet | ✅ كامل |
| فتح من `file://` | ✅ يعمل (مع بعض محدودية PWA) |
| فتح من `http://` | ✅ كامل بما فيه PWA |

---

## 🤝 المساهمة

المشروع مفتوح للمساهمات! يُرجى:

1. Fork المستودع
2. أنشئ branch جديد: `git checkout -b feature/اسم-الميزة`
3. Commit التغييرات: `git commit -m 'إضافة ميزة ...'`
4. Push: `git push origin feature/اسم-الميزة`
5. افتح Pull Request

### أفكار للمساهمة
- [ ] دعم قواعد بيانات (IndexedDB) لبيانات أكبر
- [ ] مزامنة عبر الشبكة المحلية
- [ ] نظام Tags/Labels للمهام
- [ ] تقارير الإنتاجية مع charts
- [ ] دعم Markdown في المذكرة
- [ ] تكامل مع التقويم

---

## 📄 الترخيص

MIT License — أنظر ملف [LICENSE](LICENSE) للتفاصيل.

---

## 👤 المؤلف

**Ahmed** — Business Analyst @ MEWA, Saudi Arabia  
حاصل على شهادة PMI-PBA

---

<div align="center">

صُنع بـ ❤️ للمنتجين العرب

**[⬆ العودة للأعلى](#مُنجز--نظام-التخطيط-الشخصي)**

</div>
