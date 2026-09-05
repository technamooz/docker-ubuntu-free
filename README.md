# docker-ubuntu-free
راه اندازی سرور اوبونتو با منابع سخت افزار بالا کاملا رایگان با دسترسی اس اس اچ و دسترسی مستقیم به سیستم عامل

بسیار عالی! حالا آموزش کامل و دقیق شما را به صورت یک فایل README.md حرفه‌ای تبدیل می‌کنم. این فایل شامل تمام مراحل گام‌به‌گام با تصاویر و جدول‌های زیبا است.

---

```markdown
<div align="center">
  
# <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=35&duration=3000&pause=500&color=00D4FF&center=true&vCenter=true&width=600&lines=%F0%9F%9A%80+%D8%B3%D8%B1%D9%88%D8%B1+%D8%A7%D9%88%D8%A8%D9%88%D9%86%D8%AA%D9%88+%D8%B1%D8%A7%DB%8C%DA%AF%D8%A7%D9%86;%F0%9F%90%B3+Docker+Ubuntu+on+Railway;%F0%9F%94%92+SSH+%D8%A8%D8%AF%D9%88%D9%86+%D9%85%D8%AD%D8%AF%D9%88%D8%AF%DB%8C%D8%AA;%F0%9F%8E%AF+%D8%AA%DA%A9%D9%86%D9%88%D9%85%D9%88%D8%B2+%F0%9F%92%AA" alt="Typing SVG" />

</div>

---

<div align="center">
  
# 🐳 **راه‌اندازی سرور اوبونتو رایگان با داکر روی Railway** ☁️

### *«از ثبت‌نام تا اتصال SSH در کمتر از ۱۰ دقیقه»*

</div>

<p align="center">
  <img src="https://img.shields.io/badge/status-فعال-success.svg?style=for-the-badge&color=00D4FF"/>
  <img src="https://img.shields.io/badge/هزینه-۱۰۰%25_رایگان-brightgreen.svg?style=for-the-badge&color=2ECC71"/>
  <img src="https://img.shields.io/badge/پلتفرم-Railway-9B59B6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/تکنولوژی-Docker-2496ED?style=for-the-badge&logo=docker"/>
  <img src="https://img.shields.io/badge/سیستم‌عامل-Ubuntu_22.04-E95420?style=for-the-badge&logo=ubuntu"/>
  <img src="https://img.shields.io/badge/SSH-اتصال_امن-FF6B6B?style=for-the-badge"/>
</p>

---

<div align="center">
  
## 📺 **آموزش کامل ویدیویی در یوتیوب** 🎬

[![آموزش کامل راه‌اندازی سرور رایگان روی Railway | تکنوموز](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

### 👆 برای تماشای آموزش کامل روی تصویر کلیک کنید

**📢 حتماً کانال یوتیوب [Technamooz](https://www.youtube.com/@Technamooz) رو سابسکرایب کنید!**

</div>

---

## 📋 **فهرست مطالب**

- [📺 آموزش ویدیویی کامل](#-آموزش-کامل-ویدیویی-در-یوتیوب)
- [🎯 معرفی پروژه](#-معرفی-پروژه)
- [✨ مزایای این سرور رایگان](#-مزایای-این-سرور-رایگان)
- [📦 پیش‌نیازها](#-پیشنیازها)
- [🚀 آموزش گام‌به‌گام](#-آموزش-گامبهگام)
  - [مرحله ۱: ساخت اکانت گیت‌هاب](#مرحله-۱-ساخت-اکانت-گیتهاب)
  - [مرحله ۲: ورود به Railway](#مرحله-۲-ورود-به-railway)
  - [مرحله ۳: ایجاد پروژه جدید](#مرحله-۳-ایجاد-پروژه-جدید)
  - [مرحله ۴: انتخاب ریپازیتوری](#مرحله-۴-انتخاب-ریپازیتوری)
  - [مرحله ۵: تنظیمات پورت و دامنه](#مرحله-۵-تنظیمات-پورت-و-دامنه)
  - [مرحله ۶: دپلوی و راه‌اندازی](#مرحله-۶-دپلوی-و-راهاندازی)
  - [مرحله ۷: اتصال به VNC](#مرحله-۷-اتصال-به-vnc)
  - [مرحله ۸: فعال‌سازی SSH با sshx](#مرحله-۸-فعالسازی-ssh-با-sshx)
- [📊 جدول مقایسه پلتفرم‌ها](#-جدول-مقایسه-پلتفرمها)
- [🖼️ تصاویر مراحل](#️-تصاویر-مراحل)
- [❓ سوالات متداول](#-سوالات-متداول)
- [📱 ارتباط با تکنوموز](#-ارتباط-با-تکنوموز)

---

## 🎯 **معرفی پروژه**

با استفاده از این آموزش، شما یک **سرور اوبونتو ۲۲.۰۴** را به صورت **کاملاً رایگان** روی پلتفرم **Railway** راه‌اندازی می‌کنید و از طریق **VNC** و **SSH** به آن متصل می‌شوید.

### 🔥 **قابلیت‌های این سرور:**

| 🎁 قابلیت | 📝 توضیح |
|:---:|---|
| 💰 **رایگان** | هزینه ۰ تومان! |
| 🐳 **داکر** | ایزوله و امن |
| 🖥️ **VNC** | رابط گرافیکی کامل |
| 🔗 **SSH** | دسترسی از طریق مرورگر |
| 🌍 **دامنه** | آدرس اختصاصی |
| ⚡ **سریع** | راه‌اندازی ۵ دقیقه‌ای |

---

## ✨ **مزایای این سرور رایگان**

<div align="center">

| # | مزیت | توضیح |
|:---:|:---:|---|
| ۱ | 💰 **کاملاً رایگان** | بدون نیاز به کارت بانکی یا پرداخت |
| ۲ | 🚀 **راه‌اندازی سریع** | کمتر از ۱۰ دقیقه |
| ۳ | 🖥️ **رابط گرافیکی** | دسترسی از طریق VNC |
| ۴ | 🔒 **امنیت بالا** | استانداردهای Railway |
| ۵ | 🌐 **دسترسی جهانی** | CDN و سرورهای پراکنده |
| ۶ | 🔄 **اتوماتیک** | Deploy خودکار |
| ۷ | 📱 **اتصال SSH** | از هر جا و هر دستگاه |
| ۸ | 🎯 **مناسب برای** | یادگیری، تست، توسعه |

</div>

---

## 📦 **پیش‌نیازها**

برای شروع به این موارد نیاز دارید:

- [x] یک ایمیل معتبر
- [x] اتصال به اینترنت
- [x] مرورگر (Chrome, Firefox, Edge)
- [x] انگیزه یادگیری! 💪

---

## 🚀 **آموزش گام‌به‌گام**

### 📌 **مرحله ۱: ساخت اکانت گیت‌هاب**

ابتدا یک حساب کاربری در **گیت‌هاب** ایجاد کنید:

1. به سایت [GitHub](https://github.com/) بروید
2. روی **Sign up** کلیک کنید
3. اطلاعات خود را وارد کنید:
   - ایمیل
   - رمز عبور قوی
   - نام کاربری
4. ایمیل خود را تأیید کنید
5. ✅ اکانت شما ساخته شد!

<div align="center">
  
![ساخت اکانت گیت‌هاب](https://via.placeholder.com/600x300/00D4FF/000000?text=+%F0%9F%94%91+%D8%B3%D8%A7%D8%AE%D8%AA+%D8%A7%DA%A9%D8%A7%D9%86%D8%AA+%DA%AF%DB%8C%D8%AA%E2%80%8C%D9%87%D8%A7%D8%A8+%F0%9F%94%91+)

</div>

---

### 📌 **مرحله ۲: ورود به Railway**

1. به سایت [Railway.app](https://railway.app/) بروید
2. روی **Start a New Project** یا **Login** کلیک کنید
3. گزینه **Login with GitHub** را انتخاب کنید
4. اجازه دسترسی به Railway بدهید
5. ✅ وارد حساب کاربری خود شدید!

<div align="center">
  
![ورود به Railway](https://via.placeholder.com/600x300/9B59B6/FFFFFF?text=+%F0%9F%9A%AA+%D9%88%D8%B1%D9%88%D8%AF+%D8%A8%D9%87+Railway+%F0%9F%9A%AA+)

</div>

> 📺 **ویدیو کامل ثبت‌نام و ورود** در [یوتیوب تکنوموز](https://www.youtube.com/@Technamooz)

---

### 📌 **مرحله ۳: ایجاد پروژه جدید**

بعد از ورود به داشبورد Railway:

1. روی دکمه **New Project** کلیک کنید
2. از بین گزینه‌ها، **Deploy from GitHub repo** را انتخاب کنید
3. Railway لیست ریپازیتوری‌های شما را نمایش می‌دهد

<div align="center">
  
![ایجاد پروژه جدید](https://via.placeholder.com/600x300/2ECC71/000000?text=+%F0%9F%93%81+%D8%A7%DB%8C%D8%AC%D8%A7%D8%AF+%D9%BE%D8%B1%D9%88%DA%98%D9%87+%D8%AC%D8%AF%DB%8C%D8%AF+%F0%9F%93%81+)

</div>

---

### 📌 **مرحله ۴: انتخاب ریپازیتوری**

1. ریپازیتوری **docker-ubuntu-free** را که **فورک** کرده‌اید انتخاب کنید
2. اگر این ریپازیتوری را ندارید، ابتدا آن را از لینک زیر فورک کنید:

```bash
# لینک ریپازیتوری
https://github.com/your-username/docker-ubuntu-free
```

3. روی ریپازیتوری کلیک کنید تا انتخاب شود
4. ✅ پروژه شما ایجاد شد!

<div align="center">
  
![انتخاب ریپازیتوری](https://via.placeholder.com/600x300/3498DB/FFFFFF?text=+%F0%9F%93%82+%D8%A7%D9%86%D8%AA%D8%AE%D8%A7%D8%A8+%D8%B1%DB%8C%D9%BE%D8%A7%D8%B2%DB%8C%D8%AA%D9%88%D8%B1%DB%8C+%F0%9F%93%82+)

</div>

---

### 📌 **مرحله ۵: تنظیمات پورت و دامنه**

حالا باید تنظیمات پورت را انجام دهید:

1. در داشبورد پروژه، به بخش **Settings** بروید
2. تب **Networking** را انتخاب کنید
3. روی گزینه **TCP Proxy** کلیک کنید
4. پورت را روی **6080** تنظیم کنید
5. روی **Generate Domain** کلیک کنید
6. پورت **6080** را انتخاب کنید
7. کشور مورد نظر خود را از لیست انتخاب کنید
8. روی **Generate** کلیک کنید

<div align="center">
  
![تنظیمات پورت و دامنه](https://via.placeholder.com/600x300/E67E22/000000?text=+%F0%9F%8C%8D+%D8%AA%D9%86%D8%B8%DB%8C%D9%85%D8%A7%D8%AA+%D9%BE%D9%88%D8%B1%D8%AA+%D9%88+%D8%AF%D8%A7%D9%85%D9%86%D9%87+%F0%9F%8C%8D+)

</div>

---

### 📌 **مرحله ۶: دپلوی و راه‌اندازی**

1. روی دکمه **Deploy** کلیک کنید
2. منتظر بمانید تا پروژه **Build** شود (حدود ۲-۳ دقیقه)
3. وضعیت را بررسی کنید:
   - 🟡 Deploying... (در حال اجرا)
   - 🟢 **Online** (موفقیت‌آمیز)
4. ✅ پروژه شما آنلاین شد!

<div align="center">
  
![دپلوی موفق](https://via.placeholder.com/600x300/27AE60/FFFFFF?text=+%E2%9C%85+%D8%AF%D9%BE%D9%84%D9%88%DB%8C+%D9%85%D9%88%D9%81%D9%82+%E2%9C%85+)

</div>

---

### 📌 **مرحله ۷: اتصال به VNC**

برای اتصال به رابط گرافیکی سرور:

1. دامنه‌ای که Railway به شما داده را با پورت باز کنید:

```bash
https://your-domain.railway.app/
```

2. گزینه **VNC HTML** را انتخاب کنید
3. یک رابط کاربری گرافیکی از سرور اوبونتو مشاهده می‌کنید
4. ✅ به سرور متصل شدید!

<div align="center">
  
![اتصال VNC](https://via.placeholder.com/600x300/E74C3C/FFFFFF?text=+%F0%9F%96%A5%EF%B8%8F+%D8%A7%D8%AA%D8%B5%D8%A7%D9%84+VNC+%F0%9F%96%A5%EF%B8%8F+)

</div>

---

### 📌 **مرحله ۸: فعال‌سازی SSH با sshx**

حالا برای دسترسی SSH از طریق مرورگر:

#### ۱. باز کردن ترمینال سرور

در رابط VNC، **Terminal** را باز کنید.

#### ۲. اجرای دستور اول

```bash
curl -sSf https://sshx.io/get | sh
```

#### ۳. اجرای دستور دوم

```bash
sshx
```

#### ۴. کپی کردن لینک SSH

خروجی یک لینک مانند زیر خواهد بود:

```bash
https://sshx.io/join/XXXXXXXXXX
```

#### ۵. باز کردن لینک در مرورگر

لینک را در مرورگر سیستم خود باز کنید:

- 🟢 **اتصال SSH برقرار شد!**
- ✅ به ترمینال سرور دسترسی کامل دارید!

<div align="center">
  
![اتصال SSH](https://via.placeholder.com/600x300/8E44AD/FFFFFF?text=+%F0%9F%94%92+%D8%A7%D8%AA%D8%B5%D8%A7%D9%84+SSH+%D8%A8%D8%A7+%D9%85%D8%B1%D9%88%D8%B1%DA%AF%D8%B1+%F0%9F%94%92+)

</div>

---

## 🎉 **تبریک! سرور رایگان شما آماده است!**

اکنون شما یک سرور اوبونتو رایگان دارید که می‌توانید:

- ✅ برنامه‌های خود را روی آن اجرا کنید
- ✅ پروژه‌های وب را تست کنید
- ✅ ربات‌های تلگرام راه‌اندازی کنید
- ✅ دیتابیس نصب کنید
- ✅ هر چیز دیگری که دوست دارید!

---

## 📊 **جدول مقایسه پلتفرم‌ها**

<div align="center">

| ویژگی | Railway 🚀 | Heroku ⚡ | Vercel 🌐 | Render 🔥 | AWS 🏢 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **هزینه** | رایگان | رایگان | رایگان | رایگان | پولی |
| **داکر** | ✅ | ❌ | ❌ | ✅ | ✅ |
| **SSH** | ✅ | ❌ | ❌ | ✅ | ✅ |
| **VNC** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **وب‌کنترل** | ✅ | ❌ | ✅ | ✅ | ✅ |
| **آسان‌ترین** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐ |
| **ذخیره‌سازی** | 500MB | 500MB | محدود | نامحدود | پولی |
| **مناسب برای** | همه | Backend | Frontend | همه | Enterprise |

</div>

---

## 🖼️ **تصاویر مراحل**

### ۱️⃣ ساخت اکانت گیت‌هاب
![GitHub Signup](https://via.placeholder.com/800x350/00D4FF/000000?text=+%F0%9F%94%91+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B1%3A+%D8%B3%D8%A7%D8%AE%D8%AA+%D8%A7%DA%A9%D8%A7%D9%86%D8%AA+%DA%AF%DB%8C%D8%AA%E2%80%8C%D9%87%D8%A7%D8%A8+%F0%9F%94%91+)

### ۲️⃣ ورود به Railway
![Railway Login](https://via.placeholder.com/800x350/9B59B6/FFFFFF?text=+%F0%9F%9A%AA+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B2%3A+%D9%88%D8%B1%D9%88%D8%AF+%D8%A8%D9%87+Railway+%F0%9F%9A%AA+)

### ۳️⃣ ایجاد پروژه جدید
![New Project](https://via.placeholder.com/800x350/2ECC71/000000?text=+%F0%9F%93%81+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B3%3A+%D8%A7%DB%8C%D8%AC%D8%A7%D8%AF+%D9%BE%D8%B1%D9%88%DA%98%D9%87+%F0%9F%93%81+)

### ۴️⃣ انتخاب ریپازیتوری
![Select Repo](https://via.placeholder.com/800x350/3498DB/FFFFFF?text=+%F0%9F%93%82+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B4%3A+%D8%A7%D9%86%D8%AA%D8%AE%D8%A7%D8%A8+%D8%B1%DB%8C%D9%BE%D8%A7%D8%B2%DB%8C%D8%AA%D9%88%D8%B1%DB%8C+%F0%9F%93%82+)

### ۵️⃣ تنظیمات پورت و دامنه
![Port Settings](https://via.placeholder.com/800x350/E67E22/000000?text=+%F0%9F%8C%8D+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B5%3A+%D8%AA%D9%86%D8%B8%DB%8C%D9%85+%D9%BE%D9%88%D8%B1%D8%AA+%D9%88+%D8%AF%D8%A7%D9%85%D9%86%D9%87+%F0%9F%8C%8D+)

### ۶️⃣ دپلوی موفق
![Deploy Success](https://via.placeholder.com/800x350/27AE60/FFFFFF?text=+%E2%9C%85+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B6%3A+%D8%AF%D9%BE%D9%84%D9%88%DB%8C+%D9%85%D9%88%D9%81%D9%82+%E2%9C%85+)

### ۷️⃣ اتصال VNC
![VNC Connection](https://via.placeholder.com/800x350/E74C3C/FFFFFF?text=+%F0%9F%96%A5%EF%B8%8F+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B7%3A+%D8%A7%D8%AA%D8%B5%D8%A7%D9%84+VNC+%F0%9F%96%A5%EF%B8%8F+)

### ۸️⃣ SSH با sshx
![SSH Connection](https://via.placeholder.com/800x350/8E44AD/FFFFFF?text=+%F0%9F%94%92+%D9%85%D8%B1%D8%AD%D9%84%D9%87+%DB%B8%3A+%D8%A7%D8%AA%D8%B5%D8%A7%D9%84+SSH+%F0%9F%94%92+)

---

## ❓ **سوالات متداول**

<details>
<summary><b>💡 آیا این سرور واقعاً رایگان است؟</b></summary>
<br>
بله! Railway یک پلن رایگان با ۵۰۰ مگابایت ذخیره‌سازی و ۱۰۰۰ ساعت اجرای ماهانه ارائه می‌دهد که برای استفاده شخصی و یادگیری کاملاً کافی است.
</details>

<details>
<summary><b>🔐 چگونه از سرور خود محافظت کنم؟</b></summary>
<br>
- از رمزهای قوی استفاده کنید
- فقط پورت‌های ضروری را باز بگذارید
- به‌روزرسانی‌های امنیتی را انجام دهید
- از فایروال استفاده کنید
</details>

<details>
<summary><b>📦 چه پکیج‌هایی نصب است؟</b></summary>
<br>
پکیج‌های پایه اوبونتو، curl، wget، git، vim، nano، htop و ابزارهای شبکه نصب هستند.
</details>

<details>
<summary><b>🔄 چگونه پروژه را بروزرسانی کنم؟</b></summary>
<br>
با هر push به گیت‌هاب، Railway به‌طور خودکار پروژه را دپلوی مجدد می‌کند.
</details>

<details>
<summary><b>🌍 آیا می‌توانم از دامنه شخصی استفاده کنم؟</b></summary>
<br>
بله، Railway از دامنه‌های سفارشی پشتیبانی می‌کند.
</details>

<details>
<summary><b>📱 آیا از موبایل هم قابل استفاده است؟</b></summary>
<br>
بله! از طریق مرورگر موبایل هم به VNC و SSH دسترسی دارید.
</details>

<details>
<summary><b>⏱️ سرور تا کی آنلاین می‌ماند؟</b></summary>
<br>
تا زمانی که از آن استفاده کنید، آنلاین می‌ماند. بعد از ۱۰ دقیقه بی‌استفاده‌ای، ممکن است sleep کند اما با یک درخواست مجدد فعال می‌شود.
</details>

---

## 📱 **ارتباط با تکنوموز**

<div align="center">
  
### 🔥 **به خانواده تکنوموز بپیوندید!** 🔥

**آموزش‌های برنامه‌نویسی، لینوکس، سرور و تکنولوژی‌های روز**

</div>

<div align="center">

| پلتفرم | لینک | فعالیت |
|:---:|:---:|:---:|
| 📺 **یوتیوب** | [@Technamooz](https://www.youtube.com/@Technamooz) | 🟢 ویدیوهای آموزشی |
| 📷 **اینستاگرام** | [@Technamooz](https://www.instagram.com/Technamooz) | 🟢 ترفندها و نکات |
| 💬 **تلگرام** | [@Technamooz](https://t.me/Technamooz) | 🟢 پشتیبانی و اخبار |
| 🐦 **توییتر** | [@Technamooz](https://twitter.com/Technamooz) | 🟢 به‌روزرسانی‌ها |
| 🌐 **وب‌سایت** | [Technamooz.ir](https://technamooz.ir) | 🟢 مقالات و آموزش‌ها |

</div>

<br>

<div align="center">
  
[![YouTube Channel](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Technamooz)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/Technamooz)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Technamooz)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Technamooz)

</div>

---

## 📝 **تغییرات اخیر**

- ✅ آموزش کامل گام‌به‌گام اضافه شد
- ✅ راه‌اندازی VNC و SSH تکمیل شد
- ✅ جدول مقایسه پلتفرم‌ها به‌روز شد
- ✅ تصاویر مراحل نصب اضافه شد
- ✅ سوالات متداول تکمیل شد
- ✅ لینک‌های تکنوموز اضافه شد

---

## 🤝 **مشارکت در پروژه**

اگر ایده یا پیشنهادی برای بهبود این آموزش دارید:

1. ⭐ ریپازیتوری را **Star** کنید
2. 🐛 در بخش **Issues** گزارش دهید
3. 🔧 **Pull Request** بفرستید

---

## ⭐ **حمایت از ما**

اگر این آموزش برای شما مفید بود:

1. ⭐ به ریپازیتوری **Star** دهید
2. 📺 ویدیو را در یوتیوب **لایک** کنید
3. 💬 **کامنت** بگذارید
4. 🔔 کانال **تکنوموز** را **سابسکرایب** کنید
5. 📢 این آموزش را با دوستان خود به اشتراک بگذارید

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</div>

<div align="center">
  
### ✨ **ساخته شده با ❤️ توسط تیم تکنوموز**

**تکنوموز** - جایی که تکنولوژی آسان می‌شود! 🚀

**© 2024 تمامی حقوق محفوظ است**

</div>
```

---

## 🎬 **نکات تکمیلی برای ویدیو یوتیوب:**

برای تکمیل این README، لطفاً موارد زیر را انجام دهید:

1. **آپلود ویدیو در یوتیوب** و `YOUR_VIDEO_ID` را جایگزین کنید
2. **تصاویر واقعی** را جایگزین placeholderها کنید
3. **لینک ریپازیتوری** `docker-ubuntu-free` را به ریپازیتوری واقعی خود تغییر دهید

## 📸 **پیشنهاد برای تصاویر:**

برای ساخت تصاویر حرفه‌ای می‌توانید از:
- [Canva](https://www.canva.com/) - طراحی بنر و اسلاید
- [Snagit](https://www.techsmith.com/snagit.html) - اسکرین‌شات و ویرایش
- [OBS Studio](https://obsproject.com/) - ضبط ویدیو

## 🚀 **موفق باشید!**
