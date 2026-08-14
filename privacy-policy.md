# سياسة الخصوصية — ذاكر و حل (Study & Solve)

**تاريخ السريان:** 2026-08-01  
**آخر تحديث:** 2026-08-14

## 1. مقدمة

تطبيق **ذاكر و حل (Study & Solve)** هو منصة تعليمية مخصصة للطلاب.

توضح سياسة الخصوصية هذه أنواع البيانات التي نقوم بجمعها، وكيف نستخدمها ونحميها، والحقوق المتاحة للمستخدمين، وكيف يمكن التواصل معنا أو طلب حذف الحساب والبيانات المرتبطة به.

---

## 2. البيانات التي نجمعها

| الفئة | البيانات | الغرض |
|---|---|---|
| **بيانات الحساب** | الاسم، البريد الإلكتروني، رقم الهاتف | إنشاء الحساب وتأمينه والتواصل بشأن حالة الاشتراك |
| **بيانات الجهاز** | Android Build ID، طراز الجهاز، الشركة المصنعة، اسم الجهاز البرمجي (Codename) | ربط الحساب بجهاز موثوق واحد للمساعدة في منع مشاركة الحساب |
| **النشاط التعليمي** | إجابات الاختبارات، الدرجات، أوقات المحاولات | عرض تقدم المستخدم ونتائج الاختبارات |
| **الاشتراك** | قائمة المحتوى أو التسجيلات، تاريخ انتهاء الاشتراك | إتاحة المحتوى المميز |
| **بيانات الأعطال والتشخيص** | سجلات Firebase التشخيصية (ولا تتضمن معلومات شخصية في إصدارات الإنتاج) | تحسين استقرار التطبيق واكتشاف الأخطاء |

---

## 3. البيانات التي لا نجمعها

لا نقوم بجمع:

- ❌ معلومات بطاقات الدفع
- ❌ الموقع الجغرافي الدقيق
- ❌ جهات الاتصال
- ❌ الصور أو ملفات المستخدم الشخصية
- ❌ محتوى الميكروفون أو الكاميرا
- ❌ معرّفات الإعلانات

---

## 4. مشاركة البيانات

نحن **لا نبيع بيانات المستخدمين**.

قد تتم معالجة البيانات من خلال الخدمات التالية عند الحاجة لتشغيل التطبيق:

- **Google Firebase** (Authentication, Firestore, Functions, App Check) — لتوفير خدمات المصادقة وقاعدة البيانات والوظائف والحماية.
- **WhatsApp / Telegram** — فقط عندما يختار المستخدم التواصل معنا من خلال إحدى هذه الوسائل. عندها يتم فتح تطبيق المراسلة باستخدام رسالة معدة مسبقًا تحتوي على المعلومات اللازمة للتعرف على صاحب الطلب، ويقوم المستخدم بنفسه بإرسال الرسالة.

لا نقوم بإرسال بيانات المستخدم إلى WhatsApp أو Telegram دون إجراء من المستخدم.

---

## 5. حماية البيانات

نطبق إجراءات تقنية مناسبة للمساعدة في حماية بيانات المستخدم، وتشمل:

- تشفير البيانات أثناء النقل باستخدام HTTPS/TLS.
- استخدام قواعد وصول في Firestore لتقييد الوصول إلى البيانات وفقًا للصلاحيات.
- تنفيذ عمليات تصحيح نتائج الاختبارات الحساسة على الخادم عند الحاجة.
- استخدام Firebase App Check للمساعدة في منع الوصول غير المصرح به والطلبات الآلية الضارة.

---

## 6. حقوق المستخدم

يحق للمستخدم طلب:

- الوصول إلى بياناته.
- تصحيح بياناته.
- حذف حسابه وبياناته الشخصية المرتبطة به.

يمكن تقديم طلب الحذف أو أي طلب متعلق بالبيانات باستخدام وسائل التواصل الموضحة في قسم **حذف الحساب والبيانات** أدناه.

