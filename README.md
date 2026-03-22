# Legacy System Technical Revitalization | مشروع تأهيل الأنظمة القديمة 🐉

### Overview | نظرة عامة
This project documents the transformation of a legacy laptop from Windows 7 to a professional Kali Linux environment dedicated to network engineering.
يوثق هذا المشروع عملية تحويل حاسوب محمول قديم من نظام Windows 7 إلى بيئة عمل احترافية بنظام Kali Linux مخصصة لهندسة الشبكات.

---

### Technical Specifications | المواصفات التقنية
* **Legacy OS | النظام السابق:** Windows 7
* **Current OS | النظام الحالي:** Kali Linux (64-bit / amd64)
* **Objective | الهدف:** Building a mobile cybersecurity lab | بناء مختبر متنقل للأمن السيبراني

---

### Challenges & Solutions | التحديات والحلول

#### 1. Graphical Boot Issue | مشكلة الإقلاع الرسومي
The system encountered a "Black Screen" issue during boot due to legacy graphics driver incompatibility with the modern kernel.
واجه النظام صعوبة في تحميل الواجهة الرسومية (الشاشة السوداء) بسبب عدم توافق تعريفات كرت الشاشة القديم مع النواة الحديثة.

* **Solution | الحل:** Modified the GRUB bootloader by adding the `nomodeset` parameter to ensure GUI stability.
تم تعديل محمل الإقلاع (GRUB) وإضافة معامل `nomodeset` لضمان استقرار واجهة المستخدم.

#### 2. User Management & Security | إدارة المستخدمين والأمان
Transitioned from using the Root account to creating a dedicated **User** account to enhance security practices.
تم الانتقال من استخدام حساب الجذر (Root) إلى إنشاء حساب مستخدم (**User**) مخصص لتعزيز ممارسات الأمان.

* **Solution | الحل:** Created a new administrative **User**, granted `sudo` privileges, and configured a professional command-line interface.
إنشاء مستخدم إداري جديد ومنحه صلاحيات الإدارة `sudo` مع تهيئة واجهة الأوامر الاحترافية.

#### 3. Hostname Resolution Fix | إصلاح تعريف المضيف
Resolved local hostname resolution conflicts to improve command execution speed and system stability.
حل مشكلة التعارض في تعريف اسم الجهاز المحلي لتسريع تنفيذ الأوامر البرمجية وضمان استقرار النظام.

* **Solution | الحل:** Edited local configuration files to map the hostname to internal loopback addresses correctly.
تعديل ملفات التكوين المحلية لربط اسم الجهاز بالعناوين الداخلية بشكل صحيح.

---

### Current Capabilities | القدرات الحالية
The device is now equipped for network analysis and practicing cybersecurity skills through platforms like TryHackMe.
الجهاز مجهز الآن بكفاءة عالية لتحليل الشبكات وممارسة مهارات الأمن السيبراني عبر منصات مثل TryHackMe.

---

### Author | صاحب المشروع
**Abdullah Alshammari | عبدالله الشمري**
*Network Engineer | مهندس شبكات*
