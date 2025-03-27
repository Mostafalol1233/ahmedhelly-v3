# منصة الأستاذ أحمد حلي التعليمية

منصة تعليمية متكاملة تتيح للطلاب مشاهدة المحاضرات المرئية والتفاعل مع المحتوى بسهولة.

## المميزات الرئيسية

- **نظام إدارة محتوى كامل**: يمكن للمسؤولين تحميل ورفع المحاضرات المرئية وإدارتها
- **نظام أكواد المحاضرات**: إمكانية إضافة كود محاضرة لكل فيديو للتحكم بالوصول (كود لمرة واحدة فقط)
- **لوحة تحكم للطلاب**: تمكن الطلاب من متابعة المحاضرات وكتابة الملاحظات
- **المساعد الذكي**: دردشة ذكية باستخدام واجهة برمجة OpenAI للإجابة على استفسارات الطلاب
- **نظام استعادة كلمة المرور**: إمكانية استعادة كلمة المرور عبر البريد الإلكتروني أو رقم الهاتف
- **واجهة مستخدم معربة**: المنصة مصممة بشكل كامل باللغة العربية

## متطلبات النظام

- Python 3.7+
- Flask
- SQLAlchemy
- Flask-Login
- Flask-WTF
- Werkzeug
- MySQL (للاستضافة على InfinityFree)

## التثبيت على InfinityFree

1. قم برفع جميع الملفات إلى حسابك على InfinityFree
2. قم بإنشاء قاعدة بيانات MySQL جديدة من لوحة تحكم InfinityFree
3. قم بزيارة `http://your-domain.com/setup` لإعداد المنصة
4. أدخل بيانات قاعدة البيانات ومعلومات الاتصال الأخرى
5. بمجرد الانتهاء من الإعداد، ستكون المنصة جاهزة للاستخدام

## بيانات تسجيل الدخول الافتراضية

**المسؤول**:
- اسم المستخدم: admin
- كلمة المرور: admin123

**طالب للتجربة**:
- اسم المستخدم: student
- كلمة المرور: student123

_ملاحظة: يرجى تغيير كلمات المرور الافتراضية فور تسجيل الدخول لأول مرة._

## الاستخدام

### مسؤول النظام:
- رفع وإدارة مقاطع الفيديو
- إنشاء أكواد المحاضرات
- نشر الإعلانات والمنشورات للطلاب
- إدارة حسابات المستخدمين

### الطلاب:
- مشاهدة المحاضرات المتاحة
- استخدام أكواد المحاضرات للوصول إلى المحتوى المقيد
- كتابة وتنظيم الملاحظات الشخصية
- استخدام المساعد الذكي للمساعدة في فهم المفاهيم

© 2025 منصة الأستاذ أحمد حلي. جميع الحقوق محفوظة.