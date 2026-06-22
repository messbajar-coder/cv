# cv
# CV Builder Pro — User Manual & About Software
Welcome to the **CV Builder Pro** User Manual and software documentation. This document details everything you need to know about the software, its features, how it works under the hood, and how to use it to generate professional CVs.
---
## 📖 About CV Builder Pro
**CV Builder Pro** is a modern, offline-capable desktop application . It is designed to help job seekers, recruiters, and agencies create clean, industry-standard Curriculum Vitae (CV) + visa processing documents matching professional Word/pdf templates.
### Why Use CV Builder Pro?
* **Zero Formatting Hassles**: Designing CVs in Microsoft Word is notoriously tedious. Adjusting margins, aligning colons, and handling side-by-side tables often leads to layout breaking. CV Builder Pro automates the entire formatting process.
* **Template Alignment**: It fills pre-formatted Word templates (`.docx`) rather than generating documents from scratch. This guarantees that font sizes, styling rules, borders, and margins comply exactly with corporate design specifications.
* **Single-Page Spacing Enforcement**: Fitting a CV onto a single A4 page is a common requirement. The app implements programmatic optimization that tightens line heights, margins, and cell spacing dynamically based on the amount of content you enter.
* **Offline First**: All document parsing, image resizing, and PDF/Word generation occur locally on your machine, ensuring data privacy and fast export speeds.
* **Profile Management**: Save candidate details locally as JSON configuration profiles, making it easy to reload, edit, or regenerate them later.
---
## 🛠️ User Interface Overview
The application features a sleek dark-themed UI structured across several functional tabs:
**Dashboard / License Info**: Displays software registration status, remaining trial days, registered device identifier, and options 
---
## 🚀 Step-by-Step User Guide
### Step 1: Launch and License Activation
On startup, the software checks for licensing.
* **Free Trial**: If you are a new user, you can register a 30-day Free Trial directly from the Dashboard. 
* **Activation**: If you have purchased a license, paste your License Key in the registration input field and click **Activate**. This registers your PC to activate access.
* **Offline Use**: Once activated online, the software stores a cryptographically signed license token locally. You can run the application offline without an active internet connection.
### Step 2: Entering Candidate Details
Fill out the forms in each tab sequentially:
* **Colons Realignment**: Type information normally. On export, details are dynamically aligned with tab-stops so that labels, colons (`:`), and values line up in a clean grid.
* **Adding/Removing Rows**: In sections like *Work Experience*, *Education*, and *Language Proficiency*, click the **Add Row** button to add entries, or click the **✕** button next to any row to remove it.
* **Language Grid**: Enter your languages and specify proficiency grades (e.g., Excellent, Good, Fair) for Reading, Writing, Listening, and Speaking.
### Step 3: Importing Photos and Signatures
1. Navigate to the **Media Tab**.
2. Click **Browse Profile Image** to load a candidate photo. Supported formats: JPG, JPEG, PNG, WEBP.
3. Click **Browse Signature** to load a signature image.
4. Preview the loaded assets to verify alignment.
5. *Note: The software automatically crops and resizes these images programmatically to fit clean margins inside the document placeholders.*
### Step 4: Saving Profile Progress ( Transgaurd) 
If you want to save candidate details to edit or generate later:
1. Navigate to the **Export** tab.
2. Click **Save Progress (JSON)**.
3. Choose a path on your machine to save the file.
4. To reload this candidate later, click **Load JSON Profile** and select your saved file.
### Step 5: Generating the CV Document
1. Navigate to the **Export** tab.
2. Choose your preferred layout in the **Select Template** dropdown:
   * **1 Page CV**: Best for standard applications; enforces narrow A4 layouts.
   * **2 Page CV**: Best for candidates with extensive work history.
   * **Worker CV**: Tailored layout for vocational roles and manual trades.
   * **Review Sheet**: Overview page to audit profile details.
3. Click **Generate CV Document**.
4. Choose a destination folder and filename.
5. Once complete, a success dialog will appear. You can open the generated Word file (`.docx`) in Microsoft Word, WPS Office, or LibreOffice to make custom final adjustments if desired.
#### Q: I get a "Trial period already claimed on this PC" error.
The licensing engine records a persistent system marker in your Windows configuration directories. Free trials are limited to one per unique hardware device. To request an extended trial or reset licensing, contact your software administrator.
#### Q: The generated CV is slightly flowing over onto a second page.
This happens if you input large blocks of text inside fields like *Objective*, *Work Experience*, or *Skills*. You can:
1. Shorten the descriptions in the app and re-export.
2. Open the exported `.docx` in Microsoft Word and manually decrease font size or reduce margins.

For More Querry - worldtechnology.xyz  