---

# 7. حذف الحساب والبيانات

يمكن للمستخدم في أي وقت طلب **حذف حسابه والبيانات الشخصية المرتبطة به**.

لإرسال طلب حذف الحساب والبيانات، يرجى التواصل معنا باستخدام إحدى وسائل التواصل التالية:

- **WhatsApp**
- **Telegram**
- **البريد الإلكتروني**

عند إرسال طلب الحذف، يرجى تضمين المعلومات التالية للمساعدة في التحقق من ملكية الحساب:

- الاسم المسجل في الحساب
- البريد الإلكتروني المرتبط بالحساب
- رقم الهاتف المرتبط بالحساب، إن وجد

بعد استلام الطلب، نقوم بمراجعة الطلب والتحقق من ملكية الحساب، ثم نبدأ عملية حذف الحساب والبيانات المرتبطة به.

**سيتم تنفيذ طلب الحذف خلال مدة تصل إلى 30 يومًا من تاريخ استلام الطلب والتحقق منه.**

قد يتم الاحتفاظ ببيانات محدودة بعد حذف الحساب إذا كان الاحتفاظ بها مطلوبًا بموجب القانون، أو كان ضروريًا للامتثال لالتزام قانوني، أو لأغراض أمنية ومكافحة الاحتيال، أو لحل النزاعات والمطالبات القانونية. وفي هذه الحالات، يتم الاحتفاظ فقط بالبيانات اللازمة للغرض المحدد ووفقًا للمتطلبات القانونية المعمول بها.

### معلومات مهمة

طلب حذف الحساب والبيانات هو إجراء نهائي، وقد يؤدي إلى فقدان الوصول إلى:

- الحساب
- سجل التقدم والنتائج
- محاولات الاختبارات
- المحتوى أو المزايا المرتبطة بالحساب

بعد اكتمال عملية الحذف، قد لا يكون من الممكن استعادة هذه البيانات.

---

## 8. خصوصية الأطفال

يستهدف التطبيق الطلاب، ولكنه **ليس موجهًا بشكل خاص إلى الأطفال الذين تقل أعمارهم عن 13 عامًا**.

لا نجمع عن قصد بيانات شخصية من أطفال تقل أعمارهم عن 13 عامًا.

إذا علمنا أن طفلًا دون سن 13 عامًا قدم بيانات شخصية دون الحصول على الموافقات المطلوبة، فسنتخذ الإجراءات المناسبة لحذف هذه البيانات.

---

## 9. التواصل معنا

للاستفسارات المتعلقة بالخصوصية أو طلب الوصول إلى البيانات أو تصحيحها أو حذفها، يمكنك التواصل معنا باستخدام إحدى وسائل التواصل التالية:

- **WhatsApp:** متاح من خلال تطبيق **ذاكر و حل → الإعدادات → التواصل**
- **Telegram:** متاح من خلال تطبيق **ذاكر و حل → الإعدادات → التواصل**
- **البريد الإلكتروني:** `studyandsolve.egypt@gmail.com`

عند تقديم طلب متعلق بالحساب أو البيانات، قد نطلب معلومات إضافية للتحقق من ملكية الحساب وحماية بيانات المستخدم من طلبات الحذف غير المصرح بها.

---

# 10. تحديث سياسة الخصوصية

قد نقوم بتحديث سياسة الخصوصية هذه من وقت لآخر لتعكس التغييرات في التطبيق أو الخدمات المستخدمة أو المتطلبات القانونية.

سيتم نشر أي تحديثات على هذه الصفحة مع تحديث تاريخ **"آخر تحديث"** في أعلى الصفحة.

---

# English Version

# Privacy Policy — Study & Solve (ذاكر و حل)

**Effective date:** 2026-08-01  
**Last updated:** 2026-08-14

## 1. Introduction

**Study & Solve (ذاكر و حل)** is an educational platform designed for students.

