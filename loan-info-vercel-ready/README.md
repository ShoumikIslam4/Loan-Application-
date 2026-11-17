# Vercel-ready static loan information site

এটি একটি নিরাপদ, static informational demo। এটি কোনো আর্থিক প্রতিষ্ঠানের অফিসিয়াল সাইট নয় এবং কোনো account number, OTP, PIN বা password নেয় না।

## Deploy to Vercel
1. ZIP extract করুন।
2. Vercel-এ **Add New → Project** নির্বাচন করুন।
3. GitHub repository import করুন অথবা Vercel CLI দিয়ে এই folder deploy করুন।
4. Framework Preset: **Other**.
5. Build Command এবং Output Directory ফাঁকা রাখুন (static files root-এ আছে)।
6. Deploy চাপুন।

## Local preview
project root-এর `index.html` ব্রাউজারে খুলুন। অথবা project root-এ static server চালান।

## Files
- `index.html` — homepage
- `style.css` — styling
- `app.js` — minimal frontend script
- `vercel.json` — Vercel headers/clean URLs

## Important
Original archive-এর PHP admin/backend, database এবং OTP/PIN সংগ্রহের flow Vercel static deployment-এ অন্তর্ভুক্ত করা হয়নি। OTP/PIN সংগ্রহ বা সংরক্ষণ করার ব্যবস্থা তৈরি/ডিপ্লয় করা নিরাপদ নয়। প্রকৃত loan application দরকার হলে সংশ্লিষ্ট licensed provider-এর অনুমোদিত API ও security requirements ব্যবহার করতে হবে।
