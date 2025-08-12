# সমিতি ম্যানেজার (Somiti Manager)

আধুনিক সমিতি ও ক্ষুদ্রঋণ ব্যবস্থাপনা সফটওয়্যার। বাংলাদেশের সবচেয়ে উন্নত ও নিরাপদ সমিতি ব্যবস্থাপনা সমাধান।

## ✨ বৈশিষ্ট্যসমূহ

- 📊 **সদস্য ব্যব���্থাপনা** - সম্পূর্ণ সদস্য তথ্য ও লেনদেন ব্যবস্থাপনা
- 💰 **দৈনিক সংগ্রহ** - কর্মী ভিত্তিক দৈনিক সংগ্রহ সিস্টেম
- 📅 **মাসিক ক্যালেন্ডার** - সংগ্রহের বিস্তারিত রিপোর্ট
- 🔐 **এডমিন প্যানেল** - সিস্টেম কন্ট্রোল ও ব্যবস্থাপনা
- 🌐 **দ্বিভাষিক** - বাংলা ও ইংরেজি সাপোর্ট
- 💾 **ডেটা সুরক্ষা** - ব্যাকআপ ও রিস্টোর সিস্টেম

## 🚀 দ্রুত ইনস্টলেশন

### 1. GitHub Pages (ফ্রি)

```bash
# কোড ক্লোন করুন
git clone https://github.com/YOUR_USERNAME/builder-flare-realm.git
cd builder-flare-realm

# Dependencies ইনস্টল
npm install

# Build করুন
npm run build

# আপনার GitHub repo-তে push করুন
git add .
git commit -m "Deploy somiti manager"
git push origin main
```

তারপর GitHub Settings → Pages → Source: "GitHub Actions" সিলেক্ট করুন।

### 2. Netlify (সহজ ড্র্যাগ অ্যান্ড ড্রপ)

```bash
npm run build
```

`dist` ফোল্ডার [Netlify](https://netlify.com) এ drag & drop করুন।

### 3. Vercel (তাৎক্ষণিক)

```bash
# Vercel CLI ইনস্টল
npm i -g vercel

# Deploy
vercel --prod
```

### 4. যেকোনো Web Hosting

```bash
# Build করুন
npm run build

# dist ফোল্ডারের সব ফাইল হোস্টিং এ আপলোড করুন
# Apache/Nginx এর জন্য .htaccess/.conf ফাইল প্রয়োজন হতে পারে
```

## 🔧 লোকাল ডেভেলপমেন্ট

```bash
# Dependencies ইনস্টল
npm install

# Development server চালু
npm run dev

# http://localhost:8080 এ দেখুন
```

## 👨‍💼 এডমিন অ্যাক্সেস

**Demo Admin Credentials:**

- Email: `admin@somitimanager.com`
- Password: `admin123`
- Admin Code: `SM2024`

## 📱 মোবাইল সাপোর্ট

সফটওয়্যারটি সম্পূর্ণ responsive এবং মোবাইল ডিভাইসে অনুকূল।

## 🛡️ নিরাপত্তা

- সকল ডেটা localStorage এ encrypted থাকে
- Admin panel এ multi-factor authentication
- ডেটা backup ও restore সিস্টেম

## 📞 সাপোর্ট

- Email: info@somitimanager.com
- Phone: +৮৮০ ১৭ ১২৩৪ ৫৬৭৮

## 📄 লাইসেন্স

এই প্রকল্পটি MIT লাইসেন্সের অধীনে।

---

© 2024 সমিতি ম্যানেজার। সর্বস্বত্ব সংরক্ষিত।
