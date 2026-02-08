---
layout: persian  # یا single با کلاس rtl-layout
classes: wide rtl-layout
dir: rtl
title: "تخمین گر بیز- تابع ضرر مربعات"
permalink: /teaching/toolkit/BayesianEstimator/
author_profile: true
sidebar:
  nav: "toolkit"
header:
  overlay_image: "/assets/images/background.jpg"
  overlay_filter: 0.3
  overlay_color: "#5e616c"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

**مولف-دکتر علیرضا مهرابی**


## صورت مسئله

در جریان محاسبهٔ عبارت زیر

$$
\frac{
\int_{-\infty}^{\infty} \mu \, f(\mu \mid x_1, x_2, \dots, x_N)\, d\mu
}{
\int_{-\infty}^{\infty} f(\mu \mid x_1, x_2, \dots, x_N)\, d\mu
}
$$

فرض می‌کنیم:

### پیشین (Prior)

$$
\mu \sim \mathcal{N}(\mu_0, \sigma_0^2)
$$

### مدل داده‌ها (Likelihood)

داده‌ها مستقل بوده و

$$
x_i = \mu + \eta
$$

که در آن

$$
\eta \sim \mathcal{N}(0, \sigma_n^2)
$$

در نتیجه

$$
x_i \mid \mu \sim \mathcal{N}(\mu, \sigma_n^2)
$$

---

## هدف

محاسبهٔ دو انتگرال:

### صورت

$$
A =
\int_{-\infty}^{\infty}
\mu \,
\frac{1}{(\sqrt{2\pi}\sigma_n)^N}
\exp\!\left(
-\frac{\sum_{i=1}^{N}(\mu-x_i)^2}{2\sigma_n^2}
\right)
\frac{1}{\sqrt{2\pi}\sigma_0}
\exp\!\left(
-\frac{(\mu-\mu_0)^2}{2\sigma_0^2}
\right)
d\mu
$$

### مخرج

$$
C =
\int_{-\infty}^{\infty}
\frac{1}{(\sqrt{2\pi}\sigma_n)^N}
\exp\!\left(
-\frac{\sum_{i=1}^{N}(\mu-x_i)^2}{2\sigma_n^2}
\right)
\frac{1}{\sqrt{2\pi}\sigma_0}
\exp\!\left(
-\frac{(\mu-\mu_0)^2}{2\sigma_0^2}
\right)
d\mu
$$

---

## ساده‌سازی نمایی‌ها

ابتدا مجموع مربعات را بسط می‌دهیم:

$$
\sum_{i=1}^{N}(\mu-x_i)^2
=
N\mu^2 - 2\mu\sum_{i=1}^{N}x_i + \sum_{i=1}^{N}x_i^2
$$

جملات وابسته به $\mu$ در توان عبارت نمایی:

$$
-\frac12
\left[
\left(\frac{N}{\sigma_n^2}+\frac{1}{\sigma_0^2}\right)\mu^2
-
2\left(\frac{\sum x_i}{\sigma_n^2}+\frac{\mu_0}{\sigma_0^2}\right)\mu
\right]
$$

---

## کامل کردن مربع

می‌نویسیم

$$
-\alpha \mu^2 + \beta \mu
=
-\alpha
\left(
\mu - \frac{\beta}{2\alpha}
\right)^2
+
\frac{\beta^2}{4\alpha}
$$

که در آن

$$
\alpha =
\frac12\left(\frac{N}{\sigma_n^2}+\frac{1}{\sigma_0^2}\right)
$$

$$
\beta =
\frac{\sum x_i}{\sigma_n^2}+\frac{\mu_0}{\sigma_0^2}
$$

---

## نتیجهٔ مهم

پس توزیع پسین نیز گوسی است:

$$
\mu \mid x \sim \mathcal{N}(\mu_{\text{post}}, \sigma_{\text{post}}^2)
$$

که

$$
\sigma_{\text{post}}^2 =
\frac{1}{\frac{N}{\sigma_n^2}+\frac{1}{\sigma_0^2}}
$$

و

$$
\mu_{\text{post}} =
\sigma_{\text{post}}^2
\left(
\frac{\sum_{i=1}^{N} x_i}{\sigma_n^2}
+
\frac{\mu_0}{\sigma_0^2}
\right)
$$

---

## محاسبهٔ نسبت انتگرال‌ها

از تعریف امید ریاضی داریم:

$$
\frac{A}{C}
=
\mathbb{E}[\mu \mid x]
$$

پس:

$$
\boxed{
\frac{A}{C}
=
\frac{
\frac{1}{\sigma_n^2}\sum_{i=1}^{N} x_i
+
\frac{1}{\sigma_0^2}\mu_0
}{
\frac{N}{\sigma_n^2}+\frac{1}{\sigma_0^2}
}
}
$$

---

## فرم ساده‌تر با میانگین نمونه

اگر

$$
\bar{x} = \frac1N \sum_{i=1}^{N} x_i
$$

آنگاه

$$
\boxed{
\mu_{\text{post}}
=
\frac{
\frac{N}{\sigma_n^2}\bar{x}
+
\frac{1}{\sigma_0^2}\mu_0
}{
\frac{N}{\sigma_n^2}+\frac{1}{\sigma_0^2}
}
}
$$

---

## تفسیر آماری

این رابطه یک میانگین وزنی است:

$$
\mu_{\text{post}}
=
w \bar{x} + (1-w)\mu_0
$$

که وزن‌ها متناسب با دقت (precision) هستند:

$$
\text{precision} = \frac{1}{\sigma^2}
$$

---

## نتیجهٔ نهایی

$$
\boxed{
\frac{A}{C} = \mu_{\text{post}}
}
$$

یعنی نسبت دو انتگرال دقیقاً برابر **میانگین توزیع پسین** است.
