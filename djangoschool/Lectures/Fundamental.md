* คำสั่งการ activate env ใน window 
  => .\env\scripts\activate


* user
  id: admin
  pswd: 12345

  id: admin2
  pswd: x51290257


* ตัวอย่างการใช้ HttpResponse

=> from django.http import HttpResponse

   def Homepage(request):
  	   return HttpResponse('<h1>Hello Uncle Engineer</h1>')


* รูปแบบการเพิ่ม templates ใน settings ของ project นี้ไม่เหมือนกับทุกครั้งที่เราได้ทำมา

=> 'DIRS': [os.path.join(BASE_DIR, 'school/templates')],