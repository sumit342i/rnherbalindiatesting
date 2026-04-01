# 🚀 QUICK START - Email Order System

**Complete this in 5 minutes to test locally!**

## Step 1️⃣: Install Dependencies
```bash
npm install
```
Wait for installation to complete (2-3 minutes).

---

## Step 2️⃣: Set Up Gmail App Password

### A. Enable 2-Step Verification:
1. Go to [myaccount.google.com](https://myaccount.google.com)
2. Click "Security" → "2-Step Verification"
3. Complete phone verification

### B. Generate App Password:
1. After 2FA is enabled, go back to Security
2. Click "App passwords"
3. Select: **Mail** and **Windows Computer**
4. Google gives you a **16-character password**
5. Copy it (spaces are fine)

---

## Step 3️⃣: Create .env File

Create a file named `.env` (no extension) in your project folder:

```
EMAIL_USER=digital.work.3442@gmail.com
EMAIL_PASSWORD=paste-your-16-char-password-here
PORT=5000
NODE_ENV=development
```

**⚠️ IMPORTANT:** 
- Use the **App Password** Google gave you (NOT your regular password)
- Never share this file
- It's already ignored by Git

---

## Step 4️⃣: Start Server
```bash
npm start
```

You should see:
```
✅ Email server is ready to send messages
🚀 Server is running on http://localhost:5000
📧 Email system configured for: digital.work.3442@gmail.com
```

---

## Step 5️⃣: Test the Form

1. Open browser: `http://localhost:5000`
2. Fill in the order form with test data:
   - Name: Test User
   - Phone: 1234567890
   - Email: your-test-email@gmail.com
   - Address: Test Address
   - City: Test City
   - State: Test State
   - Pincode: 123456
   - **Quantity: 5** (test the new quantity feature!)

3. Click "PLACE ORDER NOW"

4. Check both email inboxes:
   - ✅ Admin email: digital.work.3442@gmail.com
   - ✅ Customer email: your-test-email@gmail.com

---

## ✅ That's It!

Your email order system is working locally. Now:

### For Production/Deployment:
See [SETUP_GUIDE.md](SETUP_GUIDE.md) for options:
- **Heroku** (recommended, free tier)
- **Railway.app** (simple)
- **Render.com** (reliable)

### To Stop Server:
Press `Ctrl + C` in terminal

### Auto-Reload During Development:
```bash
npm run dev
```

---

## 🎯 What's New?

✨ **NEW Features:**
- Add quantity column to order form ✓
- Dynamic price calculation ✓
- Professional HTML emails ✓
- Separate admin & customer emails ✓
- Form validation ✓
- Error handling ✓

---

## 📧 Emails Include:

**Admin Email:**
- Customer details
- Delivery address
- Quantity ordered
- Total amount

**Customer Email:**
- Order confirmation
- Order summary
- Payment details
- Contact info

---

**🔗 Need Details?** See [SETUP_GUIDE.md](SETUP_GUIDE.md)

**🆘 Issues?** Check Troubleshooting section in SETUP_GUIDE.md
