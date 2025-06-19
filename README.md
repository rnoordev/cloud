#  Cloud-Based Document Analytics

هذا المشروع عبارة عن تطبيق ويب مبني باستخدام Flask يتيح رفع، تصنيف، فرز، والبحث في ملفات PDF وWord المخزّنة على السحابة محليًا.

## الوظائف الأساسية

**البحث** داخل النصوص باستخدام كلمات مفتاحية
**تصنيف المستندات** باستخدام نموذج Naive Bayes
**فرز المستندات** حسب العنوان
**عرض إحصائيات التخزين**



##  طريقة التشغيل (محليًا)

### 1. تثبيت المتطلبات


pip install -r requirements.txt


### 2. تشغيل الخادم


python app.py


ثم افتح المتصفح على:  
http://127.0.0.1:5000



##  هيكل المشروع


cloud_doc_analytics/
│
├── app.py                # ملف التطبيق الرئيسي
├── cloud_storage/        # مجلد المستندات المرفوعة
├── templates/            # ملفات HTML
├── requirements.txt      # المكتبات المطلوبة
└── README.md             # هذا الملف




##  تدريب النموذج

- توجه إلى  /train وأدخل التصنيفات للمستندات
- النموذج يتم حفظه في classifier.jobli



##  الأدوات المستخدمة

- Flask
- PyMuPDF
- python-docx
- scikit-learn
- joblib



##  ملاحظات

- جميع الملفات يتم حفظها محليًا في `cloud_storage`.





- Noor Yusuf – [GitHub Profile](https://github.com/rnoordev)
