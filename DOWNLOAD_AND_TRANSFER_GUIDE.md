# 📦 MRT Energy Website - Download & Transfer Guide

## 🎯 How to Get Source Code & Transfer to Your Hosting Company

---

## 📂 **COMPLETE FILE LIST (What You Need)**

### **Essential Website Files (Must Download):**

```
📁 Your Website Files:
│
├── 📄 index.html                    (Main website page - 42KB)
├── 📁 css/
│   └── 📄 style.css                 (All styling - 31KB)
├── 📁 js/
│   └── 📄 main.js                   (Interactive features - 18KB)
└── 📁 images/
    └── 🖼️ mrt-logo.png              (Your logo - 23KB)
```

### **Documentation Files (Optional but Recommended):**

```
📁 Documentation:
│
├── 📄 README.md                     (Technical documentation)
├── 📄 LOGO_SIZE_UPDATE.md          (Logo update notes)
├── 📄 SHARING_GUIDE.md             (Sharing instructions)
├── 📄 DEPLOYMENT_CHECKLIST.md      (Launch checklist)
└── 📄 QUICK_START.md               (Quick reference)
```

**TOTAL SIZE:** ~150KB (very lightweight!)

---

## 🎯 **METHOD 1: Download via File Explorer** (RECOMMENDED)

### **Step-by-Step:**

#### **Step 1: Access Your Files**
Look at the **left sidebar** or **file explorer** in your workspace where you can see:
- index.html
- css/ (folder)
- js/ (folder)
- images/ (folder)

#### **Step 2: Download Each File**

**For Individual Files:**
1. **Right-click** on file name (e.g., index.html)
2. Select **"Download"** from menu
3. File saves to your Downloads folder

**For Folders (css, js, images):**
1. Click on folder to open it
2. Right-click on each file inside
3. Download one by one

#### **Step 3: Organize on Your Computer**

Create this folder structure on your computer:
```
📁 mrt-energy-website/
├── index.html
├── 📁 css/
│   └── style.css
├── 📁 js/
│   └── main.js
└── 📁 images/
    └── mrt-logo.png
```

---

## 🎯 **METHOD 2: Use Browser Developer Tools** (Alternative)

### **Step-by-Step:**

#### **Download HTML:**
1. Open the website in browser
2. Press `Ctrl + U` (View Source)
3. Press `Ctrl + S` (Save Page)
4. Save as `index.html`

#### **Download CSS:**
1. Open browser Developer Tools (`F12`)
2. Go to "Sources" or "Network" tab
3. Find `style.css` file
4. Right-click → Save

#### **Download JS:**
1. Same as CSS
2. Find `main.js` file
3. Right-click → Save

#### **Download Logo:**
1. Right-click on logo on website
2. Select "Save image as..."
3. Save as `mrt-logo.png`

---

## 🎯 **METHOD 3: Copy & Paste Code** (Manual Backup)

I can provide you the complete source code here if needed:

### **To Copy HTML:**
1. I'll share the complete `index.html` code
2. You copy and paste into text editor
3. Save as `index.html`

### **To Copy CSS:**
1. I'll share the complete `style.css` code
2. You copy and paste into text editor
3. Save as `css/style.css`

### **To Copy JS:**
1. I'll share the complete `main.js` code
2. You copy and paste into text editor
3. Save as `js/main.js`

**Would you like me to show you the code to copy?** Just ask!

---

## 📤 **UPLOADING TO YOUR HOSTING COMPANY**

### **Option A: cPanel (Most Common)**

#### **Step 1: Access cPanel**
1. Log into your hosting account
2. Open cPanel
3. Find "File Manager" icon

#### **Step 2: Navigate to Website Root**
Go to one of these folders:
- `public_html/` (most common)
- `www/`
- `htdocs/`
- Or specific domain folder

#### **Step 3: Upload Files**

**Upload via File Manager:**
1. Click **"Upload"** button
2. Drag and drop files:
   - `index.html` (to root)
3. Click **"New Folder"** to create:
   - `css/` folder
   - `js/` folder
   - `images/` folder
