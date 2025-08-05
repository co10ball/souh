<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<h2 align="center">سواح - Souah</h2>

<p align="center">
  منصة تقييم وتجربة الوجهات السياحية باستخدام Laravel 🌍
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Laravel-10-red" alt="Laravel Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Active-success" alt="Project Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"></a>
</p>

---

## 📌 نبذة عن المشروع

**سواح** هو تطبيق ويب يساعد المستخدمين على اكتشاف وتقييم الوجهات السياحية، وإرسال توصياتهم وتجاربهم، والتواصل عبر الدردشة. يدعم النظام أيضًا صلاحيات للمشرفين لإدارة المحتوى والتقارير.

---

## 🚀 المميزات

- تسجيل وتسجيل دخول آمن مع التحقق بخطوتين (2FA)
- إرسال واستقبال الرسائل بين الأعضاء
- رفع الصور والملفات إلى التخزين السحابي (AWS S3)
- إدارة كاملة للرحلات والتوصيات بواسطة المشرفين
- واجهة دردشة تفاعلية
- توليد تقارير PDF
- نظام أدوار وصلاحيات باستخدام Spatie Permissions
- نظام إشعارات وملف شخصي متكامل للمستخدم

---

## 🧰 الأدوات والتقنيات

| تقنية | وصف |
|--|--|
| Laravel 10 | إطار عمل التطبيق |
| Laravel Breeze / UI | واجهة تسجيل الدخول |
| Spatie Permissions | إدارة الأدوار |
| DomPDF | توليد ملفات PDF |
| Intervention Image | تعديل الصور |
| AWS S3 | تخزين سحابي |
| SQLite | قاعدة بيانات مدمجة للتطوير |

---

## 🔧 طريقة التشغيل محلياً

```bash
git clone https://github.com/your-username/souah.git
cd souah
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
