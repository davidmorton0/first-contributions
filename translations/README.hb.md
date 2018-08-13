<div dir="rtl">
  <a href="https://www.codetriage.com/roshanjossey/first-contributions" rel="nofollow"><img src="https://camo.githubusercontent.com/8e53aecabdd0316ce198fe932798bb0f8754b30f/68747470733a2f2f7777772e636f64657472696167652e636f6d2f726f7368616e6a6f737365792f66697273742d636f6e747269627574696f6e732f6261646765732f75736572732e737667" alt="Open Source Helpers"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://camo.githubusercontent.com/76f0e887c183ccc31c1cb63c33d2dbf48cb2df51/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667" alt="License: MIT"></a>
  <a href="https://github.com/ellerbrock/open-source-badges/"><img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" alt="Open Source Love"></a>
</div>

<div dir="rtl">
# תרומות ראשונות
</div>

<div dir="rtl">
זה קשה. זה תמיד קשה שעושים משהו בפעם הראשונה. במיוחד כאשר משתפים פעולה, לעשות טעויות זה לא משהו נוח. רצינו להקל על הדרך שבה תורמים בפעם הראשונה לומדים ותורמים בפעם הראשונה.
לקרוא כתבות ולצפות בסרטוני הדרכה יכולים לעזור, אבל מה יותר טוב מאשר לבצע את הדברים בסביבת למידה? המטרה של הפרויקט הזה היא לתת הכוונה ולפשט את הדרך שבה מתחילים מבצעים את התרומה הראשונה שלהם. אם אתם מחפשים לבצע את התרומה הראשונה שלכם, עקבו אחרי הצעדים למטה.
</div>

<div dir="rtl">
#### אם לא מתאים לכם להשתמש בטרמינל, כאן יש קישור תוך שימוש בכלים גרפיים
<a href="#tutorials-using-other-tools">קישור לכלים גרפיים</a>
</div>

<div dir="rtl">
####ניתן לתקרוא את המאמר
<a href="">בשפות אחרות</a>
</div>

<div dir="rtl">
<a href="https://help.github.com/articles/set-up-git/">אם אין לכם GIT ניתן להתקין GIT בקישור</a>
</div>

<div dir="rtl">
<a href="/Roshanjossey/first-contributions/blob/master/assets/fork.png"><img img style="float: left;" width="300" src="../assets/fork.png" alt="fork this repository"></a>
</div>

<div dir="rtl">
## בצעו FORK למאגר זה
</div>

<div dir="rtl">
כדי לבצע FORK למאגר זה, ניתן ללחוץ על כפתור ה – FORK בתחילת העמוד. פעולה זה תיצור עותק של מאגר זה בחשבון שלכם.
</div>


<div dir="rtl">
## שכפול המאגר
</div>

<div dir="rtl">
  <img align="left" width="300" src="../assets/clone.png" alt="clone this repository" />
</div>

<div dir="rtl">
כעת, שכפלו את המאגר הזה למחשב שלכם. לכו לדף ה-GitHub שלכם, לחצו על כפתור השכפול ואז לחצו על הצלמית 'העתק ללוח'
פתחו טרמינל והריצו את הפקודה הבאה:
</div>

```
git clone "url you just copied"
```
<div dir="rtl">
כאשר הביטוי "url you just copied" (ללא סימני הגרשיים) הוא הקישור למאגר שביצעתם עליו FORK מקודם. ראו את הצעדים הקודמים כדי להשיג את הקישור.
</div>

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

<div dir="rtl">
לדוגמא:
</div>

```
git clone https://github.com/this-is-you/first-contributions.git
```
<div dir="rtl">
כאשר 'this-is-you' הוא שם המשתמש שלכם ב-GitHub. כאן, אתם מעתיקים את התוכן של מאגר first-contributions ב-GitHub לתוך המחשב שלכם.
</div>

<img style="float: left;" width="300" src="../assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

<div dir="rtl">
## יצירת ענף
</div>

<div dir="rtl">
תחליפו לתיקיית המאגר בתוך המחשב שלכם (אם אתם כבר לא נמצאים שם)
</div>

```
cd first-contributions
```
<div dir="rtl">
כעת, תצרו ענף בשימוש הפעולה 'git checkout':
</div>

```
git checkout -b <add-your-new-branch-name>
```
<div dir="rtl">
  לדוגמא:
</div>

```
git checkout -b add-alonzo-church
```

<div dir="rtl">
(שם הענף לא חייב להכיל את המילה add בתוכו, אבל זה הגיוני להוסיף אותה מכיוון שהמטרה של הענף היא להוסיף את השם שלכם לרשימה)
</div>

<div dir="rtl">
## בצעו שינוי הכרחי ובצעו(commit) את השינויים
</div>

<div dir="rtl">
כעת תפתחו את הקובץ, 'Contributors.md' בתוכנת עריכת טקסט והוסיפו את השם שלכם אליו. אל תוסיפו את השם בתחילת הקובץ או בסופו. הוסיפו אותו באמצע. לאחר שסיימתם, שמרו את הקובץ.


