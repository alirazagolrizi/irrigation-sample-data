# Generate Irrigation Sensor Sample Data | تولید دادهٔ نمونهٔ حسگر آبیاری

**Proposed GitHub repository name:** `irrigation-sample-data`

## Purpose | هدف
Create a small illustrative CSV dataset for the irrigation classifier.

تولید دادهٔ نمونهٔ حسگر آبیاری: این مخزن یک نمونهٔ مستقل مبتنی بر یک سلول کد استخراج‌شده است؛ برای شرح کوتاه فارسی، هدف پروژه را در عنوان بالا ببینید.

## Prerequisites | پیش‌نیازها
Python 3.9+; pandas.

## Install | نصب
Use Python 3 and Jupyter. Install the packages listed in `requirements.txt` with:

```bash
python -m pip install -r requirements.txt
```

پایتون و Jupyter را نصب کنید؛ سپس وابستگی‌های `requirements.txt` را با دستور بالا نصب کنید. برخی وابستگی‌ها اختیاری یا وابسته به سیستم‌عامل/سخت‌افزار هستند.

## Run | اجرا
Open notebook.ipynb in Jupyter; it writes sensor_data.csv to the current directory.

فایل `notebook.ipynb` را در Jupyter باز کنید و یک سلول کد آن را اجرا کنید. ورودی‌ها و مسیرهای لازم در بخش محدودیت‌ها آمده‌اند.

## Limitations and input assets | محدودیت‌ها و ورودی‌ها
The ten-row synthetic/example dataset is only for demonstration, not real agricultural decisions or model validation.

این نمونه‌ها صرفاً آموزشی‌اند و اجرای انتها‌به‌انتها در این بسته تضمین یا تأیید نشده است. ورودی/دادهٔ تخصصی یا سخت‌افزار در صورت نیاز باید جداگانه فراهم شود.
