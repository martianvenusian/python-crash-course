## Bo'lim 1: Asoslar
Bu kitobning birinchi bo'limi sizga Python dasturlarini yozishingizda kerak bo'ladigan asosiy tushinchalrni o'rgatadi. Ushbu tushinchalarning aksariyati barcha dasturlash tillari uchun umumiydir va bu sizning dasturchi sifatida butun hayotinggiz davomida foydali bo'ladi.
 - **1-bob**da Python dasturini compyuteringizga o'rnatasiz va _Hello world!_ degan xabarni ekranga chiqaruvchi birinchi dasturingizni ishga tushirasiz.
 - **2-bob**da ma'lumot va o'zgaruvchilarni saqlash va matn va raqamlar bilan ishlashni o'rganasiz.
 - **3-bob** va **4-bob** sizga `list`larni tanishtiradi. [list]()lar bir o'zgaruvchida siz istagan miqdordagi ma'lumotlarni saqlay oladi va bu ma'lomotlar bilan samarali ishlashga imkon beradi.
 - **5-bob**da siz `if` bayonotini ishlatib kod yozasiz. Kodingiz, agar shart [true]() bo'lsa ma'lum bir javobni qaytaradi, agar shart [false]() bo'lsa boshqa bir tarzda javob qaytaradi.
- **6-bob** Pythonning `dictionary`()larini qanday ishlatishni ko'rsatadi. `Dictionary`lar turli xil ma'lumotlar o'rtasida aloqalar o'rnatishga imkon beradi. [List]lar kabi [dictionary]lar ham siz istagan miqdordagi ma'lumotlarni saqlashga imkon beradi.
- **7-bob**da dasturlaringizni interfaol qilish uchun foydalanuvchidan qanday qilib [input]() qabul qilishni o'rganasiz.Qolaversa `while` takrorlovchisi haqida o'rganasiz. [while](), bu shart [true](_to'g'ri_) bo'lib turganda kodning malum bir [block]() qismini davomiy takrorlaydi.
- **8-bob**da siz `function`()lar yozasiz. Funksiyalar bu nomlangan kodning bir [block]() qismi bo'lib maxsus vazifani bajaradi va funksiyalarni kerak bo'lib qolganda istalgan vaqtda ishga tushirishingiz mumkin.
- **9-bob** `class`lasrni tanishtiradi. [class]lar it, mushuk, raketa kabi haqiqiy dunyoviy narsalarning modelini yaratishga imkon beradi va sizning kodingiz istalgan haqiqiy va mavhum narsalarni ifodalay olishi mumkin bo'ladi.
- **10-bob** qanday qilib `file`()lar bilan ishlashni va dasturingiz to'satdan [carsh]() chiqmasligi uchun [error]()ni qanday qilib bartaraf etishni ko'rsatadi. Dasturingiz yopilishidan oldin ma'lumotlarni saqlab va dastur qayta ishga tushganda ma'lumotlarni qayta o'qiydigan bo'lasiz. Siz Pythonning `exception`()lari haqida o'rganasiz. Bu sizga ko'tilayotgan xatolarga tayyor turish va dasturingiz bu xotolarni ajoyib tarizda bartaraf etishga imkon beradi.
- **11-bob**da dasturingiz risoladagidek ishlashini bilish uchun kodlaringizga qanday qilib `test` yozishni o'rganasiz. Natijada, yangi [bug]()lar chiqishidan havotir olmasdan o'z dasturingizni kengaytirib boradigan bo'lasiz. Kodni test qilish bu boshlang'ich darajadan o'rta darajadagi dasturchiga aylanishingizga yordam beradigan dastlabki ko'nikmalarning biridir.


### 1-bob: Birinchi qadam
Bu bobda o'zingizning birinchi Pyhton dasturingiz, _hello_world.py_ni ishga tushirasiz. Birinchi, Python o'rnatilgan yoki o'rnatilmaganligini tekshirasiz; agar o'rnatilmagan bo'lsa, unda uni o'rnatasiz. Qolaversa Python bilan ishlash uchun matnni taxrirlovchi dastur [text editor]ni o'rnatasiz. Matnni taxrirlovchi dastur Python kodini tushinadi va yozishingiz davomida bo'limlarni ajratib ko'rsatadi, kodingiznig tuzilishini oson tushinish uchun kodni belgilar bilan ifodalaydi.

#### Dasturlash muhitini sozlash
Python turli operatsion tizimlarda biroz farq qiladi, shuning uchun bazi narsalarni yodda tutishingiz kerak. Bu yerda, siz amalda ishlatiladigan Pythonning ikkita asosiy versiyasini va uni operatsion tizimingizga o'rnatish bosqichlarini ko'rib chiqasiz. 

