<div align="center">

# 🐧 Ubuntu Free Server — Railway Edition

### سرور اوبونتوی کاملاً رایگان با دسترسی گرافیکی و ترمینال آنلاین

<img src="1.jpg" alt="Ubuntu Free Server Banner" width="100%" />

<p>
  <img src="https://img.shields.io/badge/Platform-Railway-8A2BE2?style=for-the-badge&logo=railway&logoColor=white" />
  <img src="https://img.shields.io/badge/OS-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Access-VNC%20%7C%20SSH-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cost-100%25%20Free-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made%20by-technamooz-ff4500?style=for-the-badge" />
</p>

</div>

---

## 📖 معرفی پروژه

با این پروژه می‌تونی در کمتر از **۱۰ دقیقه** یک **سرور اوبونتوی کاملاً رایگان** روی پلتفرم **Railway** راه‌اندازی کنی؛ سروری با دسکتاپ گرافیکی (قابل دسترسی از مرورگر) و همچنین دسترسی کامل ترمینال (SSH) بدون نیاز به هیچ نرم‌افزار یا تنظیمات پیچیده‌ای.

<div align="center">
  <img src="2.jpg" alt="Server Dashboard Preview" width="80%" />
</div>

---

## ✨ ویژگی‌های پروژه

| ویژگی | توضیح |
|:---:|:---|
| 💸 رایگان | بدون نیاز به پرداخت هزینه، فقط با پلن رایگان Railway |
| 🖥️ دسکتاپ گرافیکی | دسترسی به محیط گرافیکی اوبونتو از طریق مرورگر (noVNC) |
| 💻 ترمینال آنلاین | دسترسی SSH آنی با یک لینک ساده، بدون تنظیم کلید |
| ⚡ راه‌اندازی سریع | کل فرآیند نصب کمتر از ۱۰ دقیقه زمان می‌برد |
| 🌍 دسترسی جهانی | از هر جای دنیا، فقط با یک مرورگر وب |

---

## 📋 پیش‌نیازها

| مورد نیاز | لینک |
|:---|:---:|
| حساب کاربری گیتهاب | [github.com](https://github.com) |
| حساب کاربری Railway | [railway.app](https://railway.app) |
| مرورگر وب (Chrome / Firefox) | — |

---

## 🚀 آموزش نصب و راه‌اندازی، قدم به قدم

<table>
<tr><th>مرحله</th><th>عملیات</th></tr>

<tr>
<td><b>۱</b></td>
<td>یک حساب کاربری در <a href="https://github.com">گیتهاب</a> بسازید (در صورتی که ندارید).</td>
</tr>

<tr>
<td><b>۲</b></td>
<td>ریپازیتوری <code>docker-ubuntu-free</code> را با زدن دکمه <b>Fork</b> در حساب گیتهاب خودتان کپی کنید.</td>
</tr>

<tr>
<td><b>۳</b></td>
<td>وارد سایت <a href="https://railway.app">Railway</a> شوید و با گزینه <b>Sign in with GitHub</b> وارد حساب خود شوید.</td>
</tr>

<tr>
<td><b>۴</b></td>
<td>
روی <b>New Project</b> کلیک کنید → گزینه <b>Deploy from GitHub repo</b> را انتخاب کنید → ریپازیتوری فورک‌شده (<code>docker-ubuntu-free</code>) را انتخاب کنید.
</td>
</tr>

<tr>
<td><b>۵</b></td>
<td>صبر کنید تا Railway پروژه را Build و Deploy کند و وضعیت آن به <b>Online</b> تغییر کند.</td>
</tr>

<tr>
<td><b>۶</b></td>
<td>وارد تب <b>Settings</b> پروژه شوید → به بخش <b>Networking</b> بروید → گزینه <b>TCP Proxy</b> را فعال کرده و روی پورت <code>6080</code> تنظیم کنید.</td>
</tr>

<tr>
<td><b>۷</b></td>
<td>روی <b>Generate Domain</b> کلیک کنید → پورت <code>6080</code> را انتخاب کنید → کشور مورد نظر را از لیست انتخاب نمایید.</td>
</tr>

<tr>
<td><b>۸</b></td>
<td>روی <b>Deploy</b> بزنید و صبر کنید پروژه دوباره وضعیت <b>Online</b> بگیرد.</td>
</tr>

<tr>
<td><b>۹</b></td>
<td>دامنه‌ای که Railway ساخته را به همراه پورت در مرورگر باز کنید و گزینه <b>VNC HTML</b> را انتخاب کنید تا به دسکتاپ اوبونتو متصل شوید.</td>
</tr>

</table>

<div align="center">
  <img src="3.jpg" alt="VNC Desktop Access" width="80%" />
</div>

---

## 🔑 فعال‌سازی دسترسی ترمینال (SSH آنی با sshx)

پس از اتصال به دسکتاپ گرافیکی، ترمینال سرور را باز کنید و مراحل زیر را دنبال کنید:

**۱. نصب ابزار sshx:**
```bash
curl -sSf https://sshx.io/get | sh
```

**۲. اجرای sshx و دریافت لینک دسترسی:**
```bash
sshx
```

**۳.** لینکی که در خروجی نمایش داده می‌شود را کپی کرده و در مرورگر سیستم خودتان باز کنید — اکنون به ترمینال کامل سرورتان از هر جایی دسترسی دارید. ✅

---

## 🎥 آموزش تصویری کامل

> برای دیدن آموزش کامل و گام‌به‌گام این پروژه به همراه توضیحات تصویری، حتماً ویدیوی زیر را در کانال یوتیوب ما تماشا کنید:

<div align="center">

### 📺 آموزش صفر تا صد در کانال یوتیوب technamooz

</div>

---

## ⚠️ نکات مهم

- این پروژه از پلن رایگان Railway استفاده می‌کند؛ محدودیت منابع (CPU / RAM / ساعت اجرا) طبق سیاست فعلی Railway اعمال می‌شود و ممکن است در آینده تغییر کند.
- لینک تولیدشده توسط `sshx` عمومی و قابل دسترسی برای هرکسی است که آن را داشته باشد — آن را با افراد غریبه به اشتراک نگذارید.
- پیشنهاد می‌شود قبل از استفاده طولانی‌مدت یا تجاری، شرایط استفاده (ToS) پلتفرم Railway را مطالعه کنید.

---

<div align="center">

## 📣 ما را در شبکه‌های اجتماعی دنبال کنید

| پلتفرم | آیدی / نام کانال |
|:---:|:---:|
| ▶️ یوتیوب | **technamooz** |
| 📷 اینستاگرام | **technamooz** |
| ✈️ تلگرام | **technamooz** |
| 🐦 توییتر (X) | **technamooz** |

### 🔔 با عضویت و دنبال کردن ما، جدیدترین آموزش‌های رایگان سرور، لینوکس و شبکه رو از دست نده!

</div>

---

<p align="center">🚀 ساخته‌شده با ❤️ توسط <b>technamooz</b> برای جامعه فارسی‌زبان علاقه‌مند به لینوکس و سرورهای رایگان</p>
