<div dir="rtl">

# 🤖 فهرست مدل‌های رایگان OpenRouter (آپدیت خودکار)

این ریپازیتوری شامل **فهرست به‌روز مدل‌های رایگان OpenRouter** است که می‌توان از آن‌ها در:

- افزونه‌های وردپرس
- نرم‌افزارهای دسکتاپ
- اسکریپت‌های سمت سرور
- پروژه‌های هوش مصنوعی

استفاده کرد.

🎯 **هدف اصلی:**  
فراهم‌کردن یک منبع ساده، قابل اعتماد و همیشه آپدیت برای مدل‌های رایگان OpenRouter، بدون نیاز به بررسی دستی.

---

## 📂 فایل‌های موجود

- `ai-desc.json`  
  فهرست کامل مدل‌های رایگان به‌همراه مشخصات

- `ai.txt`  
  لیست ساده نام مدل‌ها (مناسب استفاده مستقیم در تنظیمات)

---

## 🔄 نحوه استفاده در افزونه یا نرم‌افزار

شما می‌توانید این فایل‌ها را **مستقیم از GitHub دانلود** کرده و در پروژه خود استفاده کنید.  
پیشنهاد می‌شود دانلود به‌صورت زمان‌بندی‌شده (مثلاً روزانه) انجام شود.

---

## 🐍 مثال دانلود با Python

```python
import requests

url = "https://raw.githubusercontent.com/intellsoft/openrouter-free-ai-model-auto-update/main/ai-desc.json"

response = requests.get(url, timeout=10)
response.raise_for_status()

with open("ai-desc.json", "w", encoding="utf-8") as f:
    f.write(response.text)

print("Models list downloaded successfully.")
````

---

## 🐘 مثال دانلود با PHP

```php
<?php

$url = "https://raw.githubusercontent.com/intellsoft/openrouter-free-ai-model-auto-update/main/ai-desc.json";
$data = file_get_contents($url);

if ($data === false) {
    die("Download failed");
}

file_put_contents("ai-desc.json", $data);
echo "Models list downloaded successfully";
```

---

## 💡 موارد استفاده پیشنهادی

* انتخاب خودکار مدل رایگان در افزونه‌های AI
* جلوگیری از خطا هنگام حذف یا تغییر مدل‌ها
* کاهش هزینه API
* به‌روزرسانی بدون دخالت کاربر

---

## 🌐 وب‌سایت توسعه‌دهنده

توسعه داده شده توسط **IntellSoft**
🔗 [https://intellsoft.ir](https://intellsoft.ir)

ابزارها و افزونه‌های تخصصی نرم‌افزار و هوش مصنوعی

---

## 📜 لایسنس

MIT License – استفاده آزاد در پروژه‌های تجاری و شخصی

</div>

---

# 🤖 OpenRouter Free Models List (Auto Updated)

This repository provides an **auto-updated list of free OpenRouter AI models** that can be used in:

* WordPress plugins
* Desktop applications
* Server-side scripts
* AI-powered products

🎯 **Main Goal:**
Offer a simple, reliable, and always up-to-date source of free OpenRouter models without manual checks.

---

## 📂 Included Files

* `ai-desc.json`
  Full list of free models with metadata

* `free_models.txt`
  Plain list of model names (ready to use)

---

## 🔄 How to Use in Your Plugin or App

You can **download these files directly from GitHub** and load them into your project.
It is recommended to update them periodically (e.g. daily or weekly).

---

## 🐍 Download Example (Python)

```python
import requests

url = "https://raw.githubusercontent.com/intellsoft/openrouter-free-ai-model-auto-update/main/ai-desc.json"

response = requests.get(url, timeout=10)
response.raise_for_status()

with open("ai-desc.json", "w", encoding="utf-8") as f:
    f.write(response.text)

print("Models list downloaded successfully.")
```

---

## 🐘 Download Example (PHP)

```php
<?php

$url = "https://raw.githubusercontent.com/intellsoft/openrouter-free-ai-model-auto-update/main/ai-desc.json";
$data = file_get_contents($url);

if ($data === false) {
    die("Download failed");
}

file_put_contents("ai-desc.json", $data);
echo "Models list downloaded successfully";
```

---

## 💡 Suggested Use Cases

* Auto-select free AI models
* Prevent model removal issues
* Reduce API costs
* Zero-maintenance updates

---

## 🌐 Developer Website

Developed by **IntellSoft**
🔗 [https://intellsoft.ir](https://intellsoft.ir)

Professional software & AI tools

---

## 📜 License

MIT License – Free for personal and commercial use

