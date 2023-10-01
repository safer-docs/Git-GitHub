# GITHUB

### Git ga asoslangan VCS - version control system kod hosting platformasi

### GitHub dagi repostory ni yuklab olish uchun
> - `git clone repostoryURL`

### Boshqa online tizimlar

* [GitHub](https://github.com/)
* [GitLab](https://about.gitlab.com/)
* [Bitbucket](https://bitbucket.org/)

---

## Yangi repostory yaratish uchun

![GitHub](https://media.geeksforgeeks.org/wp-content/uploads/20190826233513/223-1.png)

---

![GitHub](https://assets.digitalocean.com/articles/how-to-push-an-existing-project-to-github/new-github-repo.png)

---

![GitHub](https://d186loudes4jlv.cloudfront.net/git/images/github_new_repo3.png)

---

# Git push

> - `git remote add origin URL` example `"git remote add origin master"` - yangi github repostory manzil 
> - `git push -u origin master` - git local loyihani githubga joylash 
>   - `git` - bu Git'ni ishga tushuruvchi komanda
>   - `push` - o'zgarishlarini local reportorydan remote repostoryga yuborish uchun ishlatiladi
>   - `-u` yoki `--set-upstream` - ushbu flag `origin` remote repostoryni `master` branch bilan bog'lash uchun tracking branch sifatida sozlanadi. Bu keyinroq `git push` komandalari bajarilganda avtomatik ravishda `origin master` ni ishlatishga yordam beradi
>   - `origin` - bu `git push` komandasining remote repostory nomi yoki URL'i. Bu nom, odatda origin nomi bilan ta'riflanadi va boshqa bir repository nomi yoki URL'i bo'lishi mumkin.
>   -  `master` - Bu local repositorydagi asosiy branch nomi. 
> - `git remote -v` - github project manizlini bilish uchun

---

## Git pull

> - `git pull origin master`  - so'ngi o'zgarishlarni githubdan yuklab oladi

