<div align="center">

<img src="assets/icon.png" width="120" height="120" alt="Locanger Icon" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.18);" />

# Locanger
### محاكي وتثبيت الموقع الجغرافي لنظام iOS بدون جيلبريك وبدون كمبيوتر
**Advanced Jailed iOS Location Simulation Engine**

<p align="center">
  <a href="https://github.com/alibusut/Locanger-App/releases/latest">
    <img src="https://img.shields.io/github/v/release/alibusut/Locanger-App?color=1C300E&label=Release&style=flat-square" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/badge/Platform-iOS%2016.0%20—%2027.0%2B-18181b?style=flat-square" alt="iOS Support" />
  <img src="https://img.shields.io/badge/Architecture-CoreDevice%20DDI%20%2F%20Loopback%20VPN-18181b?style=flat-square" alt="Architecture" />
  <img src="https://img.shields.io/badge/Sideload-TrollStore%20%7C%20AltStore%20%7C%20SideStore-18181b?style=flat-square" alt="Sideloading" />
  <img src="https://img.shields.io/badge/License-Proprietary-18181b?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="https://github.com/alibusut/Locanger-App/releases/latest">
    <img src="https://img.shields.io/badge/%E2%86%93_Download_Locanger.ipa-A3E635?style=for-the-badge&labelColor=1C300E&color=A3E635" height="38" alt="Download IPA" />
  </a>
</p>

</div>

---

### ◈ نظرة عامة — Overview

تطبيق **Locanger** هو محرك برمجي متكامل لتغيير وتثبيت ومحاكاة إحداثيات الموقع الجغرافي (GPS) على جميع أجهزة iPhone و iPad دون الحاجة لكسر حماية النظام (No Jailbreak)، وبشكل ذاتي ومستقل تماماً على الجهاز دون الحاجة لربطه بجهاز كمبيوتر أثناء الاستخدام.

يعتمد المحرك على تكامل تقني مباشر بين بروتوكول **Apple CoreDevice DDI** ونفق محلي معزول (**Internal Loopback Split-Tunnel NetworkExtension**)، مما يتيح حقن الإحداثيات مباشرة إلى خدمة الموقع المركزية (`locationd`) في نظام iOS بدقة واستقرار تام.

---

### ◈ واجهة التطبيق — Application Interface

<div align="center">
  <table>
    <tr>
      <th width="33%" align="center">الوضع الداكن (Dark Mode)</th>
      <th width="33%" align="center">الوضع الفاتح (Light Mode)</th>
      <th width="33%" align="center">English Interface</th>
    </tr>
    <tr>
      <td align="center"><img src="assets/screenshot-dark-ar.png" width="100%" alt="Locanger Dark Mode Arabic" /></td>
      <td align="center"><img src="assets/screenshot-light-ar.png" width="100%" alt="Locanger Light Mode Arabic" /></td>
      <td align="center"><img src="assets/screenshot-light-en.png" width="100%" alt="Locanger Light Mode English" /></td>
    </tr>
  </table>
</div>

---

### ◈ المواصفات الهندسية والمميزات — Key Features

- **✦ تثبيت الموقع والانتقال الفوري (Instant Teleportation)**  
  اختيار وتحديد أي موقع في العالم بلمسة واحدة والانتقال إليه فوراً بدقة عالية تصل إلى $\pm 5$ أمتار.

- **✦ محاكاة السرعة المتعددة (Multi-Speed Motion Simulation)**  
  محاكاة حركة واقعية للمسارات مع أنماط سرعة متعددة:
  - **نمط المشي (Walk)**: سرعة واقعية (1.2 م/ث — 4.3 كم/س).
  - **نمط الدراجة (Bike)**: سرعة متوسطة (4.5 م/ث — 16.0 كم/س).
  - **نمط السيارة (Car)**: سرعة تنقل قيادة (15.0 م/ث — 54.0 كم/س).
  - **نمط الطيران (Flight)**: سرعة تنقل فائقة للمسافات البعيدة (60.0 م/ث).

