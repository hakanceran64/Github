# About Github

## Setup & Configuration (Kurulum Ve Yapılandırma)

Git kullanmaya başlamadan önce terminal üzerinden git loglar vb için kullanıcı adı ve kullanıcı e-posta adresi tanımlamanız gerekmektedir. Bu bilgiler commit ettiğinizde kimin tarafından commit edilmiş bilgisini tutmak için kullanılacaktır. Aynı zamanda local alanınızda çalıştığınız projeyi Github'a yüklediğinizde de burada tanımlanan kullanıcı adı ve kullanıcı e-posta adresi üzerinden yükleme yapacaktır.

### Kullanıcı adı

```Bash

# Kullanıcı adını öğrenmek için
> git config --global user.name

# Kullanıcı adını değiştirin
> git config --global user.name "Hakan CERAN"

```

### Kullanıcı E-Posta

```Bash

# Kullanıcı E-Posta öğrenmek için
> git config --global user.email

# Kullanıcı E-Posta değiştirin
> git config --global user.email "hakanceran64@gmail.com"
```

---

## Getting and Creating Projects (Proje Oluşturma ve Projeyi Klonlama)

Mevcut projeniz için yeni bir Git Deposu oluşturun.

```Bash

# Bir .git dizini oluşturun.
> git init

# Tüm dosyaları dizine ekleyin.
> git add .

# Projenizin güncel halini commit yaparak history'ye kayıt edin.
> git commit 

# Tebrikler projenizin yeni bir versiyonunu oluşturdunuz.
```

Mevcut projenizi buluttan local alanınıza indirin.

```Bash

> git clone https://github.com/hakanceran64/Github.git (git_address)

```
---

## Basic Snapshotting (Temel Anlık Görüntü)

```Bash

# Dosya İçeriğini dizine ekleyin.
> git add .

# 
> git status

#
> git diff

#
> git commit

#
> git notes

#
> git restore

#
> git reset

#
> git rm

#
> git mv


```

---

## Branching and Merging (Dallanma ve Birleşme)

```Bash

> git branch
> checkout
> switch
> merge
> mergetool
> log
> stash
> tag
> worktree

```

---

## Sharing and Updating Projects (Projeleri Paylaşma ve Güncelleme)

```Bash

# remote'daki master branch'ini locale güncelle
> fetch origin master

#
> pull

# Yerel reponuzu uzak repoya transfer eder.
> git push [alias] [branch]

# takma ad kullanarak bir git url'si belirleyin.
> git remote add [alias (takma ad)] [url]

# Örnek
> git remote add origin https://github.com/hakanceran64/Github.git

#
> submodule

```