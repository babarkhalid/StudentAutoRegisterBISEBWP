# Student Auto Register - User Instructions

## English

### What this app does

Student Auto Register helps you load student records from an Excel file and fill them into the SSC portal registration form using Google Chrome.

### Before you start

Make sure you have:

- Google Chrome installed.
- Your Excel file ready in `.xlsx` format.
- Student pictures saved in one folder, if you want the app to attach pictures.
- Portal login details available.

### How to open the app

1. Extract the portable zip file to a normal folder.
2. Open the extracted folder.
3. Double-click `StudentAutoRegister.exe`.

### First-time setup

1. Check the `Portal URL`.
   The default portal URL is already filled.

2. Keep `Chrome debug port` as `9222` unless there is a problem.

3. Choose `Chrome profile folder`.
   You can keep the default folder. This is a separate Chrome profile used only for this app.

4. Choose `Student picture folder`.
   Select the folder where student pictures are saved.

5. Enter `Pic ext.`.
   Use `.jpg`, `.jpeg`, or `.png`, depending on your picture files. The default is `.jpg`.

6. Choose `Excel source file`.
   Select the student Excel file.

7. Click `Save Settings`.

### Excel file requirements

The first worksheet must contain the student data. The first row must contain column names.

Common required columns include:

- `ClassRollNo`
- `CandidateName`
- `FatherName`
- `BFormNo`
- `FatherCNIC`
- `DateOfBirth`
- `IdentificationMark`
- `CurrentAddress`
- `PermanentAddress`
- `GuardianContactNo`
- `DateOfAdmission`
- `Medium`
- `Group`
- `StudentPictureName`

Date values should be written as `DD/MM/YYYY` or `DD-MM-YYYY`.

For student pictures, write only the picture name in `StudentPictureName`, without the extension. For example, if the file is `123.jpg`, write `123`.

### Normal daily use

1. Open `StudentAutoRegister.exe`.
2. Click `Open Portal Chrome`.
3. Chrome will open with the portal page.
4. Log in to the portal normally.
5. Go to the Fresh 9th Registration Form page if it is not already open.
6. Return to the app and click `Check Portal Ready`.
7. Click `Load Excel`.
8. Review the student rows shown in the table.
9. Select one row and click `Fill Selected Row`, or click `Fill All Rows`.

### Auto Save option

If `Auto Save` is unchecked, the app fills the portal form but does not press Save. You can review the form and save manually.

If `Auto Save` is checked, the app fills the form and clicks the portal Save button automatically.

For first use, it is safer to keep `Auto Save` unchecked and test one student record first.

### Use Picture Magic option

If `Use Picture Magic` is checked, the app processes the student picture before uploading it to the portal.

If picture upload causes any issue, try turning this option off and run the row again.

### Status meanings

- `Pending`: The row is loaded but not processed yet.
- `Done`: The row was filled successfully.
- `Error`: The row could not be completed. Read the message shown by the app.

### Common problems

**Chrome was not found**

Install Google Chrome, then open the app again.

**Chrome debugging is not available**

Click `Open Portal Chrome` from inside the app. Use the Chrome window opened by the app, not a normal Chrome window.

**Portal page is not ready**

Log in to the portal and open the registration form page. Then click `Check Portal Ready` again.

**Could not load Excel**

Make sure the file is an `.xlsx` file and the first worksheet contains column headers in the first row.

**Date error**

Use `DD/MM/YYYY` or `DD-MM-YYYY`, for example `10/05/2026`.

**Picture skipped**

Check that `Student picture folder` is correct, `Pic ext.` matches the picture files, and `StudentPictureName` contains the file name without extension.

---

## اردو ہدایات

### یہ ایپ کیا کرتی ہے

Student Auto Register ایکسل فائل سے طلبہ کا ڈیٹا پڑھ کر Google Chrome کے ذریعے SSC پورٹل کے رجسٹریشن فارم میں معلومات درج کرنے میں مدد دیتی ہے۔

### شروع کرنے سے پہلے

یہ چیزیں تیار رکھیں:

- Google Chrome انسٹال ہو۔
- طلبہ کی Excel فائل `.xlsx` فارمیٹ میں تیار ہو۔
- اگر تصاویر اپ لوڈ کرنی ہیں تو تمام طلبہ کی تصاویر ایک فولڈر میں موجود ہوں۔
- پورٹل کے لاگ اِن کی معلومات موجود ہوں۔

### ایپ کھولنے کا طریقہ

1. portable zip فائل کو کسی عام فولڈر میں extract کریں۔
2. extract شدہ فولڈر کھولیں۔
3. `StudentAutoRegister.exe` پر double-click کریں۔

### پہلی بار سیٹنگ

1. `Portal URL` چیک کریں۔
   عام طور پر default URL پہلے سے موجود ہوتا ہے۔