##### Python 2 va Python 3
Shu kunda, Pythonning 2ta versiyasi mavjub. Python 2 va yangiroq bo'lgan Python 3. Har bir dasturlash tili yangi g'oya va texnologiyalar kelib chiqishidan vujudga keladi, va Python dasturchilari uzluksiz bu tilni ko'p tarmoqli va ko'chli qilib rivojlantirib kelishdi. Ko'plab o'zgarishlar bosqichma-bosqich va anglash qiyin, bazi hollarda Python 2 uchun yozilgan kod Python 3 o'rnatilgan tizimlarda ishlamasligi ham mumkin. Bu kitob davomida Python 2 va Python 3 orasidagi muhim farqlarni ko'rsatib o'taman, va qaysi birini ishlatishingizdan qat'iy nazar, kitobdagi ko'rsatmalarga ergasha olasiz.
 
Agar tizimingizda ikkala versiya ham o'rnatilgan bo'lsa yoki Pythonni o'rnatishingiz kerak bo'lsa, Python3 ni ishlating. Agar Python 2 tizimda o'rnatilgan yagona versiya bo'lsa va siz Pythonni o'rnatmasdan birdan kod yozishga o'tib ketishni istasangiz, unda, Python 2 dan foydalansangiz bo'ladi. Ammao, tez orada Python 3ga yangilashingiz yaxshiroqdir, va shunda siz eng yangi versiya bilan ishlayotgan bo'lasiz.

##### Python kodining qimlarini ishga tushirish
Python windows [terminal]()ida ishlaydigan [interpreter]() bilan birga keladi va u dasturini saqlamasdan va butun dasturni ishga tushirmasdan Pythondan qisman foydalanishga imkon beradi.
 
Bu kitob davomida, quydagi kabi parchalarni ko'rasiz."
```bash
>>> print("Hello Python interpreter")
Hello Python interpreter
```
Qora yozuv bilan yozilgan yozuv bu siz yozadigan va keyin `ENTER`ni bosib ishga tushiradigan kod. Bu kitobdagi ko'plab misollar kichik va mustaqil dasturlardan iborat. Ularni [editor]() yordamida ishga tushirasiz, chunki siz kodingizning ko'p qismini shunday yozasiz. Lekin ba'zan asos tushinchalar kod qismlari ketma-ketligi shaklida Python `terminal`i orqali ko'rsatiladi. Va bu ba'zi yakka holda uchraydigan mavzularni yanada samarali ifodalashgan imkon beradi. Har safar kod ketma-ketligida uchta burchali qavslarni ko'rganingizda, siz `terminal`dan foydalanayotgan bo'lasiz. Birozdan so'ng tizim uchun `interpreter`da kodni yozishni ko'rib chiqamiz.

##### Hello World!
Dasturlash olamida yangi tilda birinchi dastur sifatida _Hello world!_ xabarini ekranga chiqarish baxt keltiradi degan uzoq-yillik ishonch bor.
Pythonda, _Hello World_ dasturini bir qator kod bilan yozish mumkin.
```bash
print("Hello World!")
```
Bunday oddiy dastur juda haqiqiy maqsadlar uchun xizmat qiladi. Agar u tizimingizda to'g'ri ishlasa, demak siz yozadigan har qanday boshqa Python dasturi ham ishlashi kerak. Biz tez orada malum bir operatsion tizimda bu dasturni qanday yozishni ko'rib chiqamiz.

#### Turli operatsion tizimlarda Python
Python [cross-platform]() dasturlash tilidir, yani u katta ososiy operatsion tizimlarning barchasida ishlaydi. Har qanday siz yozgan Python dasturi Python o'rnatilgan har qanday yangi [computer]()da ishlashi kerak. Biroq, Pythonni turli operatsion tizimlariga o'rnatish usuli biroz farq qiladi.

Bu bo'limda qanday qilib Pythonni tizimingizga o'rnatish va _Hello World_ dasturini ishga tushirishni o'rganasiz. Birinchi Python tizimda o'rnatilgan-o'rnatilmagaini tekshirasiz, agar o'rnatilmagan bo'lsa uni o'rnatasiz. Keyin oddiy matn taxrirlash dasturini o'rnatasiz va _hello_world.py_ deb nomlangan bo'sh Python faylni saqlaysiz. Yakunida, _Hello World_ dasturini ishga tushirasiz va agar biror nima ishlamasa muammolarni bartaraf etasiz. Man har bir operatsion tizimda bu jarayonlar davomida siz bilan birga bo'laman va siz Python dasturlash muhitiga yangi boshlovchi sifatida ko'nikmalar hozil qilasiz.

##### Linuxda Python
Linux tizimi dasturchilar uchun ishlab chiqarilgan, va shuning uchun Python allaqachon ko'pchilik Linux [computer]larida o'rnatilgan bo'ladi. Linuxni yaratgan va uni rivojlantiruvchilar sizdan qaysidir vaqtda o'z dasturingizni yozishingizga umid qilishadi va buning uchun sizni qo'llab-qo'vvatlashadi. Shu sababdan dasturlashni boshlashingiz uchun o'rnatish va sozlamalarni juda kim amalga oshirasiz.

##### Python versiyasini tekshirish
Tizimingizdagi `Terminal` ilovasini ishga tushirish orqali [terminal]() oynasini ishga tushiring ([Ubuntu]()da, `CTRL-ALT-T` ni bosishingiz mumkin). Python o'rnatilgan-ornatilmaganini tekshirish uchun, **python** deb kichkina _p_ xarf bilan kiriting. Shunda siz o'rnatilgan Pythonnig versiyasini ko'rishingiz kerak va `>>>` belgi bu siz python buyruqlarini yozadigan joydir:

