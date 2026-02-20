# 🚀  GitHub Push Notes

## 🔹 প্রথমবার কোড GitHub-এ আপলোড করার ধাপ

1. **প্রজেক্ট ডিরেক্টরিতে যান**
   ```bash
   cd path/to/your_flutter_project
   ```

2. **Git চালু করুন (Initialize)**
   ```bash
   git init
   ```

3. **সব ফাইল স্টেজ করুন**
   ```bash
   git add .
   ```

4. **প্রথম কমিট দিন**
   ```bash
   git commit -m "initial commit"
   ```
   👉 এখানে `"initial commit"` এর জায়গায় নিজের মতো মেসেজ লিখতে পারেন।

5. **মেইন শাখার নাম ঠিক করুন**
   ```bash
   git branch -M main
   ```

6. **GitHub রিমোট রিপোজিটরি যোগ করুন**
   - **SSH হলে**
     ```bash
     git remote add origin git@github.com:ariful10159/Task-Manager-App.git
     ```
   - **HTTPS হলে**
     ```bash
     git remote add origin https://github.com/ariful10159/Task-Manager-App.git
     ```

7. **রিমোট সঠিকভাবে যুক্ত হয়েছে কি না চেক করুন**
   ```bash
   git remote -v
   ```

8. **সবশেষে কোড পুশ করুন**
   ```bash
   git push -u origin main
   ```
   ✅ সব ঠিক থাকলে আপনার প্রজেক্ট GitHub-এ আপলোড হয়ে যাবে।

---

## 🔹 কোডে পরিবর্তন করার পর GitHub-এ আপলোডের ধাপ

1. **ফাইল পরিবর্তন করুন**
   - যেমন `lib/main.dart`, `assets/images/my_image.png`, `.gitignore` ইত্যাদি।

2. **পরিবর্তিত ফাইল স্টেজ করুন**
   ```bash
   git add .
   ```
   অথবা নির্দিষ্ট ফাইল:
   ```bash
   git add lib/main.dart
   ```

3. **কমিট দিন**
   ```bash
   git commit -m "আপডেট: নতুন ফিচার যুক্ত বা বাগ ফিক্স"
   ```
   👉 এখানে নিজের মতো মেসেজ লিখবেন।

4. **পুশ করুন**
   ```bash
   git push origin main
   ```

---

## 🔹 প্রতিবার কাজ করার সংক্ষিপ্ত নিয়ম

প্রতিবার পরিবর্তনের পর শুধু এই ৩টা কমান্ড দিলেই হবে:
```bash
git add .
git commit -m "message"
git push origin main
```

এবং রিপোজিটরির অবস্থা চেক করার জন্য:
```bash
git status
```

---

✍️ **Note:**  
- প্রথমবার শুধু `git init`, `git branch -M main`, আর `git remote add origin ...` লাগবে।  
- একবার সেটআপ হয়ে গেলে পরে কেবল `add → commit → push` করলেই যথেষ্ট।

  
✍️ **Note:** 
-git init

-git add README.md
-git commit -m "first commit"
-git branch -M main
-git remote add origin https://github.com/xxxxxxxxxxxxx.git
-git push -u origin main
