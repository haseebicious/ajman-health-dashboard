# Ajman Health & Food Safety Dashboard

**Created by Haseeb Juma | Ajman University**

A dynamic, bilingual, and interactive dashboard built for the **Ajman Data Visualization Challenge 2025**. This project transforms official open data into a powerful tool for citizens, policymakers, and researchers to explore and understand the landscape of public health and food safety in Ajman.

[![Language: English/العربية](https://img.shields.io/badge/Language-English%20%2F%20%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-blue.svg)](https://haseebicious.github.io/ajman-health-dashboard/) [![Tech: HTML/CSS/JS](https://img.shields.io/badge/Tech-HTML%20%2F%20CSS%20%2F%20JS-orange.svg)](https://github.com/haseebicious/ajman-health-dashboard) [![Library: Chart.js](https://img.shields.io/badge/Library-Chart.js-red.svg)](https://www.chartjs.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

### [**View the Live Dashboard Here**](https://haseebicious.github.io/ajman-health-dashboard/) 

---

## 🌟 Key Features

This dashboard was engineered to be more than just a static report. It's an interactive journey through Ajman's public health data, designed with the user in mind.

*   **Interactive Year-Based Filtering:** A central dropdown control allows users to filter the entire dashboard by a specific year or view trends across all available years. This instantly tailors the data to the user's analytical needs.
*   **Dual-Mode Visualizations:** The charts are intelligently designed to be responsive to the year filter:
    *   **All Years View:** Displays powerful year-over-year trend lines, perfect for long-term strategic analysis.
    *   **Single Year View:** Automatically pivots the data to a detailed month-by-month breakdown, ideal for identifying seasonal patterns and short-term impacts.
*   **Seamless Bilingual Interface:** With a single click, the entire dashboard—from titles and labels to narratives and insights—flips between **English** and **Arabic (العربية)**, ensuring accessibility for all users.
*   **At-a-Glance KPI Metrics:** Key performance indicators are presented in clear, concise metric cards at the top, providing an immediate summary of the selected time period.
*   **Fully Responsive Design:** The dashboard is meticulously crafted to provide a seamless experience on any device, from a large desktop monitor to a smartphone.
*   **Custom Bilingual Tooltips:** Rich, interactive tooltips provide detailed data points and are fully translated when switching between English and Arabic.
*   **Verifiable and Credible Data:** To ensure full transparency and build trust, every chart includes a direct, clickable link to its original source on the official Ajman Data Portal.

---

## 🔬 Data-Driven Insights & Observed Patterns

By visualizing the data, we can uncover trends and patterns that are not obvious from raw numbers alone. This dashboard reveals several key insights into Ajman's health and safety operations:

1.  **Proactive Enforcement and Seasonality:** There is a clear correlation between the **number of shops inspected** and the volume of **confiscated products**. For example, in 2018 and 2019, significant spikes in confiscations directly followed periods of intensified inspections, demonstrating a proactive rather than reactive enforcement strategy. Furthermore, inspections often peak in the first and second quarters of the year.

2.  **Improving Food Safety Standards:** The "Food Laboratory Test Results" chart shows a positive long-term trend. When viewed across "All Years," the proportion of **'Fit'** samples has steadily increased while **'Unfit'** samples have declined. This suggests that regulatory efforts and industry compliance are successfully improving the safety of the food supply in Ajman.

3.  **Resilience During Global Disruptions:** The dashboard data for **2020** shows the clear impact of the COVID-19 pandemic. There was a noticeable dip in activities like food inspections and the issuance of export certificates during the second quarter (April-June), corresponding with global lockdowns. However, the data also shows a strong recovery in the latter half of the year, highlighting the resilience of Ajman's public health systems.

4.  **Targeted Violation Enforcement:** The "Warnings & Violations" chart consistently shows that **Companies** are the primary recipients of violations. This data-backed insight provides a clear direction for policymakers, suggesting that targeted awareness campaigns, workshops, and stricter enforcement for commercial entities could yield the most significant improvements in public health compliance.

---

## 💻 Technical Stack

The project is built with modern, accessible web technologies, ensuring it is lightweight, fast, and easy to maintain.

*   **HTML5:** For the core structure and content.
*   **CSS3:** For styling, responsiveness, and the modern visual aesthetic.
*   **JavaScript (ES6+):** For all interactivity, data processing, filtering, and dynamic chart rendering.
*   **Chart.js:** A powerful and flexible open-source library used to create all the interactive and responsive visualizations.
*   **No Frameworks:** The dashboard is built with vanilla JavaScript to ensure maximum performance and zero external dependencies.

---

## 📊 Data Sources

All datasets are sourced directly from the official **Ajman Data Portal**. Each visualization on the dashboard includes a direct link to its source.

| Dataset Name                                  | Local File                                         | Official Source URL                                                                                             |
| --------------------------------------------- | -------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Medical Certificates Issued                   | `data/medical-certificates-issued.json`            | [Link](https://data.ajman.ae/explore/dataset/health-certificates-for-food-export/information/)                  |
| Food Laboratory Test Results                  | `data/food-laboratory-test-results.json`           | [Link](https://data.ajman.ae/explore/dataset/food-laboratory-test-results/information/)                         |
| Confiscated Food & Health Products            | `data/confiscated-food-and-health-products.json`   | [Link](https://data.ajman.ae/explore/dataset/confiscated-food-and-health-products/information/)                 |
| Warnings and Public Health Violations         | `data/warnings-and-public-health-violations.json`  | [Link](https://data.ajman.ae/explore/dataset/warnings-and-public-health-violations/information/)                |
| Shops Visited                                 | `data/shops-visited.json`                          | [Link](https://data.ajman.ae/explore/dataset/shops-visited/information/)                                        |

### Data Processing Note
To improve visualization clarity, the "Shops" category within the "Warnings & Public Health Violations" dataset was excluded from its corresponding chart. This category contained null or zero values across all available years and its removal helps focus the analysis on more relevant data points.

---

## 🎯 Alignment with Ajman Vision 2030

This project directly supports the core pillars of the [Ajman Vision 2030](https://drive.google.com/file/d/117tCPxZFDSuK42dQhU_oRK0INWZ8Su2k/view) initiative:

*   **A Happy Society:** By providing transparent, accessible data on public health and food safety, this dashboard empowers citizens with knowledge and builds trust, contributing to community well-being and a higher quality of life.
*   **A Motivated and Engaged Government:** The interactive analytics enable evidence-based policymaking. Officials can use this tool to monitor trends, evaluate the effectiveness of campaigns, and allocate resources more efficiently, fostering government excellence.

---

## 🚀 How to Run Locally

To explore this project on your local machine, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/haseebicious/ajman-health-dashboard.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd ajman-health-dashboard
    ```
3.  **Open `index.html` in your browser:**
    You can simply double-click the `index.html` file, or if you are using a code editor with a live server (like VS Code's Live Server), you can run it through that.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---
---

<div dir="rtl" lang="ar">

# لوحة بيانات الصحة وسلامة الغذاء في عجمان (README.md - العربية)

**إعداد: حسيب جمعة | جامعة عجمان**

لوحة بيانات تفاعلية ديناميكية وثنائية اللغة، تم إنشاؤها خصيصًا **لتحدي عجمان لتصوير البيانات 2025**. يقوم هذا المشروع بتحويل البيانات الرسمية المفتوحة إلى أداة قوية للمواطنين وصناع السياسات والباحثين لاستكشاف وفهم مشهد الصحة العامة وسلامة الغذاء في إمارة عجمان.

[![اللغة: English/العربية](https://img.shields.io/badge/Language-English%20%2F%20%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-blue.svg)](https://haseebicious.github.io/ajman-health-dashboard/) [![التقنية: HTML/CSS/JS](https://img.shields.io/badge/Tech-HTML%20%2F%20CSS%20%2F%20JS-orange.svg)](https://github.com/haseebicious/ajman-health-dashboard) [![المكتبة: Chart.js](https://img.shields.io/badge/Library-Chart.js-red.svg)](https://www.chartjs.org/) [![الرخصة: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

### [**شاهد لوحة البيانات مباشرة من هنا**](https://haseebicious.github.io/ajman-health-dashboard/)

---

## 🌟 الميزات الرئيسية

تم تصميم لوحة البيانات هذه لتكون أكثر من مجرد تقرير ثابت؛ إنها رحلة تفاعلية عبر بيانات الصحة العامة في عجمان، مع التركيز على تجربة المستخدم.

*   **فلترة تفاعلية حسب السنة:** تتيح قائمة منسدلة مركزية للمستخدمين فلترة بيانات لوحة التحكم بأكملها حسب سنة معينة أو استعراض الاتجاهات عبر جميع السنوات المتاحة، مما يخصص عرض البيانات لاحتياجات المستخدم التحليلية.
*   **رسوم بيانية مزدوجة الوضع:** صُممت الرسوم البيانية بذكاء لتستجيب لفلتر السنة:
    *   **عرض جميع السنوات:** يعرض اتجاهات سنوية قوية، وهو مثالي للتحليل الاستراتيجي طويل الأمد.
    *   **عرض سنة واحدة:** يحول البيانات تلقائيًا إلى تفصيل شهري، مما يجعله مثاليًا لتحديد الأنماط الموسمية والتأثيرات قصيرة المدى.
*   **واجهة ثنائية اللغة بالكامل:** بنقرة واحدة، تتحول لوحة البيانات بأكملها — من العناوين والتسميات إلى الشروحات والأفكار — بين **الإنجليزية** و**العربية**، مما يضمن سهولة الوصول لجميع المستخدمين.
*   **مؤشرات أداء رئيسية سريعة:** تُعرض مؤشرات الأداء الرئيسية في بطاقات واضحة وموجزة في الأعلى، مما يوفر ملخصًا فوريًا للفترة الزمنية المحددة.
*   **تصميم متجاوب بالكامل:** تم تصميم لوحة البيانات بعناية لتوفر تجربة سلسة على أي جهاز، من شاشات سطح المكتب الكبيرة إلى الهواتف الذكية.
*   **تلميحات أدوات مخصصة ثنائية اللغة:** توفر تلميحات الأدوات التفاعلية والغنية نقاط بيانات مفصلة وتتم ترجمتها بالكامل عند التبديل بين اللغتين الإنجليزية والعربية.
*   **بيانات موثوقة ومُثبتة المصدر:** لضمان الشفافية الكاملة وبناء الثقة، يتضمن كل رسم بياني رابطًا مباشرًا وقابلاً للنقر إلى مصدره الأصلي على بوابة بيانات عجمان الرسمية.

---

## 🔬 رؤى وأنماط مستندة إلى البيانات

من خلال تصوير البيانات، يمكننا الكشف عن اتجاهات وأنماط لا تظهر بوضوح في الأرقام الأولية وحدها. تكشف لوحة البيانات هذه عن عدة رؤى رئيسية حول عمليات الصحة والسلامة في عجمان:

1.  **الإنفاذ الاستباقي والأنماط الموسمية:** هناك علاقة واضحة بين **عدد المحلات التي تم تفتيشها** وحجم **المنتجات المصادرة**. على سبيل المثال، في عامي 2018 و2019، تبعت الزيادات الكبيرة في المصادرات فترات من التفتيش المكثف، مما يظهر استراتيجية إنفاذ استباقية وليست مجرد رد فعل. علاوة على ذلك، تصل عمليات التفتيش غالبًا إلى ذروتها في الربعين الأول والثاني من العام.

2.  **تحسن معايير سلامة الغذاء:** يُظهر الرسم البياني لـ "نتائج اختبارات مختبر الأغذية" اتجاهًا إيجابيًا طويل الأمد. عند عرض "كل السنوات"، زادت نسبة العينات **"الصالحة"** بشكل مطرد بينما انخفضت نسبة العينات **"غير الصالحة"**. يشير هذا إلى أن الجهود التنظيمية وامتثال الصناعة ينجحان في تحسين سلامة الإمدادات الغذائية في عجمان.

3.  **المرونة أثناء الاضطرابات العالمية:** تُظهر بيانات عام **2020** التأثير الواضح لجائحة كوفيد-19. كان هناك انخفاض ملحوظ في أنشطة مثل تفتيش الأغذية وإصدار شهادات التصدير خلال الربع الثاني (أبريل-يونيو)، بالتزامن مع الإغلاقات العالمية. ومع ذلك، تُظهر البيانات أيضًا انتعاشًا قويًا في النصف الثاني من العام، مما يسلط الضوء على مرونة أنظمة الصحة العامة في عجمان.

4.  **إنفاذ المخالفات الموجه:** يُظهر الرسم البياني لـ "الإنذارات والمخالفات" باستمرار أن **الشركات** هي المتلقي الرئيسي للمخالفات. توفر هذه الرؤية المدعومة بالبيانات توجيهًا واضحًا لصانعي السياسات، حيث تشير إلى أن الحملات التوعوية الموجهة وورش العمل والإنفاذ الأكثر صرامة للكيانات التجارية يمكن أن تحقق أهم التحسينات في الامتثال للصحة العامة.

---

## 💻 الحزمة التقنية

تم بناء المشروع باستخدام تقنيات ويب حديثة وسهلة الوصول، مما يضمن أنه خفيف الوزن وسريع وسهل الصيانة.

*   **HTML5:** للهيكل والمحتوى الأساسي.
*   **CSS3:** للتصميم، والاستجابة، والجمالية البصرية الحديثة.
*   **JavaScript (ES6+):** لجميع التفاعلات، ومعالجة البيانات، والفلترة، وعرض الرسوم البيانية الديناميكية.
*   **Chart.js:** مكتبة قوية ومرنة ومفتوحة المصدر تُستخدم لإنشاء جميع التصورات التفاعلية والمتجاوبة.
*   **بدون أطر عمل (No Frameworks):** تم بناء لوحة البيانات باستخدام JavaScript الخام لضمان أقصى أداء وعدم وجود أي تبعيات خارجية.

---

## 📊 مصادر البيانات

جميع مجموعات البيانات مأخوذة مباشرة من **بوابة بيانات عجمان** الرسمية. يتضمن كل تصور في لوحة البيانات رابطًا مباشرًا إلى مصدره.

| اسم مجموعة البيانات                       | الملف المحلي                                      | رابط المصدر الرسمي                                                                                             |
| ------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| الشهادات الصحية الصادرة                   | `data/medical-certificates-issued.json`            | [الرابط](https://data.ajman.ae/explore/dataset/health-certificates-for-food-export/information/)                 |
| نتائج اختبارات مختبر الأغذية                | `data/food-laboratory-test-results.json`           | [الرابط](https://data.ajman.ae/explore/dataset/food-laboratory-test-results/information/)                      |
| المواد الغذائية والمنتجات الصحية المصادرة    | `data/confiscated-food-and-health-products.json`   | [الرابط](https://data.ajman.ae/explore/dataset/confiscated-food-and-health-products/information/)              |
| الإنذارات والمخالفات الصحية العامة         | `data/warnings-and-public-health-violations.json`  | [الرابط](https://data.ajman.ae/explore/dataset/warnings-and-public-health-violations/information/)             |
| المحلات التي تمت زيارتها للتفتيش            | `data/shops-visited.json`                          | [الرابط](https://data.ajman.ae/explore/dataset/shops-visited/information/)                                     |

### ملاحظة حول معالجة البيانات
لتحسين وضوح التصور البياني، تم استبعاد فئة "المحلات التجارية" من مجموعة بيانات "الإنذارات والمخالفات الصحية العامة" من الرسم البياني الخاص بها. احتوت هذه الفئة على قيم فارغة أو صفرية عبر جميع السنوات المتاحة، وتساعد إزالتها في تركيز التحليل على نقاط البيانات الأكثر صلة.

---

## 🎯 التوافق مع رؤية عجمان 2030

يدعم هذا المشروع بشكل مباشر الركائز الأساسية لمبادرة [رؤية عجمان 2030](https://drive.google.com/file/d/117tCPxZFDSuK42dQhU_oRK0INWZ8Su2k/view):

*   **مجتمع سعيد:** من خلال توفير بيانات شفافة وسهلة الوصول حول الصحة العامة وسلامة الغذاء، تمكّن لوحة البيانات هذه المواطنين بالمعرفة وتبني الثقة، مما يساهم في رفاهية المجتمع وجودة حياة أفضل.
*   **حكومة متميزة:** تُمكّن التحليلات التفاعلية من وضع سياسات قائمة على الأدلة. يمكن للمسؤولين استخدام هذه الأداة لمراقبة الاتجاهات وتقييم فعالية الحملات وتخصيص الموارد بكفاءة أكبر، مما يعزز التميز الحكومي.

---

## 🚀 كيفية تشغيل المشروع محليًا

لاستكشاف هذا المشروع على جهازك المحلي، اتبع هذه الخطوات البسيطة:

1.  **استنسخ المستودع (Clone the repository):**
    ```bash
    git clone https://github.com/haseebicious/ajman-health-dashboard.git
    ```
2.  **انتقل إلى مجلد المشروع:**
    ```bash
    cd ajman-health-dashboard
    ```
3.  **افتح ملف `index.html` في متصفحك:**
    يمكنك ببساطة النقر المزدوج على ملف `index.html`، أو إذا كنت تستخدم محرر أكواد مع خادم مباشر (مثل Live Server في VS Code)، فيمكنك تشغيله من خلاله.

---

## 📜 الرخصة

هذا المشروع مرخص بموجب **رخصة MIT**. انظر ملف `LICENSE` لمزيد من التفاصيل.

</div>
