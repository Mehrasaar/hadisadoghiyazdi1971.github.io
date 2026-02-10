
layout: persian  # یا single با کلاس rtl-layout
classes: wide rtl-layout
dir: rtl
title: "مدل‌های چندوجهی بزرگ"
permalink: /teaching/toolkit/lmm/
author_profile: false
sidebar:
  nav: "toolkit"
header:
  overlay_image: "/assets/images/background.jpg"
  overlay_filter: 0.3
  overlay_color: "#5e616c"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

# Large Multimodal Models (LMM)
 

# مدل‌های چندوجهی بزرگ
---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1770649111587.jpg" alt="lmm_1" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
جهان فقط از کلمات ساخته نشده.  
</div>
ما انسان‌ها جهان را می‌بینیم، می‌شنویم، لمس می‌کنیم، می‌خوانیم  
و از ترکیب همهٔ این حس‌ها، «فهم» می‌سازیم.

تا چند سال پیش، هوش مصنوعی فقط یک حس داشت:  
حسِ «خواندن متن».

اما حالا وارد دوره‌ای شده‌ایم که مدل‌ها فقط متن را نمی‌خوانند؛  
می‌بینند، می‌شنوند، تحلیل می‌کنند و استدلال می‌کنند.

این همان جایی است که LMM وارد صحنه می‌شود.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1767034117990.jpeg" alt="lmm_2" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
یک مغز چندحسی
</div>
تصور کنید یک مدل هوش مصنوعی روبه‌روی شماست.  
به او یک عکس نشان می‌دهید، یک جمله می‌گویید، یک فایل صوتی پخش می‌کنید.  
او همه را با هم می‌فهمد.

LMM مثل انسانی است که:

- تصویر را می‌بیند  
- متن را می‌خواند  
- صدا را می‌شنود  
- و از ترکیب این‌ها، معنا استخراج می‌کند  

این مدل‌ها فقط «پاسخ» نمی‌دهند؛  
استدلال چندحسی انجام می‌دهند.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_17705649433976.jpeg" alt="lmm_3" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
پرسش بنیادین: مدل چطور از چند حس، یک فهم واحد می‌سازد؟

</div>
وقتی شما یک عکس از یک میز شلوغ نشان می‌دهید، این فقط پیکسل است.  
وقتی می‌گویید «لیوان را بردار»، این فقط کلمات است.

اما مدل باید بفهمد:

- این شیء روی میز یک لیوان است  
- این جمله دربارهٔ «برداشتن لیوان» است  
- و این دو باید به هم وصل شوند  

LMM دقیقاً برای همین ساخته شده:  
اتصال «دیدن»، «خواندن» و «شنیدن» به یکدیگر.

---
تعریف ساده LMM
LMM مدلی است که:

- تصویر را می‌فهمد  
- متن را می‌فهمد  
- صدا را می‌فهمد  
- و از ترکیب این‌ها استدلال می‌سازد  

این تعریف ساده، پایهٔ بسیاری از سیستم‌های هوشمند امروز است.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_1770650195509.jpeg" alt="lmm_4" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
مثال شهودی: مربی ورزشی هوشمند

</div>

تصور کنید به مدل می‌گویید:

«این ویدیو رو نگاه کن. ببین چرا ضربه‌هام اشتباهه.»

مدل:

1. ویدیو را نگاه می‌کند  
2. زاویهٔ دست و پا را تحلیل می‌کند  
3. متن شما را می‌فهمد  
4. استدلال می‌کند: سرعت کم است؟ زاویه غلط است؟ هماهنگی مشکل دارد؟  
5. پاسخ می‌دهد: «زاویهٔ آرنجت خیلی باز است، باید نزدیک‌تر نگهش داری.»

اینجا مدل از تصویر و متن و حرکت، یک فهم واحد ساخته است.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1770650421082.jpeg" alt="lmm_5" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
مثال شهودی: دستیار تعمیرات
</div>
یک تکنسین صدای موتور را ضبط می‌کند و می‌گوید:

«این صدا غیرعادیه. مشکل از کجاست؟»

LMM:

- صدا را تحلیل می‌کند  
- متن را می‌خواند  
- الگوی خرابی را تشخیص می‌دهد  
- و یک تحلیل چندوجهی ارائه می‌دهد  

این همان چیزی است که مدل‌های فقط زبانی نمی‌توانستند انجام دهند.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_1778883976.jpeg" alt="lmm_6" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
کاربردهای گسترده: از خانه تا کارخانه
</div>
LMM فقط برای تحلیل عکس نیست.  
در ده‌ها حوزه کاربرد دارد:

- پزشکی  
- آموزش  
- خودروهای خودران  
- رباتیک  
- طراحی  
- امنیت  
- تولید محتوا  

هرجا لازم باشد چند حس با هم فهمیده شوند، LMM حضور دارد.

---

