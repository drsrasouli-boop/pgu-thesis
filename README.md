<div align="center">

# 📘 pgu-thesis

**قالب رسمی لاتک پایان‌نامه — دانشگاه خلیج فارس**
**Official LaTeX Thesis Template — Persian Gulf University**

[![Made with LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![XeLaTeX](https://img.shields.io/badge/Compiler-XeLaTeX-4B0082?style=for-the-badge)](https://www.tug.org/texlive/)
[![Persian](https://img.shields.io/badge/Language-Persian-F05A3C?style=for-the-badge)](https://fa.wikipedia.org/wiki/زبان_فارسی)
[![License](https://img.shields.io/badge/License-MIT-D7A01E?style=for-the-badge)](LICENSE)

<img src="https://img.shields.io/badge/Version-2.0-4B0082?style=flat-square" />
<img src="https://img.shields.io/badge/Status-Active-00A05A?style=flat-square" />
<img src="https://img.shields.io/badge/Degrees-B.Sc.%20%7C%20M.Sc.%20%7C%20Ph.D.-F05A3C?style=flat-square" />

</div>

---

<div dir="rtl" align="right">

## 📖 دربارهٔ پروژه

**pgu-thesis** یک قالب رسمی، کامل و ماژولار لاتک برای نگارش **پروژهٔ کارشناسی**، **پایان‌نامهٔ کارشناسی ارشد** و **رسالهٔ دکتری** در **دانشگاه خلیج فارس** است. این قالب با **XeLaTeX** و بستهٔ **`xepersian`** پیاده‌سازی شده و از زبان فارسی و چیدمان راست‌به‌چپ به‌طور کامل پشتیبانی می‌کند.

قالب مطابق با **آیین‌نامهٔ نگارش دانشگاه خلیج فارس** طراحی شده و تمام بخش‌های ضروری یک پایان‌نامهٔ رسمی را به‌صورت خودکار فراهم می‌کند؛ به‌گونه‌ای که دانشجو تنها با پر کردن فایل‌های اطلاعات و فصل‌ها، می‌تواند سند نهایی و استاندارد خود را تولید کند.

> 🎯 **هدف:** تمرکز بر محتوای علمی، نه تنظیمات قالب‌بندی.

</div>

<div dir="ltr" align="left">

## 📖 About

**pgu-thesis** is an official, complete, and modular LaTeX template for writing **Bachelor projects**, **Master's theses**, and **PhD dissertations** at **Persian Gulf University**. It is built with **XeLaTeX** and **`xepersian`**, offering full Persian and right-to-left support.

The template follows the **official PGU thesis formatting guidelines** and automatically provides every required section of a formal thesis, so students only need to fill in the information and chapter files to produce a standard, publication-ready document.

> 🎯 **Goal:** Focus on your research, not on formatting.

</div>

---

## ✨ ویژگی‌ها | Features

<div align="center">

| # | ویژگی | توضیح |
|---|--------|--------|
| 1️⃣ | **صفحات مقدماتی خودکار** | عنوان فارسی/انگلیسی، بسم‌الله، تقدیم، نیایش، سپاس‌گزاری، تعهدنامه، پیشگفتار، مقدمه و چکیده‌ها |
| 2️⃣ | **صفحهٔ عنوان استاندارد** | لوگوی دانشگاه، تزئینات `pgfornament`، اطلاعات دانشکده/گروه، اساتید و داوران |
| 3️⃣ | **صفحهٔ ارزیابی داوران** | کادر اختصاصی با درجهٔ ارزیابی و مشخصات هیئت داوران (فارسی/انگلیسی) |
| 4️⃣ | **صفحهٔ تعهدنامه** | متن رسمی مالکیت نتایج و حق نشر دانشگاه |
| 5️⃣ | **صفحهٔ پوستر دفاع** | اطلاع‌رسانی جلسهٔ دفاع با زمان و مکان |
| 6️⃣ | **طراحی مدرن فصل** | شمارهٔ فصل با نستعلیق و نوارهای گرادیانی تزئینی |
| 7️⃣ | **محیط‌های آماده** | تعریف، قضیه، لم، گزاره، نتیجه، نکته، مثال، الگوریتم و پاسخ |
| 8️⃣ | **پشتیبانی علمی** | `amsmath`, `amsthm`, `siunitx`, `pgfplots`, `algorithm2e` |
| 9️⃣ | **جدول و شکل حرفه‌ای** | `booktabs`, `caption`, `subcaption`, `float`, `array` |
| 🔟 | **فونت‌های فارسی** | `XB Niloofar`, `XB Yas`, `XB Titre`, `IranNastaliq` |
| 1️⃣1️⃣ | **ارجاعات هوشمند** | `hyperref` با رنگ تم + `backref` کنترل‌شده |
| 1️⃣2️⃣ | **واژه‌نامه و اختصارات** | `glossaries` با پشتیبانی `xindy` فارسی |
| 1️⃣3️⃣ | **دوزبانه** | چکیده و عنوان فارسی/انگلیسی، منابع با `plain-fa` |
| 1️⃣4️⃣ | **ساختار ماژولار** | جداسازی کامل بخش‌ها در `supp/` و `chapters/` |

</div>

---

## 🚀 شروع سریع | Quick Start

<div dir="rtl" align="right">

### ۱. نصب توزیع تک‌لایو (TeX Live)

آخرین نسخهٔ **TeX Live** را از آدرس رسمی زیر دانلود و نصب کنید:

🔗 <https://www.tug.org/texlive/windows.html>

### ۲. نصب ویرایشگر TeXstudio

ویرایشگر **TeXstudio** را از آدرس رسمی زیر دریافت کنید:

🔗 <https://www.texstudio.org/>

### ۳. دریافت قالب و فونت‌ها

قالب، فونت‌های ضروری و بستهٔ کامل فونت‌ها از این مخزن قابل دریافت است:

🔗 <https://github.com/drsrasouli-boop/pgu-thesis>

### ۴. کامپایل

فایل اصلی را با **XeLaTeX** کامپایل کنید (نه PDFLaTeX):

```bash
xelatex main.tex
```

</div>

<div dir="ltr" align="left">

### 1. Install TeX Live

Download and install the latest **TeX Live** distribution:

🔗 <https://www.tug.org/texlive/windows.html>

### 2. Install TeXstudio

Get the **TeXstudio** editor:

🔗 <https://www.texstudio.org/>

### 3. Get the Template & Fonts

Download the template, required fonts, and the full font bundle from this repository:

🔗 <https://github.com/drsrasouli-boop/pgu-thesis>

### 4. Compile

Compile the main file with **XeLaTeX** (not PDFLaTeX):

```bash
xelatex main.tex
```

</div>

---

## ⚙️ پیش‌نیازها | Requirements

<div dir="rtl" align="right">

| ابزار | نسخهٔ پیشنهادی | توضیح |
|-------|----------------|--------|
| **TeX Live** | 2023 یا جدیدتر | توزیع اصلی لاتک |
| **XeLaTeX** | همراه TeX Live | کامپایلر اصلی (اجباری) |
| **TeXstudio** | آخرین نسخه | ویرایشگر پیشنهادی |
| **XB Niloofar** | — | فونت فارسی پیش‌فرض متن |
| **XB Yas** | — | فونت اعداد |
| **XB Titre** | — | فونت عناوین |
| **IranNastaliq** | — | فونت نستعلیق (عنوان فصل‌ها و صفحات مقدماتی) |

> ⚠️ **توجه:** تمام فونت‌های فوق باید روی سیستم نصب باشند. بستهٔ کامل فونت‌ها در پوشهٔ `fonts/` مخزن موجود است.

</div>

<div dir="ltr" align="left">

| Tool | Recommended | Notes |
|------|-------------|-------|
| **TeX Live** | 2023+ | Main LaTeX distribution |
| **XeLaTeX** | Bundled | Required compiler |
| **TeXstudio** | Latest | Recommended editor |
| **XB Niloofar** | — | Default Persian text font |
| **XB Yas** | — | Digits font |
| **XB Titre** | — | Headings font |
| **IranNastaliq** | — | Nastaliq font (chapter titles & front matter) |

> ⚠️ **Note:** All fonts above must be installed on your system. The full font bundle is available in the `fonts/` directory.

</div>

---

## 📂 ساختار پروژه | Project Structure

```
pgu-thesis/
├── README.md
├── LICENSE
├── pgu.cls                     # کلاس اصلی — تعریف اطلاعات و صفحات عنوان
├── main.tex                    # فایل اصلی پروژه
├── fonts/                      # فونت‌های ضروری فارسی
│   ├── XB Niloofar.ttf
│   ├── XB Yas.ttf
│   ├── XB Titre.ttf
│   └── IranNastaliq.ttf
├── images/
│   └── logo.png                # لوگوی دانشگاه
├── supp/
│   ├── commands.tex            # بسته‌ها، رنگ‌ها، فونت‌ها، محیط‌ها
│   ├── Information.tex         # اطلاعات پایان‌نامه
│   ├── glossary.tex            # تنظیمات واژه‌نامه
│   ├── mygloss.tex             # تعریف واژه‌نامه‌ها
│   ├── fa_title.tex            # صفحهٔ عنوان فارسی
│   ├── en_title.tex            # صفحهٔ عنوان انگلیسی
│   ├── fa_abstract.tex         # چکیدهٔ فارسی
│   ├── en_abstract.tex         # چکیدهٔ انگلیسی
│   ├── besm.tex                # صفحهٔ بسم‌الله
│   ├── dedicationpage.tex      # صفحهٔ تقدیم
│   ├── chantpage.tex           # صفحهٔ نیایش
│   ├── acknowledgementpage.tex # صفحهٔ سپاس‌گزاری
│   ├── commitmentpage.tex      # صفحهٔ تعهدنامه
│   ├── prefacepage.tex         # صفحهٔ پیشگفتار
│   ├── Introduction.tex        # مقدمه
│   └── references.bib          # منابع
└── chapters/
    ├── chapter0.tex
    ├── chapter1.tex
    └── ...
```

---

## 🎓 گزینه‌های مقطع | Degree Options

<div dir="rtl" align="right">

در خط `\documentclass` فایل `main.tex`، یکی از گزینه‌های زیر را انتخاب کنید:

```latex
% --- کارشناسی (پروژه) ---
\documentclass[oneside,openany,bsc]{pgu}

% --- کارشناسی ارشد (پایان‌نامه) ---
\documentclass[oneside,openany,msc]{pgu}

% --- دکتری (رساله) ---
\documentclass[oneside,openany,phd]{pgu}
```

**گزینه‌های صفحه‌بندی (اختیاری):**

| گزینه | توضیح |
|-------|--------|
| `oneside` / `twoside` | تک‌رو / دو‌رو |
| `openany` / `openright` | شروع فصل از هر صفحه / صفحهٔ فرد |

برچسب‌ها (پروژه/پایان‌نامه/رساله)، مقطع تحصیلی و متن‌های توضیحی به‌طور **خودکار** بر اساس گزینهٔ انتخابی تنظیم می‌شوند.

</div>

<div dir="ltr" align="left">

In the `\documentclass` line of `main.tex`, choose one of the following options:

```latex
% --- Bachelor (Project) ---
\documentclass[oneside,openany,bsc]{pgu}

% --- Master's (Thesis) ---
\documentclass[oneside,openany,msc]{pgu}

% --- PhD (Dissertation) ---
\documentclass[oneside,openany,phd]{pgu}
```

**Pagination options (optional):**

| Option | Description |
|--------|-------------|
| `oneside` / `twoside` | Single-sided / Double-sided |
| `openany` / `openright` | Chapter starts on any page / odd page |

Labels (project/thesis/dissertation), degree, and descriptive texts are **set automatically** based on the chosen option.

</div>

---

## 🖥️ کامپایل | Compilation

<div dir="rtl" align="right">

### روش ۱: خط فرمان

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

### روش ۲: در TeXstudio

`Build → XeLaTeX` را انتخاب کنید و سپس `BibTeX` و مجدداً `XeLaTeX` را اجرا کنید.

### روش ۳: برای واژه‌نامه

پس از اجرای اولیه، ابزار Glossary را با دستور زیر اجرا کنید:

```bash
xindy -L persian-variant1 -C utf8 -I xindy -M main.xdy -t main.glg -o main.gls main.glo
```

> 💡 **نکته:** در TeXstudio مسیر `Options → Configure TeXstudio → Build → Default Glossary Tool` را به دستور بالا تنظیم کنید.

</div>

<div dir="ltr" align="left">

### Option 1: Command line

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

### Option 2: In TeXstudio

Select `Build → XeLaTeX`, then run `BibTeX`, then `XeLaTeX` again.

### Option 3: For the glossary

After the first run, execute the Glossary tool with:

```bash
xindy -L persian-variant1 -C utf8 -I xindy -M main.xdy -t main.glg -o main.gls main.glo
```

> 💡 **Tip:** In TeXstudio, set `Options → Configure TeXstudio → Build → Default Glossary Tool` to the command above.

</div>

---

## 🎨 سفارشی‌سازی | Customization

<div dir="rtl" align="right">

- **رنگ اصلی قالب:** در فایل `supp/commands.tex` خط `\colorlet{themecolor}{ultramarine}` را تغییر دهید. رنگ‌های آماده: `sangria`, `alizarin`, `burntorange`, `deepskyblue`, `darkmidnightblue`, `zaffre` و …
- **فونت‌ها:** در همان فایل، `\settextfont` و `\setdigitfont` را تغییر دهید.
- **اطلاعات پایان‌نامه:** تمام موارد در `supp/Information.tex` تعریف شده‌اند.
- **محیط‌های قضیه:** کادرهای `defbox`, `thbox`, `exbox`, `rebox` در `supp/commands.tex` قابل تنظیم‌اند.

</div>

<div dir="ltr" align="left">

- **Theme color:** In `supp/commands.tex`, change `\colorlet{themecolor}{ultramarine}`. Available colors: `sangria`, `alizarin`, `burntorange`, `deepskyblue`, `darkmidnightblue`, `zaffre`, etc.
- **Fonts:** In the same file, modify `\settextfont` and `\setdigitfont`.
- **Thesis information:** All fields are defined in `supp/Information.tex`.
- **Theorem boxes:** `defbox`, `thbox`, `exbox`, `rebox` are customizable in `supp/commands.tex`.

</div>

---

## 📚 محیط‌های آماده | Predefined Environments

<div align="center">

| محیط | کاربرد | کادر |
|--------|---------|------|
| `definition` | تعریف | `defbox` |
| `theorem` | قضیه | `thbox` |
| `lemma` | لم | `thbox` |
| `proposition` | گزاره | `thbox` |
| `corollary` | نتیجه | `thbox` |
| `remark` | نکته | `rebox` |
| `example` | مثال | `exbox` |
| `alg` | الگوریتم | `thbox` |
| `solution` | پاسخ | — |

</div>

---

## 🤝 مشارکت | Contributing

<div dir="rtl" align="right">

از مشارکت شما استقبال می‌کنیم. برای ارسال اصلاحات یا پیشنهادها:

1. مخزن را **Fork** کنید.
2. یک شاخهٔ جدید بسازید: `git checkout -b feature/my-feature`
3. تغییرات را **Commit** کنید: `git commit -m "Add my feature"`
4. شاخه را **Push** کنید: `git push origin feature/my-feature`
5. یک **Pull Request** باز کنید.

**قواعد مشارکت:**
- کدها باید با **XeLaTeX** بدون خطا کامپایل شوند.
- توضیحات و کامنت‌ها به فارسی یا انگلیسی روان باشند.
- تغییرات ساختاری در `pgu.cls` با ذکر دلیل ارائه شوند.

</div>

<div dir="ltr" align="left">

Contributions are welcome. To submit fixes or suggestions:

1. **Fork** the repository.
2. Create a branch: `git checkout -b feature/my-feature`
3. **Commit** your changes: `git commit -m "Add my feature"`
4. **Push** the branch: `git push origin feature/my-feature`
5. Open a **Pull Request**.

**Contribution guidelines:**
- Code must compile cleanly with **XeLaTeX**.
- Comments and documentation should be clear in Persian or English.
- Structural changes to `pgu.cls` should include a rationale.

</div>

---

## 📬 ارتباط با ما | Contact

<div align="center">

| | |
|---|---|
| 📧 **Email** | [srasouli@pgu.ac.ir](mailto:srasouli@pgu.ac.ir) |
| 📱 **Phone** | 09375197298 |
| 💬 **Bale** | **DSRasouli** |
| 🐙 **GitHub** | [@drsrasouli-boop](https://github.com/drsrasouli-boop) |

</div>

<div dir="rtl" align="right">

در صورت هرگونه سوال، پیشنهاد یا گزارش مشکل، می‌توانید از راه‌های بالا با نگارنده در ارتباط باشید. 🌱

</div>

<div dir="ltr" align="left">

For any questions, suggestions, or issue reports, feel free to reach out via any of the channels above. 🌱

</div>

---

## 📄 مجوز | License

<div align="center">

Released under the **MIT License** · منتشرشده تحت مجوز **MIT**

استفاده از این قالب در سایر دانشگاه‌ها با ذکر منبع مجاز است.
Use of this template in other universities is permitted with proper citation.

</div>

---

## 🙏 قدردانی | Acknowledgments

<div dir="rtl" align="right">

- از **دانشگاه خلیج فارس** برای حمایت از توسعهٔ این قالب.
- از جامعهٔ **لاتک فارسی** و توسعه‌دهندگان `xepersian` و `pgfornament`.
- از تمام دانشجویانی که با بازخورد خود به بهبود این قالب کمک کرده‌اند.

</div>

<div dir="ltr" align="left">

- **Persian Gulf University** for supporting the development of this template.
- The **Persian LaTeX community** and the developers of `xepersian` and `pgfornament`.
- All students whose feedback has helped improve this template.

</div>

---

<div align="center">

### ⭐ اگر این پروژه برایتان مفید بود، یک ستاره بدهید!
### ⭐ If this project helped you, please give it a star!

<img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20for%20PGU%20students-C8286E?style=for-the-badge" />

**pgu-thesis** · Persian Gulf University · LaTeX Thesis Template
</div>