4. Enter each folder and upload respective files:
   - Upload `style.css` to `css/` folder
   - Upload `main.js` to `js/` folder
   - Upload `mrt-logo.png` to `images/` folder

**Final Structure on Server:**
```
📁 public_html/
├── index.html
├── 📁 css/
│   └── style.css
├── 📁 js/
│   └── main.js
└── 📁 images/
    └── mrt-logo.png
```

---

### **Option B: FTP Upload (FileZilla)**

#### **Step 1: Get FTP Credentials**
From your hosting company:
- FTP Host: `ftp.yourdomain.com`
- Username: Your FTP username
- Password: Your FTP password
- Port: Usually 21

#### **Step 2: Download FileZilla**
- Go to: https://filezilla-project.org
- Download free FTP client
- Install on your computer

#### **Step 3: Connect to Server**
1. Open FileZilla
2. Enter credentials at top:
   - Host: `ftp.yourdomain.com`
   - Username: [your username]
   - Password: [your password]
   - Port: 21
3. Click "Quickconnect"

#### **Step 4: Upload Files**

**Left Side** = Your Computer  
**Right Side** = Your Server

1. Navigate to `public_html/` on server (right side)
2. Drag files from left to right:
   - Drag `index.html`
   - Drag entire `css/` folder
   - Drag entire `js/` folder
   - Drag entire `images/` folder

---

### **Option C: Direct Code Upload via cPanel**

#### **For Small Files (HTML, CSS, JS):**

1. In cPanel File Manager
2. Click "New File" → name it `index.html`
3. Right-click file → "Edit"
4. Paste HTML code
5. Save

Repeat for CSS and JS files.

---

## 🌐 **ACCESSING YOUR WEBSITE**

After upload, your website will be available at:

**If uploaded to root (public_html/):**
- `https://www.yourdomain.com`
- `https://yourdomain.com`

**If uploaded to subfolder:**
- `https://www.yourdomain.com/foldername`

**Test it:**
1. Open browser
2. Type your domain
3. Website should load!

---

## ✅ **POST-UPLOAD CHECKLIST**

After uploading, verify:

- [ ] Website loads at your domain
- [ ] Logo displays correctly
- [ ] All sections visible (scroll through)
- [ ] Navigation links work
- [ ] Mobile view works (test on phone)
- [ ] Contact form displays
- [ ] CSS styling applied correctly
- [ ] JavaScript features working
- [ ] No broken images or links

---

## 🔧 **TROUBLESHOOTING**

### **Problem: Website shows only text (no styling)**
**Solution:**
- Check folder structure is correct
- Verify `css/style.css` path in index.html
- Check file permissions (should be 644)

### **Problem: Logo doesn't display**
**Solution:**
- Verify `images/mrt-logo.png` uploaded
- Check image path in index.html
- Make sure image file name matches exactly (case-sensitive)

### **Problem: JavaScript features not working**
**Solution:**
- Verify `js/main.js` uploaded correctly
- Check browser console for errors (F12)
- Clear browser cache (Ctrl + Shift + R)

### **Problem: 404 Error**
**Solution:**
- File not uploaded to correct location
- Check you're in `public_html/` or correct root folder
- Verify file names match exactly (case-sensitive)

---

## 📧 **INFORMATION FOR YOUR HOSTING COMPANY**

### **What to Tell Them:**

```
Subject: Upload Static Website Files

Hi [Hosting Support],

I need to upload a static HTML website to my hosting account.

Website Details:
- Static HTML/CSS/JavaScript website
- No database required
- No server-side processing
- Total size: ~150KB

Files to upload:
- 1 HTML file (index.html)
- 1 CSS file (in css/ folder)
- 1 JavaScript file (in js/ folder)
- 1 image file (in images/ folder)

Questions:
1. What folder should I upload to? (public_html?)
2. Can you provide FTP credentials?
3. Any specific file permissions needed?

Thank you!
```

---

## 🎯 **QUICK REFERENCE: File Locations**

### **After Upload, Files Should Be At:**

