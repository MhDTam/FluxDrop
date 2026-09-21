# FluxDrop — التنزيلات الرسمية

مشاركة ملفات مباشرة بين هاتفك وحاسوبك على نفس شبكة Wi-Fi — بلا حساب، بلا رفع إلى سحابة، وبلا حدود للحجم.

## التنزيل — نسخة ويندوز

| الملف | الملاحظة |
| --- | --- |
| `FluxDrop-Windows-v1.0.0.zip` | **النسخة الموصى بها** (داخلها exe + تعليمات + التراخيص) |
| `FluxDrop-Windows-v1.0.0.exe` | ملف مباشر لمن يفضّل ذلك |

**للأندرويد:** التطبيق يُوزَّع من **Google Play** (قريبًا) — ولا تُنشر حزمته هنا.

## التثبيت على ويندوز

1. فُكّ ضغط ملف `.zip`.
2. شغّل `FluxDrop-Windows.exe`.
3. إن ظهر تحذير ويندوز (SmartScreen): اضغط **More info** ثم **Run anyway**.
   السبب أن الملف **غير موقّع رقميًا** (بلا شهادة توقيع) — والتحذير لا يعني أن الملف خطير.
   لإزالته نهائيًا: نقر يمين على الملف ← **Properties** ← تبويب **General** ← علّم **Unblock** ← OK.
4. المتطلّبات: ويندوز 10 أو 11 مع .NET Framework 4.8 (مضمّن أصلًا في النظام).
5. عند أول نقل سيطلب جدار الحماية السماح للتطبيق — اختر **«السماح على الشبكات الخاصة»**.

## التحقّق من سلامة الملف

قارن بصمة الملف بالبصمة المكتوبة في `SHA256SUMS.txt`:

```powershell
Get-FileHash .\FluxDrop-Windows-v1.0.0.zip -Algorithm SHA256
```

إن اختلفت القيمة فلا تشغّل الملف، وأعد التنزيل من هذا المستودع.

## الرخصة

الملفات المنشورة مجانية للاستخدام الشخصي، والكود المصدري **غير منشور**. التفاصيل في `LICENSE`.

---

## English

Direct file sharing between your phone and a PC over the same Wi-Fi network. No account, no cloud.
This repository distributes the **Windows** build only; the Android app ships through Google Play.

1. Download `FluxDrop-Windows-v1.0.0.zip` and unzip it.
2. Run `FluxDrop-Windows.exe`.
3. If Windows SmartScreen warns, choose **More info → Run anyway** — the build is simply unsigned.
   To stop the warning permanently: right-click the file → **Properties** → **General** → check **Unblock**.
4. Requires Windows 10/11 with .NET Framework 4.8 (built in).
5. Allow the app on private networks when the firewall asks.

Verify your download against `SHA256SUMS.txt` (`Get-FileHash <file> -Algorithm SHA256`).
The source code is not published and is not licensed for reuse.
