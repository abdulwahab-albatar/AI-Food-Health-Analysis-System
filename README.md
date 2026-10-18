# FoodHealth
## Intelligent Food Product Analysis and Health Suitability Assessment System

### 1. Project Overview

FoodHealth is an intelligent software project designed to analyze food products and assess their health suitability using food product data, nutritional information, ingredients, and artificial intelligence techniques where implemented.

The system aims to help users explore food products, review their available nutritional information, and understand the health assessment provided by the application.

The project includes a source-code application, a desktop application package, a final project report, screenshots documenting the running system, and a Python dependency file.

**Important:** The system's assessments are intended for informational purposes and should not replace professional medical or nutritional advice.

---

### 2. Project Files and Folders

The project contains the following main files and folders.

#### A. `app.py` — Main Application

This file serves as the main application entry point when configured to run the Flask application.

It initializes the application and connects the required routes and services.

**How to open it:**
1. Open the project directory.
2. Locate `app.py`.
3. Open it using Visual Studio Code or another Python code editor.
4. Review or modify the source code as needed.

#### B. `FoodHealth_Final_Project_Report.docx` — Final Project Report

This document contains the project's academic report.

It can be used to review the project description, objectives, design, implementation, and results documented in the report.

**How to open it:**
1. Locate `FoodHealth_Final_Project_Report.docx`.
2. Double-click the file.
3. Open it with Microsoft Word or another compatible DOCX application.

#### C. `FoodHealth_Desktop_Application` — Desktop Application

This folder contains the packaged desktop version of FoodHealth.

It is intended to provide a convenient way to run the application on compatible Windows computers.

**How to run it:**
1. Open the `FoodHealth_Desktop_Application` folder.
2. Locate `FoodHealth.exe`, if present.
3. Double-click the executable.
4. Wait for the application interface to appear.

The application may require additional bundled files, network access, or external service configuration, depending on how it was packaged.

#### D. `Running_System_Screenshots` — Application Screenshots

This folder contains screenshots documenting the application interfaces while the system is running.

These images can be used for project documentation, demonstrations, presentations, and academic discussions.

**How to view the screenshots:**
1. Open `Running_System_Screenshots`.
2. Select an image.
3. Double-click it to open it in the default image viewer.

#### E. `requirements.txt` — Python Dependencies

This file lists Python packages and their versions when generated from the project's Python environment.

It helps developers recreate the software environment required to run or modify the source code.

The development environment used for this project runs Python 3.9.25.

**How to view the file:**
1. Locate `requirements.txt`.
2. Open it with Notepad or Visual Studio Code.
3. Review the package names and version numbers.

---

### 3. Running the Source Code

To run the application from its Python source code:

1. Install a compatible Python environment.
2. Open Anaconda Prompt.
3. Activate the appropriate Conda environment.
4. Navigate to the project directory.
5. Install the required dependencies.
6. Configure the necessary environment variables and external services.
7. Start the application.

Example commands:

```bash
conda activate foodhealth
```

Navigate to the project directory:

```bat
cd /d "D:\AI\Code\نظام ذكي لتحليل المنتجات الغذائية وتقييم ملاءمتها الصحية باستخدام الذكاء الاصطناعي\foodhealth"
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

These commands assume that the Conda environment already exists and that `app.py` is the correct entry point.

The project may require additional configuration, including database credentials and environment variables, before it can run successfully.

---

### 4. Running the Desktop Application

To run the packaged desktop application on a Windows computer:

1. Copy the `FoodHealth_Desktop_Application` folder to the target computer.
2. Open the folder.
3. Locate `FoodHealth.exe`.
4. Double-click the executable.
5. Ensure that any required external services are available.

If the application connects to a cloud database, an internet connection and valid configuration may be necessary.

A properly packaged PyInstaller application can generally run without a separate Python installation, provided that all required dependencies and supporting files are included.

---

### 5. Opening and Modifying the Source Code

Developers can use Visual Studio Code or another compatible Python editor.

Recommended procedure:

1. Open the main project directory in the editor.
2. Open `app.py` to review the application entry point.
3. Explore the `routes`, `services`, and `utils` directories if present.
4. Review the configuration and database-related files.
5. Make the required changes.
6. Save the modified files.
7. Run and test the application.

Always create a backup before making significant changes.

Do not publish database credentials, API keys, or other secrets contained in environment configuration files.

---

### 6. Python Environment and Dependencies

The project's development environment uses Python 3.9.25.

The `requirements.txt` file can be used to install the listed packages:

```bash
python -m pip install -r requirements.txt
```

For a new computer, create or configure a compatible Python environment before installing the dependencies.

The dependency file does not include the project's source code, product dataset, database contents, or secret configuration values.

---

### 7. Project Demonstration and Academic Presentation

For an academic demonstration, the following sequence is recommended:

1. Present `FoodHealth_Final_Project_Report.docx` to explain the project objectives and design.
2. Open `Running_System_Screenshots` to show the documented interfaces.
3. Run the desktop application to demonstrate its available features.
4. Review `app.py` and the relevant source-code modules.
5. Present `requirements.txt` to document the Python dependencies.
6. Explain the dataset, preprocessing, algorithms, training, testing, and evaluation based on the actual implementation.

Algorithm names, model performance, and dataset sources should be reported only when supported by the project's source code and experimental records.

---

### 8. Important Notes

- Keep backup copies of the source code and project data.
- Protect all database credentials and API keys.
- Verify the required configuration before running the application on another computer.
- Keep the source code separate from the packaged desktop application.
- Review the nutritional data and assessment logic before relying on the system's results.
- The application provides informational support and does not replace professional medical advice.

---

### 9. Conclusion

FoodHealth is a software project focused on food product analysis and health suitability assessment.

Its source code supports development and maintenance, the desktop package provides a convenient execution option, the final report documents the academic work, the screenshots demonstrate the running interfaces, and the dependency file helps developers prepare the Python environment.

Together, these resources support project operation, documentation, demonstration, and future development.




عربي..
# مشروع نظام ذكي لتحليل المنتجات الغذائية وتقييم ملاءمتها الصحية باستخدام الذكاء الاصطناعي
**FoodHealth — Intelligent Food Product Analysis and Health Suitability Assessment System**

## 1. نبذة عن المشروع

يهدف مشروع FoodHealth إلى تطوير نظام ذكي يساعد المستخدم على تحليل المنتجات الغذائية وتقييم مدى ملاءمتها الصحية بالاعتماد على البيانات الغذائية ومكونات المنتجات وتقنيات الذكاء الاصطناعي.

يوفر النظام واجهة استخدام تسهّل التعامل مع المنتجات الغذائية واستعراض بياناتها والاستفادة من نتائج التحليل والتقييم الصحي التي يقدمها النظام.

يتكون المشروع من تطبيق برمجي، وملفات الكود المصدري، وتقرير المشروع، وصور توثيقية لواجهات النظام أثناء التشغيل، وملف يوثق مكتبات Python المستخدمة في بيئة المشروع.

**ملاحظة:** نتائج التقييم التي يقدمها النظام هي معلومات مساعدة وليست بديلًا عن الاستشارة الطبية أو التقييم الغذائي المتخصص.

## 2. مكونات المشروع وملفاته

يتضمن المشروع الملفات والمجلدات التالية:

### أولًا: `app`

يمثل هذا الاسم تطبيق المشروع أو ملف تشغيل التطبيق المصدري، بحسب امتداد الملف الموجود داخل المجلد.

إذا كان الملف هو `app.py`، فإنه يمثل نقطة الدخول الرئيسية لتشغيل تطبيق Python، ويتولى إنشاء التطبيق وربط المسارات والخدمات اللازمة لعمل النظام.

**طريقة الوصول إليه:**
1. افتح مجلد المشروع الرئيسي.
2. ابحث عن الملف `app.py`.
3. افتحه باستخدام محرر أكواد مثل Visual Studio Code.
4. استعرض الكود المصدري أو عدّله عند الحاجة.

لا يُنصح بتعديل الكود المصدري دون فهم تأثير التغييرات على بقية ملفات المشروع.

### ثانيًا: `FoodHealth_Final_Project_Report.docx`

هذا هو ملف التقرير النهائي للمشروع، ويُستخدم لتوثيق فكرة المشروع وأهدافه ومكوناته وطريقة عمله والنتائج التي تم التوصل إليها.

**طريقة فتح التقرير:**
1. افتح مجلد المشروع.
2. ابحث عن الملف `FoodHealth_Final_Project_Report.docx`.
3. انقر عليه نقرًا مزدوجًا لفتحه باستخدام Microsoft Word أو برنامج متوافق مع ملفات DOCX.
4. استعرض محتويات التقرير أو اطبعه عند الحاجة.

### ثالثًا: `FoodHealth_Desktop_Application`

هذا المجلد مخصص لنسخة برنامج سطح المكتب التي جرى تجهيزها للتشغيل على أجهزة Windows.

قد يحتوي المجلد على الملف التنفيذي `FoodHealth.exe`، إضافة إلى ملفات أخرى يحتاج إليها البرنامج.

**طريقة تشغيل البرنامج:**
1. افتح مجلد `FoodHealth_Desktop_Application`.
2. ابحث عن الملف `FoodHealth.exe`.
3. انقر عليه نقرًا مزدوجًا لتشغيل البرنامج.
4. انتظر حتى تظهر واجهة النظام.
5. استخدم الواجهة للوصول إلى وظائف المشروع المتاحة.

إذا لم يعمل البرنامج، فتحقق من وجود الملفات المطلوبة معه، ومن توافقه مع نظام التشغيل، ومن متطلبات الاتصال بقاعدة البيانات إن كان يعتمد على خدمة خارجية.

لا تفترض أن الملف التنفيذي سيعمل على كل جهاز دون إعداد؛ فقد يحتاج إلى ملفات إضافية أو اتصال شبكي أو إعدادات بيئة مناسبة.

### رابعًا: `Running_System_Screenshots`

هذا المجلد مخصص لحفظ صور توثيقية لواجهات المشروع أثناء تشغيل النظام فعليًا.

توضح هذه الصور شكل الواجهات وطريقة ظهور عناصر النظام أثناء الاستخدام، وتساعد في توثيق الجانب العملي من المشروع.

**طريقة استعراض الصور:**
1. افتح المجلد `Running_System_Screenshots`.
2. اختر الصورة التي تريد مشاهدتها.
3. انقر عليها نقرًا مزدوجًا لفتحها باستخدام عارض الصور.
4. انتقل بين الصور لمشاهدة واجهات النظام المختلفة.

يمكن استخدام هذه الصور في التقرير النهائي أو أثناء عرض المشروع ومناقشته.

### خامسًا: `requirements.txt`

يحتوي هذا الملف على أسماء مكتبات Python وإصداراتها المسجلة في بيئة المشروع، إذا جرى إنشاؤه باستخدام الأمر `pip freeze`.

يساعد الملف في إعادة تجهيز بيئة التطوير وتثبيت المكتبات المطلوبة لتشغيل الكود المصدري وتعديله.

**طريقة فتح الملف:**
1. افتح مجلد المشروع.
2. انقر بزر الفأرة الأيمن على `requirements.txt`.
3. اختر فتح باستخدام Notepad أو Visual Studio Code.
4. استعرض أسماء المكتبات وإصداراتها.

**طريقة تثبيت المكتبات عند تجهيز بيئة التطوير:**

بعد تثبيت Python أو Anaconda وتجهيز البيئة المناسبة، افتح Anaconda Prompt ونفّذ:

```bash
conda activate foodhealth
```

انتقل إلى مجلد المشروع:

```bat
cd /d "D:\AI\Code\نظام ذكي لتحليل المنتجات الغذائية وتقييم ملاءمتها الصحية باستخدام الذكاء الاصطناعي\foodhealth"
```

ثم ثبّت المكتبات:

```bash
python -m pip install -r requirements.txt
```

يجب تنفيذ هذه الخطوات داخل البيئة المناسبة للمشروع. وقد تحتاج إلى إنشاء البيئة أولًا إذا لم تكن موجودة على الجهاز الجديد.

## 3. إرشادات تشغيل المشروع من الكود المصدري

إذا أردت تشغيل التطبيق من ملفات Python بدلًا من النسخة التنفيذية، فاتبع الخطوات التالية:

1. ثبّت Python بالإصدار المتوافق مع المشروع، وهو Python 3.9.25 في بيئة التطوير التي جرى التحقق منها.
2. جهّز بيئة Python المناسبة وثبّت المكتبات الواردة في `requirements.txt`.
3. افتح مجلد المشروع باستخدام Visual Studio Code أو محرر أكواد آخر.
4. تأكد من وجود ملف الإعدادات ومتغيرات البيئة المطلوبة.
5. تأكد من إعداد الاتصال بقاعدة البيانات والخدمات الخارجية التي يعتمد عليها المشروع.
6. افتح الطرفية داخل مجلد المشروع.
7. فعّل البيئة الافتراضية المناسبة.
8. شغّل التطبيق باستخدام الأمر:

```bash
python app.py
```

قد تختلف طريقة التشغيل بحسب إعدادات التطبيق الفعلية. وإذا كان المشروع يستخدم ملفًا آخر كنقطة دخول، فيجب تشغيل الملف المحدد في إعدادات المشروع.

## 4. إرشادات تعديل الكود المصدري

لإجراء تعديلات على المشروع:

1. افتح مجلد المشروع في Visual Studio Code.
2. افتح ملف `app.py` لمراجعة نقطة الدخول الرئيسية.
3. استعرض مجلدات المشروع، مثل `routes` و`services` و`utils`، إذا كانت موجودة.
4. راجع ملفات الإعدادات وقاعدة البيانات قبل تعديلها.
5. احفظ التعديلات بعد الانتهاء.
6. شغّل التطبيق واختبر الوظائف المتأثرة بالتعديل.
7. احتفظ بنسخة احتياطية قبل إجراء تغييرات كبيرة.

يجب عدم حذف ملفات الخدمات أو قواعد البيانات أو ملفات الإعدادات دون التأكد من عدم اعتماد أجزاء أخرى من المشروع عليها.

## 5. تشغيل نسخة سطح المكتب على جهاز آخر

لتشغيل نسخة سطح المكتب على جهاز Windows آخر:

1. انسخ مجلد `FoodHealth_Desktop_Application` إلى الجهاز المطلوب.
2. افتح المجلد.
3. شغّل `FoodHealth.exe`.
4. تأكد من توفر الاتصال بالإنترنت إذا كان النظام يعتمد على قاعدة بيانات سحابية.
5. إذا ظهرت رسالة خطأ، فتحقق من الملفات المصاحبة للبرنامج وإعدادات الاتصال ومتطلبات التشغيل.

إذا جُمّع البرنامج باستخدام PyInstaller بطريقة صحيحة، فقد لا يحتاج المستخدم النهائي إلى تثبيت Python بصورة منفصلة، لكن ذلك يعتمد على طريقة التجميع والملفات والاعتماديات التي يتطلبها التطبيق.

## 6. إرشادات استعراض المشروع ومناقشته

عند تقديم المشروع أو مناقشته أكاديميًا، يُنصح باتباع الترتيب التالي:

1. ابدأ بعرض `FoodHealth_Final_Project_Report.docx` لتوضيح فكرة المشروع وأهدافه.
2. افتح `Running_System_Screenshots` لعرض صور الواجهات.
3. شغّل `FoodHealth.exe` لعرض التطبيق عمليًا.
4. افتح `app.py` لشرح البنية البرمجية وطريقة تشغيل النظام.
5. اعرض `requirements.txt` لتوضيح مكتبات Python وإصداراتها المسجلة.
6. اشرح طريقة تخزين البيانات ومعالجتها والخوارزمية المستخدمة استنادًا إلى الكود الفعلي وملفات التدريب.

## 7. ملاحظات مهمة للمستخدم

- لا تشارك كلمات المرور أو مفاتيح الاتصال الموجودة في ملفات الإعدادات.
- لا تعدّل قاعدة البيانات أو ملفات النموذج دون الاحتفاظ بنسخة احتياطية.
- احرص على الاحتفاظ بنسخة من الكود المصدري، وليس الملف التنفيذي وحده.
- ملف `requirements.txt` يوثق المكتبات، لكنه لا يحتوي على الكود المصدري أو بيانات المنتجات نفسها.
- صور الواجهات توثّق شكل التطبيق، لكنها لا تغني عن تشغيل البرنامج واختباره.
- يجب التحقق من سلامة البيانات ودقة النتائج قبل الاعتماد عليها في اتخاذ قرارات غذائية مهمة.

## 8. الخلاصة

يجمع مشروع FoodHealth بين التطبيق البرمجي وملفات التطوير والتوثيق الأكاديمي والتوثيق المرئي لواجهات النظام.

يوفر التقرير النهائي شرحًا للمشروع، بينما تتيح نسخة سطح المكتب تشغيل النظام، وتساعد صور الواجهات على توثيق تجربته العملية، ويتيح الكود المصدري إجراء التعديلات والتطوير، ويُستخدم ملف `requirements.txt` لتجهيز بيئة Python المناسبة.

وبذلك يمكن للمستخدم استعراض المشروع وتشغيله ومراجعة مكوناته والاستعداد لعرضه ومناقشته أكاديميًا.
