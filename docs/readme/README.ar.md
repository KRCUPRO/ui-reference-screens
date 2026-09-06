<div dir="rtl">

<h1 align="center">شاشات مرجعية لواجهة المستخدم</h1>

<p align="center">
  [English](../readme/README.en.md) | [한국어](../readme/README.ko.md) | [简体中文](../readme/README.zh.md) | [日本語](../readme/README.ja.md) | [Español](../readme/README.es.md) | [Français](../readme/README.fr.md) | [Русский](../readme/README.ru.md) | **العربية** | [हिन्दी](../readme/README.hi.md) • [📜 سجل التغييرات](../changelog/CHANGELOG.ar.md)
</p>

---

> 248 شاشة مرجعية بصيغة HTML مستقلة — لوحة تشغيل بوابة API وصفحة هبوط بأسلوب تحريري.

### [▶ المعرض المباشر](https://krcupro.github.io/ui-reference-screens/)

تصفّح كل الشاشات في المتصفح

## كيف تبدو

![كيف تبدو](../assets/gallery-demo.gif)

*مرّر المؤشر فوق أي صف لمعاينة الشاشة الحقيقية؛ ورشّح حسب العنوان أو مقاس العرض.*

| شاشات سطح المكتب تُعرض بعرض 1280 بكسل | شاشات الجوال تُعرض بعرض 390 بكسل |
| --- | --- |
| ![](../assets/preview-desktop.jpg) | ![](../assets/preview-mobile.jpg) |

## أبرز الميزات

- **معاينة بمجرد التمرير.** الإشارة إلى صف تعرض الشاشة الحقيقية في مكانها — بلا صور مصغّرة وبلا جلب أي شيء من مكان آخر.
- **كلٌّ بمقاس عرضه.** التخطيط للجوال يُعاين بعرض 390 بكسل ولسطح المكتب بعرض 1280 بكسل، فلا ينكمش ولا يتشوّش.
- **ملفات مستقلة.** كل شاشة ملف HTML واحد يُفتح في المتصفح دون أي خطوة بناء.
- **ترشيح أثناء الكتابة.** بحث بالعنوان، وتضييق حسب مقاس العرض، وتنقّل بين الأقسام؛ واضغط `/` للانتقال إلى مربع البحث.
- **فاتح وداكن.** يتبع المعرض سمة النظام.

## المحتويات

| القسم | الشاشات |
| --- | ---: |
| Marginalia — صفحة الهبوط | 94 |
| لوحة التحكم — نظرة عامة | 25 |
| لوحة التحكم — المفاتيح | 18 |
| لوحة التحكم — التحليلات | 17 |
| لوحة التحكم — الشاشات | 12 |
| لوحة التحكم — نظام التصميم | 21 |
| لوحة التحكم — السجلات | 7 |
| لوحة التحكم — الإعدادات | 13 |
| لوحة التحكم — MCP | 6 |
| لوحة التحكم — ساحة الاختبار | 2 |
| لوحة التحكم — أخرى | 33 |
| **الإجمالي** | **248** |

## مقاسات العرض

| مقاس العرض | الشاشات | عرض التصيير |
| --- | ---: | --- |
| Desktop | 165 | 1280px |
| Mobile | 54 | 390px |
| Tablet | 29 | 834px |

## البنية

```
index.html                 gallery
catalog.json               metadata for all 248 screens
screens/
  marginalia-landing/      94
  operations-console/      154
docs/
  readme/                  9 languages
  changelog/               9 languages
  assets/
```

## طريقة الاستخدام

1. افتح [المعرض المباشر](https://krcupro.github.io/ui-reference-screens/) — لا شيء لتثبيته.
2. أو استنسخ المستودع وافتح `index.html` مباشرة:

```bash
git clone https://github.com/KRCUPRO/ui-reference-screens.git
cd ui-reference-screens
# open index.html
```

## `catalog.json`

مدخل واحد لكل شاشة:

```json
{
  "file": "screens/operations-console/overview/dashboard-overview.html",
  "title": "Dashboard Overview",
  "category": "operations-console/overview",
  "device": "DESKTOP",
  "prompt": "⚡ 외부 MCP 에이전트 연동으로 생성됨",
  "createdAt": "2026-08-31T13:54:01.252Z"
}
```

## ملاحظات

- الشاشات نماذج ثابتة. كل القيم الظاهرة فيها مُختلقة للتوضيح — لا توجد حسابات أو مفاتيح أو مضيفات أو بيانات شخصية حقيقية.
- تُحمَّل الخطوط فقط عبر الشبكة من Google Fonts، وكل ما عداها مضمَّن داخل الملف.
- تتكرّر بعض العناوين بحالات مختلفة — تحميل، فارغ، خطأ، تشغيل أول، أداء متدهور.

---

<p align="center">
  <a href="https://krcupro.github.io/ui-reference-screens/">المعرض المباشر</a> · <a href="../../README.md">العودة إلى الملف التعريفي الرئيسي</a>
</p>

</div>
