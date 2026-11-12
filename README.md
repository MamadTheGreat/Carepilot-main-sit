# CarePilot | وب‌سایت معرفی پروژه

این مخزن کد وب‌سایت معرفی پروژه **CarePilot** را نگه‌داری می‌کند. CarePilot یک سامانه و خدمت یکپارچه برای پایش و مدیریت مراقبت‌های پس از ترخیص بیماران پرخطر مبتلا به بیماری‌های مزمن است؛ با هدف پیوند بهتر میان بیمارستان، بیمار و مراقبت در منزل.

> این وب‌سایت برای معرفی پروژه است و خودِ سامانه ارائه‌دهنده مراقبت یا ابزار تشخیص پزشکی نیست.

## درباره CarePilot

CarePilot با تکیه بر گزارش‌های ساختاریافته بیمار یا مراقب، آموزش و یادآوری، قواعد بالینیِ تعریف‌شده و پیگیری انسانی تیم درمان، از تداوم مراقبت پس از ترخیص پشتیبانی می‌کند. هدف پروژه، کمک به شناسایی به‌موقع وضعیت‌های نیازمند بررسی، بهبود هماهنگی پیگیری و فراهم‌کردن امکان ارزیابی منظم فرایند مراقبت است.

منطق سطح‌بندی وضعیت‌ها (سبز، زرد و قرمز) باید توضیح‌پذیر، بازبینی‌پذیر و مورد تأیید بالینی باشد. هشدارها برای هدایت پیگیری تیم درمان به‌کار می‌روند و جایگزین قضاوت متخصصان نیستند.

## مخاطبان و دامنه اولیه

- بیماران و مراقبان خانوادگی
- پزشکان، پرستاران و هماهنگ‌کنندگان مراقبت
- بیمارستان‌ها، دانشگاه‌های علوم پزشکی و سایر همکاران نظام سلامت
- پژوهشگران و ارزیابان اجرای پایلوت

پروژه برای اجرای مرحله‌ای و ارزیابی در بستر بیمارستانی طراحی شده است. بیمارستان شهداء قم و همکاری احتمالی با دانشگاه علوم پزشکی قم در اسناد پیشنهادی پروژه به‌عنوان زمینه پایلوت مطرح شده‌اند؛ جزئیات اجرا نیازمند توافق و تأیید ذی‌نفعان است. گروه‌های بیماری مورد توجه اولیه شامل نارسایی قلبی، دیابت و COPD هستند و گسترش به CAD/ACS و CKD به‌عنوان مسیر توسعه مطرح شده است.

## محتوای وب‌سایت

صفحه اصلی و صفحات موضوعی، بخش‌هایی از معرفی پروژه را ارائه می‌کنند، از جمله:

- مسئله مراقبت پس از ترخیص و چشم‌انداز CarePilot
- خدمات و نقش‌های بیمار، مراقب و تیم بالینی
- مسیر بیمار و مدل ارائه مراقبت
- ارزش مورد انتظار برای بیمار، تیم درمان و سازمان سلامت
- پایلوت، همکاری‌های بیمارستانی و دانشگاهی و مسیر توسعه
- محدودیت‌ها، مسئولیت‌ها، حریم خصوصی و امنیت
- مستندات معرفی پروژه و محتوای مرتبط با مسیر دیابت

## ساختار مخزن

- `index.html` — صفحه اصلی و نقشه محتوای سایت
- فایل‌های HTML ریشه — صفحات موضوعی معرفی پروژه
- `style.css` — استایل مشترک صفحات
- `assets/` — تصاویر و فایل‌های پیوست‌شده به سایت
- `CNAME` — دامنه سفارشی انتشار سایت

این مخزن یک وب‌سایت ایستا است؛ وجود این صفحات به معنی پیاده‌سازی سامانه پایش بیمار، داشبورد بالینی یا یکپارچگی با HIS نیست.

## اجرا و پیش‌نمایش محلی

فایل `index.html` را در مرورگر باز کنید. برای سرویس‌دهی محلی می‌توانید در ریشه مخزن اجرا کنید:

```bash
python -m http.server 8000
```