2. `Chrome debug port` کو `9222` ہی رہنے دیں، جب تک کوئی مسئلہ نہ ہو۔

3. `Chrome profile folder` منتخب کریں۔
   default فولڈر استعمال کیا جا سکتا ہے۔ یہ Chrome profile صرف اس ایپ کے لیے استعمال ہوتی ہے۔

4. `Student picture folder` منتخب کریں۔
   وہ فولڈر منتخب کریں جہاں طلبہ کی تصاویر موجود ہیں۔

5. `Pic ext.` درج کریں۔
   اپنی تصاویر کے مطابق `.jpg`, `.jpeg`, یا `.png` لکھیں۔ default `.jpg` ہے۔

6. `Excel source file` منتخب کریں۔
   طلبہ والی Excel فائل منتخب کریں۔

7. `Save Settings` پر کلک کریں۔

### Excel فائل کی ضروریات

پہلی worksheet میں طلبہ کا ڈیٹا ہونا چاہیے۔ پہلی row میں column names ہونے چاہئیں۔

عام طور پر استعمال ہونے والے ضروری columns:

- `ClassRollNo`
- `CandidateName`
- `FatherName`
- `BFormNo`
- `FatherCNIC`
- `DateOfBirth`
- `IdentificationMark`
- `CurrentAddress`
- `PermanentAddress`
- `GuardianContactNo`
- `DateOfAdmission`
- `Medium`
- `Group`
- `StudentPictureName`

تاریخ `DD/MM/YYYY` یا `DD-MM-YYYY` فارمیٹ میں لکھیں۔

تصویر کے لیے `StudentPictureName` میں صرف تصویر کا نام لکھیں، extension نہ لکھیں۔ مثال کے طور پر اگر فائل `123.jpg` ہے تو صرف `123` لکھیں۔

### روزانہ استعمال کا طریقہ

1. `StudentAutoRegister.exe` کھولیں۔
2. `Open Portal Chrome` پر کلک کریں۔
3. Chrome پورٹل کے ساتھ کھل جائے گا۔
4. پورٹل میں معمول کے مطابق login کریں۔
5. اگر Fresh 9th Registration Form page نہ کھلا ہو تو اسے کھولیں۔
6. واپس ایپ میں آئیں اور `Check Portal Ready` پر کلک کریں۔
7. `Load Excel` پر کلک کریں۔
8. table میں طلبہ کی rows چیک کریں۔
9. ایک row منتخب کر کے `Fill Selected Row` پر کلک کریں، یا تمام rows کے لیے `Fill All Rows` پر کلک کریں۔

### Auto Save option

اگر `Auto Save` بند ہو تو ایپ فارم بھر دے گی لیکن Save button نہیں دبائے گی۔ آپ فارم چیک کر کے خود Save کر سکتے ہیں۔

اگر `Auto Save` آن ہو تو ایپ فارم بھر کر portal کا Save button خود دبا دے گی۔

پہلی بار استعمال کرتے وقت بہتر ہے کہ `Auto Save` بند رکھیں اور پہلے ایک طالب علم کا ریکارڈ test کریں۔

### Use Picture Magic option

اگر `Use Picture Magic` آن ہو تو ایپ تصویر کو portal کے لیے process کر کے upload کرے گی۔

اگر تصویر upload میں مسئلہ آئے تو اس option کو بند کر کے row دوبارہ چلائیں۔

### Status کا مطلب

- `Pending`: row load ہو چکی ہے لیکن ابھی process نہیں ہوئی۔
- `Done`: row کامیابی سے fill ہو گئی۔
- `Error`: row مکمل نہیں ہو سکی۔ ایپ میں دکھایا گیا message پڑھیں۔

### عام مسائل

**Chrome was not found**

Google Chrome انسٹال کریں، پھر ایپ دوبارہ کھولیں۔

**Chrome debugging is not available**

ایپ کے اندر سے `Open Portal Chrome` پر کلک کریں۔ اسی Chrome window کو استعمال کریں جو ایپ نے کھولی ہے۔

**Portal page is not ready**

پورٹل میں login کریں اور registration form page کھولیں۔ پھر `Check Portal Ready` دوبارہ دبائیں۔

**Could not load Excel**

چیک کریں کہ فائل `.xlsx` ہے اور پہلی worksheet کی پہلی row میں column headers موجود ہیں۔

**Date error**

تاریخ `DD/MM/YYYY` یا `DD-MM-YYYY` میں لکھیں، مثال `10/05/2026`۔

**Picture skipped**

چیک کریں کہ `Student picture folder` درست ہے، `Pic ext.` تصاویر کے مطابق ہے، اور `StudentPictureName` میں file name بغیر extension کے لکھا ہے۔