```bash
$ python
Python 2.7.6 (default, Mar 22 2014, 22:59:38)
[GCC 4.8.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Bu natija Python 2.7.6ni ko'rsatadi va bu ayni vaqtda shu [computer]()da o'rnatilgan Pythonning standart versiyasi bo'ladi. Siz bu natijani ko'rganingizda, Python bo'yruq oynasidan chiqish uchun `CTRL-D`ni bosing yoki `exit()` ni kiriting.

Python 3 ni tekshirish uchun, bu versiyaning tasdiqlab ko'rsatishingizga to'g'ri kelishi mumkin; natija Pythonnning standart versiyasini Python 2.7 deb ko'rsatgan bo'lsa ham, **python3** deb yozib ko'ring

```bash
$ python3
Python 3.5.0 (default, Sep 17 2015, 13:05:18)
[GCC 4.8.4] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Bu natija sizda Python 3 ham o'rnatilganini anglatadi, va shuning uchun istagan ikkita versiyani ishlatishingiz mumkin. Bu kitobning qayerida bo'lsa ham **python** buyrug'ini ko'rsangiz, buning o'rniga **python3** deb kiriting. Ko'pchilik Linux tarqatmalarida Python oldindan o'rnatilgan bo'ladi, ammo qandaydir sabab bilan sizning tizimingizda o'rnatilmagan bo'lsa yoki Python 2 o'rnatilgan bo'lsa va siz Python 3 ni o'rnatmoqchi bo'lsangiz, [Appendix A]() ga qarang.

#### Matn taxrirlovchi dasturni o'rnatish

`Geany` sodda matn taxrirlovchi dasturdir: U o'rnatish oson, deyarli barch dasturlaringizni to'g'ridan to'g'ri terminalsiz matn taxrirlovchi dasturning o'zidan ishga tushirishga imkon beradi, kodlaringizni ranglarda ko'rsatish uchun sintaksis belgilarini ishlatadi, va kodingizni terminal oynasida ishga tushiradi va siz terminaldan foydalanishga ko'nikmalar hosil qilasiz. [Appendix B]() boshqa matn taxrirlovchi dasturlar haqida malumot beradi, amma agar sizda boshqa matn taxrirlovchi dasturdan ishlatishga yaxshi bir o'rinli sabab bo'lmasa men sizlarga Geanydan foydalanishni maslaxat beraman.

Linux tizimida Geanyni bir qator kode bilan o'rnatishingiz mumkin
```bash
$ sudo apt-get install geany
```



































### 2-bob

### 3-bob

### 4-bob

### 5-bob

### 6-bob

### 7-bob

### 8-bob: Funcsiyalar
Bu bobda siz `function`larni yozishni o'rganasiz. Funksiyalar bu nomlangan kodning blok qismi bo'lib maxsus vazifani bajarish uchun yaratiladi. Siz [function]() orqali belgilagan biror bir vazifani ishga tushirishni istasangiz, o'sha vazifaga javobgar bo'lgan funksiyaning nomini chaqirasiz. Dasturingiz davomida bu vazifani bir necha marta ishga tushirmoqchi bo'lsangiz bu vazifa uchun kodlarni qayta qayta yozishingiz kerak bo'lmaydi; shunchaki bu vazifani bajarishga ma'sul bo'lgan funksiyani chaqirasiz, va bu chaqiriq Pythonga bu funksiya ichidagi kodni ishga tushirishni aytadi. Funksiyadan foydalanish dastur yozishni, o'qishni, test qilishni va kodni tuzatishni osonlashtirishi haqida bilib olasiz.
Bu bobda siz yana malumotlarni funksiyaga o'tkazish yo'llarini o'rganasiz. Asosiy ishi ma'lumotlarni namoyish qilish bo'lgan yaxlit funksiyalar va [data]()larni qayta ishlab o'zgaruvchi yoki o'zgaruvchilar to'plamini qaytarishga mo'ljallangan boshqa funksiyalarni qanday qilib yozishni o'rganasiz. Nihoyat, asosiy dasturingizning fayllarini tartibga solishga yordam berish uchun funksiyalarni _modul_lar deb ataluvchi alohida fayllarda saqlashni o'rganasiz.

#### Funksiyani yaratish
```
1| def greet_user():
2|    """Display a simple greeting."""
3|    print("Hello!")
 | 
4|    greet_user()
```
| Status | Response  |
| ------ | --------- |
| 200    | `json`                          |
|        | `   {`                          |
|        | ` "id": 10,`                    |
|        | ` "username": "alanpartridge",` |
|        | ` more code...`                 |
|        | `}`                             |
| 400    |                                 |

### 9-bob

### 10-bob

### 11-bob


## Bo'lim 2: Loyihalar


## Loyiha 1

### 12-bob

### 13-bob

### 14-bob

## Loyiha 2

### 15-bob

### 16-bob

### 17-bob

## Loyiha 3

### 18-bob

### 19-bob

### 20-bob

