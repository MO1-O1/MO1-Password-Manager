# MO1-Password-Manager

Scaffold أولي لتطبيق إدارة كلمات المرور:
- Stack: TypeScript + React + Vite
- Desktop: Electron (scaffold بسيط)
- Local storage: IndexedDB (مع تشفير عبر Web Crypto)

تشغيل (واجهة ويب):
1. npm install
2. npm run dev

تشغيل النسخة المكتبية (بعد بناء/تهيئة Electron):
1. npm install
2. npm run start:electron

المراحل التالية:
- إضافة تشفير قوي (Argon2 + AES-GCM)
- مزايا: مولد كلمات، استيراد/تصدير مشفر، صيغ استرجاع
- إعداد CI (GitHub Actions) واختبارات E2E

اخترت إعداد افتراضي؛ علمني لو تحب صفر-معرفة (zero-knowledge) أو تفعيل TOTP/2FA الآن.