אם תנווטו לתיקיית הפרויקט ותבצעו את הפעולה 'git status', תוכלו לראות את השינויים שביצעתם שם.
הוסיפו את השינויים האלו לענף שיצרתם תוך שימוש בפקודה 'git add':
</div>

```
git add Contributors.md
```
<div dir="rtl">
עכשיו, בצעו(commit) את שינויים הללו תוך שימוש בפקודת 'git commit':
</div>

```
git commit -m "Add <your-name> to Contributors list"
```
<div dir="rtl">
החליפו את הביטוי '<your-name>' עם השם שלכם
</div>

<div dir="rtl">
## לדחוף את השינויים ל-GitHub
</div>

<div dir="rtl">
דחפו את השינויים תוך שימוש בפקודה 'git push':
</div>

```
git push origin <add-your-branch-name>
```
<div dir="rtl">
החליפו את '<add-your-branch-name>' עם השם של הענף שיצרתם מוקדם יותר
</div>

<div dir="rtl">
## הגישו את השינויים שלכם לסקירה
</div>

<div dir="rtl">
אם תלכו למאגר שלכם ב-GitHub, אתם תראו כפתור עם הכיתוב 'Compare & pull request'. לחצו על כפתור זה.

<img style="float: left;" src="../assets/compare-and-pull.png" alt="create a pull request" />

כעת, הגישו את בקשת הדחיפה

<img style="float: right;" src="../assets/submit-pull.png" alt="submit pull request" />

בקרוב, אני אצרף את כל השינויים לתוך הענף הראשי של פרויקט זה. אתם תקבלו עדכון במייל ברגע שהשינויים ימוזגו.
</div>

<div dir="rtl">
## מחקו את הענף שלכם אחרי שבקשת הדחיפה אושרה
</div>

<div dir="rtl">
ניתן למחוק בבטחה את הענף שלכם '<add-your-branch-name>' אחרי שבקשת הדחיפה מוזגה. אתם תראו כפתור למחיקת הענף:

<img style="float: left;" src="../assets/delete-branch-after-pr.png" alt="delete branch after PR is merged" />

אם בקשת הדחיפה נסגרה ללא מיזוג, GitHub, יזהיר אתכם לגבי מחיקת commits שלא מוזגו והכפתור יראה כך:

<img style="float: left;" src="../assets/delete-branch-warning.png" alt="delete branch after PR is not merged" />

</div>

<div dir="rtl">
## מה לעשות מכאן?
</div>

<div dir="rtl">
כל הכבוד! כרגע סיימתם את מעגל הזרימה הסטנדרטי של Fork->Clone->Edit->PR שאתם תפגשו באופן שכיח כתורמים!
חגגו את התרומה שלכם ושתפו אותה עם חברים שלכם ועוקבים שלכם בכך שתלכו ל- [web app](https://roshanjossey.github.io/first-contributions/#social-share).
אתם יכולים להצטרף לצוות הסלאק שלנו אם אתם צריכים עזרה או אם יש לכם שאלות.
[הצטרפו לסלאק team](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY).
עכשיו אפשר להתחיל לתרום לפרויקטים אחרים. הכנו רשימה של פרויקטים על נושאים קלים שאתם יכולים להתחיל לעבוד עליהם. תבדקו את  [רשימה של פרויקטים באפליקציית WEB app](https://roshanjossey.github.io/first-contributions/#project-list).
</div>

<div dir="rtl">
### [חומר נוסף](additional-material/git_workflow_scenarios/additional-material.md)
</div>

<div dir="rtl">
## הדרכות בשימוש כלים אחרים
</div>

<div dir="rtl">
|<a href="github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://www.visualstudio.com/wp-content/uploads/2017/11/microsoft-visual-studio.svg" width="100"></a>|<a href="gitkraken-tutorial.md"><img alt="GitKraken" src="../assets/gk-icon.png" width="100"></a>|
|---|---|---|
|[GitHub Desktop](github-desktop-tutorial.md)|[Visual Studio 2017](github-windows-vs2017-tutorial.md)|[GitKraken](gitkraken-tutorial.md)|
</div>

<div dir="rtl">
## קידום עצמי
</div>

<div dir="rtl">
אם אהבתם את הפרויקט הזה, תתנו לו כוכב [GitHub](https://github.com/Roshanjossey/first-contributions)
אם אתם מרגישים נדיבים במיוחד, תעקבו אחרי [Roshan](https://roshanjossey.github.io/)
בטוויטר, [Twitter](https://twitter.com/sudo__bangbang)
ובגיטהב [GitHub](https://github.com/roshanjossey)

<a href="http://saasgrids.com"> <img alt="https://app.saasgrids.com" src="../assets/saasgrids-banner.png" width="500"></a>
</div>