معماری LMM
چهار مرحلهٔ اصلی — همراه با مثال‌های شهودی

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1770650964572.jpeg" alt="lmm_7" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
۱) رمزگذار بینایی – فهم تصویر
</div>
مدل تصویر را می‌گیرد و آن را به مفاهیم قابل‌فهم تبدیل می‌کند.

مثال:  
یک عکس از یک میز کار شلوغ را به مدل می‌دهید.  
او باید بفهمد:

- این لپ‌تاپ است  
- این لیوان قهوه است  
- این دفترچه است  
- این کابل به کجا وصل است  

مدل پیکسل‌ها را به «مفهوم» تبدیل می‌کند.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_17706426521152.jpeg" alt="lmm_8" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
۲) رمزگذار زبان – فهم متن
</div>
مدل جملهٔ شما را می‌گیرد و آن را به ساختار معنایی تبدیل می‌کند.

مثال:  
شما می‌گویید:

«بگو کدوم کابل مربوط به شارژره.»

مدل باید بفهمد:

- موضوع: کابل  
- هدف: تشخیص کابل شارژ  
- محدودیت: از میان چند کابل موجود روی میز  

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1770651164216.jpeg" alt="lmm_9" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
۳) ادغام چندوجهی – اتصال حس‌ها
</div>
در این مرحله، مدل تصویر و متن را کنار هم قرار می‌دهد.

مثال:  
مدل می‌فهمد:

- در تصویر چند کابل وجود دارد  
- جملهٔ شما دربارهٔ «کابل شارژ» است  
- پس باید از میان کابل‌ها، آن یکی را پیدا کند که به آداپتور وصل است یا به پورت شارژ لپ‌تاپ می‌رود  

این همان لحظهٔ «وصل شدن حس‌ها»ست.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/copilot_image_1770650983167.jpeg" alt="lmm_10" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
۴) استدلال – نتیجه‌گیری
</div>

مدل تصمیم می‌گیرد چه چیزی مهم است و چه پاسخی مناسب است.

مثال:  
مدل بررسی می‌کند:

- کدام کابل به پورت شارژ وصل است  
- کدام کابل به دستگاه دیگری می‌رود  
- کدام ویژگی‌ها نشان می‌دهد این کابل، کابل شارژ است  

و در نهایت می‌گوید:

«کابلی که سمت راست لپ‌تاپ قرار دارد، کابل شارژ است.»

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_177665345.jpeg" alt="lmm_11" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
چرا این چرخه مهم است؟
</div>
زیرا جهان واقعی فقط متن نیست.  
ما با چشم، گوش، زبان و تجربه جهان را می‌فهمیم.

LMM اولین نسل از مدل‌هایی است که این چندحسی بودن را تقلید می‌کند.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/7d9bbcf40aeede660a8537e713922ce6.jpg" alt="lmm_12" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
تا اینجا LMM فقط «می‌فهمد».  
</div>
اما فهمیدن کافی نیست.  
جهان واقعی نیاز به عمل دارد.

اینجاست که VLA وارد می‌شود:  
چرخهٔ دیدن → فهمیدن → عمل کردن.

اما یک سؤال مهم وجود دارد:

ربات برای فهمیدنِ جهان از چه مغزی استفاده می‌کند؟

در نسل‌های جدید رباتیک، این مغز همان LMM است.

ربات:

- تصویر را به LMM می‌دهد  
- دستور شما را به LMM می‌دهد  
- LMM معنا و هدف را استخراج می‌کند  
- VLA این معنا را به «عمل» تبدیل می‌کند  

به زبان ساده:

LMM می‌فهمد، VLA عمل می‌کند.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_1770678579746.jpeg" alt="lmm_13" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
مثال شهودی: ربات دستیار
</div>
شما می‌گویید:

«این کتاب رو پیدا کن و روی میز مطالعه بذار.»

ربات:

1. قفسه‌ را نگاه می‌کند  
2. تصویر را به LMM می‌دهد  
3. LMM می‌فهمد: این کتاب است، این شماره ی رده‌بندی است  
4. دستور شما را می‌خواند و هدف را استخراج می‌کند  
5. VLA تصمیم می‌گیرد چه حرکتی لازم است  
6. ربات کتاب را برمی‌دارد  
7. دوباره نگاه می‌کند، دوباره تصمیم می‌گیرد  
8. چرخه ادامه پیدا می‌کند  

اینجا LMM «فهم» را می‌سازد  
و VLA «عمل» را.

---
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/Toolkitimages/lmm/image_1770651539461.jpeg" alt="lmm_14" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
LMM و آیندهٔ هوش مصنوعی
</div>
هرجا لازم باشد:

- تصویر دیده شود  
- متن فهمیده شود  
- صدا تحلیل شود  
- و از ترکیب این‌ها نتیجه‌گیری شود  

LMM حضور دارد.

---





