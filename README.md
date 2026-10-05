# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMM131a1Z5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  -إليك توثيقاً احترافياً كاملاً وجاهزاً بلغة Markdown لنسخه مباشرة ووضعه في ملف `README.md` الخاص بمستودع المشروع على GitHub:

```markdown
# Frontend Mentor - Bento Grid Solution

هذا هو حلي لتحدي **Bento Grid** المقدم من منصة [Frontend Mentor](https://www.frontendmentor.io). يساعد هذا التحدي على تطوير مهارات بناء الواجهات الحديثة باستخدام تقنيات CSS Grid المتطورة والتصميم المتجاوب.

---

## 📋 جدول المحتويات (Table of Contents)

- [نظرة عامة (Overview)](#نظرة-عامة-overview)
  - [التحدي (The challenge)](#التحدي-the-challenge)
  - [لقطة الشاشة (Screenshot)](#لقطة-الشاشة-screenshot)
  - [الروابط (Links)](#الروابط-links)
- [خطوات العمل والتقنيات (My process)](#خطوات-العمل-والتقنيات-my-process)
  - [التقنيات المستعملة (Built with)](#التقنيات-المستعملة-built-with)
  - [ما تعلمته (What I learned)](#ما-تعلمته-what-i-learned)
  - [التطوير المستقبلي (Continued development)](#التطوير-المستقبلي-continued-development)
- [المؤلف (Author)](#المؤلف-author)

---

## 🌟 نظرة عامة (Overview)

### 🎯 التحدي (The challenge)

يجب أن يكون المستخدم قادراً على:
- عرض التنسيق المثالي للموقع بناءً على حجم شاشة جهازه (سطح المكتب، اللوحي، الهواتف الذكية).
- رؤية حالات التفاعل (Hover states) لجميع العناصر التفاعلية في الصفحة.

### 📸 لقطة الشاشة (Screenshot)

![التصميم النهائي](./design/desktop-design.jpg)

### 🔗 الروابط (Links)

- **رابط الحل على Frontend Mentor:** [عرض الحل](https://www.frontendmentor.io/solutions/bento-grid-solution)
- **رابط الموقع المباشر (Live Site):** [معاينة الموقع](https://seyyidalirebouhi-a11y.github.io/bento-grid/)

---

## 🛠️ خطوات العمل والتقنيات (My process)

### 🚀 التقنيات المستعملة (Built with)

- **Semantic HTML5:** بناء هيكلية صحيحة ووصولية.
- **CSS Custom Properties (Variables):** إدارة الألوان والأنماط بمرونة.
- **CSS Grid (4x4 Matrix):** لبناء هيكل الشبكة المعقد وتوزيع البطاقات.
- **Flexbox:** لتوسيط التكست والعناصر داخل كل بطاقة فردية.
- **Mobile-First Workflow:** التدرج في التنسيق من الهواتف حتى شاشات سطح المكتب.

### 💡 ما تعلمته (What I learned)

خلال هذا المشروع، تعمقت في مفاهيم متقدمة في CSS Grid وإدارة الصور:

1. **التحكم الدقيق في الشبكة (Grid Coordinates):**
   تحديد مواقع وتمدد الكروت عبر الأسطر والأعمدة باستخدام `grid-column` و `grid-row`:
   ```css
   .item-1 {
       grid-column: 2 / 4;
       grid-row: 1 / 3;
   }