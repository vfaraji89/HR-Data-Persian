# HR-Data-Persian
**الگوی ساختار داده در منابع انسانی**

شماتیک داده های منابع انسانی برای جمع آوری، تحلیل و یا بازطراحی سیستم یا محصول داده منابع انسانی


این داده ها می‌توانند در سیستم های منابع انسانی ذخیره و مدیریت شوند، اما باید توجه داشت که داده های منابع انسانی به سیستم های منابع انسانی محدود نمی‌شوند.

داده های منابع انسانی می‌توانند به طرق مختلفی استفاده شوند، مانند مدیریت مهارت ها، مدیریت عملکرد و بازخورد، برنامه ریزی منابع انسانی، آموزش و توسعه، مدیریت حقوق و دستمزد و .... 
ولی مهم ترین اتصال داده منابع انسانی باید با وضعیت شرکت و شرایط اقتصادی همسو باشد. در نتیجه می‌توانند در تحلیل های کسب و کار استفاده شوند تا تصمیمات بهتری در زمینه استخدام، حقوق و دستمزد، توسعه کاری و غیره گرفته شود.

مثال عملیاتی
برای پیش‌ بینی رشد یا تعدیل کارکنان با توجه به داده‌های قبلی شرکت، می‌توان از روش‌های مختلفی استفاده کرد.:

مدل‌های پیش‌ بینی: می‌توان از مدل‌های پیش‌بینی مختلفی مانند مدل‌های خطی، مدل‌های شبکه عصبی، مدل‌های درخت تصمیم و غیره استفاده کرد تا با توجه به داده‌های قبلی شرکت، الگوی رشد یا تعدیل کارکنان تا حدودی مشخص شود و یا اگر داده ای در اختیار ما نبود برای سالهای آینده زمینه این پیش بینی فراهم شود.
 با استفاده از تحلیل داده‌های تاریخی مانند میزان رشد کارکنان در سال‌های گذشته، تعداد کارکنان جدید استخدام شده در سال‌های قبلی و غیره، می‌توان رشد یا تعدیل کارکنان را حداقل پیش‌بینی کرد یا سناریوهای مختلف را بر اساس وضعیت کسب و کار تهیه کرد.

پیش‌بینی با استفاده از معیارهای عملکرد: می‌توان با استفاده از معیارهای عملکردی مانند درآمد شرکت، سود شرکت، تعداد مشتریان جدید و غیره، پیش‌بینی رشد یا تعدیل کارکنان را انجام داد.


Data shematic

**Person data

full_name	string
first_name	string
gender	string
birth_year	date
birth_date	date
linkedin_url	string
github_url	string
personal_emails	string
recommended_personal_email	string
mobile_phone	string
industry	string
job_title (desired)	string,
job_title_role	keyword
job_title_sub_role	keyword
job_title_levels	keyword
job_company_name (ex-employer)	keyword
job_company_website	keyword
job_company_size	keyword
job_company_industry	keyword
job_company_linkedin_url	keyword





**Employee Information:
- Employee ID: string
- First Name: string
- Last Name: string
- Gender: string
- Date of Birth: date
- Address: string
- Phone Number: string
- Email Address: string




**Employment Information:

- Employee ID: string
- Hire Date: date
- Job Title: string
- Department: string
- Supervisor: string
- Salary: decimal
- Employment Status: string
- Performance Rating: decimal

**Skills Information:

- Employee ID: string
- Skill Name: string
- Skill Level: string
- Certification: string


**Training Information:

- Employee ID: string
- Training Type: string
- Training Date: date
- Trainer Name: string
- Training Location: string

**Leave Information:

- Employee ID: string
- Leave Type: string
- Leave Start Date: date
- Leave End Date: date
- Leave Reason: string

**Growth prediction criteria

year: The year for which the data is recorded.
company_income: The total income of the company in that year.
employee_count: The total number of employees in the company in that year.
hiring_growth_rate: The percentage increase in the number of employees due to hiring in that year, compared to the previous year.
employee_growth_rate: The overall percentage increase in the number of employees in that year, compared to the previous year.

Economic Parameter	Data Type	Financial Statement Data

Inflation rate	Percentage (%)	-
Exchange rate	Currency	Revenue, Expenses
Unemployment rate	Percentage (%)	Payroll Expenses, Employee Turnover
Gross domestic product	Currency	Revenue, Net Income
Interest rates	Percentage (%)	Debt Interest Expenses, Investments
Consumer price index	Index	Cost of Goods Sold, Pricing Strategies





