دستورات 
ابتدا git bash  رو باز میکنم و در ادامه داریم: 
بخش اول 
Creat name:
Git config –-global user.name “Zeinab Yaghoubi”
Create gmail:
Git config –global user.emailz.yaghoubi69@gmail.com
Check setting :
Git config –global –list 
Clone:
از قسمت کد fork  با دستور git clone  در پوشه ای که میخواهم ان را clone   میکنم :
Git clone + url
بخش دوم :
برای ایجاد فایل ابتدا وارد git_github -toturial  میشویم و سپس با دستور 
Echo” text “ > about_me.text  فایلی که میخواهم رو میسازم

با دستور git add about_me.txt  و بعد ان git commit -m “…”  فایل را کامیت کردم 
و با git status  فرایند رو چک کردم
در نهایت برای دیدن تاریخچه کامل از دستور git log  و برای دیدن خلاصه از تاریخچه از git log –oneline    استفاده کردم
 بخش سوم :
ابتدا وارد پوشه ای که commit کردم میشم و فایل های زیر رو ایجا میکنم
Cd git-github-tutorial
با دستور echo”…..> secrets.txt  و ehcho “…..> test.log  رو ایجاد میکنم
سپس با دستور git status  وضعیت را چک میکنم
و با دستور echo “الگو      > gitignore  رو ایجاد میکنم و بعد وضعیت رو چک میکنم
که در این حالت Untracked files:
        .gitignore نمایش داده میشود
با دستورات git add .gitignore
git commit -m "Add gitignore to ignore secrets and log files"  فایل gitignore  رو  stage and commit میکنم

بخش چهارم:
با دستور git branch feature /skiles  شاخع را ایجاد و بعد با git checkout feature /sliles  وارد این شاخه شده و یا با یک دستور git checkout -b   شاخه را ساخته و وارد ان میشوم 
و بعد برای برگشتن به main از دستور git checkout main  استفاده میکنم
بخش پنجم:
برای اضافه کردن از دستور echo “ … >> file name   استفاده میکنم
Git stash  تغیرات رو ذخیره میکنم
Git stash pop  تغییرات را روی شاخه ایجاد میکنم 
بخش ششم:
Git revert HEAD  وارد vim  شدم و با :Q!  از ان خارج شدم برای پاک کردن اخرین کامیت
Git reset -soft head~1 برای پاک کردن اخدین کامیت
بخش هفتم:
Git rm  که یک فایل را از گیت خذف ولی روی کامپیوتر نگه میدارم
بخش هشتم : 
Push   و ارسال شاخه های main , feature/add-slkies  که ابتدا با کد git checkout  وارد هر کدام میشوم و بعد با کد git push -u origin branch  ان را به github  ارسال میکنم 
که ابتدا برای اولین بار باید هویت خود را درgithub  تائید کنم

بخش نهم: 
به فایل readme,md  رفتم و با گرزینه edit  یک خط جدید به اون اضافه کردم و سپس در بخش message  هم یک جمله نوشتم و در نهایت commit changes  و انتخاب گزینه Commit directly to the main branch
Git fetch origin  دستورات را دانلود کرده ولی وارد main  نمیکند
Git log origin/main  لیست commitهای شاخه‌ی main در GitHub را نشان می‌دهد، بدون اینکه روی شاخهٔ local ، merge شود.
برای چک کردن تغییرات فایل reademe.md  را در vs code  باز کردم و تغییرات را مشاهده کردم

بخش دهم:
تمامی دستورات را طبق درسنامه انجام دادم و برای چک کردن وضعیت skills.txt  در git bash  با دستور ls  دیدم که این فایل در شاخه main  محلی هست
بخش 11 : 
ابتدا در vs code  دومورد دیگر از مهارت هایم را اضافه کردم و بعد در git bash  تغییرات ان را دیدم با دستور git diff  که خطوط جدید با رنگ سبز نمایش داده شده بودند
برای مشاهد diff  بین  commit  ها ابتدا از git log –oneline  تمام کامیت ها را مشاهده و سپس دو تا از هش را انتخاب و از دستور git diff COMMIT1 COMMIT2 استفاده میکنم
چالش ها : 
برای ساخت فایل جدید فاصله echo and “  رو رعایت نمیکردم و هر بار ارور میگرفتم 
در کل در ابتدا برای هر دستوری به دلیل رعایت نکردن فاصله یا نوشتن صحیح ان مجبور بودم هر دستور را چند بار بنویسم

نکات کلیدی:
کار کردن با clone , commit , push 
ایجاد شاخه و اعمال تغییرات مثل merge and pull request 
تحلیل تغییرات با git log , git diff , git status , ls 

سوالات : تقریبا انچه که میخواستم رو پیاده کردم و سوالی نماند ه


