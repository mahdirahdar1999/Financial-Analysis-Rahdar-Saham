# 📊 ربات تحلیل مالی: راهدار سهام

> یک ربات تحلیل مالی حرفه‌ای برای تحلیل شرکت‌های سهام با استفاده از پایتون

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![YFinance](https://img.shields.io/badge/yfinance-%E2%9C%94-green)
![Pandas](https://img.shields.io/badge/pandas-%E2%9C%94-green)
![Google Colab](https://img.shields.io/badge/Run%20in%20Colab-%E2%9C%85-orange)

---

## 🔍 ویژگی‌ها
- ✅ تحلیل فنی (SMA, RSI, MACD, Bollinger Bands)
- ✅ تحلیل بنیادی (P/E, ROE, P/B, EPS, Beta)
- ✅ گزارش خودکار با تفسیر
- ✅ نمودارهای حرفه‌ای
- ✅ قابلیت اجرا در Google Colab بدون نیاز به نصب
- ✅ پشتیبانی از شرکت‌های ایرانی (مثل `FAMILY.TSE`, `KHAZAR.TSE`)

---

## 🛠️ نحوه اجرا (فقط ۳ مرحله)

1. به [Google Colab](https://colab.research.google.com) برو.
2. یک نوتبوک جدید بساز.
3. کد را کپی و اجرا کن.

> 💡 نکته: فقط کافیه خط زیر رو عوض کنی:
>
> ```python
> analyze_company("FAMILY.TSE", "شرکت مدیریت سرمایه فملی")
> ```
>
> به:
>
> ```python
> analyze_company("نام_نماد.TSE", "نام شرکت")
> ```

---

## 📌 مثال اجرایی
```python
analyze_company("KHAZAR.TSE", "شرکت سرمایه‌گذاری خزر")
