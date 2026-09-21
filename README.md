# FluxDrop — Official Windows Downloads

Direct file sharing between your phone and a PC over the same local Wi-Fi network — no account, no cloud, no file size limits.

## Downloads — Windows

| File | Notes |
| --- | --- |
| **`FluxDrop-Windows-v1.0.0.zip`** | **Recommended** (includes executable, user guide, and licenses) |
| `FluxDrop-Windows-v1.0.0.exe` | Standalone executable |

> **Android App:** The companion mobile app is distributed via **Google Play** (coming soon) and is not hosted here.

## Installation on Windows

1. Extract the downloaded `.zip` file.
2. Run `FluxDrop-Windows.exe`.
3. If Windows SmartScreen shows a prompt: click **More info** then **Run anyway**.
   * *Why?* The build is not Authenticode-signed with an expensive commercial certificate, but it is completely safe and runs 100% locally.
   * To permanently unblock: right-click `FluxDrop-Windows.exe` → **Properties** → **General** tab → check **Unblock** → **OK**.
4. **Requirements:** Windows 10 or 11 with .NET Framework 4.8 (pre-installed by default on modern Windows).
5. When Windows Firewall prompts on first transfer, select **"Allow on private networks"**.

## Verifying Download Integrity

Compare the SHA-256 checksum of your download with the values in `SHA256SUMS.txt`:

```powershell
Get-FileHash .\FluxDrop-Windows-v1.0.0.zip -Algorithm SHA256
```

If the hash does not match, do not run the file and re-download from this official repository.

## License

The published binaries are free for personal use. The source code is not published and is not licensed for reuse. See `LICENSE` for details.

---

## العربية (Arabic)

مشاركة ملفات مباشرة وسريعة بين هاتفك وحاسوبك على نفس شبكة Wi-Fi — بلا حساب، بلا رفع إلى سحابة، وبلا حدود للحجم.

### التنزيل — نسخة ويندوز

| الملف | الملاحظة |
| --- | --- |
| **`FluxDrop-Windows-v1.0.0.zip`** | **النسخة الموصى بها** (داخلها exe + تعليمات + التراخيص) |
| `FluxDrop-Windows-v1.0.0.exe` | ملف مباشر لمن يفضّل ذلك |

**للأندرويد:** التطبيق يُوزَّع من متجر **Google Play** (قريبًا) — ولا تُنشر حزمته هنا.

### التثبيت على ويندوز

1. فُكّ ضغط ملف `.zip`.
2. شغّل `FluxDrop-Windows.exe`.
3. إن ظهر تحذير ويندوز (SmartScreen): اضغط **More info** ثم **Run anyway**.
   السبب أن الملف **غير موقّع رقميًا** بشهادة تجارية — والتحذير لا يعني أن الملف خطير.
   لإزالته نهائيًا: نقر يمين على الملف ← **Properties** ← تبويب **General** ← علّم **Unblock** ← **OK**.
4. **المتطلّبات:** ويندوز 10 أو 11 مع .NET Framework 4.8 (مضمّن أصلًا في النظام).
5. عند أول نقل سيطلب جدار الحماية السماح للتطبيق — اختر **«السماح على الشبكات الخاصة»**.

### التحقّق من سلامة الملف

قارن بصمة الملف بالبصمة المكتوبة في `SHA256SUMS.txt`:

```powershell
Get-FileHash .\FluxDrop-Windows-v1.0.0.zip -Algorithm SHA256
```

### الرخصة

الملفات المنشورة مجانية للاستخدام الشخصي، والكود المصدري **غير منشور**. التفاصيل في `LICENSE`.