This Privacy Policy explains what data we collect, how we use and protect it, what rights are available to users, and how users can contact us or request deletion of their account and associated data.

---

## 2. Data We Collect

| Category | Data | Purpose |
|---|---|---|
| **Account identity** | Name, Email address, Phone number | Create and secure your account and communicate subscription status |
| **Device information** | Android Build ID, device model, manufacturer, software codename | Bind your account to one trusted device to help prevent account sharing |
| **Learning activity** | Quiz answers, scores, attempt times | Show your learning progress and quiz results |
| **Subscription** | Enrollment list, subscription expiry date | Unlock premium content |
| **Crash & diagnostics** | Firebase diagnostic logs (no personal information in production builds) | Stability monitoring and error detection |

---

## 3. What We Do NOT Collect

We do not collect:

- ❌ Payment card information
- ❌ Precise location
- ❌ Contacts
- ❌ Photos or personal files
- ❌ Microphone or camera content
- ❌ Advertising identifiers

---

## 4. Data Sharing

We **do not sell user data**.

Data may be processed through the following services when necessary to operate the application:

- **Google Firebase** (Authentication, Firestore, Functions, App Check) — for authentication, database, server-side functionality, and application protection.
- **WhatsApp / Telegram** — only when the user chooses to contact us through one of these services. The messaging application is opened with a prepared message containing the information necessary to identify the account holder, and the user actively sends the message.

We do not send user information to WhatsApp or Telegram without an action initiated by the user.

---

## 5. Data Security

We implement appropriate technical measures to help protect user data, including:

- Encryption of data in transit using HTTPS/TLS.
- Firestore access controls that restrict access according to permissions.
- Server-side processing of sensitive quiz-grading operations where applicable.
- Firebase App Check to help prevent unauthorized access and malicious automated requests.

---

## 6. Your Rights

You may request:

- Access to your data.
- Correction of your data.
- Deletion of your account and associated personal data.

You can submit a deletion request or any data-related request using the contact methods described in the **Account & Data Deletion** section below.

---

# 7. Account & Data Deletion

You may request **deletion of your account and associated personal data at any time**.

To submit an account and data deletion request, please contact us using one of the following methods:

- **WhatsApp**
- **Telegram**
- **Email**

When submitting a deletion request, please include the following information to help us verify account ownership:

- Name registered on the account
- Email address associated with the account
- Phone number associated with the account, if applicable

After receiving the request, we will review it and verify account ownership before starting the account and data deletion process.

**The deletion request will be processed within up to 30 days from the date the request is received and account ownership is successfully verified.**

We may retain limited information after account deletion if retention is required by law, necessary to comply with a legal obligation, necessary for security and fraud prevention, or necessary to resolve disputes or legal claims. In such cases, only the information necessary for the specific purpose will be retained and handled according to applicable legal requirements.

### Important Information

Account and data deletion is a permanent action and may result in the loss of access to:

- Your account
- Learning progress and results
- Quiz attempts
- Content or features associated with your account

Once the deletion process has been completed, this information may not be recoverable.

---

## 8. Children's Privacy

The application is intended for students but is **not specifically directed at children under the age of 13**.

We do not knowingly collect personal information from children under 13.

If we become aware that a child under 13 has provided personal information without the required consent, we will take appropriate steps to delete that information.

---

## 9. Contact Us

For privacy questions or requests to access, correct, or delete your data, you can contact us using any of the following methods:

- **WhatsApp:** Available through **Study & Solve → Settings → Contact**
- **Telegram:** Available through **Study & Solve → Settings → Contact**
- **Email:** `studyandsolve.egypt@gmail.com`

For account or data-related requests, we may ask for additional information to verify account ownership and protect user data against unauthorized deletion requests.

---

## 10. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes to the application, services we use, or applicable legal requirements.

Any updates will be published on this page, and the **"Last updated"** date at the top of the policy will be updated accordingly.