سپس به `http://localhost:8000` بروید.

## اصول محتوایی و ایمنی

- CarePilot جایگزین پزشک، قضاوت بالینی یا خدمات اورژانسی نیست.
- سامانه تشخیص قطعی ارائه نمی‌کند و درمان یا دارو را به‌طور خودکار تغییر نمی‌دهد.
- قواعد بالینی باید نسخه‌بندی، مستند، بازبینی و پیش از استفاده عملیاتی تأیید شوند.
- ادعاهای مربوط به پیامدهای بالینی، کاهش بستری مجدد، صرفه‌جویی یا آمادگی عملیاتی باید به‌عنوان هدف یا فرضیه ارزیابی مطرح شوند، مگر آنکه شواهد تأییدشده برایشان موجود باشد.
- اطلاعات حساس بیمار نباید در محتوای عمومی سایت یا مخزن قرار گیرد.

## مستندات مرجع پروژه

محتوای این معرفی بر اساس چارچوب و اسناد رسمی پروژه نگه‌داری می‌شود. برای تغییر ادعاها یا دامنه محصول، ابتدا منابع رسمی پروژه را بررسی کنید و میان واقعیت مستند، هدف پیشنهادی و موضوع نیازمند اعتبارسنجی تمایز بگذارید.

---

# CarePilot | Project Introduction Website

This repository contains the source code for the **CarePilot** project introduction website. CarePilot is an integrated system and service for monitoring and managing post-discharge care for high-risk patients with chronic conditions. It aims to strengthen the connection between hospitals, patients, and care at home.

> This website introduces the project. It is not itself a care-delivery platform or a medical diagnostic tool.

## About CarePilot

CarePilot supports continuity of care after discharge through structured information reported by patients or caregivers, education and reminders, defined clinical rules, and follow-up by a human care team. The project aims to help identify situations that need timely review, improve follow-up coordination, and enable systematic evaluation of the care process.

Status levels (green, yellow, and red) must be explainable, reviewable, and clinically approved. Alerts are intended to guide follow-up by the care team and do not replace professional clinical judgment.

## Intended Users and Initial Scope

- Patients and family caregivers
- Physicians, nurses, and care coordinators
- Hospitals, medical universities, and other health-system partners
- Researchers and pilot evaluators

The project is designed for phased implementation and evaluation in a hospital setting. Shahada Hospital in Qom and potential collaboration with Qom University of Medical Sciences are described in project proposal documents as a possible pilot context; implementation details require agreement and approval from relevant stakeholders. Initial conditions of interest include heart failure, diabetes, and COPD. Expansion to CAD/ACS and CKD is described as a potential later stage.

## Website Content

The home page and topic pages introduce parts of the project, including:

- The post-discharge care problem and CarePilot’s vision
- Services and the roles of patients, caregivers, and the clinical team
- The patient journey and care-delivery model
- Expected value for patients, care teams, and health organizations
- The pilot, hospital and university collaboration, and development roadmap
- Limitations, responsibilities, privacy, and security
- Project introduction documents and content related to the diabetes pathway

## Repository Structure

- `index.html` — home page and website content map
- Root-level HTML files — project introduction topic pages
- `style.css` — shared page styles
- `assets/` — images and files used by the website
- `CNAME` — custom domain configuration for website publishing

This is a static website repository. The presence of these pages does not mean that a patient-monitoring platform, clinical dashboard, or HIS integration has been implemented.

## Run and Preview Locally

Open `index.html` in a browser. To serve the site locally, run this command from the repository root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Content and Safety Principles

- CarePilot does not replace physicians, clinical judgment, or emergency services.
- The system does not provide definitive diagnoses or automatically change treatment or medication.
- Clinical rules must be versioned, documented, reviewed, and approved before operational use.
- Claims about clinical outcomes, reduced readmissions, cost savings, or operational readiness should be presented as goals or hypotheses unless supported by validated evidence.
- Sensitive patient information must not be included in public website content or this repository.

## Project Reference Documents

This introduction is maintained in line with the project’s official framework and documents. Before changing claims or product scope, consult the official project sources and distinguish documented facts from proposed goals and items requiring validation.