- **✦ مساعد البيانات الخلوية (Cellular Assistant)**  
  نظام تكيف ذكي يسمح بتثبيت وتأكيد إحداثيات الموقع حتى أثناء الاتصال بشبكات الهاتف الخلوية (4G / 5G) دون تشتت الإشارة مع أبراج التغطية، عبر تسلسل تهيئة سريع ومباشر.

- **✦ عصا التحكم الافتراضية العائمة (Floating Virtual Joystick)**  
  أداة تحكم سلسة على الشاشة تتيح المناورة واستكشاف المحيط في جميع الاتجاهات بزوايا دقيقة.

- **✦ نفق شبكة محلي آمن (Zero-Exposure Loopback Tunnel)**  
  نفق الـ VPN يعمل كلياً داخل عنوان الحلقة المحلية (`127.0.0.1`) لمخاطبة خدمات النظام فقط. لا يتم توجيه أو تسجيل أي حزم بيانات خارج جهازك، مما يحافظ على الخصوصية والسرعة الأصلية لاتصالك.

- **✦ لغة تصميم Apple Liquid Glass**  
  واجهات مستخدم مريحة للعين تدعم التباين العالي والتناغم اللوني الدقيق للوضعين الليلي والنهاري، مع دعم تلقائي كامل للغتين العربية والإنجليزية.

---

### ◈ طرق التثبيت والتشغيل — Installation

> [!TIP]
> يوصى باستخدام **TrollStore** للحصول على أفضل تجربة وتفعيل دائم دون الحاجة لإعادة التوقيع أسبوعياً.

#### 1. التثبيت عبر TrollStore (iOS 14.0 — 17.0)
1. حمّل ملف `Locanger.ipa` من [صفحة الإصدارات الرسمية](https://github.com/alibusut/Locanger-App/releases/latest).
2. افتح الملف واضغط **Share** ثم اختر **TrollStore**.
3. اضغط **Install**. التطبيق سيعمل بكامل صلاحياته مباشرة.

#### 2. التثبيت عبر AltStore / SideStore
1. حمّل ملف `Locanger.ipa` إلى تطبيق الملفات على جهازك.
2. افتح **AltStore** أو **SideStore** وانتقل إلى تبويب **My Apps**.
3. اضغط على أيقونة `+` واختر الملف لإتمام التوقيع والتثبيت.

#### 3. التثبيت عبر أدوات التوقيع الأخرى (Scarlet / LiveContainer / ESign)
- يدعم التطبيق التثبيت عبر الشهادات المباشرة وشهادات المطورين على كافة إصدارات iOS.

---

### ◈ آلية تثبيت الموقع عند استخدام البيانات الخلوية

```
[تحديد الموقع المطلوب] ──▸ [إيقاف البيانات الخلوية مؤقتاً] ──▸ [الضغط على تعيين الموقع] ──▸ [إعادة تشغيل البيانات]
```

1. **الخطوة الأولى**: حدد النقطة المراد محاكاتها على الخريطة.
2. **الخطوة الثانية**: في حال كنت متصلاً ببيانات الهاتف الخلوية، قم بإيقاف البيانات الخلوية مؤقتاً من مركز التحكم.
3. **الخطوة الثالثة**: اضغط على زر **تعيين الموقع** (أو **انتقال فوري**).
4. **الخطوة الرابعة**: أعد تشغيل البيانات الخلوية. سيبقى الموقع ثابتاً ومستقراً طوال فترة الاستخدام.

---

### ◈ الأمان والخصوصية — Privacy & Security

> [!NOTE]
> معالجة الإحداثيات وتوجيهها تتم بالكامل على معالج الجهاز (**On-Device Processing**). التطبيق لا يتصل بأي خوادم خارجية ولا يجمع أي معلومات تتعلق بالهوية أو النشاط أو سجل المواقع.

---

<div align="center">
  <sub>هندسة وتطوير: <b>Ali Latif (@alibusut)</b> • جميع الحقوق محفوظة</sub>
</div>
