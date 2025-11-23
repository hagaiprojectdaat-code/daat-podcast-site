
# פודקאסט דעת – אתר על Vercel

האתר פועל על Vercel כאתר סטטי מלא.

## קבצים:

- index.html — דף האתר המלא
- logo.png — לוגו האתר
- api/contact.js — API לשליחת מייל דרך Resend
- vercel.json — הגדרות Vercel
- README.md — מידע על הפרויקט

## עדכון האתר:
כל שינוי ב-index.html או בקבצים אחרים → Commit ל-GitHub → Vercel בונה Deploy חדש אוטומטית.

## טופס צור קשר
הטופס שולח נתונים אל /api/contact וצריך להגדיר ב-Vercel משתני סביבה:

- RESEND_API_KEY
- CONTACT_TO_EMAIL
- CONTACT_FROM_EMAIL (לא חובה)

