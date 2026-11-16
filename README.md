# Game Development MCQ Exam — GitHub Pages

An offline-friendly, single-page multiple-choice revision website based on:
- **Chapter 1:** all slides (136 questions)
- **Chapter 2:** slides **1–20 only** (59 questions)

**Total: 195 MCQs.** Practice/exam modes, chapter/topic selection, shuffled questions, progress, scoring and answer review. No external dependencies or paid hosting needed.

## النشر على GitHub Pages

1. افتح [github.com](https://github.com) وأنشئ مستودعًا جديدًا (Repository)، مثل: `game-development-exam`.
2. فك ضغط ملف ZIP الخاص بالموقع إذا كنت تستخدم الحزمة المضغوطة.
3. من صفحة المستودع، اختر **Add file → Upload files** وارفع `index.html` و `.nojekyll` و `README.md` إلى **جذر المستودع** (root). ثم اختر **Commit changes**.
4. انتقل إلى **Settings → Pages**.
5. تحت **Build and deployment** اختر **Deploy from a branch**، وحدد فرع `main` والمجلد `/(root)`، ثم اضغط **Save**.
6. بعد اكتمال النشر، افتح الرابط:

   `https://YOUR-USERNAME.github.io/game-development-exam/`

استبدل `YOUR-USERNAME` باسم المستخدم لديك، و`game-development-exam` باسم المستودع الفعلي.

> **ملاحظة:** GitHub Pages يعرض ملف `index.html` تلقائيًا. لا ترفع ملف ZIP نفسه إلى المستودع على أنه الموقع؛ ارفع الملفات الموجودة بداخله.

## Quick notes

- HTML, CSS, and JavaScript are all bundled in `index.html`.
- Site loads without any external libraries or APIs.
- To customize the question bank, edit the `BANK` array inside `index.html`.
- No login or database is included. Current quiz progress is held only in the browser tab and is reset on reload.