```
On Server                          Accessed Via Browser
─────────────────────────────────────────────────────────
/public_html/index.html        →   www.yourdomain.com
/public_html/css/style.css     →   www.yourdomain.com/css/style.css
/public_html/js/main.js        →   www.yourdomain.com/js/main.js
/public_html/images/mrt-logo.png → www.yourdomain.com/images/mrt-logo.png
```

---

## 📋 **FILE PERMISSIONS (if asked)**

Set these permissions on server:

```
Folders:    755 (drwxr-xr-x)
Files:      644 (-rw-r--r--)
```

**In cPanel:**
- Right-click file/folder → "Change Permissions"
- Folders: Check 755
- Files: Check 644

---

## 🔐 **SECURITY NOTES**

1. **HTTPS:** Ask hosting to enable SSL certificate (free with Let's Encrypt)
2. **Backups:** Keep local copy of all files
3. **Updates:** Easy to update - just replace files
4. **No Database:** No database security concerns
5. **Static Files:** Very secure (no server-side code)

---

## 💡 **COMMON HOSTING COMPANIES & THEIR INTERFACES**

### **cPanel (Most Common):**
- Bluehost, HostGator, SiteGround, GoDaddy
- Use File Manager or FTP

### **Plesk:**
- 1&1 IONOS, some VPS providers
- Similar to cPanel

### **Custom Dashboards:**
- Namecheap, DreamHost
- Usually have File Manager option

---

## 📞 **IF YOU NEED HELP**

### **Option 1: I Can Provide Code Directly**
I can share the complete source code here for you to copy & paste.

### **Option 2: Hosting Company Support**
Contact your hosting support with:
- "I need to upload static HTML files"
- Ask for FTP credentials
- Ask which folder to upload to

### **Option 3: Hire Someone**
On Fiverr or Upwork:
- Search: "Upload website files to hosting"
- Cost: Usually $5-20
- Takes: 15-30 minutes

---

## 🎯 **RECOMMENDED: Get Code from Me First**

**I can provide you with:**

### **Option A: Show Complete Code Here**
I'll paste the full HTML, CSS, and JS code in the chat for you to copy.

### **Option B: Create ZIP File Info**
I'll show you how to package everything properly.

### **Option C: Step-by-Step with Code**
I'll guide you through creating each file manually.

---

## ✅ **WHAT YOU NEED TO DO NOW:**

Choose your preferred method:

**1️⃣ Download Files from Workspace**
   - Use file explorer/sidebar
   - Download each file
   - Organize locally

**2️⃣ Get Code from Me (EASIEST)**
   - I'll share complete code
   - You copy & paste
   - No download needed

**3️⃣ Ask Your Hosting Company**
   - They can help with upload
   - Provide FTP details

---

## 📧 **EMAIL TEMPLATE FOR YOUR HOSTING COMPANY**

```
Subject: Help Uploading Website Files

Dear [Hosting Support],

I have a complete website (HTML, CSS, JavaScript files) ready to 
upload to my hosting account for [yourdomain.com].

Could you please provide:
1. FTP credentials (host, username, password)
2. Which folder to upload to (public_html?)
3. Any specific instructions for static website hosting

Website details:
- Static HTML website (no database needed)
- Total size: ~150KB
- Files: index.html, CSS folder, JS folder, images folder

Thank you for your assistance!

Best regards,
[Your Name]
```

---

## 🎊 **YOU'RE ALMOST THERE!**

Your website is complete and ready to transfer. It's a standard static HTML website that any hosting company can host easily.

**Total Time to Upload:** 10-20 minutes  
**Difficulty:** Easy (even for beginners)  
**Cost:** $0 (if you do it yourself)

---

## 🚀 **NEXT STEPS:**

1. **Tell me your preferred method:**
   - A) Share code here for copy/paste?
   - B) Guide me through downloading files?
   - C) Help me understand my hosting panel?

2. **I'll provide exactly what you need**

3. **You upload to your hosting**

4. **Your website goes live!**

---

**🌿 Ready to Transfer Your Professional Website! 🌿**

**👉 Let me know: How would you like to get the files? 👈**
