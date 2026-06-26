# 📚 SophiApp - README אישי של איתמר

## 🎯 סקירה כללית

**SophiApp** היא אפליקציה חינמית וקוד פתוח לכיוונון עדין (fine-tuning) של **Windows 10 ו-Windows 11**. 
זוהי גרסה מודרנית של פרויקט "Sophia Script" הידוע.

**Repository:** https://github.com/itd22/SophiApp (Fork מ-Sophia-Community/SophiApp)

---

## 🏗️ ארכיטקטורת הקוד

### מבנה ספריות ראשי (`/src/SophiApp`):

```
src/SophiApp/
├── Assets/                    # משאבים ויזואליים (תמונות, אייקונים)
├── Behaviors/                 # ההתנהגויות של ה-WPF (Event Behaviors)
├── Binaries/                  # קבצים בינאריים חיצוניים
├── Contracts/                 # ממשקי חוזה (Interfaces)
├── ControlTemplates/          # תבניות בקרה מותאמות
├── Converters/                # מחוללי המרות (Value Converters) לנתונים
├── Customizations/            # התאמות מותאמות (Custom Controls)
├── Extensions/                # הרחבות לשפה (Extension Methods)
├── Helpers/                   # מחלקות עזרה שימושיות
├── Models/                    # מודלים של נתונים
├── Properties/                # תכונות הפרויקט
├── RequirementsViewModels/    # ViewModels עבור דרישות המערכת
├── RequirementsViews/         # Views עבור דרישות המערכת
├── Services/                  # שירותים ועוזרים (Business Logic)
├── Strings/                   # מחרוזות ניתנות לתרגום (Localization)
├── Styles/                    # סגנונות XAML
├── UIMarkup/                  # MarkUp ממשקים משתמש
├── ViewModels/                # View Models (ViewModel)
├── Views/                     # Views (ממשקי משתמש XAML)
├── App.xaml                   # אפליקציית XAML
├── App.xaml.cs               # Logic App
├── MainWindow.xaml            # החלון הראשי
├── MainWindow.xaml.cs         # Logic החלון הראשי
├── SophiApp.csproj           # קובץ הפרויקט
└── SophiApp.sln              # Solution קובץ
```

### דפוס ארכיטקטורה: **MVVM (Model-View-ViewModel)**
- **Models**: מודלים של נתונים
- **Views**: ממשקי משתמש (XAML)
- **ViewModels**: לוגיקה בעלת מטרה

---

## ⚙️ קבוצות האופטימיזציה (Tweaks) השונות

SophiApp כולל **130+ tweaks** המחולקים לקטגוריות:

### 1️⃣ **Privacy & Telemetry** (פרטיות וטלמטריה)
- בקרה על שרותי טלמטריה של Windows
- הגדרות אבטחת נתונים
- ניהול שידור נתונים

### 2️⃣ **UI & Personalization** (ממשק משתמש והתאמה אישית)
- הגדרות תיימים (Dark/Light)
- התאמות חזותיות
- הגדרות רזולוציה

### 3️⃣ **System Configuration** (הגדרות מערכת)
- ניהול שירותים
- תצורת מערכת מתקדמת
- ביצועים

### 4️⃣ **Windows Security** (אבטחת Windows)
- הגדרות Windows Defender
- Windows Security
- Firewall settings

### 5️⃣ **Software Management** (ניהול תוכנה)
- התקנת Visual C++ Redistributable
- התקנת .NET Desktop Runtime
- הסרת OneDrive "נכונה"
- ניהול אפליקציות UWP

### 6️⃣ **Advanced Settings** (הגדרות מתקדמות)
- פונקציות מוסתרות עבור משתמשים מתקדמים
- תצורות נוספות

---

## 🎨 תכונות עיקריות

✅ **130+ tweaks** ייחודיים  
✅ ממשק משתמש מודרני עם MVVM Pattern  
✅ תיימים כהים ובהירים + החלפה דינמית  
✅ מנוע חיפוש מובנה  
✅ תמיכה ברזולוציות גבוהות (High DPI)  
✅ מצב דינמי בזמן אמת של כל תכונה  
✅ ניהול פרטיות וטלמטריה  
✅ יכולת ניהול אפליקציות UWP  
✅ Multithreading support  
✅ בדיקה ב-Static Analyzer (PVS-Studio)  

---

## 📦 דרישות המערכת

| גרסה | שם משווק | Build | ספרות | Edition |
|------|----------|-------|--------|---------|
| Windows 11 22H2 | 2022 Update | 22621+ | x64 | Home/Pro/Enterprise |
| Windows 10 22H2 | 2022 Update | 19045.2006+ | x64 | Home/Pro/Enterprise |

---

## 🔧 הוראות התקנה

### PowerShell
```powershell
irm app.sophi.app -useb | iex
```

### Chocolatey
```powershell
choco install sophiapp --confirm
```

### Scoop
```powershell
scoop bucket add extras
scoop install sophiapp
```

---

## 📝 הערות חשובות

⚠️ **הזהרות:**
- רק משתמש admin אחד יכול להיות מחובר בעת הפעלה
- עלול שלא יעבוד על Windows "homebrew" שבור
- יוצר קובץ log לאחר סגירה

💡 **יתרונות:**
- לא שמור נתונים בRegistry
- ניידות מלאה (Fully Portable)
- דינמי ולא hardcoded

---

## 🌐 דומיינים שה-App מתקשר איתם

- `raw.githubusercontent.com`
- `github.com`
- `download.visualstudio.microsoft.com`
- `builds.dotnet.microsoft.com`
- `www.google.com`
- `g.live.com`
- `oneclient.sfx.ms`

---

## 📞 קישורים ותקשורת

- 💬 [Telegram Chat](https://t.me/sophia_chat)
- 📰 [Telegram News](https://t.me/sophianews)
- 🎮 [Discord Server](https://discord.gg/sSryhaEv79)

---

## 📄 ליסנס

MIT License - קוד פתוח חופשי לשימוש

---

**עדכון אחרון:** 2026-06-26  
**סטטוס:** פעיל בפיתוח (dev-SophiApp2 branch)
