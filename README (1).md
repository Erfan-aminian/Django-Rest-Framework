
# Django Rest Framework 📦

یک پروژه‌ی ساده و تمیز بر پایه‌ی Django و Django REST Framework برای پیاده‌سازی API در جنگو. این پروژه به عنوان پایه‌ای برای توسعه‌ی RESTful API طراحی شده و قابلیت توسعه و سفارشی‌سازی بالایی دارد.

---

## 🛠 تکنولوژی‌ها

- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- Python 3.8+
- SQLite (برای توسعه)

---

## 🚀 نصب و اجرا

برای راه‌اندازی پروژه روی سیستم خود مراحل زیر را طی کنید:

```bash
# کلون کردن ریپو
git clone https://github.com/Erfan-aminian/Django-Rest-Framework.git
cd Django-Rest-Framework

# ساخت و فعال‌سازی محیط مجازی (اختیاری اما توصیه‌شده)
python -m venv venv
source venv/bin/activate   # در ویندوز: venv\Scripts\activate

# نصب وابستگی‌ها
pip install -r requirements.txt

# اعمال مایگریشن‌ها
python manage.py migrate

# اجرای سرور توسعه
python manage.py runserver
```

اکنون می‌توانید با رفتن به `http://127.0.0.1:8000/api/` به API پروژه دسترسی داشته باشید.

---

## 📁 ساختار پروژه

```
Django-Rest-Framework/
│
├── api/                 # اپلیکیشن اصلی API
│   ├── models.py        # مدل‌ها
│   ├── serializers.py   # سریالایزرها
│   ├── views.py         # ویوهای API
│   ├── urls.py          # مسیرهای اپ
│   └── ...
│
├── config/              # تنظیمات کلی پروژه
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── requirements.txt     # پکیج‌های مورد نیاز
└── manage.py
```

---

## 📬 API Endpoints

نمونه‌هایی از مسیرهای API (ممکن است بر اساس پروژه نهایی تغییر کنند):

| متد | مسیر            | توضیح               |
|------|------------------|----------------------|
| GET  | `/api/items/`    | لیست آیتم‌ها         |
| POST | `/api/items/`    | ایجاد آیتم جدید      |
| GET  | `/api/items/<id>/` | دریافت یک آیتم خاص |
| PUT  | `/api/items/<id>/` | بروزرسانی آیتم     |
| DELETE | `/api/items/<id>/` | حذف آیتم           |

---

## 🧪 تست‌کردن

برای اجرای تست‌ها:

```bash
python manage.py test
```

---

## 🙋‍♂️ توسعه‌دهنده

Created with ❤️ by [Erfan Aminian](https://github.com/Erfan-aminian)

---

## 📃 لایسنس

این پروژه تحت لایسنس MIT منتشر شده و آزادانه قابل استفاده، ویرایش و توسعه است.
