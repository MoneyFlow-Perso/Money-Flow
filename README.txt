MONEY FLOW — ANDROID / GITHUB PAGES PACKAGE

Files in this folder (upload all five directly to the root of your GitHub repository):
1. index.html
2. manifest.webmanifest
3. service-worker.js
4. icon.svg
5. README.txt

UPDATED FEATURE
Salary and Left have separate plain-text Hide/Show buttons. Hidden amounts are masked with dots on screen and shown as ------ in the generated PDF summary. The Share PDF button shares the PDF directly where supported, or downloads it so you can share it from your phone. The controls do not change saved income or expense records.

PUBLISHING
In your GitHub repository, choose Add file > Upload files and upload these five files. If index.html already exists, GitHub will replace it when you commit the update. Then enable GitHub Pages under Settings > Pages, using branch main and folder /(root).

DATA SAFETY
- Never upload your financial JSON backup or transaction data to GitHub.
- Keep a separate JSON backup in a safe private location.
- Browser storage is local to the browser/device and is not an off-device backup.
- The password gate is not encryption of browser-stored financial data.
- The app may load the Sora font from Google Fonts when online; core app files are cached for offline use after first load.


Borrowing behavior:
- Entries in the 'Been Borrowed' category count as incoming money.
- The income tile says 'Salary' when there is no borrowed income in the selected month, and 'Salary + Borrowed' when borrowed income exists.
- Share PDF includes salary and borrowed income separately, plus a date-by-date borrowed-money history for the selected month.
