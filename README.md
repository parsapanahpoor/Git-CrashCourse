# Git Crash Course | درسنامه تعاملی Git

**آموزش اسلایدی و سناریومحور Git برای توسعه‌دهندگان C# و ASP.NET Core**

این دوره فارسی و RTL است و **۱۳۱ اسلاید** در **۱۶ بخش** دارد: **۸۰ درسنامه/تمرین** و **۵۱ سؤال چهارگزینه‌ای با پاسخ تشریحی**.

## مشاهده دوره

پس از فعال‌سازی GitHub Pages از `main / (root)`:

**https://parsapanahpoor.github.io/Gti-CrashCourse/**

> توجه: فعال‌سازی اولیه Pages باید از Settings → Pages انجام شود؛ صرف وجود فایل‌های سایت به معنای فعال بودن Pages نیست.

## امکانات

- اسلایدهای Responsive برای موبایل و Desktop با Navigation از طریق Keyboard و دکمه‌های صفحه
- جست‌وجوی محتوای اسلایدها با `/`؛ فهرست درس‌ها با `O`؛ حالت Fullscreen با `F`
- سؤال‌های چهارگزینه‌ای Interactive و پاسخ تشریحی پس از انتخاب گزینه
- ذخیره پیشرفت و پاسخ‌ها در localStorage همان مرورگر، بدون نیاز به حساب کاربری
- چاپ درسنامه و کل پاسخ‌های Quiz از داخل مرورگر
- **بدون Dependency خارجی، بدون Build Step و بدون Backend**

## مهم‌ترین موضوعات

Git Mental Model، Working Directory/Index/Repository، Commit، Branch، Merge، Fast-forward، Rebase، Merge Conflict، Fetch/Pull، Pull Request، Code Review، CI Checks، Reset، Revert، Restore، Cherry-pick، Stash، Tag، Reflog، Bisect، Blame، Worktree، .gitignore، .gitattributes، Security Incident، EF Core Migrations و Workflowهای واقعی.

## ساختار پروژه

```text
index.html
.nojekyll
README.md
css/styles.css
js/course-data.js
js/app.js
assets/favicon.svg
```

`js/course-data.js` محتوای درسنامه و Quizها را نگه می‌دارد، `js/app.js` منطق نمایش و تعامل را پیاده‌سازی می‌کند و `css/styles.css` طراحی را کنترل می‌کند.

## اجرای محلی

```bash
python -m http.server 8000
```

سپس `http://localhost:8000` را باز کنید. بدون Server نیز باز کردن مستقیم `index.html` برای بسیاری از مرورگرها کار می‌کند.


## منابع فنی

- [Pro Git (2nd Edition)](https://git-scm.com/book/en/v2)
- [Git Reference](https://git-scm.com/docs)
- [GitHub Pull Requests](https://docs.github.com/en/pull-requests)
- [GitHub Pages](https://docs.github.com/en/pages)

> محتوا، توضیحات و سؤال‌ها برای این درسنامه طراحی شده‌اند؛ ترجمه مستقیم متن کتاب Pro Git نیستند.
