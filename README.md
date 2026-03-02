# This App is test app
Now I work on this matter
```
Simple run thi app
```

# How to Upload This Project to GitHub

এই ডকুমেন্টটি আপনাকে দেখাবে কিভাবে আপনার লোকাল পিসি থেকে এই প্রজেক্টটি GitHub-এ আপলোড করবেন।

## ধাপ ১: গিট সেটআপ (Prerequisites)
প্রথমে নিশ্চিত করুন আপনার পিসিতে **Git** ইনস্টল করা আছে এবং আপনি একটি **GitHub Personal Access Token (PAT)** তৈরি করে রেখেছেন।

## ধাপ ২: লোকাল রিপোজিটরি তৈরি
আপনার প্রজেক্ট ফোল্ডারে টার্মিনাল ওপেন করে নিচের কমান্ডগুলো দিন:

```bash
# গিট ইনিশিয়ালাইজ করা
git init

# সব ফাইল স্টেজ করা
git add .

# প্রথম কমিট দেওয়া
git commit -m "Initial commit: Uploading Crow project"

# মেইন ব্রাঞ্চ সেট করা
git branch -M main

```
git remote add origin [https://github.com/jydhasan/newtest.git](https://github.com/jydhasan/newtest.git)
```

## File push kora
```
git push -u origin main
```

# প্রয়োজনীয় কিছু কমান্ড (Useful Commands)
---

    Status দেখতে: git status

    রিমোট লিঙ্ক চেক করতে: git remote -v

    ভুল লিঙ্ক ডিলিট করতে: git remote remove origin
