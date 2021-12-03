# عام
عرض ليست الريمونت
git remote -v

# من مجال العمل اول مرة
لاظافة ريمونت
git remote add origin  /F/ahmed/.git
git remote add origin  /F/gitserverlocal/bajet/.git
git branch -M main
git push -u origin main

# دفع التغييرات 
اذا كانت هنالك ملفات في السيرفر هذه التعليمات تدفع التحديثات للسيرفر بالقوة
git push origi main --force   

يفضل عمل برانجين لكل سيرفر 

يقوم بارسال الى المحلي

git push origin main

يقوم بالارسال الى جيت هاب

git push origi master

عند ما تريد ان تعمل دمج وانت في البرانج المتاخر اعمل منه للمتقدم

master هو المتأخر

git merge main 

# السيرفر المحلي
في ملف السيرفي الدخلي 
git checkout main

to get branch in git
git branch


# عند السحب لمجال العمل
عند سحب من السيرفر
git checkout origin/main
git fetch origin 


