# Sohel Flour Mill — Android App (Auto Build via GitHub)

Ye app tumhari website ko WebView mein chalata hai aur ek floating overlay bubble dikhata hai jisko tap karne pe app open hota hai. Sound bhi chalta hai.

## 🚀 APK Build Karne Ka Easy Tarika (No Android Studio Needed!)

### Step 1: GitHub Account Banao
- https://github.com/signup pe jao (agar account nahi hai)
- Free account banao

### Step 2: New Repository Banao
1. GitHub login karke top-right **+** icon → **New repository**
2. Repository name: `sohel-flour-mill-app`
3. **Public** select karo (free Actions ke liye)
4. **Create repository** click karo

### Step 3: Files Upload Karo
1. Naye repo page pe **"uploading an existing file"** link click karo
2. Is zip ke **saare files aur folders** (`.github`, `app`, `build.gradle.kts`, `settings.gradle.kts`, `gradle.properties`, `README.md`) drag-drop karo
   - ⚠️ Important: `.github` folder bhi upload hona chahiye (hidden ho sakta hai)
3. Niche **"Commit changes"** click karo

### Step 4: Build Automatic Start Hoga
1. Upload hote hi top mein **"Actions"** tab pe jao
2. **"Build APK"** workflow chal raha hoga (yellow dot = running)
3. **5-8 minute wait karo** → green tick ✅ aa jayega

### Step 5: APK Download Karo
**Option A — Releases se (easy):**
- Repo home page pe right side **"Releases"** click karo
- Latest release mein `.apk` file download karo

**Option B — Actions se:**
- Actions tab → latest run click karo
- Niche **"Artifacts"** section mein `SohelFlourMill-debug-apk` download karo
- Zip extract karo → APK milega

### Step 6: Phone Mein Install
1. APK file phone mein transfer karo
2. **Settings → Security → Install Unknown Apps** enable karo
3. APK tap karke install karo
4. App khulne pe **"Display over other apps"** permission allow karo

---

## 🔄 Future Updates
Koi bhi file change karke GitHub pe edit/commit karoge → automatic naya APK build ho jayega Actions tab mein.

## 🌐 Website URL Change Karna
`app/src/main/java/com/sohel/flourmill/MainActivity.kt` file edit karo → `SITE_URL` value badlo → commit → naya APK auto-build.

## ❓ Help
- Build fail ho? Actions tab → red ❌ run click karo → error dekho → mujhe batao
- Overlay nahi dikhta? Phone settings mein "Display over other apps" permission check karo
