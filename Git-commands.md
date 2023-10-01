## Version Control System = (VCS) kod versiyasini nazorat qiluvchi tizim

# Git dasturini o'rnatish

### Windows uchun
* [Git bash](https://git-scm.com/downloads) - Linux systemada ishlashga mo'ljallangan dastur
* [Cmder](https://cmder.net/) 

### MacOs uchun

### terminal
* [iTerm](https://www.iterm2.com/downloads.html)

---

### Quyidagi muammolarni hal qiladi 

> -  Kod veriyasini nazorat qilish
> -  Qanday o'zgarishlar qilindi
> -  Qachon kim tomondan kodga o'zgartirish kiritildi  
> -  Loyihalar bilan jamoaviy ishlash
> - Open Source - loyihalarga yordam berish
> - Portfolio va ish
---

# Git vs GitHub


## Git = Local Version Control System 
![Git](https://www.malwarebytes.com/blog/news/2023/01/asset_upload_file97293_255583.jpg)

---

## GITHUB = Online Version Control System Hosting Hizmati

![GitHub](https://www.lebigdata.fr/wp-content/uploads/2021/03/DataLab_-_Chapitre_0_-_Fabriquer_sa_station_de_mesure_connect_e_github-logo-640x320-1.png)

---

# Git Config

### Git Config - gitni configuratsiya qilish uchun ishlatiladi

`Commands`
> - `git config --list` - barcha sozlanmalarni tekshirish
> - `git config user.name` - git foydalanuvchining ismi
> - `git config user.email` - git foydalanuvchi emaili

---

## Git sozlamalarni o'rnatish 

> - `git config --global user.name 'any name'` - gitga o'zimizning username mizni kiritish
>   - `--global` - bu flag, qo'shimcha attribute
> - `git config --global user.email` - gitga o'zimizning emailni kiritamiz  

---

## Git Repostory

> - `Repostory` - yango papka/loyiha
>   - `repo` - qisqartmasi
> - `git init` - yangi git loyihasini boshlash uchun ishlatiladi, faqat loyiha boshlanganda 1 marta ishlatiladi
> - `git status` - kodimizda bo'layotgan o'zgarishlarni ko'rish uchun

---

## Git add

> - `git add` - loyihadagi yangi fayllar va o'chirilgan fayllar va hkz larni xotiraga saqlash uchun navbatga qo'yadi
> - `--command`lar - flag deyiladi
> - `"."` - barcha o'zgarishlar, o'chirilish va qo'shishlar
> - `"file name"` - barcha fayllarni yoki aniq bir faylni qo'shish 
> - `A/--al` - bu ham barcha o'zgarishlar, o'chirilish va qo'shilish larni xotiraga qo'shishga tayyorlash
> - example `git add .`

---

## Git Commit

> - `git commit -m` xotiraga olingan o'zgarishlarni saqlab qo'yadi
>   - `-m`(message) - xabar qoldirish uchun flag
> - `git commit -a -m "any message"` - ham navbatga qo'shosh va xabar qoldirish uchun
> - `git log / git log --pretty` - commitlar ro'yhatini ko'rish
> - example `git commit -m "some changes"`
>


---

## Fayl - o'zgarishlarni bekor qilish

> - `git checkout --<file>` - faylda bo'lgan o'zgarishlarni bekor qilish
> - `git checkout -- .` - barcha fayllardagi o'zgarishlarni bekor qilish

---

## Git add - bekor qilish 

> - `git reset` - staged - fayllarni unstaged qiladi lekin fayl qiymatlari o'zgarmaydi, yani xotiraga olingan o'zgarishlarni ortga qaytarish mumkin
> - `git reset fileName.txt` - faqat berilgan faylni unstage qiladi
> - `git reset . ` - barcha fayllarni 

---

## Git commitni bekor qilish

> - `git commit --amend` - o'zgarishlarni xotiradan olib tashlab bo'lmaydi, faqat description ni qayta nomlash mumkin


---

# Git   Branch / Merge

## Branch nima ?

## Yangi xususiyatlar bilan ishlash

![Branch/Merge](https://res.cloudinary.com/practicaldev/image/fetch/s--hRIHAYc6--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/8gbecx6m9utg39q82a8w.png)

---

##  Branch yaratish

> - `git branch` - mavjud hozirgi branch nomi
> - `git branch newBranch` - yangi branch nomi
> - `git checkout branchNomi` - ko'rsatilgan branchga o'tish
> - `git merge branchNomi` - berilgan branchni mavjud branchga yuklab olish