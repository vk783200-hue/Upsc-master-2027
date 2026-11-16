# UPSC MASTER 2027 — Android installable web app

यह पैकेज PWA-ready है। इसे सीधे ZIP से Chrome में खोलने पर Install app नहीं आएगा।
इसे HTTPS वेबसाइट पर publish करना जरूरी है।

## सबसे आसान मुफ़्त तरीका: GitHub Pages
1. फोन/कंप्यूटर पर github.com खोलकर अकाउंट बनाएं या लॉगिन करें।
2. New repository बनाएं, नाम `upsc-master-2027` रखें और Public चुनें।
3. Add file → Upload files चुनें।
4. इस ZIP के अंदर की सभी फाइलें (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png) अपलोड करें। ZIP को खुद अपलोड न करें; पहले Extract करें।
5. Commit changes दबाएं।
6. Repository में Settings → Pages खोलें।
7. Build and deployment में Deploy from a branch चुनें; Branch `main`, folder `/(root)` चुनकर Save करें।
8. कुछ मिनट बाद GitHub Pages जो HTTPS लिंक देगा, उसे Android Chrome में खोलें।
9. Chrome ⋮ मेन्यू में `Install app` या `Add to Home screen` चुनें।

## महत्वपूर्ण
- यह APK नहीं है; यह इंस्टॉल होने योग्य वेबसाइट/PWA है।
- नोट्स, उत्तर और चेकलिस्ट उसी फोन/ब्राउज़र के लोकल स्टोरेज में सेव होते हैं। Browser data साफ करने पर वे मिट सकते हैं। बैकअप रखें।
- अभी इसमें शुरुआती नमूना नोट्स और कुछ MCQ हैं; यह पूरा UPSC पाठ्यक्रम या आधिकारिक सामग्री नहीं है।
